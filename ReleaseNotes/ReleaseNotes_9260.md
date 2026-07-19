
Poison Center feedback is critically important to ensure we can enhance Toxicall to meet the needs of all poison centers.

### Enhancements

\# 2065 Linked Case Files: Can be saved on a file share location, or stored in the database. When stored in the database, they will be accessible from toxiWEB®. This also reduces the risk of orphaned files. However, this will increase the database size.
\# 2070 Updated the substance lookups for easier selection of data to populate within the case.
\# 2084 Better usage of the user Full Name case the data lists, such as roles. Previously, the logon name was shown.
\# Updated Substance Entry to provide better clarity for Concentration/Dose entry.
\# Migration now uses the toxiCALL® 5 login name and requires Administrator rights.


### Bug Fixes

\# 2075 Recover Deleted Records updated. Should allow recovery of cases that were part of a multi-case delete. (Pending client testing)
\#  2086 Resolved issue with Migration not starting correctly.
\# 2087 Corrected problem with toxiCALL® application not closing properly for users with the SPI role.
\# 2080 Update migration verification to no longer display empty system table names which are not critical for migration.
\# 2086 Improvements to the AutoSave feature but not ready for full release. (Requires client-side feedback and testing.)



### Known Issues

\# Password reset not yet working properly through CAS Server
\# Substance Lookup does not yet support popup windows.
\# 2066 Auto Save feature does not properly work at the program level, must currently be configured for the user and for Preview Testing only. Known issues include inconsistent saving as well as a message and audible "ding" during each save.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL installer. However, the links are available here if you want to install them manually.

[.NET Desktop Runtime 8.0.14 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.14-windows-x64-installer)

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

**Will be used in a future build**
\# Upgraded to .NET 9 Desktop Requirement. (future build)
[.NET Desktop Runtime 9.0.3 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.3-windows-x64-installer)