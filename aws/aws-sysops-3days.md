AWS Sysops Fundamentals
------------------
Level: Sysops Fundamentals

Duration: 3-4 days 

Type: Workshop

--------------------

###Objective 

This training course is designed to introduce systems administrators to introduce them to AWS Services and get hands on experience provisioning, managing essential AWS components such as VPC, EC2, RDS, S3, IAM, Cloudformation etc. 

###Targeted Audience 

This introductory course is targeted for systems administrators with atleast one year of experience managing server side infrastructures, who are already using cloud platforms, or intend to use it to automate provisioning, and provide Infrastructure as a Service and manage scalable infrastructures with ease.

###Prerequisites:
 
 * Basic systems administration 
 * Understanding of linux/unix system concepts 
 * Understanding of Computer Networks 
 * Familiarity with Command Line Interface (CLI)
 * Familiarity with a Text Editor 

 ###Agenda 
 
 * Getting familiar with Cloud Computing and AWS
 * Virtual Private Cloud (VPC) • Elastic Compute Cloud (EC2)
 * Relational Database Service (RDS)
 * S3, Glacier and Cloudfront
 * Monitoring and Cloudwatch
 * Autoscaling and Load Balancing
 * Deployment Services : Cloudformation
 * Identity and Access Management
 * Other AWS Services 

 ###Detailed Course Outline 
 **Module1: Getting Familiar with Cloud and AWS**
 
 * Introduction to Cloud Computing
 	- Evolution of Cloud
 	- Distributed Computing
 	- Virtualization
 	- Cloud Computing
 	- Types of Cloud
 	- Deployment Models
 	- Key Milestones
 * Overview of AWS Services
    - Compute
    - Storage and Content Delivery
    - Database
    - Networking
    - Administration and Security
    - Deployment and Management
    - Analytics
    - Application Services
    - Mobile Services
    - Enterprise Applications

* Navigate AWS Management Console 

**Module 2:   Virtual Private Cloud**
 
* Networking Basics
   - TCP/IP
   - Networking Services
   - Network Utilities
* Virtual Private Cloud
* VPCs and Subnets 
* Internet Gateways
* Subnet Routing  Tables
* VPC Security Groups  and Network ACLs

**Module 3:  Elastic Compute Cloud (EC2)**

* Introduction to EC2
* Regions and Availability Zones
* Categorizing EC2 instances by Types and Sizes
* On demand, Spot and Reserved Instances
* Amazon Machine Image (AMI)
* EC2  Keypairs 
* Security Groups 
* EBS Volumes  : Magnetic, General SSD, IOPS
 
**Module 4:  Managed Relational Database Service (RDS)**

* Introduction to RDS 
* RDS Supported Databases
* RDS Subnet Groups 
* Multi AZ Database for High Availability
* Read Replicas
* Snapshot and Backups
* Restore
* Parameter and Option Groups
 
**Module 5: Storage  & Content Delivery ( S3 , Glacier & Cloudfront)**

* Simple Storage Service (s3)
* S3 Buckets and Objects
* Reduced Redundancy Storage 
* Hosting Static Sites with S3
* Archiving to Glacier
* Content Delivery with Cloudfront 

**Module 6 : Monitoring with Cloudwatch**

* Introduction to Cloudwatch 
* Performance Analysis and Monitoring 
* Billing and Cost Optimizations
 
**Module 7: Autoscaling and Load Balancing**
 
* Elastic Load Balancing 
* Autoscaling Concepts
* Launch Configurations
* Auto Scaling Groups
* Setting Triggers and Scaling Policies
 
**Module 8: Deployment and CloudFormation**

* Provisioning AWS components with Cloudformation
* Cloudformation Tempaltes and Stacks
* Overview to Opsworks, Elasticbeanstalk
 
**Module 9: Identity and  User Management**

* IAM user management 
* Users and Groups
* Roles
* Policies and Access Control
 
**Module 10 : Other AWS Services**
 
* Elasticache
* Simple Notification Service (SNS)
* Simple Email Service (SES)
* Simple Queuing Service (SQS)
* EC2 Container Service (ECS)
* Lambada

###Lab Exercises 

**Lab exercises involve,**
 
 * Building VPC from scratch with
    - public and private subnets
    - internet gateways 
    - outing tables
    - security groups
 * Launching EC2 linux instance with
    - AMI
    - EBS Volumes / Instance Store
    - Security Groups
    - Tags 
 * Connecting to EC2 instance with Putty and basic operations
 * Advanced EC2 Operations
   - Create, attach, format and mount EBS Volume
   - Snapshot Volume
   - Attaching Elastic IP
   - Creating Elastic Network Interface
 * AMI Operations
   - Creating AMIs
   - AMI Copy to other Region
 * MySQL RDS Operations
   - Create Subnet Groups
   - Launch RDS
   - Security Groups
   - Parameter Groups

* Configure s3 and Cloudfront 
   - Create S3 bucket
	-  Uploading files to S3
	- S3 Permissions
	- Hosting static website on S3
	- Archiving S3 objects to Glacier with lifecycle rules
	- Cloudfront Distribution Creation
* Health Monitoring and Alerting  with Cloudwatch
	- Creating Alerts and Triggers with Cloudwatch
* Autoscaling and ELB
	-  Create ELB
	- Create Launch Configurations
	- Autoscaling Group Configurations 
* Cloudformation
	- Launching a stack with Cloudformation
