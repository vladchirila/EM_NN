"# EM_NN" 

In order to be able to create the database, you may need to first run:

<code>
EXEC sp_configure 'show advanced options', 1;
RECONFIGURE;

EXEC sp_configure 'clr strict security', 0;
RECONFIGURE;
</code>

Before running the script, try to choose appropriate paths for the .mdf and .ldf files (see FILENAME), or manually create the database and run only the rest of the script.
