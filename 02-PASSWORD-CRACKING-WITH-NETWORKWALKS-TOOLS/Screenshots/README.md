# PROJECT 02 – WEB-BASED PDF PASSWORD AUDITING

### Networkwalks Hash Calculator and Password Cracker | Hash Extraction and Password Verification

## 1. Project Overview

This practical explores a browser-based approach to PDF password auditing using the **Networkwalks Hash Calculator** and **Networkwalks Password Cracker**.

The exercise involved uploading an assigned password-protected PDF, extracting its PDF-specific password hash, submitting the hash to the Password Cracker, and performing password recovery using the available built-in password list.

The recovered password was then tested against the original PDF to confirm successful document access.

Unlike Project 01, which used a locally executed command-line tool, this exercise used browser-based tools to complete the password recovery workflow.

## 2. Tools and Resources

| Tool | Purpose | Access |
|---|---|---|
| Networkwalks Hash Calculator | Extracting PDF-specific password hashes | [Open Tool](https://networkwalks.com/hash-calculator/) |
| Networkwalks Password Cracker | Performing password recovery | [Open Tool](https://networkwalks.com/password-cracker/) |
| Web Browser | Accessing the online tools | Installed browser |
| Built-in Password List | Providing candidate passwords for the cracking process | Available within Password Cracker |

**Lab reference:** [Password Cracking with Networkwalks Tools – Networkwalks Academy](https://networkwalks.com/password-cracking-with-networkwalks-tools-project-task-lab/)

**Installation requirement:** No separate software installation was required for this practical. Both Networkwalks tools were accessed through a web browser.

## 3. Objectives

- Explore the PDF hash extraction functionality of Networkwalks Tools.
- Understand the difference between general file checksums and PDF-specific password hashes.
- Extract a password hash from an assigned protected PDF.
- Use the Networkwalks Password Cracker.
- Perform password recovery using the built-in password list.
- Verify the recovery result by opening the original PDF.

## 4. Methodology and Implementation

### Step 1 – Accessing the Networkwalks Hash Calculator

Opened the Networkwalks Hash Calculator through a web browser.

**Tool:** [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/)

The tool provides different hash calculation options, including MD5, SHA-1, SHA-256, SHA-384, and SHA-512, along with a separate PDF option.

### Step 2 – Uploading the Protected PDF

Selected the PDF option and uploaded the assigned password-protected PDF document.

The PDF-specific extraction option was selected instead of the general file checksum options.

### Step 3 – Extracting the PDF Password Hash

Generated the PDF-specific password hash using the Hash Calculator.

The extracted hash was copied for use in the next stage of the practical.

The hash was kept private and was not included in this repository.

### Step 4 – Accessing the Networkwalks Password Cracker

Opened the Networkwalks Password Cracker in another browser tab.

**Tool:** [Networkwalks Password Cracker](https://networkwalks.com/password-cracker/)

The extracted hash was entered into the field labelled:

`PDF HASH ($PDF$...)`

### Step 5 – Selecting the Password List

Selected the following option:

**Built-in list (100 passwords)**

This option supplied the candidate passwords used during the password recovery process.

### Step 6 – Executing the Password Recovery Process

Started the process using the **START CRACKING** option.

The tool processed the submitted PDF hash and reported that the password had been found.

The recovered password is intentionally not disclosed in this repository.

### Step 7 – Verifying the Original PDF

Opened the original protected PDF and entered the recovered password.

The PDF opened successfully, confirming the recovery result.

## 5. Screenshots and Practical Evidence

The following screenshots document the main stages of the web-based practical.

### 5.1 PDF Hash Extraction – Networkwalks Hash Calculator

![Networkwalks Hash Extraction](./Screenshots/1_Pdf_Hash_Extraction.png)

### 5.2 Password Recovery – Networkwalks Password Cracker

![Networkwalks Password Cracker Result](./Screenshots/2_Password_Cracking_Result.png)

### 5.3 PDF Unlock Verification

![PDF Unlock Verification](./Screenshots/3_Pdf_Unlock_Verification.png)

## 6. Observations

- The Hash Calculator provides different options for calculating general file checksums and extracting PDF-specific hashes.
- The PDF option is necessary for obtaining the hash format required by the Networkwalks Password Cracker.
- The built-in password list provides candidate passwords for the recovery process.
- The Password Cracker reported that the password was found.
- Successful recovery was confirmed by opening the original PDF.

## 7. Learning Outcomes

Through this practical, I gained experience in:

1. Accessing and using browser-based cybersecurity tools.
2. Extracting PDF-specific password hashes.
3. Understanding the difference between general file hashes and PDF password hashes.
4. Using a built-in password list for dictionary-based recovery.
5. Understanding the workflow of web-based password auditing.
6. Verifying recovered passwords using the original protected document.

## 8. Security and Ethical Considerations

- This practical was performed for educational purposes using an assigned training document.
- Only documents that you own or have explicit permission to assess should be uploaded to online password-auditing tools.
- Online services may process uploaded files or hashes; sensitive documents should not be submitted without reviewing the service's privacy and data-handling policies.
- Extracted hashes, recovered passwords, and original locked PDFs are excluded from this public repository.
- Password-cracking tools must only be used for authorized security assessments.

## 9. Conclusion

This practical provided hands-on experience with the Networkwalks Hash Calculator and Password Cracker.

The exercise demonstrated a browser-based PDF password auditing workflow, including hash extraction, password-list selection, password recovery, and document verification.

The successful recovery and opening of the assigned PDF provided practical insight into how web-based password auditing tools can be used for authorized security assessments.

## 10. Author

**Harini Madasu**  
B.Tech – Mathematics and Computing  
Central University of Karnataka

**LinkedIn:** [Connect with me](https://www.linkedin.com/in/harini-madasu-91258b357)

---
