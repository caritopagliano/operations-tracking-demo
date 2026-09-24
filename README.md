# Consular Operations Suite & Case Tracking Ecosystem (Demo)

An end-to-end operational framework designed to resolve citizen intake bottlenecks, streamline bilingual communications, and establish proactive processing timeline tracking across consular and public service workflows.

---

## 🚀 Live Interactive Web Apps
- **[App 1: Intake & Pre-Appointment Orientation](https://caritopagliano.github.io/operations-tracking-demo/)**: Interactive self-service guide clarifying booking procedures and document prerequisites before scheduling an appointment, eliminating avoidable email inquiries.
- **[App 2: Bilingual Confirmation Generator](https://caritopagliano.github.io/operations-tracking-demo/appointment-email-generator-demo.html)**: 1-click bilingual (UK/ES) email template copy tool with custom date/time selection and clear document checklists.
- **[App 3: Daily Intake Data Normalizer](https://caritopagliano.github.io/operations-tracking-demo/daily-intake-data-normalizer-demo.html)**: Clean ingestion tool that normalises system-logged daily intake records into a standard 7-column schema ready to paste into tracking sheets.

---

## 📊 Operations Hub: Tracking Matrix & Overview

![Executive Dashboard Preview](https://caritopagliano.github.io/operations-tracking-demo/dashboard-preview.png)

### 🔗 Spreadsheet Model & Governance:
- **[Interactive Google Sheets (Live Web Preview)](https://docs.google.com/spreadsheets/d/1xzHYt2N249V33yz2WzebO4KB775dw9X5/preview)** *(Click to view all 4 tabs, formulas, and dynamic timeline alert flags directly in your browser)*
- **[Download Raw Spreadsheet (.xlsx)](./operations-tracking-matrix-demo.xlsx)** *(Compatible with Google Sheets & Excel 2016+)*

---

## 📁 Operational Governance & Documentation
- **[Standard Operating Procedure (SOP) Manual (PDF)](./standard-operating-procedure-sop-demo.pdf)**: 1-page visual desk reference standardising workflows across all 4 operational phases for rapid onboarding and role rotation.

---

## 🏗️ Architecture & Operational Lifecycle

```text
[ Citizen Inquiry ] ➔ [ 1. Orientation & Triage ] ➔ [ 2. Confirmation Generator (1-Click Copy) ]
                                                                   │
                                                            (Appointment)
                                                                   │
[ Incoming Consignment ] ➔ [ 3. Daily System Intake Normalizer ] ➔ [ 4. Matrix & Timeline Tracking ]
                                                                   │
                                                              (Delivery)
                                                                   │
                                                        [ Completed / ARCHIVED ]
