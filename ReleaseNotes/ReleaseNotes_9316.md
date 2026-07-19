This version is intended to resolve a license issue where the license is failing on some workstations. We have also corrected an issue with the Micromedex IP authentication. Additional update details can be found below.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.


[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/).

### Enhancements


\# 2147 Moved the Close Note button to the top of the note entry for easier access
\# 2140 Windows Login option can now be disabled for All users, or for Individual users


### Bug Fixes

\# 2106 Migration: Corrected the Status Selection to include user defined status options.
\# 2152 Corrected the per-substance route order
\# 2139 Corrected problem where auto-generated passwords would not meet password criteria.
\# 2151 Corrected issue with DOB not remaining in date selection field
\# 2151 Corrected issue with the Exposed On date/time calculation. Will now be calculated both directions. (e.g. when entering the actual date/time or when entering 15m (15 minutes ago), 2h (2 hours ago), etc.




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