# MediConnect
A digital health platform connecting rural patients with qualified doctors - SDG 3

> **Healthcare for Everyone, Everywhere** > A digital public good connecting rural patients in Sierra Leone with qualified doctors via virtual consultations.

---

## 👥 Academic Project Team Info

| Full Name | University ID Number | Role / Contribution |
| :--- | :--- | :--- |
| **Berick Borbordeen Ajuno_Sesay** | 905005872 | Project Lead / UI Designer |
| **Amadu Borbor Bah** | 905005866| Frontend Developer |
| **Lennard Ben Kanu** | 905005868 | Systems Analyst |

* **Course:** PROG 102 — Principles of Software Engineering (2026)
* **Institution:** Limkokwing University of Creative Technology, Sierra Leone Campus
* **Supervisor:** Santigie Foday Kamara

---

## 📌 Overview & Problem Statement
MediConnect addresses the severe healthcare crisis where a majority of doctors are concentrated in Freetown. Patients in remote villages face costly, exhausting travel for basic care. This mobile platform bridges that gap by leveraging rising smartphone penetration to deliver free, immediate medical access.

* **SDG Target 3.8:** Directly aligns with UN Sustainable Development Goals to achieve universal, quality healthcare coverage for underserved communities.

---

## 🛠️ Key Platform Features

### For Patients
* **Symptom Checker:** Describe issues, tap an interactive body-part map, and select a severity rating.
* **Doctor Directory:** Browse and filter verified clinicians by specialty, experience, and real-time availability.
* **Booking & Consulting:** Reserve slots via an interactive calendar and attend appointments over video or live low-bandwidth chat.
* **Digital Prescriptions:** Receive, download, and share prescriptions instantly as PDFs.

### For Doctors & Admins
* **Clinicians:** Manage appointment lists, verify patient medical histories, and use a built-in prescription generator.
* **Admins:** Handle doctor credentials/licensing verification and monitor platform health metrics.

---

## 🏗️ Architecture & Planned Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend** | React Native (Mobile), React.js (Web), Figma (UI Design) |
| **Backend & Auth** | Node.js with Express, JWT (JSON Web Tokens) |
| **Database & Storage** | MySQL, AWS S3 (or local storage for PDFs) |
| **Communications** | Twilio/Agora API (Video/Chat), SendGrid (SMS/Email Alerts) |

---

## 📱 Prototype Framework (10 Key Screens)

The high-fidelity **Figma UI/UX prototype** is designed using a clean, accessible design token system:
* **Brand Colors:** Primary Green (`#1D9E75`), Dark Green (`#0F6E56`), Mint Green (`#E1F5EE`), Light Gray Background (`#F5F5F5`).

**View the interactive Figma prototype:**  
🔗 [https://www.figma.com/make/Uhf3wRNHtAMrhVrqqhFsOX/MediConnect?fullscreen=1&t=8Ofd1ikmGBsGZNUL-1&code-node-id=0-9]

### User Flow Roadmap
1. **Splash / Welcome:** Entry landing page redirecting users to Log In or Register.
2. **Patient Registration:** Multi-step signup form featuring Sierra Leone regional dropdowns.
3. **Doctor Registration:** Professional signup requiring a verifiable medical license number.
4. **Login Interface:** Tri-role credential portal split between Patient, Doctor, and Admin.
5. **Patient Dashboard:** Floating upcoming appointment summary cards and a 2x2 utility navigation grid.
6. **Doctor Directory:** Filterable doctor listings displaying real-time availability badges.
7. **Symptom Checker:** Active text inputs with diagnostic severity selectors.
8. **Book Consultation:** Live 7-column calendar matrix with adaptive hourly time slots.
9. **Consultation Room:** Dark-mode optimized call interface complete with audio/video toggles and data-saving chat fallbacks.
10. **Digital Prescription:** Verified medical documents containing automated PDF download and sharing actions.

---

## 📄 License
This project is licensed under the MIT License - see the open-source guidelines for full details.
