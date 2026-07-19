This build introduces a new installer and a variety of new enhancements. For the next build we will be testing the ability to provide automatic using an updater. You will be able to choose when to update. Poison center implementation will allow stronger control on updates, and announcements of updates.

This build, going forward, requires .NET Desktop Runtime 6.0.11 or later to be installed on the machine. This part of the installation requires **Administrator privileges** and can be installed as part of the toxiCALL(r) installation, or prior to installing toxiCALL(r).


### We offer two types of installation:
1. Install per-user: This **does not** require administrator privileges but requires the .NET runtime to be previously installed.
2. Installation per-workstation: This installation **does** require administrator privileges. toxiCALL will be available to all users on the workstation. 

### REQUIRED
Please uninstall any existing version(s) of toxiCALL v5 on your machine before performing this installation. toxiCALL 4 **can remain** on your machine. This new installer will (should) automatically perform the uninstall first in future upgrade.

### Features
New: Install Process to handle uninstall/install properly.
New: Distribution files are digitally signed for security.
New: .NET Desktop Runtime 6.0.11 is required and is part of the installation package.
New: Migration tools are available and can be, optionally, installed as part of this installation.
New: License request process will submit email to support.
New: Validation Rules Manager.

### Enhancements
\#1388 First round of updates for Multiple Exposures, applying details from index (primary) case.
\#1554 Some minor enhancements to the case entry layout.
\#1509 Ability to import/export Reports & Dashboards design for sharing between other poison centers.
\#1529 Login screen has been updated to show database connection and change which database is used. Helpful for switching between testing, training, and production databases.
\#1541 Connection Manager now allows easy setup of databases available. Connection details are saved at the workstation level.

### Bug Fixes
\#1553 Corrected issue with weight calculation and display.
\#1563 Better separation of user configuration settings. Installer will also retain the user settings during uninstall.
Other internal bug fixes and change to the underlying architecture.