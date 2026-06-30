# Project 3: Amazon RDS MySQL Database Deployment

## Overview

This project demonstrates how to create, configure, and connect to a managed MySQL database using Amazon RDS.

## Objectives

- Create a MySQL RDS instance
- Configure networking and security
- Enable public access
- Connect from a local machine
- Execute SQL commands

## Technologies Used

- Amazon RDS
- MySQL
- AWS Management Console
- MySQL CLI

## Steps Performed

1. Created a MySQL RDS instance.
2. Configured VPC networking.
3. Configured security groups.
4. Enabled public accessibility.
5. Connected to the database using the MySQL client.
6. Verified the database by executing SQL commands.

## Outcome

Successfully connected to the Amazon RDS database and verified database functionality using SQL.

## Skills Demonstrated

- Database Administration
- Amazon RDS
- MySQL
- Security Groups
- VPC Networking

## Sample Command

```bash
mysql -h <RDS-endpoint> -u admin -p
```

```sql
SHOW DATABASES;
```

## Screenshots

- RDS Instance
- Connectivity & Security
- Security Group
- MySQL Connection
- SHOW DATABASES Output
