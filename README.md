# 🔐 Password Cracking — Cybersecurity & Ethical Hacking

## Week 3 — Project Modules 1 & 2

This repository contains my Week 3 cybersecurity and ethical hacking lab work covering two password-recovery projects:

- **Project Module 1:** Password Cracking with John the Ripper (JTR)
- **Project Module 2:** Password Cracking with Networkwalks Tools

These projects helped me gain practical experience with password hashes, password security, Linux command-line tools, and authorized cybersecurity testing.

> ⚠️ **Ethical Use:** These techniques were performed for cybersecurity education and authorized lab work only. Password-cracking tools should only be used on files, systems, and accounts that you own or have explicit permission to test.

---

# 🔐 Project Module 1 — Password Cracking with John the Ripper

## 📌 Overview

John the Ripper (JTR) is a password-cracking tool used by security professionals to test password strength.

For **Project Module 1, I completed the practical lab using John the Ripper on Kali Linux**.

Instead of using the Johnny GUI on Windows, I used the **JTR command-line tool directly through the Kali Linux terminal**.

The project involved preparing a PDF password hash, loading it into John the Ripper, performing the password-recovery process, and verifying the result.

---

## 🛠️ Tools & Environment

- Kali Linux
- John the Ripper (JTR)
- Kali Linux Terminal
- PDF password hash
- Authorized encrypted PDF
- Password candidates / wordlist

---

## ⚙️ John the Ripper Workflow

### Step 1 — Prepare the PDF Hash

The password hash of the authorized encrypted PDF was prepared in a text file.

Example:

```text
file3.txt
