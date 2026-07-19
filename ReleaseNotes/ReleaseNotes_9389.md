One important goal of this new version is to minimize or eliminate the scrolling in order to properly enter a case. New Vertical Spacing option in the Case Entry options along with the ability to control the minimum height for substances and Clinical Effects. This allows users to adjust the spacing between entry objects to help reduce, or remove, the need to scroll to see all case details. The default value is 1, try changing it to 0.01. The default minimum height is 150. If the screen has extra room, substance height can be increased by the user.

In the files, we have distributed two sample views layout changes for user feedback. These views rearrange the case entry to better optimize tabbing between data fields while retaining the primary look and feel of case entry in toxiCALL® 4. Note: Do **not** perform a reset view on these as they will revert back to the Case (Classic B) LAYOUT.

- Case - Sub Mid: This arranges the patient details under the patient address in formation for smooth tabbing through patient details. The Caller Information such as Call Type (exposure) has been moved below the Caller Information.
- Case - Sub Left: The above changes are included. However, substances have been moved to a column on the left for a vertical list of substances and below is the substance entry. This gives better flexibility of the substance height.

Please keep an eye on the system tables for updates to reports. A new Lab Trends report will be released on September 15, 2025, or later for user feedback.

AutoUpload is supported with this version. In a future version, the AutoUpload viewer will be part of toxiCALL® 5.

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

\# Substances Case List now shows more data in the grid view.
\# Added CTRL-L to show popup in the Routes, Clinical Effects, Therapies, and Scenarios sections
\# Added ability to for users to set the Minimum height of Substances and Clinical Effects. This can be used to take better advantage of screen space available and minimizing scrolling.
\# 2226 New Vertical Spacing option for Case Entry options. Using 0.01 brings the fields tighter together in an effort to remove/eliminate scrolling.
\# Exposed On calculation buttons have new icons and tooltips for better screen utilization.
\# Updated the right-click menu in the notes, removing unneded options and allowing Paste Special
\# 2250 New "Invited Users" - Case Restricted Access: Allows users to have access to ONLY specific cases. Ideal for external consults or backup poison centers who do not need access to all case data. This feature will provide convenient access to toxiWEB®. This feature requires additional testing and updates to the Security Roles system Tables. This is enabled through a new "Case List - Invited" grid with user **role** of toxiCALL® SPI - Invited 
\# New Quick Lookup Property Editor allows for quicker entry and fast select, then tab to next item. This lookup searched based on the first-few characters of items. (Provide feedback if a search using the "contains" filter will be better, and for which collection fields)
\# 2238 The Delete action has been removed from Notes so closed notes cannot be deleted. (This requires additional testing as it does not appear to cover all instances)
\# Added Reports and Search Filter dropdowns to the Home menu for quick access. Both dropdowns also show recently used Filters/Reports.
\# Adjusted the minimum size allowed for Substances. This will allow for better screen viewing of more detail in the case window.

\# 2244 Report options now contains the report title and an improved layout for the options values which can be included/excluded in reports.


### Bug Fixes

\# Corrected issue where notes could be typed in the grid but are not saved. The grid no longer allows typing per the original design.
\# Corrected similar issue with Substance Entry, substances must be entered in the detail section, not the grid.
\# 2213 Better error handling when the Linked Case Files location is not defined.
\# 2232 Corrected problem with Scenarios dropdown displaying incorrect values.
\# 2224 Corrected problem "Irritation/Pain" duplicate entries in Clinical Effects.
\# 2227 Corrected problem where a new case was not immediately locked.
\# 2240 Updated tooltip for week pregnant indicating 99=Unknown.
\# 2233 Disable Generic Code lookup button when no substance is present.
\# 2239 Updated the Micromedex Search Options Window, also corrected issue with checkbox for Drug ID search.
\# 2242 Case Notes entry now allows "Paste Special" from right-click menu, for convenience.
\# 2042 Corrected problem when opening second instance of Toxicall. Previous version opened a web browser window and would not allow substance searches to work.
\# 2263 Corrected log off issue with toxiWEB®





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
[.NET Desktop Runtime 9.0.4 x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-9.0.4-windows-x64-installer)