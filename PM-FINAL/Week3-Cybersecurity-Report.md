# WEEK 3 CYBERSECURITY PRACTICAL REPORT

## Password Cracking with JTR and NetworkWalks Tools

**Student:** Emmanuel John  
**Program:** NetworkWalks Cybersecurity Program  
**Week:** 03  
**Modules:** W3-PM1 and W3-PM2

## 1. Introduction
Week 3 focused on password security testing using an instructor-provided protected PDF in a controlled educational environment.

The two mandatory modules were W3-PM1 — Password Cracking with John the Ripper and W3-PM2 — Password Cracking with NetworkWalks Tools.

## 2. Authorization and Scope
Testing was restricted to the protected PDF supplied for the NetworkWalks laboratory. No third-party accounts, systems, credentials, or personal files were targeted.

The recovered password and complete hash are omitted from this public report because they are unnecessary for demonstrating the methodology and should not be published.

## 3. W3-PM1 — John the Ripper
The protected PDF was converted into the required PDF hash representation. The hash was saved as input for John the Ripper.

Johnny was configured to use the John the Ripper executable. The hash file was loaded and a password-recovery attack was started.

The recovered password was entered into the original laboratory PDF. The document opened successfully, confirming the recovery result.

## 4. W3-PM2 — NetworkWalks Tools
The protected PDF was uploaded to the NetworkWalks Hash Calculator, which generated the required PDF hash.

The hash was supplied to the Password Cracker. A dictionary-based attack tested candidate passwords against the hash and reported a successful match.

The recovered password was entered into the protected PDF and the document opened successfully.

## 5. Comparison

| Category | JTR / Johnny | NetworkWalks Tools |
|---|---|---|
| Environment | Local Windows installation | Web browser |
| Hash extraction | Separate PDF hash extraction workflow | Built-in Hash Calculator |
| Cracking engine | John the Ripper | NetworkWalks Password Cracker |
| Interface | Command line and GUI | Web interface |
| Wordlist approach | JTR attack configuration | Built-in/uploadable wordlist |
| Learning focus | Professional password-testing workflow | Simplified educational workflow |

Both methods followed the same conceptual sequence: protected file → extract hash → test candidate passwords → identify match → verify.

## 6. Security Analysis
Password protection is only as strong as the password and protection mechanism used.

A short, common, or dictionary-listed password may be recovered more readily by an appropriate password-testing process. Attack difficulty also depends on the protection scheme, computational resources, attack strategy, and wordlist quality.

## 7. Key Lessons
1. Password hashes are not plaintext passwords.
2. Password-recovery tools test candidate passwords against stored verification material.
3. Dictionary attacks are particularly effective against common passwords.
4. Strong, unique passwords reduce the effectiveness of simple guessing attacks.
5. Security testing should be performed only against authorized targets.
6. Technical evidence should be documented without unnecessarily publishing secrets.

## 8. Evidence
Evidence should include JTR setup, PDF hash extraction, Johnny attack progress, successful JTR recovery, NetworkWalks Hash Calculator, Password Cracker result, and final PDF verification.

Sensitive values should be redacted before publication.

## 9. Limitations
The exercise used an instructor-provided laboratory PDF and a controlled password-recovery scenario. Results should not be interpreted as representative of every PDF encryption configuration or password.

The exercise focused on dictionary-based recovery rather than comprehensive password auditing.

## 10. Conclusion
Week 3 provided practical experience with password security testing using two different workflows.

John the Ripper demonstrated a dedicated password-testing workflow, while the NetworkWalks tools provided a simpler browser-based workflow.

The practical reinforced the importance of strong, unique passwords, authorization, evidence handling, and responsible security testing.
