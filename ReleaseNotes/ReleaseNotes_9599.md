## Release Notes

> ### 🚀 Major Update: Local Database, Offline Mode, and Performance Enhancements  
> This release introduces a significant advancement in toxiCALL® 5, enabling faster performance over wide area networks, improved reliability, and continued case entry even when the network is unavailable.

---

## Notable Updates

- This version includes an update to **AutoUpload**
- **Local Database** is now available in toxiCALL® 5
- **Offline Mode** allows continued case entry when the Network Database is unavailable
- **Follow-up date/time can now be assigned directly from the Case List**
- **.NET 10 Desktop Runtime** is now required for this release

[Please note AutoUpload is a separate download, located here](https://github.com/CASSupport/ToxicallWinAutoUploadUpdater)  
**Note:** You will need to subscribe separately for the AutoUpload application.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.

[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/)

---

## 1. Update to .NET 10

- The installer will check this prerequisite automatically
- Manual download links are also available at the end of these release notes

---

## 2. Local Database

- Optimized for improved performance over slow or wide area network connections
- Includes background upload and download of cases between Local and Network databases
- **Local Mode:** Log into the Local Database  
- **Network Mode:** Log into the Network Database  
- Supports **SQLite** or **SQL Express** Local Database configurations
- Option to maintain:
  - A shared workstation Local Database  
  - Individual Local Databases per user
- Ability to save cases to the Network Database while continuing work locally
- Notifications when cases remain on the Local Database during startup or exit to reduce locked records

**Local Database Documentation:**  
NEED LINK TO LOCAL DB INSTRUCTIONS

---

## 3. Login Window

- Support to log into either the Local or Network Database
- Option to refresh local system tables
- Support for **Offline Mode**:
  - Enables rapid login without network validation  
  - Requires the Local Database to be up to date

---

## 4. Case List Enhancements

- Font size and style override options for the Case List
- Ribbon items available from the Case List **Home** menu
  - Includes new **And/Or Criteria** keyboard options
- Recent **Searches** and **Reports** accessible directly from the Home menu
- Support to enable or disable inline editing in grid views
- New **Open** and **Open as Read Only** options
- Assign **follow-up date/time directly from the Case List**
  - Designed for centers not assigning cases to specific SPIs

---

## 5. Case Entry Enhancements

- Updated default layout with improved tab organization and reduced scrolling
- Enhancements to save actions:
  - **Save & Close**
  - **Save & New**
- Support for adding new lookup values (e.g., status, gender) tied to validation rules
- Ability to **Add Case Notes** while viewing a case in read-only mode

### New Enhancements
- Optimized filtering for **Healthcare Facility selection**
- Improved support for **multiple Substance/Product lookups**
- Retention of **Substance/Product lookup page** for future reference and auditing
- Enhanced **keyboard entry for Patient details**

---

## 6. User Defined Lookup Values

- Create custom values for fields such as **Case Status** and **Patient Gender**
- Map new values to existing values for validation logic
  - Example: “QA Required” behaves like a closed case
- Map custom values to **NPDS-required values** for submission compliance

---

## 7. General Changes

- **AutoReplace Dictionary** renamed to `Sample_AutoReplaceDictionary.en.txt` in the AutoReplace folder
  - Can be customized per workstation if desired
  - Change based on feedback that the default dictionary was not broadly useful
- **Reports Management** moved to **Configuration** in the Navigation Bar
  - Reduces confusion about how to run reports
- Reports are now accessed via the **Ribbon Bar** in the Case List
- **Favorites support** added for:
  - Reports  
  - Lookup lists  
  - Dashboards  
  - Other frequently used items  
  - *Note: Report favorites do not currently retain filter criteria. This will be addressed in a future update.*

---

## 8. Dashboards

- Dashboards now support **Auto Refresh**
  - Default interval: **60 seconds**
  - Must be manually enabled at this time  
  - Future updates will support automatic startup and auto-enable behavior
- Configurable refresh interval allows better real-time monitoring

---

## 9. Reports

- Improved access to reports, filters, and tools via the Case List **Home** menu
- Over **110 reports redeveloped** in toxiCALL® 5
- Reports continue to undergo validation and confirmation by poison centers
- New **Case Detail Redacted Report**
  - Displays only notes marked as redacted
  - Non-redacted notes are excluded

---

## 10. NPDS Updates

- NPDS-related updates delivered through **System Tables**
- Enables faster adoption of evolving data requirements without requiring application updates

---

## 11. Report Improvements & Fixes

- Numerous updates across:
  - **toxiCALL® standard reports**
  - Custom reports
- Improvements to:
  - Data accuracy  
  - Filtering and grouping logic  
  - Productivity and statistical reporting  
- Increased consistency across report outputs

### FLEX™ Updates
Updates for validation rules, reports, dashboards, default search filters, and other configuration items are delivered through System Tables.

After launching toxiCALL®, users may see a notification when updates are available.

[Click here for documentation on how to update System Tables](https://toxicalldemo.com/docs/tox5/flex-updates-system-tables/)

---

## 12. Stability & Performance Improvements

- Improved system table access and error handling
- General performance enhancements across application workflows
- Better responsiveness in distributed and network-based environments
- Resolution of edge-case issues impacting usability and reliability

---

## 13. General Fixes and Enhancements

- User interface improvements across forms and grids
- Enhancements to validation and workflow consistency
- Numerous minor bug fixes improving overall user experience

For questions on specific fixes or defects, please contact CAS Support.

---

## Known Issues

- Password reset not yet working properly through CAS Server
- **2066:** Auto Save feature requires additional feedback and validation
- **2463 (minor):**
  - Cannot switch from Local to Network if Local is already selected and connection lacks a Network Database  
  - **Workaround:** Select a different connection → switch mode → reselect the correct connection  

---

## Note

**The Source Code files contain no information and do not need to be downloaded.**

---

## Microsoft Prerequisite Files

The installer will automatically install required components. Manual downloads are available below:

- [Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

- Upgraded to **.NET 10 Desktop Requirement**  
  [.NET Desktop Runtime 10.0.5 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-10.0.5-windows-x64-installer)