This version focuses on significant changes to internal handling of system tables. The transport mechanics of system tables has been optimized to address several features including the ability to handle larger datasets. 

The report designer has also been extended to allow creation of more complex SQL Queries to optimize how data are collected from the server. This is a more advanced feature which will be used for the new report designs. The existing data selection will remain for simple report design. However, this can result in slow queries or out of memory issues, if using a large dataset.

### Enhancements

Added ability to reporting to design SQL Queries. This should allow significantly faster reports at the expense of a more complex Query design for the reports.
Significant updates to importing and exporting of system table data.


### Bug Fixes

Corrected Memory issues with handling of large system tables.
Future considerations on Report Filter Criteria are in development.

### Known Issues

New Reporting Data Source requires additional enhancement to use default connection string, rather than be dependent on the designer-used connection string name.
System Tables: All previously exported data is no longer valid. The new import/export process must use the new data format.


