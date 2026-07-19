This version introduces Windows Authentication which allows login verifying the user's current Windows Login. This will be tied to a specific toxiCALL® user account.


Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.


[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/).

### Enhancements


\# 2113 Validation Rules Set can be reviewed to see which rules are being processed
\# 2128 Enhanced the case save message to provide more case details
\# 2137 Enhanced the note entry to automatically add a new note when clicking, if no note is currently selected
\# 2133 Added Case List Grid display of Clinical Effects, Therapies, and Scenarios
\# Employee Entry management has been updated for cleaner entry
\# 2142 Micromedex support for IP Authentication when no username or password is entered

### Bug Fixes

\# 2123 Corrected issue with Licensing System
\# 2134 Corrected Message display type for SQL Errors
\# 2021 Corrected problem with Case Entry Tab name display
\# 2020 Corrected problem with DOB calculation while switching between cases
\# 2128 Enhanced the case save message to provide more case details
\# 2121 Updated the Product Lookup Source Button (e.g. Micromedex)
\# 2137 New note is not automatically created in Case Detail entry




### Future Build

\# 2127 (disabled) HCF selection is incorrectly populating the Initial HCF, this bug was introduced when trying to populate the caller address information

### Known Issues

\# Password reset not yet working properly through CAS Server
\# Substance Lookup does not yet support popup windows.
\# 2066 Auto Save feature does not properly work at the program level, must currently be configured for the user and for Preview Testing only. Known issues include inconsistent saving as well as a message and audible "ding" during each save.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL installer. However, the links are available here if you want to install them manually.

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

\# Upgraded to .NET 9 Desktop Requirement. 
[.NET Desktop Runtime 9.0.5 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.5-windows-x64-installer)