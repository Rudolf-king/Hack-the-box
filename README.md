# Hack-the-box
# 🚩 Hack The Box Walkthroughs & Writeups

Welcome to my collection of **Hack The Box (HTB)** machine walkthroughs, CTF writeups, and security research notes! This repository serves as a personal knowledge base documenting my methodology in network security, web application testing, Active Directory exploitation, and privilege escalation.

---

## 🛡️ HTB Profile & Stats

<!-- Replace YOUR_HTB_USER_ID with your actual Hack The Box User ID -->
[![Hack The Box Profile](https://www.hackthebox.eu/badge/image/YOUR_HTB_USER_ID)](https://app.hackthebox.com/users/YOUR_YOUR_HTB_USER_ID)

---

## ⚠️ Disclaimer & Guidelines

> **Notice:** All content published here is strictly for **educational purposes and personal skill development**.
> - Writeups for **active/retired machines** adhere strictly to Hack The Box's official **Rules of Engagement**.
> - **No active flags** or spoilative solutions are published for live machines.
> - The techniques documented should only be executed on authorized environments.

---

## 🛠️ Tooling & Methodology

```text
  Recon & Enum      -->     Initial Access     -->    Privilege Escalation
┌────────────────┐        ┌────────────────┐        ┌─────────────────────┐
│ Nmap, Gobuster │        │ Metasploit,    │        │ LinPEAS, WinPEAS,   │
│ FFuF, BloodHound│       │ Custom Exploits│        │ GTFOBins, Token Imp.│
└────────────────┘        └────────────────┘        └─────────────────────┘
