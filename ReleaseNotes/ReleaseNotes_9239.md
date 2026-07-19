New feature to recover deleted cases. Several enhancements for Migration and Substance Lookup have been added.

Poison Center feedback is critically important to ensure we can enhance Toxicall to meet the needs of all poison centers.

### Enhancements

\# Added Restore Deleted Records option to Tools menu for Administrator
\# Connection Manager: Now allows incomplete connections to be saved. This allows preparing for a server which may not be online.
\# "User" account is no longer created when a new database is created.
\# Substance Browser lookup, right click enhancements, including Select Product addition.
\# Migration: Now uses the toxiCALL 5 login, rather than toxiCALL 4.
\# Migration: Option to select if System Tables, Data, Notes Redaction, Historical Data should be performed in the migration. This allowed the delayed migration of Redaction and Historical Data. This also allows migration from archives, without re-gathering the system tables.
\# Migration: Adjusted the layout of the SPIList Separator character to make this more easily identifiable.

### Bug Fixes

\# Migration: Corrected an issue with parsing Tox4 user names. If a name cannot be properly parsed, the name will be placed as the first name.
\# 2056 Correct problem with inactive Product Lookup Sources showing in Case entry.



### Known Issues

\# Password reset not yet working properly through CAS Server
\# Connection Manager does not test the connection or create a new database. However, Tox5 Login will create the new database.
\# Delete of multiple cases does not show all cases in the Restore Deleted Records option.
\# Substance Lookup does not yet support popup windows.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL installer. However, the links are available here if you want to install them manually.

[.NET Desktop Runtime 8.0.14 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.14-windows-x64-installer)

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

**Will be used in a future build**
\# Upgraded to .NET 9 Desktop Requirement. (future build)
[.NET Desktop Runtime 9.0.3 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.3-windows-x64-installer)