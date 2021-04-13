# Assignment-1

Terraform Module to setup a CMS (Content Management System) of your choice on AWS

·         The CMS must be backed by a relational database.

·         Scalability and Fault Tolerance should be an important consideration of your design.

·         Reusability of the terraform module should be part of the design.

·         Provide a readme how to deploy and maintain your solution.

·         Store your code in a publicly accessible git repository and send the link to the repository.




CMS (Content Management System) configuration:
We will launch WordPress application in an Amazon EC2 instance and connect it to Amazon RDS (database instance).

Why RDS:
RDS is a relational database.
We are using Amazon RDS as it provides scalability and Fault tolerance.

Prerequisites:
1. You should have an AWS account.
2. Default VPC and default subnets should be present in the Region you mentioned in main.tf. Here I am using us-west-2.
3. You have to take care of storing aws credentials. While executing this task, I stored AWS credentials in my home directory.

Deployment instruction;
1. Download both the files in the same folder.
2. Go to that folder.
2. Then Run below commands:
     a. terraform init
     b. terraform plan
     3. terraform apply

To destroy the CMS
    d. terraform destroy

Maintenance:
Change the AMI image name, VPC ID, Subnet IDs as per your need in future.

