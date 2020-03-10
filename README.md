# Welcome to the SQL sample files repository.

I've included 3 files in total. Below is a short description of each.
The files have a lot of documentation in them so I won't include it here.

Please note: **All** files end with a **.txt** extension.

Script:
	**Database_CompleteCollationInfo_ComplexV2.sql.txt**

Purpose:
	This script will show you the current SQL Server collation settings.
	It will also show you the collation settings of all databases on the Server.
	
	This script can be run in any database and is Information Only.
	
Script:
	**Parameter_Sniffing_Example.sql.txt**
	
Purpose:
	This is a quick example to show how to perform parameter sniffing.
	I've included links to documentation for further reference.
	
	This script can be run in any database.
	
Script:
	**proc_CopyDatabaseNoLogWithDiskCheck.sql.txt**
	
Purpose:
	Copy any database from any server to anyother server.
	
Requirements:
	Requires ability to execute the xp_cmdshell system stored procedure.
	
Further Reference:
	https://docs.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/xp-cmdshell-transact-sql?view=sql-server-ver15

**WARNING!!!!!!!!!!!**
	**DO NOT RUN THIS SCRIPT IN A PRODUCTION ENVIRONMENT WITHOUT THOROUGH REVIEW**
	
**USE EXTREME CAUTION.**

Note:
In the script ines 282 - 284 Set the Paths for the .MDF file.
Make sure the Full is correct for your environment!




Please let me know if you have any questions.
