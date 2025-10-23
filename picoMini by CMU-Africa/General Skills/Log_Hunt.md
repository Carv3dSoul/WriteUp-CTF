# Riddle Registry

**Category:** Forensic

---

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/991a5daf-465a-49e0-b09c-a959bb6c198a" />

---

**Attachments:**    ```server.log```

**Difficulty:** Easy

**Points:** 100

**Author:** - 

**Hint 1**  : You can use grep to filter only matching lines from the log.

**Hint 2**  : Some lines are duplicates; ignore extra occurrences.

---

## Challenge Description

Our server seems to be leaking pieces of a secret flag in its logs. The parts are scattered and sometimes repeated. Can you reconstruct the original flag?

---

## Solution

Okay, I was given a log file here. I immediately tried to analyze the contents of the server.log. Here I used the command strings

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/c4e9b723-def2-4e11-a347-a7b84f4105ee" />

okay here i found flag part 1. I thought "why don't I just search for the word FLAGPART? and i forgot about it :V " Interesting. okay, just go straight to the gas

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/674d3cde-a4f1-4e1d-8635-90efac398001" />

okay there are 4 part flags and we found them horeeeee 

## Flag

```
picoCTF{us3_y0urlinux_sk1lls_cedfa5fb}
```
