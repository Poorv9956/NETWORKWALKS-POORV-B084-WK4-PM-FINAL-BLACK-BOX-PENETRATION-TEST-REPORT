# NETWORKWALKS-POORV-B084-WK4-PM-FINAL-BLACK-BOX-PENETRATION-TEST-REPORT

linkedin post link - https://www.linkedin.com/feed/foryou/

# Week 4 Penetration Testing Project — Mediroza General Hospital

**Program:** Networkwalks Cybersecurity Internship  
**Target:** `https://medirozahospital.com` (Authorized Lab Environment)  
**Assessment Type:** Black-Box Penetration Test & Vulnerability Assessment (5 Days)  
**Author:** Poorv Patel  

> **Authorization & Ethics Notice:** All testing was performed strictly within an authorized training environment with written permission for educational and defensive security purposes. Sensitive data has been omitted/sanitized from public repository files.

---

## Overview
This repository documents the Week 4 black-box penetration testing engagement against `medirozahospital.com`, covering reconnaissance, initial portal access, offline password cracking of protected PDFs, metadata/backup exposure analysis, risk rating, and remediation guidance.

## Milestones Completed
* **Milestone 1 — Initial Access:** Identified exposed entry points and authentication weaknesses on the patient portal to access three restricted pathology lab report PDFs.
* **Milestone 2 — Password Cracking:** Extracted hashes and applied tailored cracking approaches (including pattern/character-set cracking such as `!@#$%^&` on the third report) to decrypt all three files.
* **Milestone 3 — Data Exposure Analysis:** Examined file properties and server exposure (`mediroza_db_backup_2019.sql`) to demonstrate the impact of exposed backups and sensitive organizational records.
* **Milestone 4 — Penetration Testing Report:** Produced a structured report covering Executive Summary, Scope & Methodology, Findings & Proof of Exploitation, Risk Ratings, and Remediation Recommendations.

## Tools & Environment
* **Testing & Analysis:** Kali Linux, `pdf2john`, John the Ripper (JTR) / Johnny, `qpdf`, `exiftool`, `wget`, `grep` / `less`, Python 3
* **Documentation & Review:** Windows GUI tools, Markdown / PDF / DOCX reporting

## Repository Structure
* `week-04-mediroza-pentest/report/` — Final penetration testing report
* `week-04-mediroza-pentest/screenshots/` — Sanitized evidence screenshots across milestones
* `week-04-mediroza-pentest/notes/` — Methodology notes and remediation checklist
<img width="1600" height="1600" alt="WhatsApp Image 2026-11-26 at 8 16 05 AM (1)" src="https://github.com/user-attachments/assets/c2e9a2ec-18a8-4eac-bc69-403117ef34a2" />
<img width="1600" height="1600" alt="WhatsApp Image 2026-11-26 at 8 16 05 AM" src="https://github.com/user-attachments/assets/4d0040e2-b068-48cf-800e-7dffa03052a8" />
<img width="1600" height="1600" alt="WhatsApp Image 2026-11-26 at 8 16 05 AM (3)" src="https://github.com/user-attachments/assets/b29d9e83-f129-4caa-b662-56f36d0e78d2" />
<img width="1600" height="1600" alt="WhatsApp Image 2026-11-26 at 8 16 05 AM (2)" src="https://github.com/user-attachments/assets/ab94b7ac-9eb3-48f1-8d38-4e25bed2cff7" />
![Uploading Screenshot_2026-11-24_12_21_28.png…]()
![Uploading Screenshot_2026-11-24_12_17_25.png…]()

