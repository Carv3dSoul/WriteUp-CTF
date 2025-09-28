# filter fiasco

**Category:** Web

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/5f43be7e-3b01-4b29-84ca-6805df9047fb" />

**Description:**  
Intro Challenge

**Attachments:**  ```http://64.227.171.211:3000``` 

**Difficulty:** -  

**Points:** 100 

**Author:** - 

---

## Challenge Description
The company’s internal authentication system seems simple at first glance, but something doesn’t add up. You were given access to their login portal,
Check Login
Brute-force attempts won’t help here. @localh0ste

## Solution

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/00d952b9-ca45-411c-af50-537b86a73156" />

We are given a login page to get the flag here. I didn't expect the payload to use ```{{ 7 * 7 }}```. At first, I just entered the payload for fun

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/8425fa1d-947d-469b-8154-ccc004fb28c3" />

and boom i got the flag.

## Flag

```
SPL{27ff7dc84296b8bbec0bf9797df03a12} 
```
