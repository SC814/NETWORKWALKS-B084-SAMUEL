# NETWORKWALKS | TOOLS LAB – WEEK 03
## PDF Password Recovery with John the Ripper & Johnny

<p align="center">
  <img src="https://img.shields.io/badge/NETWORKWALKS-TOOLS%20LAB-blue?style=for-the-badge" alt="NetworkWalks Tools Lab">
  <img src="https://img.shields.io/badge/PROJECT-WEEK%2003-success?style=for-the-badge" alt="Project Week 03">
  <img src="https://img.shields.io/badge/PLATFORM-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-John%20the%20Ripper-red?style=flat-square" alt="John the Ripper">
  <img src="https://img.shields.io/badge/GUI-Johnny-orange?style=flat-square" alt="Johnny">
  <img src="https://img.shields.io/badge/Focus-Password%20Auditing-purple?style=flat-square" alt="Password Auditing">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square" alt="Completed">
</p>

---

## 📌 Project Overview

This project was completed as part of the **NetworkWalks Tools Lab – Week 03**.

The practical focused on using **John the Ripper** and its graphical interface, **Johnny**, to perform password recovery on a password-protected PDF file.

The exercise involved extracting a password hash, configuring the required tools, loading the hash, and initiating the recovery process.

## 🎯 Project Objectives

- Understand the fundamentals of password hashing and password recovery.
- Install and configure John the Ripper and Johnny.
- Extract a password hash from a protected PDF document.
- Load the extracted hash into Johnny.
- Initiate a password recovery attempt.
- Troubleshoot configuration and application issues.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| John the Ripper (Jumbo) | Password hash auditing and recovery |
| Johnny | Graphical interface for John the Ripper |
| PDF Hash Extraction Tool | Extracting the PDF password hash |
| Windows | Operating system used for the practical |

## ⚙️ Practical Implementation

### 01. Downloading the Required Tools

Downloaded John the Ripper Jumbo and Johnny for Windows.

**Evidence:**

![Downloaded Tools](screenshots/01-downloaded-tools.png)

### 02. Installing Johnny

Installed Johnny on the Windows system and launched the application.

**Evidence:**

![Johnny Installation](screenshots/02-johnny-installation.png)

### 03. Extracting the PDF Hash

Used a PDF hash extraction tool to extract the password hash from the protected PDF file. Saved the extracted hash in a text file named `pass.txt`.

**Evidence:**

![Extracted PDF Hash](screenshots/03-extracted-hash.png)

### 04. Configuring John the Ripper

Extracted the John the Ripper archive and navigated to its `run` directory to locate the executable.

An issue occurred during configuration because an RVA process was interfering with the setup. After stopping the interfering process, I was able to locate the correct executable and configure Johnny successfully.

**Evidence:**

![John Configuration](screenshots/04-john-configuration.png)

### 05. Loading the Extracted Hash

Loaded the `pass.txt` file containing the extracted PDF hash into Johnny in preparation for the recovery attempt.

**Evidence:**

![Hash Loaded](screenshots/05-hash-loaded.png)

### 06. Initiating Password Recovery

Started the password recovery process using the loaded PDF hash.

**Evidence:**

![Recovery Process](screenshots/06-recovery-process.png)

### 07. Final Result

Captured the final application state as evidence of the completed practical exercise.

**Evidence:**

![Final Result](screenshots/07-final-result.png)

## 🧩 Challenges & Troubleshooting

One of the major challenges encountered was getting Johnny to locate the John the Ripper executable correctly.

An RVA process was also interfering with the setup. I resolved this by stopping the process, locating the correct executable in the `run` directory, and completing the configuration.

This experience reinforced the importance of troubleshooting and understanding how tools depend on one another.

## 📚 Key Takeaways

- Understanding the relationship between password hashes and password recovery.
- Configuring John the Ripper through its graphical interface.
- Working with PDF password hashes.
- Identifying and resolving application configuration issues.
- Gaining practical experience with offline password auditing.

## 🏁 Conclusion

The Week 03 practical provided hands-on experience with John the Ripper and Johnny, from tool installation and hash extraction to configuration and password recovery.

It strengthened my understanding of password auditing workflows and improved my troubleshooting skills.

**All activities were performed within an authorized learning environment.**

## 🔗 References

- [John the Ripper – Official Website](https://www.openwall.com/john/)
- [John the Ripper – Documentation](https://www.openwall.com/john/doc/)
- [Johnny – GitHub Repository](https://github.com/openwall/johnny)

---

<p align="center">
  **NETWORKWALKS | CYBERSECURITY TOOLS LAB**
  <br>
  <i>Learn. Practice. Document. Improve.</i>
</p>
