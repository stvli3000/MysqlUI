# MysqlUI
A Tiny GUI for both Oracle MySQL, and Microsoft SQL Server

MysqlUI, a tiny 250KB GUI for both Microsoft SQL, and MySQL query operations. It is able to perform select and update, include manually typing new row(s) by update feature for both types of relational databases. It requires minimum .Net4， and need to install MySQL Connector for .Net, which can be downloaded from:http://dev.mysql.com/downloads/connector/net/

The Features:

    - 'x'(Delete):  in the top navigation bar to perform deleting, must SAVE the table to make the deleting effective.

    - '💾'(Save Icon): same with <Save Table>. Save all deleting and editing of the table.

    - show 500 rows: The defaul rows limit is 500 for initial 'select * ' query, but 'show 1000 rows' limit and 'no limit' options are available.

    - Server:Port:  Leave blank, the program will use default.

    - Table Name:  For Microsoft SQL Server, here is <Schema.Table>, it needs the full path of table includes the schema, in case any customized schema is in use. The default schema name is 'dbo.'.

    - Hide / Show Password.

    - Save settings ( data stored as plain file, please keep the computer safely).

    - (query box): Allow manully input query syntax into here. Then click <Execute Query> will fire it.

    - MySQL / SQL: Oracle MySQL Server, and the Microsoft SQL Server modes switch by selecting the 'MySQL' or 'SQL' from the right top drop down list to change database type between.

    - Show Table  Perform  'Select * from table' , And pass the query to Query text box.

    - Save Table : Update database base On the table's contents. Please remember select ALL COLUMNS before editing, or may miss values. All update and delete operations require a Primary Key as the row identifier, if no PK is in the table, such operations will not process succeessfully.

    - Execute Query : Execute the query text box's contents.

Presume it is a new year gift ^o^

Happy New Year!
