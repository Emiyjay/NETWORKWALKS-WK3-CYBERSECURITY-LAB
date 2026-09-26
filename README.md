# NETWORKWALKS — WEEK 3 CYBERSECURITY LAB

## Password Cracking with John the Ripper and NetworkWalks Tools

**Program:** NetworkWalks Cybersecurity Program  
**Week:** 03  
**Student:** Emmanuel John  
**Required Modules:** W3-PM1 and W3-PM2  
**Status:** Completed

## Overview

Week 3 focused on password security testing in an authorized educational lab environment.

The two essential modules completed were **W3-PM1 — Password Cracking with JTR** and **W3-PM2 — Password Cracking with NetworkWalks Tools**.

The objective was to recover the password of the instructor-provided protected PDF using two different workflows and verify the recovered password by opening the PDF.

> Authorization: These activities were performed only against the instructor-provided laboratory PDF. No third-party account, system, or password was targeted.

## W3-PM1 — John the Ripper

1. Obtain the authorized protected PDF.
2. Extract the PDF password hash.
3. Save the hash as the JTR input.
4. Load it into John the Ripper/Johnny.
5. Run the password-recovery attack.
6. Record the successful result.
7. Verify the recovered password by opening the protected PDF.

**Tools:** John the Ripper, Johnny GUI, PDF hash extraction workflow, Windows.

## W3-PM2 — NetworkWalks Tools

1. Obtain the authorized protected PDF.
2. Upload it to the NetworkWalks Hash Calculator.
3. Extract the PDF hash.
4. Submit the hash to the NetworkWalks Password Cracker.
5. Run the dictionary-based recovery process.
6. Record the successful result.
7. Verify the recovered password by opening the protected PDF.

**Tools:** NetworkWalks Hash Calculator, NetworkWalks Password Cracker, web browser.

## Comparison

| Area | JTR / Johnny | NetworkWalks Tools |
|---|---|---|
| Environment | Local installation | Web browser |
| Hash preparation | PDF hash extraction | Built-in Hash Calculator |
| Cracking interface | JTR / Johnny | Web interface |
| Wordlist | JTR configuration | Built-in/uploadable list |
| Learning focus | Professional password testing | Educational workflow |

Both methods follow the same concept: **protected file → hash → candidate passwords → match → verification**.

## Security Lessons

A password hash is not the plaintext password. Password-recovery tools test candidate passwords against stored verification material.

Weak or common passwords can be more susceptible to dictionary-based guessing. Strong, unique passwords make simple guessing attacks more difficult.

## Public Repository Safety

Do not commit the original protected PDF, complete password hash, recovered password, credentials, cookies, tokens, or other sensitive material.

## Evidence

Recommended sanitized evidence:

- JTR/Johnny setup
- Hash extraction
- JTR recovery result
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker result
- Protected PDF verification

## Conclusion

Week 3 provided practical experience with password-security testing using both a locally installed professional tool and a browser-based educational workflow. The exercises reinforced password strength, authorization, evidence handling, and responsible security testing.

---

**NetworkWalks — Week 03**
