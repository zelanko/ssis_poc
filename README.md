# ssis_poc
SQL Server Integration Services Proofs of Concept

## Emit_Biml_Files.dtsx
Given a rowset `(BIML varchar(8000), filename varchar(8000))`, for each row, a file `C:\temp\{{filename}}.biml` is output containing the value of `BIML`.

