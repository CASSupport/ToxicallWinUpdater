This version focuses on bug fixes and enhancements to existing features.

Poison Center feedback is critically important to ensure we can enhance Toxicall to meet the needs of all poison centers.

### Enhancements

\# 2066 Preview Only: Auto Save a Case. Settings are in the Employee Configuration tab for each employee. There is also a program level option.
\# 2065 Linked Case Files are migrating as link attachments. Toxicall can now support both embedded Linked Files or separate attachments. Configure in the Program Options.
\# 2067 Administrator feature to temporarily disable validations when needed. Please contact support before using this feature.
\# When quicksaving a case, built-in validations like Required Free Areas are not validated. This was stopping a quicksave from completing.
\# Inactive Clinical Effects, Therapies, Sceanrios, and Routes are no longer displayed. This will require a System Tables release.
\# Substance Product Lookup now supports right-click for Select Product for non-integrated websites like Drugs.com


### Bug Fixes

\# Substance Routes are no longer automatically populated and can be set per substance.




### Known Issues

\# Migration is not working for this version. Please use build 9239 to perform migration. You can then upgrade to build 9246
\# Password reset not yet working properly through CAS Server
\# Delete of multiple cases does not show all cases in the Restore Deleted Records option.
\# Substance Lookup does not yet support popup windows.
\# Auto Save feature does not properly work at the program level, must currently be configured for the user and for Preview Testing only. Known issues include inconsistent saving as well as a message and audible "ding" during each save.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL installer. However, the links are available here if you want to install them manually.

[.NET Desktop Runtime 8.0.14 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.14-windows-x64-installer)

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

**Will be used in a future build**
\# Upgraded to .NET 9 Desktop Requirement. (future build)
[.NET Desktop Runtime 9.0.3 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.3-windows-x64-installer)