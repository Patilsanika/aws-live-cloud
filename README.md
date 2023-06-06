# aws-live-cloud

We have created simple employee database application which takes first 
name, last name, etc as input and store it in the relational database system service 
by AWS. Our project uses four cloud services which are EC2, RDS, S3 Bucket 
and IAM role. EC2 provides a flexible and scalable platform for running 
applications in the cloud, with a wide range of options and configurations to suit 
the needs of any user. Also we are taking image as input in application which got 
stored in S3 Bucket. S3 provides a reliable, scalable, and cost-effective way to 
store and manage large amounts of data in the cloud, with a wide range of options 
and features to suit the needs of any user.
            Way to manage permissions in AWS, allowing you to grant access to 
resources to entities without having to manage long-term access keys or 
passwords using creation of IAM Role.

## Methodology

a. Creation of RDS in AWS

To create an RDS (Relational Database Service) in AWS, you can follow these 
steps:
1. Click on the "Create database" button.
2. Choose the database engine you want to use (e.g., MySQL)
3. Select the version of the database engine you want to use.
4. Review your configuration settings and click on the "Create database" button 
to launch your RDS instance.
After your RDS instance is created, you can connect to it using the endpoint 
provided by AWS and start using it to store and retrieve data for your 
applications.

b. EC2 Instance

To create an EC2 (Elastic Compute Cloud) instance in AWS, you can follow 
these steps:
1. Click on the "Launch instance" button.
2. Choose the Amazon Machine Image (AMI) you want to use (e.g., Amazon 
Linux, Ubuntu, Windows, etc.).
3. Configure the instance details, such as the number of instances, network 
settings, IAM role, and advanced options (if needed).
4. Configure any additional settings, such as security groups, key pairs, and user 
data.
5. Review your configuration settings and launch your instance
            Once your EC2 instance is launched, you can connect to it via SSH (for Linux 
instances) using the public IP address or DNS name provided by AWS. EC2 
(Elastic Compute Cloud) instances in AWS are a flexible and scalable way to 
run your applications in the cloud.

c. I AM Role:
IAM is a web service that enables you to manage users and permissions for your 
AWS resources.

d. S3 Bucket

Amazon S3 (Simple Storage Service) is a scalable and secure object storage 
service provided by AWS (Amazon Web Services). An S3 bucket is a container 
for storing objects, which can be any type of data including documents, images, 
videos, and application asset
