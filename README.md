# PDF PASSWORD SECURITY ASSESSMENT

### Practical Implementation Using John the Ripper and Networkwalks Tools

<p align="center">
  <img src="https://img.shields.io/badge/NETWORKWALKS-B084-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/WEEK-03-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PROJECTS-02-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PLATFORM-Windows-lightgrey?style=for-the-badge" />
</p>

## 1. Project Overview

The exercises focus on assessing password-protected PDF documents through password-hash extraction and dictionary-based password recovery.

Two different approaches were explored:

- **Command-Line Approach:** Using John the Ripper Jumbo to perform wordlist-based password auditing through PowerShell.
- **Web-Based Approach:** Using Networkwalks Hash Calculator and Networkwalks Password Cracker to extract PDF password hashes and perform password recovery through a browser.

Both exercises involved extracting a PDF-specific hash, performing password recovery, and verifying the result by opening the original protected document.

## 2. Objectives

- Understand PDF password protection and password-hash extraction.
- Identify the correct hash format required for PDF password auditing.
- Explore dictionary-based password attacks.
- Perform password auditing using John the Ripper.
- Explore browser-based password auditing using Networkwalks Tools.
- Verify password recovery using the original PDF documents.
- Understand the importance of strong passwords and secure document handling.

## 3. Tools and Resources

The following tools and resources were used during the practical exercises.

| Tool / Resource | Purpose | Access |
|---|---|---|
| John the Ripper Jumbo | Command-line password auditing and recovery | [Official Download](https://www.openwall.com/john/) |
| PowerShell | Executing John the Ripper commands | Built into Windows |
| OnlineHashCrack PDF Hash Extractor | Extracting the PDF password hash for Project 1 | [Open Tool](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php) |
| Networkwalks Hash Calculator | Extracting the PDF-specific hash for Project 2 | [Open Tool](https://networkwalks.com/hash-calculator/) |
| Networkwalks Password Cracker | Performing browser-based password recovery | [Open Tool](https://networkwalks.com/password-cracker/) |
| Built-in `password.lst` | Wordlist supplied with the John the Ripper package | Included in the extracted John `run` directory |
| Windows | Operating environment | — |

**Note:** John the Ripper was used through its command-line interface. Johnny GUI was not used in the completed practical.

## 4. Practical Exercises

### Project 01 – Command-Line PDF Password Auditing

**Tool:** John the Ripper Jumbo

This exercise involved extracting the password hash from an assigned protected PDF and using John the Ripper through PowerShell to perform a dictionary-based password audit.

**Major activities:**

- Downloading and extracting John the Ripper Jumbo for Windows.
- Verifying the command-line installation.
- Extracting the PDF password hash using OnlineHashCrack.
- Preparing the hash file locally.
- Executing a wordlist-based password audit.
- Checking the recovery result using the `--show` option.
- Verifying the recovered password by opening the original PDF.

**Project Documentation:** [View Project 01 – John the Ripper](./01-PASSWORD-CRACKING-WITH-JTR/)

### Project 02 – Web-Based PDF Password Auditing

**Tools:** Networkwalks Hash Calculator and Networkwalks Password Cracker

This exercise explored a browser-based approach to PDF password recovery using the Networkwalks online tools.

**Major activities:**

- Uploading the assigned PDF to the Networkwalks Hash Calculator.
- Selecting the PDF-specific hash extraction option.
- Extracting and copying the PDF password hash.
- Submitting the hash to Networkwalks Password Cracker.
- Selecting the built-in list of 100 passwords.
- Executing the password recovery process.
- Verifying the result by opening the original PDF.

**Project Documentation:** [View Project 02 – Networkwalks Tools](./02-PASSWORD-CRACKING-WITH-NETWORKWALKS-TOOLS/)

## 5. Skills and Learning Outcomes

The practical exercises provided hands-on experience in the following areas:

- **Password Hash Extraction:** Understanding how password-protected PDF documents can be prepared for password auditing.
- **Dictionary-Based Attacks:** Understanding how candidate passwords from a wordlist are tested against an extracted hash.
- **Command-Line Operations:** Executing password auditing commands using PowerShell and John the Ripper.
- **Web-Based Security Tools:** Exploring online hash extraction and password recovery workflows.
- **Result Verification:** Confirming recovered passwords by opening the original protected documents.
- **Security Awareness:** Understanding the importance of strong and unique passwords for protecting documents.

## 6. Comparison of Approaches

| Aspect | Project 01 | Project 02 |
|---|---|---|
| Approach | Command-line | Web-based |
| Main tool | John the Ripper Jumbo | Networkwalks Password Cracker |
| Hash extraction | OnlineHashCrack PDF Hash Extractor | Networkwalks Hash Calculator |
| Password candidates | `password.lst` | Built-in list of 100 passwords |
| Execution environment | Windows PowerShell | Web browser |
| Verification | Original PDF opened successfully | Original PDF opened successfully |

## 7. Security and Ethical Considerations

These exercises were performed for educational purposes using assigned training documents.

- Password auditing should only be performed on files that you own or have explicit authorization to assess.
- Password hashes and recovered passwords must be treated as confidential information.
- Original protected PDFs, extracted hashes, and recovered passwords are intentionally excluded from this public repository.
- Sensitive documents should not be uploaded to online tools without considering their privacy and data-handling policies.
- Password-cracking techniques must never be used for unauthorized access.

## 8. Conclusion

These practical exercises provided experience with two approaches to PDF password security assessment: a local command-line workflow using John the Ripper and a browser-based workflow using Networkwalks Tools.

By performing hash extraction, dictionary-based password recovery, and document verification, I gained a better understanding of how password auditing tools operate and why strong password practices are essential for protecting sensitive documents.

## 9. Author

**Harini Madasu**  
B.Tech – Mathematics and Computing  
Central University of Karnataka

**LinkedIn:** [Connect with me](https://www.linkedin.com/in/harini-madasu-91258b357)

**Training Program:** Network Walks – Cybersecurity Training  
**Batch:** B084  
**Week:** 03

---
