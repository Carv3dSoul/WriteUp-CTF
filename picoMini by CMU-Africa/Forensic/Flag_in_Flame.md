# Riddle Registry

**Category:** Forensic

---

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/9cc154e7-76a7-423f-a777-40d7dfb8c5fd" />

---

**Attachments:**    ```logs.txt```

**Difficulty:** Easy

**Points:** 100

**Author:** - 

**Hint 1**  : Use base64 to decode the data and generate the image file.

---

## Challenge Description

The SOC team discovered a suspiciously large log file after a recent breach. When they opened it, they found an enormous block of encoded text instead of typical logs. Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it. The team is relying on your skills to uncover any concealed information within this unusual log.

## Solution

we are given a txt file here.

<img width="1458" height="462" alt="image" src="https://github.com/user-attachments/assets/bed79dc5-5567-4822-a79e-d9fb32ceb8a3" />

okay here I decode using python script

```
import base64

with open("logs.txt", "r") as f:
    data = f.read().strip()

decoded_data = base64.b64decode(data)

with open("decoded.png", "wb") as f:
    f.write(decoded_data)

print("decoded.png")
```

<img width="500" height="400" alt="image" src="https://github.com/user-attachments/assets/deacd45d-2fae-4e47-b75a-6cf5858a1fb3" />

In the picture we are given a hex code, here I immediately decode it and I decode it using cybercheff.

<img width="800" height="500" alt="image" src="https://github.com/user-attachments/assets/ee2b08cb-0300-46c1-ab8e-1d562fb891c1" />

## Flag

```
picoCTF{forensics_analysis_is_amazing_ac1e3584}
```
