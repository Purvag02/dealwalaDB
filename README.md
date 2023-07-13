# Liquibase makes easy to define changes in database.

# Liquibase Installation 
Step 1: Download Liquibase Files -> https://docs.liquibase.com/start/install/home.html

Step 2: Unzip liquibase 
        By using command: unzip liquibase-4.23.0.tar.gz

Step 3: Add liquibase to path for that
        Open the ~/.bashrc file

Step 4: Export a Path to install the liquibase
Add the following command: "export PATH="$PATH:<path to liquibase installation>"

Step 5: Save and Close the .bashrc file
        source ~/.bashrc

Step 6: Verify the installation
        Command: liquibase --version

# Now to connect to PostgreSQL database and perform schema migration operations.
# Liquibase requires the JDBC Driver for PostgreSQL.

Download JDBC Driver : https://jdbc.postgresql.org/download/

# Codeing Part to configure the liquibase to Database

Firslty create a Database from Terminal
Step1:  sudo -u postgres psql
Step2: create database 
        command: "database_name"

Let's write a Code to generate postgres database, create a folder and in it create a liquibase.properties file.

Write a Code by following content which is attached on my git repository.

Then create a dbChangelog.xmll file in which we are going to define our table 

