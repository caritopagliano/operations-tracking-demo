# Consular Operations Suite & Case Tracking Ecosystem (Demo)

An end-to-end operational framework designed to resolve citizen intake bottlenecks, automate bilingual communications, and establish proactive SLA case tracking across consular and public service workflows.

---

## 🚀 Live Interactive Web Apps
- **[App 1: Intake & Eligibility Triage](https://caritopagliano.github.io/operations-tracking-demo/)**: Interactive self-service routing ensuring applicants meet document prerequisites prior to booking an in-person slot.
- **[App 2: Bilingual Confirmation Generator](https://caritopagliano.github.io/operations-tracking-demo/appointment-email-generator-demo.html)**: 1-click bilingual (UK/ES) email dispatch with exact fee breakdowns and mandatory checklists.
- **[App 3: Daily Intake Data Normalizer](https://caritopagliano.github.io/operations-tracking-demo/daily-intake-data-normalizer-demo.html)**: Automated stream ingestion and 7-column data hygiene tool featuring pre-loaded sample data.

---

## 📊 Operations Hub: Executive Dashboard & Tracking Matrix

![Executive Dashboard Preview](https://caritopagliano.github.io/operations-tracking-demo/dashboard-preview.png)

### 🔗 Spreadsheet Model & Governance:
- **[Interactive Google Sheets (Live Web Preview)](https://docs.google.com/spreadsheets/d/1xzHYt2N249V33yz2WzebO4KB775dw9X5/preview)** *(Click to view all 4 tabs, formulas, and dynamic SLA status flags directly in your browser)*
- **[Download Raw Spreadsheet (.xlsx)](./operations-tracking-matrix-demo.xlsx)** *(Compatible with Google Sheets & Excel 2016+)*

---

## 📁 Operational Governance & Documentation
- **[Standard Operating Procedure (SOP) Manual (PDF)](./standard-operating-procedure-sop-demo.pdf)**: 1-page visual desk manual standardising workflows across all 4 operational phases.

---

## 🏗️ Architecture & Operational Lifecycle

```text
[ Citizen Inquiry ] ➔ [ 1. Triage Assistant ] ➔ [ 2. Confirmation Generator ]
                                                          │
                                                    (Appointment)
                                                          │
[ Courier Pouch Arrives ] ➔ [ 3. Barcode Batch Intake ] ➔ [ 4. Matrix & Dashboard ]
                                                          │
                                                    (Handover)
                                                          │
                                            [ End-of-Day Slip Scanning ] ➔ [ ARCHIVED ]
