# Corrupted file

**Category:** Forensic

---

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/24d2a52c-50db-4bc6-8aa8-e9fb76ae8f3e" />

---

**Attachments:**    ```file```

**Difficulty:** Easy

**Points:** 100 

**Author:** - 

**Hint 1**  : Try checking the file’s header.

**Hint 2** : JPEG

**Hint 3** : Tools like xxd or hexdump can help you inspect and edit file bytes.

---

## Challenge Description
This file seems broken... or is it? Maybe a couple of bytes could make all the difference. Can you figure out how to bring it back to life?

## Solution

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/6ae103ca-891e-4a55-b26e-93d2eed4010d" />

OK, we are given a file but it is in data form. what we don't realize is that this is a jpg image file.

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/59345562-05bf-4557-9f33-d5b80b793243" />

Look at that, this is a jpg file but it is blocked by an anomaly code, namely \x. in hexadecimal ```5c78``` is wrong the correct one is ```ffd8```.
Here I change it only using the hexeditor tool.

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/a434b95d-f2b8-40be-996b-127890abfd88" />

we just need to change the hexadecimal. and don't forget we change the ```file``` extension from file to ```file.jpg```. If it's ready, we just open the image file

<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/e7feee95-ceeb-4be3-b9da-eb7b1014f98c" />


## Flag

```
picoCTF{r3st0r1ng_th3_by73s_efd8c8c0}
```
