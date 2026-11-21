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

<img width="1594" height="825" alt="locked pdf" src="https://github.com/user-attachments/assets/18a2a5a8-241d-4931-9759-b29f98d3fdb0" />


### Step 2: Extracting the PDF Hash

I opened the NetworkWalks Hash Calculator and uploaded the downloaded PDF file.

The tool processed the document and generated a PDF hash beginning with `$pdf$`.

I copied the complete hash for the next stage of the exercise.

**Screenshot:**

<img width="1600" height="772" alt="image" src="https://github.com/user-attachments/assets/f3229182-2514-41f3-aa19-8dd101a37018" />


### Step 3: Submitting the Hash to the Password Cracker

Next, I opened the NetworkWalks Password Cracker and pasted the extracted PDF hash into the provided input field.

This allowed the tool to begin testing password candidates against the extracted hash.

**Screenshot:**

<img width="1580" height="821" alt="image" src="https://github.com/user-attachments/assets/44f313eb-36a1-43df-a2a0-dde04d780603" />


### Step 4: Starting the Password-Cracking Process

After submitting the hash, I initiated the password-cracking process using the Start Attack option.

I allowed the tool to process the hash and attempt to identify the matching password.

**Screenshot:**

<img width="1597" height="781" alt="passwrd found" src="https://github.com/user-attachments/assets/b45b3fed-9fd9-478a-8e2b-0e59947b996e" />


### Step 5: Recovering the Password

The password-cracking tool identified the password associated with the protected PDF.

The recovered password was:

`password1`

**Screenshot:**

<img width="1600" height="774" alt="passworddd" src="https://github.com/user-attachments/assets/ab08b98d-0c28-4d43-8ef1-8a4457d08bdc" />


### Step 6: Verifying the Recovered Password

Finally, I opened the downloaded PDF file and entered the recovered password.

The document opened successfully, confirming that the password-recovery exercise was completed.

**Screenshot:**

<img width="1597" height="725" alt="congra" src="https://github.com/user-attachments/assets/85a57d18-53e1-484b-90f4-46b284009304" />


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
