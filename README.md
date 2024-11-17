# CTF Write-Up of TPW 2024 🛠️🎯

Welcome to the **CTF Write-Up Repository**! This is a guide for solving various Capture The Flag (CTF) challenges. Intended for learning, practicing, or just curious, I've wrote detailed step-by-step solutions to help you understand and tackle each challenge.

## Repository Structure 📂

Here’s how the repository is laid out:

- **webex/**  
  Learn about **XML External Entity (XXE) Injection**. This involves exploiting vulnerabilities in XML parsers to access sensitive server data. 🛠️

- **binex/**  
  Dive into **binary exploitation** challenges. Specifically, we cover integer overflow issues, where adding two positive numbers (`n1 > 0` and `n2 > 0`) somehow gives you a negative result. 🤔

- **cryptography/**  
  Crack some codes with classic cryptographic techniques. This section includes challenges like brute-forcing Caesar ciphers and understanding how simple encryption works. 🔑

- **forensic/**  
  Analyze corrupted hex data and TCP captures to uncover hidden information. Put your detective skills to the test. 🕵️‍♂️

> **Note:** Each directory comes with its own `README.md` explaining the challenge in detail **AND** includes a challenge file or source code so you can try breaking it yourself. Perfect for hands-on learning! 💻✨

---

## What’s in Each Section? 🤓

### Web Exploitation (`webex`)
This section dives into **XXE Injection**—a vulnerability that can expose files or system information via XML parsing. You'll learn to craft payloads to exploit this vulnerability and understand how it works step by step. 

### Binary Exploitation (`binex`)
Binary exploitation challenges here revolve around **integer overflow**, where numbers don’t behave as they should due to computational limits. This section explains how to detect the vulnerability and write an exploit for it.

### Cryptography (`cryptography`)
Focuses on cracking encryption schemes like **Caesar ciphers**. The walkthroughs will show you how to script a brute-force attack and decode the flag.

### Forensics (`forensic`)
In this section, you’ll analyze corrupted hex files or dissect TCP packet captures to recover hidden data. The walkthroughs explain tools and methods to get to the solution.

---

## How to Use This Repository 🚀

1. Pick a category from the list above and go to its folder.
2. Read the `README.md` for an explanation of the challenge and the solution.
3. Try solving the included challenge files or source code to test your skills. 
4. Refer to the write-ups if you get stuck or want to understand the approach better.

---

## A Quick Heads-Up ⚠️

This repository is purely for **learning** and **practice**. It’s meant to help you sharpen your cybersecurity skills in a safe environment. Always remember: **don’t use these techniques outside CTFs or without proper authorization**. Play fair and stay ethical!

---
Happy Hacking, Fellas! 🎉  

