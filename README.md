# Sql-server-hands-on
Necessary SQL concepts and related practices.
====================================================

#### Q1) creating, altering and dropping a database.
#### 
    -- To Create the database using a query   
    Create Database sample
    Whether, you create a database graphically using the designer or, using a query, the following 2 files gets generated.
    .MDF file - Data File (Contains actual data)
    .LDF file - Transaction Log file (Used to recover the database)

    -- To alter a database, once it's created 
    alter database sample modify name="Sample" 

    -- Alternatively, you can also use system stored procedure
    Execute sp_renameDB 'Sample','NewSample'




