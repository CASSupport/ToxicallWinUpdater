This version addresses known issues with AutoUpload for NPDS and MDB file export for RADARS. This version is ready for client feedback for RADARS and AutoUpload. Our team will provide support in setting up AutoUpload for testing.

[Please note AutoUpload is a separate download, located here](https://github.com/CASSupport/ToxicallWinAutoUploadUpdater).
Note: You will need to subscribe separately for the AutoUpload application.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.

[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/).

### FLEX™ Updates
Updates for validation rules, report, dashboards, default search filters and many other items are provided through the system tables. After starting toxiCALL®, you may see a notification indicating that new System Tables are available. 

As of October 15th, over 110 reports have been redeveloped in toxiCALL® 5 but still require testing/confirmation.

[Click here for documentation on how to update System Tables](https://toxicalldemo.com/docs/tox5/flex-updates-system-tables/).

### Enhancements

- \# 2334 Password did not clear on login screen under certain conditions
- \# 2238 Corrected unique situations where delete button is present for case notes.
- \# 2323 Add a Ribbon Dropdown option to the home menu, allowing easy access to search items without going to filter tab.
- \# Entry Layout changes for the Custom Rule Criteria Validation form.
- \# Ensure weight and age values cannot be 0, they should be NULL.
- \# 2255 AutoUpload: Rejected Message - Missing Tag
- \# 2177 Employee Form Entry Layout, Move Active Directory entry field to first tab
- \# 2241 Caller/Patient Address Window now available through double-click.
- \# Case. Followup Num has been changed to nullable integer
- \# 2275 When deleting Substance: More details are now shown in the dialog box for confirmation.
- \# 2328 Corrected issue where View Variants are overwritten
- \# 2329 AutoUpload: Suppress Passed all schema validation checks message.
- \# 2303 AutoUpload: Server Online Check, will check to see when AU Services/DB comes back online
- Auto Upload: NPDS xml weight rounded to 1 decimal place (0.1 Kg)
- Auto Upload Viewer: No longer throw errors and allows to save ConnectionInfo.config file changes.
- “Customize Columns” action has been added across allowing List View column names to be changed (View Menu Item).
- \# 2223 Ribbon Bar: User Select Small Icons
- \# 2291 CASLicense and System Tables: Error At Startup
- \# Migration Tool: before creating CodeValueCategory check if incoming codeID exists across CodeValue and CodeValueCategory tables.


### Bug Fixes

\# Lots of updates and corrections for AutoUpload.


### Known Issues

\# Password reset not yet working properly through CAS Server
\# 2066 Auto Save feature requires user feedback and testing to ensure it meets center needs.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL® installer. However, the links are available here if you want to install them manually.

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

\# Upgraded to .NET 9 Desktop Requirement. 
[.NET Desktop Runtime 9.0.4 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.4-windows-x64-installer)