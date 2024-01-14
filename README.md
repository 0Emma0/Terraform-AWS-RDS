Amazon Relational Database Service (Amazon RDS) is a web service to set up, operate, and scale a relational database in the AWS Cloud. It provides cost-efficient, resizable capacity for an industry-standard relational database and manages common database administration tasks.

First, we will see how to create an MS SQL Server Instance through the AWS Management Console using RDS:

## Create new database instance
https://catalog.us-east-1.prod.workshops.aws/workshops/897acbd7-8f2e-46ed-8dcd-c97872d5b3ce/en-US/lab1/1-createdatabase

## Get Endpoint for database instance
https://catalog.us-east-1.prod.workshops.aws/workshops/897acbd7-8f2e-46ed-8dcd-c97872d5b3ce/en-US/lab1/2-endpoint

## Retrieve Database Password from Secrets Manager
https://catalog.us-east-1.prod.workshops.aws/workshops/897acbd7-8f2e-46ed-8dcd-c97872d5b3ce/en-US/lab1/3-password

## Connect to RDS instance using SSMS
https://catalog.us-east-1.prod.workshops.aws/workshops/897acbd7-8f2e-46ed-8dcd-c97872d5b3ce/en-US/lab1/4-clientconnection

## Enable High Availability / Always On
https://catalog.us-east-1.prod.workshops.aws/workshops/897acbd7-8f2e-46ed-8dcd-c97872d5b3ce/en-US/lab2/1-enablemultiaz

## Identity & Access Management
https://catalog.us-east-1.prod.workshops.aws/workshops/897acbd7-8f2e-46ed-8dcd-c97872d5b3ce/en-US/lab6/2-iam

# Terraform example for MSSQL Server
https://registry.terraform.io/modules/terraform-aws-modules/rds/aws/latest/examples/complete-mssql 

# AWS RDS Terraform module
The official RDS Terraform module is the best way to create RDS resources and supports all relational databases. You can inspect documentation and Terraform examples here: https://github.com/terraform-aws-modules/terraform-aws-rds

