# 🚗 Automotive Airbag ECU — Project Team Readiness & Skills Repository

> **Hochschule Harz · PMI Course: Generative AI for Project Managers**  
> Project Charter Ref: `LCP01-AIRBAG-ECU-001` · Safety Classification: ISO 26262 ASIL D / IEC 61508 SIL 3  
> Project Manager: Alita Shrestha · Date: June 2026

---

## 📌 What This Repository Contains

This repository documents a complete **AI-assisted project management workflow** applied to a real safety-critical engineering project at Hochschule Harz. Starting from 11 LinkedIn profiles and a project charter PDF, we used Generative AI (Claude) to build a full team skills management system — from raw data to executive dashboards.

---

## 📁 Repository Contents

| File | Type | Description |
|------|------|-------------|
| `Talent_Skills_Registry.xlsx` | Excel Spreadsheet | Central team skills database. Populated from 11 LinkedIn profiles. Includes proficiency levels, experience, education, and certifications for all team members. |
| `Team_Skills_Dashboard.html` | Interactive HTML | Visual overview of the team's collective skills and experience. Open in any browser — no installation needed. Features drill-down by skill domain, radar charts per member, heatmap, and bubble chart. |
| `Airbag_ECU_Project_Charter.pdf` | PDF | Original project charter for the Automotive Airbag ECU Simulation System. The source document used for all skills and gap analysis. |
| `Airbag_ECU_Skills_Competencies.docx` | Word Document | Comprehensive list of all 44 skills and competencies required by the project. Organised by domain with priority ratings, proficiency requirements, and responsible roles. |
| `Airbag_ECU_Gap_Analysis.docx` | Word Document | Detailed comparison of current team capabilities against project requirements. Includes role coverage assessment, domain gap tables, and a 10-point priority action plan. |
| `Airbag_ECU_Training_Plan.docx` | Word Document | Specific learning resources for every skill gap — courses, providers, durations, costs, and direct links. Includes role-specific learning paths and a budget estimate. |
| `Skills_Gap_Executive_Dashboard.html` | Interactive HTML | Executive-facing dashboard translating all gap analysis findings into visual, jargon-free charts and summaries. Open in any browser. Hover over underlined terms for plain-English tooltips. |
| `Process_Summary_Guide.docx` | Word Document | Step-by-step explanation of everything built in this project — ideal for anyone new to AI-assisted project management workflows. |
| `README.md` | Markdown | This file. |

---

## 🚀 Quick Start

### To view the dashboards
1. Download `Team_Skills_Dashboard.html` and/or `Skills_Gap_Executive_Dashboard.html`
2. Double-click the file to open it in any web browser (Chrome, Firefox, Edge, Safari)
3. No internet connection required — all resources are embedded or loaded from public CDNs
4. Both dashboards are fully interactive — click, hover, and explore

### To view the Word documents
1. Download any `.docx` file
2. Open with Microsoft Word, Google Docs, or LibreOffice Writer

### To view the spreadsheet
1. Download `Talent_Skills_Registry.xlsx`
2. Open with Microsoft Excel, Google Sheets, or LibreOffice Calc

---

## 🗂 Suggested Reading Order

If you're new to this project, read/explore in this order:

```
1. Airbag_ECU_Project_Charter.pdf      ← What the project is about
2. Talent_Skills_Registry.xlsx          ← Who is on the team and what they can do
3. Team_Skills_Dashboard.html           ← Visual overview of team skills
4. Airbag_ECU_Skills_Competencies.docx ← What skills the project needs
5. Airbag_ECU_Gap_Analysis.docx        ← Where the gaps are
6. Skills_Gap_Executive_Dashboard.html  ← Executive summary (best for presentations)
7. Airbag_ECU_Training_Plan.docx       ← How to close the gaps
8. Process_Summary_Guide.docx           ← How all of this was created
```

---

## 🤖 How This Was Built — AI-Assisted Workflow

All documents and dashboards in this repository were created using **Generative AI (Anthropic Claude)** as a project management assistant. Here is the high-level workflow:

```
LinkedIn PDFs (11 files)
        ↓
   AI extracts & normalises data
        ↓
  Talent_Skills_Registry.xlsx
        ↓
   AI generates interactive dashboard
        ↓
  Team_Skills_Dashboard.html
        ↓
Project Charter PDF → AI analyses requirements
        ↓
  Skills_Competencies.docx
        ↓
   AI compares team vs. requirements
        ↓
  Gap_Analysis.docx + Training_Plan.docx
        ↓
   AI translates findings for executives
        ↓
  Executive_Dashboard.html
```

**No manual data entry was required.** The AI read the PDFs, extracted structured data, normalised it, identified patterns, wrote the analysis, generated the code for the dashboards, and created the Word documents — all from natural language instructions.

---

## 🛠 Technologies Used

