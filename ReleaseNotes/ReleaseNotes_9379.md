This version corrects a License Issue introduced in an earlier build. This version, or later, will be important to ensure there are no issues to applying a license for toxiCALL®. This version also introduces a number of changes to the ribbon bar and right-click menu in the Case List. This should help minimize the confusion by move items to areas which are more relevant to workflow.

For Case Entry, we have introduced a new control to help streamline entry selection for dropdown lists. The dropdown will allow you to type a few characters of the desired item, then hit tab. This removes the need to press enter for selection. This dropdown still supports the up/down arrows to choose an item in the list.

**Note**: It has been discovered that the new control is causing a conflict with the search filters. This version is **NOT recommended for production**. However, testing will still allow specialists to provide feedback on the new entry controls as well as many of the other new features.

Please keep an eye on the system tables for updates to reports.

AutoUpload is now supported with this version. In a future version, the AutoUpload viewer will be part of toxiCALL® 5.

Poison Center feedback is critically important to ensure we can enhance toxiCALL® to meet the needs of all poison centers.


[Click here for instructions on how to subscribe to new version notifications](https://toxicalldemo.com/docs/non-knowledgebase/download-subscriptions-and-report-issues/).

### FLEX™ Updates
Updates for report, dashboards, default search filters and many other items are provided through the system tables. After starting toxiCALL®, you may see a notification indicating that new System Tables are available. 

As of September 7th, approximately 81 reports have been redeveloped in toxiCALL® 5 but still require testing/confirmation.

[Click here for documentation on how to update System Tables](https://toxicalldemo.com/docs/tox5/flex-updates-system-tables/).

### Data Review Required for "Irritation/pain" selection in Dermal or Ocular

\# 2224 When selecting the Clinical Effect "Irritation/pain" in the Ocular group, we have noticed that "Irritation/pain" is also selected in the Dermal group. This problem appears to occur back to v5.0.9260 and can be corrected using the system table update process described above in FLEX™ Updates.

**Additional Details**
1. This problem can be resolved by updating the System Tables. Specifically, the FieldCodeValue system tables contains the change.
2. We have renamed the "Irritation/pain" to specifically identify Ocular or Dermal. This also maintains consistency with the other irritation Clinical Effects.
3. We are also reviewing the code to ensure identical names, across categories, don't cause this problem in the future.

**Verify your data:** Any production cases captured in toxiCALL® 5 should be verified to ensure there are no data problems. Please reach out to support and we will help build a filter to review any cases meeting these criteria. This will be a simple fix.

### Enhancements

\# 2217 Updates to the ribbon bar and right-click menu. Better clarity and less clutter.
\# 2078 Connection Manager will now prompt to save.
\# New Dropdown Entry Box for entry like "Reason for Exposure" allow typing characters to filter list, then tab to next item. Goal is to optimize keyboard entry and navigation. Up/Down arrows can be used to navigate between filtered items.
\# Several adjustments have been made to the Case Entry form "Classic B"
\# Added Report Title to the Reports Options. A user entered title will be shown in reports
\# Substances Preview now has ribbon bar option to show all preview windows at one time.

### Bug Fixes

\# 2214 License Issue: Unable to apply license problem has been resolved.
\# 2186 When running a selected report, such as case detail, now only selected cases will be included.



### Views

\# In the Assets, there is a view which can be imported. This is provided for testing and feedback. The substances section and Clinical Effect/Outcome areas have been repositioned. This is provided as an optional view for review and feedback.
\# Unable to reset layout fix.


### Known Issues

\# It has been discovered that the new control is causing a conflict with the search filters. This version is **NOT recommended for production**. However, testing will still allow specialists to provide feedback on the new entry controls as well as many of the other new features.
\# Changing View Variants for items like Case Entry require closing the tab, and re-opening after a new View Variant has been selected.
\# Password reset not yet working properly through CAS Server
\# 2066 Auto Save feature requires user feedback and testing to ensure it meets center needs.

### Note

The Source Code files do not contain information and do not need to be downloaded.

### Microsoft Prerequisite Files

The Prerequisite files can be installed as part of the toxiCALL® installer. However, the links are available here if you want to install them manually.

[Visual C++ Redistributable for Visual Studio 2015-2022 x64](https://download.visualstudio.microsoft.com/download/pr/c7707d68-d6ce-4479-973e-e2a3dc4341fe/1AD7988C17663CC742B01BEF1A6DF2ED1741173009579AD50A94434E54F56073/VC_redist.x64.exe)

\# Upgraded to .NET 9 Desktop Requirement. 
[.NET Desktop Runtime 9.0.5 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.5-windows-x64-installer)