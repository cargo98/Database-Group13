# Database-Group13
Final Project

Setup:

Download/Update SQL Developer:https://www.oracle.com/database/sqldeveloper/technologies/download/

Run "lsnrctl status" in a command prompt. This will tell you the name of your oracle 19c instance.

It will also tell you the port of your connection.

![image](https://github.com/cargo98/Database-Group13/assets/45134207/a8fddc51-08db-4a44-8a34-0b9eb86f4eed)

Then we log into a user with system privileges. I'm using SYS. If you forgot the password for SYS you can set it as shown below:

![image](https://github.com/cargo98/Database-Group13/assets/45134207/484e6ae1-6458-4640-a4d5-4f468eb922a5)

Setting up the connection in SQL Developer:

![image](https://github.com/cargo98/Database-Group13/assets/45134207/1d3918bc-9075-4596-ad7f-c67a1e2676b9)

Enable JSON Features using the following SQL Command (these can be run in SQL developer from now on):

ALTER SYSTEM SET enable_ddl_logging=TRUE SCOPE=SPFILE;
ALTER SYSTEM SET enable_pluggable_database=TRUE SCOPE=SPFILE;

Run the table creation script.
