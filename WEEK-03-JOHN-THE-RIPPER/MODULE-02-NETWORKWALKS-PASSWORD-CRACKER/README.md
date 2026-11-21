# 🔐 Password Cracking with NetworkWalks Tools

<p align="left">
  <img src="https://img.shields.io/badge/NETWORKWALKS-CYBERSECURITY-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PROJECT-PASSWORD%20CRACKING-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/WEEK-03-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/MODULE-02-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/STATUS-COMPLETED-brightgreen?style=for-the-badge" />
</p>

## 📌 Project Overview

This practical focused on understanding password cracking using the online tools provided by **NetworkWalks**.

The exercise involved extracting a password hash from a password-protected PDF file using the NetworkWalks Hash Calculator and submitting the extracted hash to the NetworkWalks Password Cracker to recover the PDF password.

The objective was to understand how password recovery works and how weak or commonly used passwords can be vulnerable to cracking attempts.

## 🎯 Objectives

- Understand the basic concept of password cracking.
- Extract a hash from a password-protected PDF file.
- Use an online password-cracking tool to test the extracted hash.
- Recover the PDF password.
- Verify the recovered password by opening the protected PDF.

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| NetworkWalks Hash Calculator | Extracting the PDF password hash |
| NetworkWalks Password Cracker | Attempting to recover the password |
| Web Browser | Accessing the online tools and downloading the PDF |

**Tool links:**
- [NetworkWalks Hash Calculator](https://networkwalks.com/hash-calculator/)
- [NetworkWalks Password Cracker](https://networkwalks.com/password-cracker/)

## 🔬 Practical Procedure

### Step 1: Downloading the Password-Protected PDF

I visited the NetworkWalks project task page and downloaded the provided password-protected PDF file named `My Locked PDF1.pdf`.

This file served as the target for the password-recovery exercise.

**Screenshot:**

![Downloaded PDF](screenshots/01-downloaded-pdf.png)

### Step 2: Extracting the PDF Hash

I opened the NetworkWalks Hash Calculator and uploaded the downloaded PDF file.

The tool processed the document and generated a PDF hash beginning with `$pdf$`.

I copied the complete hash for the next stage of the exercise.

**Screenshot:**

![PDF Hash Extraction](screenshots/02-pdf-hash-extraction.png)

### Step 3: Submitting the Hash to the Password Cracker

Next, I opened the NetworkWalks Password Cracker and pasted the extracted PDF hash into the provided input field.

This allowed the tool to begin testing password candidates against the extracted hash.

**Screenshot:**

![Hash Submitted](screenshots/03-hash-submitted.png)

### Step 4: Starting the Password-Cracking Process

After submitting the hash, I initiated the password-cracking process using the Start Attack option.

I allowed the tool to process the hash and attempt to identify the matching password.

**Screenshot:**

![Password Cracking Process](screenshots/04-password-cracking-process.png)

### Step 5: Recovering the Password

The password-cracking tool identified the password associated with the protected PDF.

The recovered password was:

`password1`

**Screenshot:**

![Recovered Password](screenshots/05-recovered-password.png)

### Step 6: Verifying the Recovered Password

Finally, I opened the downloaded PDF file and entered the recovered password.

The document opened successfully, confirming that the password-recovery exercise was completed.

**Screenshot:**

![PDF Successfully Opened](screenshots/06-pdf-opened-successfully.png)

## 📚 What I Learned

Through this practical, I learned:

- How password-protected PDF files can be processed to extract password hashes.
- How extracted hashes can be used in password-recovery tools.
- How password-cracking tools test possible passwords against a hash.
- Why weak and commonly used passwords can be easier to recover.
- The importance of using strong and unique passwords to protect sensitive documents.

## 🛡️ Security Lessons

This exercise demonstrated why users should avoid weak and predictable passwords.

Some recommended security practices include:

- Use long and unique passwords.
- Avoid common passwords and predictable combinations.
- Use a password manager to generate and store strong passwords.
- Protect sensitive documents with strong passwords.

## 📝 Conclusion

This practical provided hands-on experience with password recovery using NetworkWalks tools.

I worked through the process of downloading a protected PDF, extracting its hash, submitting the hash to a password-cracking tool, and verifying the recovered password by opening the document.

The exercise improved my understanding of password security and the risks associated with weak passwords.

---

**Training Platform:** NetworkWalks  
**Project:** Cybersecurity & Ethical Hacking  
**Week:** 03  
**Module:** 02 – Password Cracking with NetworkWalks Tools
