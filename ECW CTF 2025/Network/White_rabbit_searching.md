# Have you read the rules ? 

**Category:** Rules  

---

![WhatsApp Image 2025-11-08 at 23 04 50_373f419a](https://github.com/user-attachments/assets/78ae09e6-4210-4cb4-8cfc-07e1d133b3ec)

---

**Attachments:** ```Searching_this_rabbit.pcap```

**Difficulty:** Easy

**Points:** 100

**Author:** - 

---

## Challenge Description
Alice set out to find a trace of the White Rabbit... But as always, the paths in Wonderland are confusing, and some traces of the white rabbit have been found on the network.
Try to assemble the different paths and recover the clue!

## Solution

OK, we are given a pcap file, without further ado, we immediately open Wireshark

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/e1fbd3f3-c2c7-4753-a05a-7329d7b76f64" />

the first thing i did was filter using http. 

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/20a3dfe9-5535-4b42-bf2b-894cfc962467" />

OK, it looks like there's nothing wrong with http and TCP. I tried to analyze everything and found something here.

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/b4fd06ed-f9ae-4ce0-9d06-e67764cdf18b" />

here I do right click follow udp stream.

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/b3c0ee7e-0963-4033-b4f2-8e0c4d4e0275" />

Look at stream 6 there is a base64 code. Here I try to find another base64 code. I have found another base64 code ```RUNXe0ZvbGxvd190aGVfd2hpdGVfcmFiYml0fQ``` and I decode it. 

<img width="600" height="600" alt="image" src="https://github.com/user-attachments/assets/29ceba7e-496a-4b2e-9d59-7557a3ca8296" />

## Flag

```
ECW{Follow_the_white_rabbit}
```
