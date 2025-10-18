# Riddle Registry

**Category:** Forensic

---

<img width="500" height="500" alt="Screenshot 2025-10-18 230412" src="https://github.com/user-attachments/assets/35fafc75-8e1f-4352-8e6b-c5d6a69f46d5" />

---

**Attachments:**    ```confidential.pdf```

**Difficulty:** Easy

**Points:** 50

**Author:** - 

**Hint 1**  : Don't be fooled by the visible text; it’s just a decoy!

**Hint 2** : Look beyond the surface for hidden clues.

---

## Challenge Description

Hi, intrepid investigator! 📄🔍 You've stumbled upon a peculiar PDF filled with what seems like nothing more than garbled nonsense. But beware! Not everything is as it appears. Amidst the chaos lies a hidden treasure—an elusive flag waiting to be uncovered.

## Solution

We are given a file here, the file extension is called pdf

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/327a6a1a-f342-468c-bcd1-e9a20ccaed68" />

here I use strings to see the text inside that file

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/caafefcb-5709-452a-a95b-83f8d77e7a40" />

and there is a base64 code there and we decode that code and the result is a flag.

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/656c07ec-a111-41b1-b108-d37a707b9d8c" />


## Flag

```
picoCTF{puzzl3d_m3tadata_f0und!_87be60c0}
```
