# Setting up POSTGRES SQL for Gemini_NL2SQL_BigQuery

## Create a POSTGRES SQL instance with the following config:

 - In the search bar, search sql and select sql
 - Select "Create Instance"
 - Select "Choose PostgreSQL"
 - Set the following:
     - Instance ID = pg15-nl2sql-pgvector
     - password = hr_tutorial
     - Database version = PostgreSQL 15
     - region = us-central1
     - Machine configuration/machine shapes = 2vCPU, 16GB
 - Create Instance
 
## Create a POSTGRES SQL database with the following config:
 - On the left, select the Databases tab
 - Select "CREATE DATABASE"
 - Set database name as "nl2sql-admin"
 - Select Create
 
## Create a POSTGRES SQL user with the following config:
 - On the left, select the Users tab
 - Select "ADD USER ACCOUNT"
 - Set username as "nl2sql-admin"
 - Set password as "hr_tutorial"
 - Select Add
 
 Please continue with the rest of the notebook