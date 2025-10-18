# Hidden in plainsight

**Category:** Forensic

---

<img width="500" height="500" alt="Screenshot 2025-10-19 001207" src="https://github.com/user-attachments/assets/357e009c-26a0-41c5-87ab-709155d84eb8" />

---

**Attachments:**    ```img.jpg```

**Difficulty:** Easy

**Points:** 100

**Author:** - 

**Hint 1**  : Download the jpg image and read its metadata.

---

## Challenge Description

You’re given a seemingly ordinary JPG image. Something is tucked away out of sight inside the file. Your task is to discover the hidden payload and extract the flag.

## Solution

OK, we are given an img.jpg file. In the hint, we are asked to check the metadata.

<img width="600" height="600" alt="Screenshot 2025-10-19 001927" src="https://github.com/user-attachments/assets/f1917b72-89ca-42f0-8177-8cd9eb8a756a" />

I found a base64 code here, I immediately decoded the code directly.

<img width="701" height="71" alt="image" src="https://github.com/user-attachments/assets/1ee5309c-e968-4803-81a3-c40ac98d8000" />

that there is steghide:cEF6endvcmQ= when I decode it, where the contents are pAzzword.

<img width="638" height="94" alt="image" src="https://github.com/user-attachments/assets/b7801a45-21fa-453b-8073-3fe2cee93017" />

which extracts a file called flag.txt.

<img width="715" height="72" alt="image" src="https://github.com/user-attachments/assets/97ebe826-d94d-478c-a83a-d8df1a1809e2" />

## Flag

```
picoCTF{h1dd3n_1n_1m4g3_1c55ccd0}
```
