This version introduces the use of .NET 9, which may require updating your .NET libraries. The installer will provide this installation, if needed. You can also use the link below to install directly.

Note: This build supersedes built 8296 which is being removed from the releases list.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.

### Enhancements


\# 2109 Extended the name length for Free Area Descriptions.
\# 2079 Added Test Databases button in the Connection Manager.
\# 2089 Substance Strength Per Sample Layout has been added, simplifying the view of the Per Dose presentation for substances.
\# 2102 Added option to manually migrate cases back to Tox4 with MigratedOn date.
\# 2113 New Manage Rule Set action to evaluate and reset Case Validation Rules.
\# 2107 Substance Website Lookup: The highlighted text will be saved as the substance description when selecting a product.
\# 2116 Auto Save, updated to stop the popup windows indicating the auto save has been performed. Note, the case status will change to quick saved when an auto save is performed.
\# 2115 Substance Lookup Window size and position are now retained between sessions.
\# 2119 Custom Validation rules are now refresh after a rule is saved.
\# 2120 Corrected issue where Initial and Final HCF values are not migrating
\# 2121 Change Product Lookup Source to dropdown button allowing source selection and search within one mouse click or selection.
\# Additional Enhancements to System Tables

### Bug Fixes

\# 2097 Addressed issues when trying to save a case. DETAILS
\# 2113 Custom Validation Rule Verification Actions (for use with support)
\# 2088 Corrected issue when migrating by a single Status.
\# 2097 Corrected issue with Substance Product Code field updating with Poisindex Code.
\# 2107 Substance Website Lookup: corrected issue with Product details save from popup windows.


### Future Build

\# 2112 Still finalizing details on Windows Authentication for application login.

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