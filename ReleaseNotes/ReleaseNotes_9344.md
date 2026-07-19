Major: Corrected an issue with the notes entry for Toxicall SPI, which was introduced in v5.0.9337. Several other improvements are also included. The notes below include enhancement details for build 9337 and 9344

This version brings a large number of enhancements including zip codes lookup and more. See list of details below.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.


[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/).

### Enhancements

**Build 9337**:
\# 2154 Substance Lookup now has right-click option Notes, allowing information to be pushed directly to the open note
\# 2127 HCF now Populates Address/Phone
\# 1637 Changes to the Audit Log Layout
\# 2169 Added password requirements to password change screen
\# 2150 Allow a user-changeable Note date/time for retroactively entered notes
\# 1903 Zip Code Look up has been enhanced for better user experience when using CTRL-L
\# Employee entry: Move windows login credentials to main page
\# Added Side Panel Navigation items tooltips
\# Substance Description now has a lookup button to show the saved substance page
\# Substance lookup URL now supports long URls
\# Substance Lookup URL is now clickable to open in a browser window
\# Substance Web Lookups now supports popup windows
\# Added Current Windows Login detail to the toxiCALL® Login window
\# Status Bar on the bottom of the toxiCALL® application has been reordered and includes username rather than logon name
\# Substance Generic Code lookup can now be initiated with double-click, or a new action button
\# Clearing the case assignment will now clear the Follow up Type
\# Primary Case field has been added to the default Case List view
\# Caller/Patient address field will now open the details entry when double-clicked 



### Bug Fixes

**Build 9344**:
\# Corrected issue where Toxicall SPI user accounts could not enter/edit notes.
\# Corrected issue when creating a Survey.  
\# Corrected Issue where Show/Hide Labels during case entry was not updating properly.
\# Updated Notes to ensure notes are in chronological order (not reverse). Ribbon bar is now only on one line. Find panel is now disabled by default.  
\# Updated the case Tab names, removing the view name so only case details are presented.
\# Updated Case Entry moving the Start Date and Status fields to the top left side, above the Notes entry area. This is for better visibility and workflow. 
\# Corrected issue where Tab key does not move when in the routes selection grid.
\# Corrected Clinical Effects, Therapies, and other popup windows to display the Ribbon Bar, when the main application ribbon bar is hidden.
\# Quick entries fix and rework,
\# Open Case popup new icon,
\# Do not allow to close case with substance external bowser open


**Build 9337**:
\# 2155 Corrected problem with cases not locking properly
\# 2126 License can now be applied by a different user than the submitting user
\# Corrected exposure time entry to allow entries like "19m" for 19 minutes ago where the "m" would remain in place.
\# Keycuts now display only active entries, by default
\# Clinical Effects, Therapies, Scenarios, and Routes no longer display Inactive entries, unless the inactive entry is already selected


### Future Build

\# Lots of items in the works

### Known Issues

\# Password reset not yet working properly through CAS Server
\# 2066 Auto Save feature requires user feedback and testing to ensure it meets center needs.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL® installer. However, the links are available here if you want to install them manually.

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

\# Upgraded to .NET 9 Desktop Requirement. 
[.NET Desktop Runtime 9.0.5 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.5-windows-x64-installer)