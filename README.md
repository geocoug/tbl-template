# tbl-template.py

Create an ODS file containing column names matching an input list of database tables.
If no table names are specified, all tables in the database schema will be used.
Optionally use pattern matching to select table subsets.

## Example Usage

`python tbl-template.py -v localhost -d dbname -s public -u db_user -t *employee* output.ods`
