# toxiCALL® 5 Release Notes

## Version 5.0 Build 9693
### Upgrade from Build 9599

Build **9693** is a major GoLive milestone for **toxiCALL® 5**. This release emphasizes workflow refinement, production readiness, configurability, AI-assisted documentation, export reliability, and customer-requested usability enhancements identified during poison center testing.

More than **75 enhancements and fixes** are included, making this the most significant update since the original Release Candidate.

---

# What's New in Build 9693

## Live Validations

Live Validations provide immediate visual guidance as Specialists document cases. Required fields are highlighted as soon as validation rules determine they are needed, allowing users to resolve missing information before attempting to save or close a case.

### Highlights

- Real-time highlighting of required fields.
- Validation rules are configurable to support poison center-specific workflows.
- Highlight colors are user configurable for improved accessibility.
- Reduces incomplete documentation.
- Improves data quality and successful case closure.

> [!IMPORTANT]
> Live Validations guide Specialists throughout case entry instead of waiting until Save or Close to identify missing information.

---

## Artificial Intelligence

AI capabilities continue to expand throughout toxiCALL® 5.

### AI Case Summary

Generate concise summaries from reports, including **Case Detail Reports**, to quickly understand lengthy or complex cases.

### SmartPaste *(Technology Preview)*

SmartPaste analyzes narrative text and automatically populates many Case Entry fields.

**Highlights**

- Extract patient demographics.
- Extract exposure information.
- Populate Case Entry fields automatically.
- Reduce repetitive documentation.

> [!NOTE]
> SmartPaste remains an early preview feature. Accuracy will continue improving as additional poison center workflows are incorporated.

### AI Requirements

AI features require:

- OpenAI API Platform account
- OpenAI API key configured in Program Options
- Internet connectivity

AI usage is billed directly through your organization's OpenAI account. CAS does not add additional fees for AI usage.

Additional AI providers are being evaluated for future releases.

---

## Redesigned Case Review & Note Redaction

The Case Review workflow has been redesigned to improve review efficiency while simplifying note redaction prior to export.

- Streamlined review workflow
- Improved Next / Previous navigation
- Mark All / Restore All
- Improved Print Preview
- Improved export validation
- Automatic refresh after note redaction

---

## Intelligent Dropdown Filtering

Many lookup controls now support both **Begins With** and **Contains** search modes.

- Press **Ctrl+L** to switch search modes.
- Preference is remembered per control and per user.

---

## User-Defined Validation Rules

User-defined lookup values can inherit existing validation rules.

**Example**

Create a Status named **QA Review** and configure it to use the same validation behavior as **Closed**, eliminating the need for duplicate validation rules.

---

## Simplified Transfer Mapping

Transfer Mapping now supports user-defined lookup values.

**Example**

Create a custom Patient Gender and configure how it is reported to NPDS without custom programming.

---

## Enhanced ToxExport

- Improved validation
- Improved redaction messaging
- Required destination folder
- Related Case Number export
- Case Number Offset
- ZIP Code anonymization
- Saved export settings
- Improved filtering

---

## Improved Case Entry

- Expanded 24-hour time support
- Improved Healthcare Facility workflow
- Caller Site filtering
- ZIP Code copying
- Improved note entry
- Improved weight calculation

---

## Local Database & Migration

- Improved migration recovery
- Improved synchronization
- Enhanced SmartExtract™
- Improved Connection Manager
- Improved startup validation

---

# Enhancements & Fixes

Enhancements and fixes in this release are grouped by functional area for easier review.

## Case Entry
- #2410 — Follow-up Time calculation improvements.
- #2415 — Expanded 24-hour time support.
- #2509 — Weight calculation improvements.
- #2510 — Healthcare Facility filtering by Caller Site.
- #2511 — Populate Caller from Healthcare Facility.
- #2512 — Notes grid editing.
- #2513 — Hide Final HCF Copy button.
- #2515 — Substance PDF review.
- #2519 — Copy Patient or Caller ZIP Code.
- #2520, #2522, #2523, #2528, #2529 — Free Area and caller workflow improvements.

## Case Review & Export
- #2536, #2537, #2538 — Case Review workflow and Print Preview improvements.
- #2546, #2547 — Transfer Mapping and AutoUpload improvements.
- #2551, #2554, #2555, #2556, #2557, #2558, #2559, #2565, #2566, #2567, #2572, #2574 — ToxExport, Case Review, Note Redaction, anonymization, filtering, and export enhancements.

## Migration & Local Database
- #2477–#2482, #2488, #2491, #2495, #2507, #2532, #2533, #2543 — Migration, Local Database, startup, synchronization, and recovery improvements.

## Reporting, Dashboards & AI
- #2453, #2473, #2483, #2487, #2493, #2571, #2573 — Reporting, Dashboard, SmartPaste, AI Summary, and user interface improvements.

## Configuration & Administration
- #2474, #2475, #2479, #2484, #2485, #2486, #2492, #2500, #2501, #2504, #2508, #2516, #2518, #2530, #2531, #2535, #2540, #2541, #2542, #2549, #2550 — Configuration, System Tables, administration, validation, and platform improvements.

---

# GoLive Readiness

Development during this release cycle focused heavily on poison center feedback received during GoLive testing. Particular emphasis was placed on workflow refinement, documentation efficiency, export reliability, configurable validation rules, and production readiness.

---

# Looking Ahead

Future releases will continue expanding AI-assisted documentation, SmartPaste, reporting, configurable workflows, interoperability, and poison center-requested enhancements.

---

# Additional Release Notes

## System Requirements & Prerequisites

The installer automatically installs required Microsoft prerequisites when necessary.

### Microsoft .NET Desktop Runtime

- https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-10.0.5-windows-x64-installer

### Microsoft Visual C++ Redistributable

- https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe

### Microsoft Access Database Engine (Optional)

- https://www.microsoft.com/en-us/download/details.aspx?id=54920

> [!NOTE]
> The toxiCALL installer intentionally **does not install** the Microsoft Access Database Engine 2016 Redistributable.
>
> Install this component only on workstations that perform Microsoft Access (.MDB) exports, including RADARS and other MDB-based export formats.

---

## AutoUpload

The AutoUpload service is distributed separately.

- https://github.com/CASSupport/ToxicallWinAutoUploadUpdater

**Note:** Subscribe separately to receive AutoUpload release notifications.

---

## Feedback

Poison Center feedback is critical to the continued development of **toxiCALL®** and directly influences future releases.

---

## Release Notifications

Subscribe to receive notifications whenever new versions are released.

- https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/
