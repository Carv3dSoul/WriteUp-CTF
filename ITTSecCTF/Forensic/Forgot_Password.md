# Forgot Password 

<img width="500" height="500" alt="Screenshot 2025-09-24 221728" src="https://github.com/user-attachments/assets/adfc2de6-3c52-4a49-a670-82fb2fd68d06" />

**Category:** Welcome  


**Description:**  
Teman saya lupa passwordnya, yang dia ingat 8 karakter (Uppercase, Number).
Tolong bantu pecahkan, terimakasih dan youRock!
Note: Format Flag: ITTSec{passwordnya} Jangan bruteforce ke server! Tombol Submit Flag akan terkunci/disable jika salah 5 kali

**Attachments:** 
```
https://ctf.ittsec.net/files/5e8feaa6534f312bcd6b22907127fd0e/handshake_ITTSec_7A-76-18-23-9F-91_2025-09-08T13-56-54.cap?token=eyJ1c2VyX2lkIjo4MiwidGVhbV9pZCI6bnVsbCwiZmlsZV9pZCI6Nn0.aNQLgg.9v3pcSjTTuMLsM92SA2GUdtqkxc
```

**Difficulty:** -  

**Points:** 12

**Author:** - 

---

## Solution
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/3e2a62d6-fcda-458a-ad3c-05880a4fa68d" />

given the ITTSec handshake_stamp_file_7A-76-18-23-9F-91_2025-09-08T13-56-54.cap here I use the wireshark tool to analyze it first

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/30e59587-589b-40fd-aa68-fe1c8551f4ff" />

here there are key messages 1, 2, 3, 4 It asked me to find a password and then there was a clue called youRock? I immediately connected that it was Rockyou so I used ```hashcat``` and ```Rockyou wordlists``` here


## Flag

```

```
