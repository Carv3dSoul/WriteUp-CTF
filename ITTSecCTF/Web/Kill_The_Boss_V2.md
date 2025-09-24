# Kill The Boss V2


<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/b2d0cbf6-0e39-4d38-81a3-230f90473470" />


**Category:** Web  

**Description:**  
None


**Attachments:**  
https://web2.ittsec.net/

**Difficulty:** -  
**Points:** 10
**Author:** -  

---

## Solution

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/9abba944-b199-43a8-bb26-a1dd9ac6eead" />

okay we are given another gelud website with the boss

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/1b6600c5-65b0-4621-95a8-8e6058890345" />

okay as usual here we always lose and notice there is nothing interesting in the parameters. If it's like this, I check the code on the website using ```Ctrl + U```

<img width="949" height="476" alt="image" src="https://github.com/user-attachments/assets/b476ead5-ed5b-440b-81e1-b12f9d6201fd" />

okay here not finding anything so i will use ```Burp Suite``` tools

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/94e356b8-9234-42d9-a88a-25b966bd0f0e" />

when I use burp suite tools I found ```data=ZGFtYWdlPTI%3D```
if we decode it will be like this ```damage=27``` if we change it to damage=9999 what will happen

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/8625def3-aa80-43a5-9c26-f63ec4a21da2" />

and boom got the flag!!!!

## Flag 

```
ITTSec{p4r4m3t3r_t4mp3r1ng_v14_p0st_b4s364_ftw}
```
