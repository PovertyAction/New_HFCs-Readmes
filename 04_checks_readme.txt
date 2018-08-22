++++++++++++++++
CHECKS
++++++++++++++++

This folder is designed to store the various input sheets that get called by the master_check do file and to store the output sheet that is produced by running this do file.

Within the 01_inputs sub-folder you will find templates for the different input spreadsheets:

- hfc_enumerators 

This is a blank document that will serve as the template for the enumerator dashboard. You should not populate this spreadsheet with any information prior to running the checks.

- hfc_replacements

This is a blank document that should only be populated if you need to make corrections to your dataset before running the master_check do file. Typically, you should proceed by running the HFCs, reading the output, determining what observations or variables have problematic values in need of adjustment (e.g. a clear outlier that is the result of a misentered value), and then applying those corrections by adding a row to the replacements spreadsheet.

- hfc_inputs

This is the main document which is where you will select which variables from your dataset you want to run in each check. Be selective with the variables you include. The more variables you have, the more comprehensive your checks may be, but it will also mean more output that will likely become difficult to read and interpret quickly.

Once you run the checks, look to the 02_outputs folder to see what has been created:

- hfc_output

This is the spreadsheet that contains the main output for the HFCs, where each tab represents a different check's output.

- hfc_enumerators

This is an eumerator dashboard, which contains enumerator specific checks to monitor performance.

- research_dashboard

This is a research dashboard, which contains one-way and two-way summary statistics for specified variables.