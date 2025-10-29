# GRC Documentation Tool Kit

**Production-ready starter kit to stand up a Security Governance, Risk & Compliance (GRC) program**—from policies and control catalogs to audit-ready evidence packs—tailored for **Startup**, **SME**, and **Advanced/Enterprise** teams.

> Built by Dulara Paranawidana GRC specialist to make real-world compliance *practical*: consistent folder structures, lean templates with embedded “how-to” pages, evidence indexes, and automation hooks.

---

## ✨ What’s inside

- **Document Catalogs (3 tiers):** curated lists by category (Governance, Risk, Compliance, Privacy, SecOps/IR, TPRM, Reporting).
- **Ready-made Folder Structures:** ISO 27001 & SOC 2 aligned trees for Startup, SME, and Advanced programs.
- **Automation-friendly Filenames:** versioning (`vX.X`) and cadence markers (`Qx_YYYY`, `MM-YYYY`) to encode ownership & review cycles.
- **Evidence Index Patterns:** requirements → controls → procedures → **evidence** for clean audits.
- **Batch Scripts (.bat):** one-click generators to scaffold the trees on Windows.

---
<img width="2305" height="1063" alt="Screenshot 2025-10-29 232208" src="https://github.com/user-attachments/assets/20619cc8-1076-4a14-810d-c36e5b710226" />

## 🧩 Templates with Embedded Prep Guides

I’ve done **extensive research** and built **sample templates for every document**.  
**Each template includes a one-page “How to Prepare” guide right on page 1** (scope, inputs, reviewers, approval, versioning, maintenance).

- **Templates root:** [`/templates/`](/templates/)
- **Workbooks (catalogs + folder maps):** [`/workbooks/`](/workbooks/)
- **Scaffolding scripts (.bat):** [`/scripts/`](/scripts/)

> In the **Document Catalog workbook** (`/workbooks/Cyber_GRC_Document_Catalog_*.xlsx`), every row includes a **hyperlink** to its template so you can open the file and follow the embedded guide immediately. The catalog also tracks **Owner**, **Cadence**, **Frameworks**, and **Evidence** for each artifact.

---

## 🚀 Quick start

1. **Pick your tier**
   - **Startup (Basic)** – essential minimums for early teams.
   - **SME (Medium)** – scaled controls readying you for ISO/SOC 2.
   - **Advanced (Practitioner)** – full ISMS scope with SoA, audits, BIA/BCP/DR.
   - 
<img width="2479" height="1125" alt="Screenshot 2025-10-29 232350" src="https://github.com/user-attachments/assets/d989fc8d-542c-4fbb-b7a5-d4921db9f9f7" />

2. **Generate folders**

   - Use the `.bat` scripts in [`/scripts/`](/scripts/) to scaffold the tree (optionally pass a target path).

5. **Open the workbook**
   - Prioritize in **Document Catalog**.
   - Follow paths in **Folder Structure**.
   - Populate templates; store **evidence** in the dated folders created by the scripts.

---

## 🗂️ Tiers at a glance

| Tier | Use when… | Focus | Typical outcome |
|---|---|---|---|
| **Startup (Basic)** | early-stage, lean team | top policies, IR checklist, vendor DDQ, risk register | pass customer security reviews; reduce incident chaos |
| **SME (Medium)** | growing org, pre-cert | control testing cadence, mapping matrix, DPIAs, BCP/DR core | ISO/SOC 2 readiness in 6–12 months |
| **Advanced (Practitioner)** | formal ISMS/SOC 2 program | SoA, internal audits, evidence packs, CCM | sustained certification & audit efficiency |

---

## 🖼️ Screenshots

_Add your screenshots here (workbooks, folder structures, template front pages, dashboards)._

---

## 🧭 What I learned from this project

- **Operationalizing GRC beats theory:** clear folder structures + embedded “how-to” pages reduce ambiguity and speed up adoption.  
- **Traceability is everything:** mapping **requirements → controls → procedures → evidence** eliminates audit thrash.  
- **Right-sizing matters:** adoption improves when artifacts are tiered (Startup / SME / Advanced) instead of one rigid framework.  
- **Automation helps humans:** predictable filenames/paths (`Qx_YYYY`, `vX.X`) make reviews and evidence exports painless.

---

## 🛠️ Upgrades in progress

- PowerShell & Bash scaffolders (prompts, safety checks, date-stamping)  
- **Evidence Binder Index** + smart PBC tracker integrated with the catalog  
- SOC 2 narrative shells (CC1–CC9) aligned to the control catalog  
- Git-friendly `.gitattributes` / `.gitignore` for policy repos  
- Optional CI (GitHub Actions) to nudge owners before review due dates

---

## 🤝 Availability

I’m making the **entire toolkit freely available to the community soon**.  
This repo currently includes the **workbooks**, **folder scaffolding scripts**, and **starter templates with embedded guides**, with more templates and automation landing in upcoming updates.

---

## 📝 License

Choose a license that matches your distribution intent (e.g., **MIT** for code, **CC BY 4.0** for docs) and add a `LICENSE` file at the repo root.
