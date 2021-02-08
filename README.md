# Sermons Database Export
02-20-17 export of the Sermons database owned by Michael Lofaro. The files are sourced from MySQL database `sermons.sql` exported via `mysqldump`. Files were then compiled into `sermons.xlsx` manually, with empty tables being ignored.

The table **ser_orig** or the file `csv/ser_orig.xlsx` appear to be original data.

```shell # → Root
├── csv/                  # → Tables exported to comma-separated values
├── xlsx/                 # → Tables exported to Microsoft Excel
├── sermons.sql           # → Original sourced MySQL file: cricket_ser__02-20-17.sql
└── sermons.xlsx          # → Compiled spreadsheet, empty tables pruned
```