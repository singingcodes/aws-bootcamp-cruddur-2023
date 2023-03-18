# Week 4 — Postgres and RDS

# Provision an RDS instance:
- I learned how to provision an RDS instance by following the AWS documentation and experimenting with different configurations. I created instances with different database engines and configured them for high availability and automatic backups.

# Temporarily stop an RDS instance:
- To temporarily stop an RDS instance, I used the AWS Management Console or the AWS CLI to issue a stop-db-instance command. I made sure to create a snapshot of the instance before stopping it to avoid data loss.

# Remotely connect to RDS instance:
- I connected to an RDS instance remotely using a SQL client such as DBeaver or pgAdmin. I entered the instance endpoint and my credentials and was able to execute SQL commands and view the database schema.

# Programmatically update a security group rule:
- To programmatically update a security group rule, I used the AWS SDK for Python (boto3) to modify the inbound rules of a security group associated with an RDS instance. I added or removed IP addresses and ports from the rule and applied the changes.

# Write several bash scripts for database operations:
- I wrote several bash scripts to automate common database operations such as backup, restore, and data import/export. I used the psql command-line tool to execute SQL commands and saved the output to files or variables for further processing.

# Operate common SQL commands:
- I am familiar with common SQL commands such as SELECT, INSERT, UPDATE, and DELETE. I have used these commands to query, insert, update, and delete data from tables in a PostgreSQL database.

# Create a schema SQL file by hand:
- I created a schema SQL file by hand by defining the tables, columns, and constraints in a text editor such as Vim or Sublime Text. I then executed the SQL file using psql to create the database schema.

# Work with UUIDs and PSQL extensions:
- I worked with UUIDs and PSQL extensions such as PostGIS and pgAdmin. I used the uuid-ossp extension to generate UUIDs and stored them in tables. I also used PostGIS to work with spatial data and perform spatial queries.

# Implement a Postgres client for Python using a connection pool:
- I implemented a Postgres client for Python using the psycopg2 module and a connection pool. I created a class that encapsulated the connection pool and provided methods to execute SQL commands and fetch results.

# Troubleshoot common SQL errors:
- I have encountered and resolved common SQL errors such as syntax errors, constraint violations, and transaction conflicts. I used error messages and logs to identify the cause of the error and took appropriate actions to fix it.

# Implement a Lambda that runs in a VPC and commits code to RDS:
- I implemented a Lambda function that runs in a VPC and commits code to an RDS instance. I used the AWS SDK for Python to establish a connection to the RDS instance and executed SQL commands to update the database.

# Work with PSQL JSON functions to directly return JSON from the database:
- I worked with PSQL JSON functions such as json_agg, json_build_object, and jsonb_agg to directly return JSON from the database. I used these functions to aggregate data from multiple tables and format it as JSON.

# Correctly sanitize parameters passed to SQL to execute:
- I correctly sanitized parameters passed to SQL to execute by using parameterized queries and prepared statements. I used the %s syntax in SQL queries to specify placeholders for parameters and passed the parameters as a tuple or dictionary to the execute method of the cursor object. This prevented SQL injection attacks and ensured data integrity.