| Tool / Technology | Used For |
|---|---|
| **Anthropic Claude** (Generative AI) | All data extraction, analysis, writing, and code generation |
| **Python + pdfplumber** | Extracting text from LinkedIn profile PDFs |
| **Python + openpyxl** | Creating and populating the Excel talent registry |
| **HTML + CSS + JavaScript** | Interactive dashboard front-end |
| **Chart.js 4.4.1** | Data visualisation (donut, radar, bar, bubble charts) |
| **Google Fonts (Inter)** | Dashboard typography |
| **Node.js + docx library** | Generating formatted Word documents programmatically |
| **Microsoft Word** | Viewing `.docx` deliverables |

---

## 📊 Dashboard Features

### Team Skills Dashboard (`Team_Skills_Dashboard.html`)
- **Donut chart** — proficiency level distribution across the team
- **Radar chart** — individual member vs. team average comparison
- **Experience bar chart** — years of experience per member
- **Domain strength bars** — clickable bars drill down into each skill domain
- **Skill heatmap** — interactive grid showing every member × every skill domain
- **Bubble chart** — experience vs. skill score, sized by certifications
- **AI-generated insights** — automatically identified strengths, concentration risks, and development priorities
- **Dark/light mode** — automatically follows your system preference

### Executive Dashboard (`Skills_Gap_Executive_Dashboard.html`)
- **8 KPI cards** — readiness metrics in plain language
- **Role coverage donut** — 14 roles mapped visually
- **Domain gap bars** — stacked bars showing current vs. required capability
- **14 role cards** — clickable, colour-coded (green/amber/orange/red)
- **11 team member cards** — individual fit assessment
- **Priority action plan** — 3-column timeline (Immediate / Short-Term / Medium-Term)
- **Investment table** — full training cost breakdown
- **Glossary** — 12 technical terms explained in plain language
- **Tooltips** — hover over any underlined term for a jargon-free explanation

---

## 👥 Team (Anonymised)

Team member names in the dashboards and Word documents have been anonymised with fictional names to protect privacy. The original real names are held in the project's internal records.

| Anonymised Name | Role in Project |
|---|---|
| Maya Torres | Project Manager & Software Dev Lead |
| Sofia Brennan | Electrical & Automation Engineer |
| Nadia Kowalski | E-CRM & Marketing Specialist |
| Lucas Chen | Automation & IIoT Engineer |
| Aryan Mehta | Research Assistant / Ex-Software Engineer |
| Priya Nakamura | Product Manager / Manufacturing |
| Kai Lindberg | Project Engineer |
| Dev Okafor | System Engineer / Ex-Infosys |
| Felix Wagner | Industrial Engineering Intern |
| Rohan Patel | Junior Project Engineer |
| Ethan Rossi | Production Engineer |

---

## ⚠️ Key Findings Summary

| Finding | Detail |
|---|---|
| **Roles ready** | 1 out of 14 (Project Manager — Maya Torres) |
| **Roles needing training** | 9 out of 14 |
| **Roles with no candidate** | 4 out of 14 (Safety Manager, 2× Risk Analysts, Testing Lead) |
| **Safety standards coverage** | 0% — no team member has formal ISO 26262 / IEC 61508 training |
| **Most critical action** | Hire or contract a certified Functional Safety Manager immediately |
| **Team training cost** | €3,500 – €6,500 (excluding external specialists) |
| **External specialist cost** | €10,000 – €40,000+ (Safety Manager + Testing Engineer) |

---

## 📋 Project Charter Key Facts

| Item | Detail |
|---|---|
| **Project Title** | Development and Functional Safety Compliance Certification of an Automotive Airbag ECU Simulation System |
| **Safety Level** | ISO 26262 ASIL D / IEC 61508 SIL 3 (highest automotive safety tier) |
| **Hardware** | Dual Arduino Due (SAM3X8E ARM Cortex-M3), CAN Bus 500kbit/s, DM74LS08N AND-gate |
| **Architecture** | 2oo2 (Two-out-of-Two) dual-redundant voting system |
| **Software Modules** | 6 modules: POST, Acquisition, Crash Detection, Deployment Control, CAN Communication, Diagnostic Monitoring |
| **Key Deliverables** | D01 Engineering Dossier, D02 HIL Prototype, D03 ASIL-D Firmware, D04 V&V Reports, D05 Presentation |
| **Integration Tests** | 16 tests (IT-01 to IT-16), 100% MC/DC + statement + branch coverage required |
| **Team Size** | 14 formal roles |

---

## 📄 License

This repository is for educational purposes as part of the PMI course on Generative AI for Project Managers at Hochschule Harz. Documents are confidential and intended for internal project use.

---

## 👤 Author

**Alita Shrestha**  
Project Manager — Automotive Airbag ECU Functional Safety Project  
Hochschule Harz (HS Harz) · Department of Automation and Computer Science  
📧 alitainbox@gmail.com

---

*Generated with the assistance of Anthropic Claude · June 2026*
