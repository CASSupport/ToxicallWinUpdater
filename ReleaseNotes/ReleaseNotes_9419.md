This version focuses on the implementation of AutoUpload for NPDS and MDB file export for RADARS.

[Please note AutoUpload is a separate download, located here](https://github.com/CASSupport/ToxicallWinAutoUploadUpdater).
Note: You will need to subscribe separately for the AutoUpload application.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.

[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/).

### FLEX™ Updates
Updates for report, dashboards, default search filters and many other items are provided through the system tables. After starting toxiCALL®, you may see a notification indicating that new System Tables are available. 

As of October 15th, over 110 reports have been redeveloped in toxiCALL® 5 but still require testing/confirmation.

[Click here for documentation on how to update System Tables](https://toxicalldemo.com/docs/tox5/flex-updates-system-tables/).

### Enhancements

\# Added Easy access to Search Filters and Reports from the Home Menu/Ribbon Bar
\# Performed cleanup on Ribbon Bar items for better clarity and organization
\# Performed cleanup on right-click menu for better clarity and organization
\# Added Product Preview window to show all products for current case
\# Added ability to release new Case Entry Views through System Tables, found in the View Menu


\# **AutoUpload Enhancements**
- AutoUpload Server Selection allows easy input of NPDS destination, without the need to manage the IP address.
- AutoUpload Destinations allow configuration of destination Output Types.
- Easily view validation messages within Case Entry.

\# **RADARS Enhancements**
- Select Ribbon Bar to choose which products/criteria will be exported. RADARS has a ribbon bar.
- Establish Base Criteria to limit what is being exported.
- Case Redaction is confirmed prior to export. Perform notes redaction directly within toxiCALL®.
- List which SPIs/Users have access to the MDB Export functionality.


### Bug Fixes

\# Lots of updates and corrections


### Known Issues

\# We are still working out some details for AutoUpload through the system tables.
\# Changing View Variants for items like Case Entry require closing the tab, and re-opening after a new View Variant has been selected.
\# Password reset not yet working properly through CAS Server
\# 2066 Auto Save feature requires user feedback and testing to ensure it meets center needs.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL® installer. However, the links are available here if you want to install them manually.

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

\# Upgraded to .NET 9 Desktop Requirement. 
[.NET Desktop Runtime 9.0.4 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.4-windows-x64-installer)