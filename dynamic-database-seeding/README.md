# Dynamic Database Seeding

### Description

Developers often utilize tooling that will seed data. Seeding data is the process of (intelligently) creating structured data in a meaningful way. This is especially useful when the volume of data that needs to be generated is high.

### Acceptance Criteria
 - Create a script that will take all the files from the `source-data` directory that will:
   - Create a table using the filename.
   - Insert all data from that file into the table. Source files contain the column names on the first row. All subsequent rows are the data.