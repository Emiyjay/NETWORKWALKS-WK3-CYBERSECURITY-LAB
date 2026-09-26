# NETWORKWALKS — WEEK 3 CYBERSECURITY LAB

## Password Cracking with John the Ripper and NetworkWalks Tools

**Program:** NetworkWalks Cybersecurity Program  
**Week:** 03  
**Student:** Emmanuel John  
**Required Modules:** W3-PM1 and W3-PM2  
**Status:** Completed

## Overview

Week 3 covered password-security testing in an authorized educational laboratory.

### Mandatory modules
- **W3-PM1 — Password Cracking with JTR**
- **W3-PM2 — Password Cracking with NetworkWalks Tools**

The practical objective was to recover the password of an instructor-provided protected PDF through two authorized workflows and verify the result by opening the protected file.

> **Authorization and scope:** Testing was limited to the instructor-provided laboratory material. No third-party account, system, or credential was targeted.

## W3-PM1 — John the Ripper

Workflow completed:

1. Obtain the authorized protected PDF.
2. Extract the PDF password hash.
3. Save the extracted hash as the JTR input.
4. Load the hash into John the Ripper / Johnny.
5. Run the password-recovery process.
6. Observe the recovery result.
7. Verify the recovered password against the protected PDF.

**Tools:** John the Ripper, Johnny GUI, PDF hash extraction workflow, Windows.

## W3-PM2 — NetworkWalks Tools

Workflow completed:

1. Obtain the authorized protected PDF.
2. Use the NetworkWalks Hash Calculator to extract the PDF hash.
3. Submit the hash to the NetworkWalks Password Cracker.
4. Run the dictionary-based recovery process.
5. Observe the recovery result.
6. Verify the result by opening the protected PDF.

**Tools:** NetworkWalks Hash Calculator, NetworkWalks Password Cracker, web browser.

## Evidence Available for Submission

The practical evidence currently available for upload consists of:

- Three screenshots showing the locked PDF laboratory files.
- Week 3 completion/congratulations screenshot.
- CTF ID screenshot.

Additional screenshots can be added to the Evidence directory later if required by the submission rubric.

## Evidence Handling

For public GitHub publication, do **not** expose:
- Complete password hashes
- Recovered passwords
- Credentials
- Cookies or session tokens
- Private personal information
- Unnecessary sensitive laboratory data

The evidence should demonstrate completion without publishing secrets.

## Comparison

| Area | JTR / Johnny | NetworkWalks Tools |
|---|---|---|
| Environment | Local installation | Web browser |
| Hash preparation | PDF hash extraction | Hash Calculator |
| Recovery interface | JTR / Johnny | Web interface |
| Wordlist approach | JTR configuration | Built-in/uploadable list |
| Learning focus | Local password-security testing | Educational password-recovery workflow |

Both workflows demonstrate the same security concept:

**Protected file → hash extraction → password candidates → matching process → verification**

## Security Lessons

The exercises demonstrate why password strength matters. Password-recovery testing can be used in an authorized environment to evaluate how resistant protected material is to guessing and dictionary-based attacks.

A security practitioner should also protect the recovered password and extracted hash as sensitive information rather than publishing them in a public repository.

## Conclusion

Week 3 provided practical experience with password-security testing using both a locally installed toolset and a browser-based educational workflow. The work reinforced password security, hash handling, authorization, evidence collection, and responsible cybersecurity practice.

---

**NetworkWalks — Week 03**
