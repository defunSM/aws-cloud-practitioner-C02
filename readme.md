# AWS Cloud Practitioner Study Guide

Welcome to your comprehensive guide for conquering the AWS Certified Cloud Practitioner exam! Whether you're just starting your cloud journey or looking to solidify your understanding of AWS fundamentals, this resource is designed to equip you with the knowledge and confidence to succeed. We'll cover essential concepts, best practices, and real-world scenarios, ensuring you're fully prepared to leverage the power of the AWS Cloud.

## Resources:
- ### [The official AWS Cloud Practitioner Exam Guide](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/awscloudpractitionerexamguide.pdf)
- ### [AWS Whitepaper 2024](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/awsoverview_whitepaper2024.pdf)
- ### [AWS Glossary](https://docs.aws.amazon.com/glossary/latest/reference/glos-chap.html)
- ### [AWS Cloud Essentials](https://aws.amazon.com/getting-started/cloud-essentials/)


## Author: Salman Hossain
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://emiliedionisio.github.io/) <!--Replace with your GitHub Page here -->
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emdionisio/) <!--Replace with your LinkedIn Page here -->

## AWS Cloud Practitioner Exam Details

The AWS Certified Cloud Practitioner certification is your official starting point for a successful journey into the world of Amazon Web Services (AWS). This foundational certification validates your understanding of core AWS services, concepts, and best practices, regardless of your specific technical role. Whether you're an IT professional, business analyst, project manager, or anyone working with the AWS Cloud, this certification demonstrates your cloud fluency and opens doors to new career opportunities.

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/awscp_domains.png)

### [Domain 1: Cloud Concepts](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/domain1-cloudconcepts.md)
- 1.1. Define the benefits of the AWS Cloud.
- 1.2. Identify design principles of the AWS Cloud.
- 1.3. Understand the benefits of and strategies for migration to the AWS Cloud.
- 1.4. Understand concepts of cloud economics.

- What is Cloud Computing?
    - Cloud computing is accessing on demand  IT resources  over the internet.
- What are the three deployment models for cloud computing, their definitions, and uses?
    - There are three different deployment models for cloud computing including public, private and hybrid. Public is where the IT resources are accessed through the cloud. Private the resources are on premise in the physical building. Hybrid is a mix of both where some resources are accessed through the cloud while others are on site.
- What are the Benefits of cloud computing and their definitions?
    - The benefits of cloud computing is the cost, scalability , availability to pay as you go pricing.
- What are the Amazon EC2 instance types and their definitions?
    - There are three types of instances that EC2 offer which are general purpose, compute optimized and memory optimized. General purpose is typically for web servers or workloads that don't always use the CPU. Compute is for machine learning or other modeling applications that require from high performance processors. Memory optimized instances are designed to offer faster performance that require a lot of memory.
- What is a Load Balancer?
    - Load Balancing distributes the load as evenly as possible to different IT resources in order to not have one IT resource handle all of the stress.
- What is the primary purpose of AWS Regions in the global infrastructure?
    - AWS Regions contains isolated locations of availability zones with servers in order to provide quick access to different places and customers in different locations.
- Describe the function of Amazon CloudFront in AWS's architecture.
    - CloudFront is used to distribute content to different locations with low latency and speed.
- How do AWS Edge locations enhance the performance of Amazon CloudFront?
    - AWS Edge locations help enhance performance by having cached content in various places in order to deploy them to customers.
- Explain how Amazon Route 53 integrates with AWS Edge locations to enhance user experiences.
    - Amazon Route 53 is a DNS service which help since it can provide low latency responses based on the location of the customer.
- What are the advantages of using AWS Outposts for local data processing needs?
    - The advantages of AWS Outputs for local data processing needs is that if there is a reason for having hardware on premise it can be done while using amazon’s services.
- How are AWS Lambda and AWS Outposts different in what they offer for cloud computing?
    - AWS Lambda is serverless and thus don't have full access to the actual physical hardware whereas AWS outposts provides direct access to the physical on premise hardware.
- What is high availability?
    - High availability means that the resources are always available and that there is virtually no downtime.
- What are the benefits of AWS having a global infrastructure with multiple regions?
    - The benefits have having AWS in multiple regions means that content can be store in various locations for better performance, features or compliance reasons.
- What is an AWS Region?
    - An AWS Region is a location that has availability zones with a set of data centers.
- Why is data sovereignty important in AWS Regions?
    - Data sovereignty means that the data is self contained and have full access to the data itself due to compliance reasons.
- How do AWS Regions enhance disaster recovery capabilities?
    - AWS Regions have multiple availability zones in order to have redundancy in their data.
- What are the four main factors to consider when choosing an AWS Region?
    - The four factors to consider when choosing an AWS Region is latency (how far are customers), features available, cost and compliance.
- What is an AWS Availability Zone?
    - AWS Availability zone is a set of data centers within a location.
- What is the purpose of having multiple Availability Zones within an AWS Region?
    - The reason for having multiple availability zones in an AWS Region is to have redundancy.
- How does AWS ensure low latency communication between Availability Zones?
    - AWS ensures low latency by using various interconnected data centers and having redundance in data.
- Why is it important to run EC2 instances across multiple AZs?
    - It is important to run multiple EC2s in different AZs because it can lead to high availability and recovery if a region is affected by disaster.
- How do regional AWS services enhance high availability?
    - By enabling high regional AWS services there are multiple places where the content is stored.
- What is the purpose of Amazon CloudFront?
    - The purpose of Amazon CloudFront is to be able to distribute content with speed and high availability around the globe.
- What are edge locations in AWS?
    - Edge locations refer to content being cached in different regions in order to allow for low latency access to them to a global array of customers.
- What is AWS Outposts?
    - AWS Outposts refers to when customers need access to physical hardware but still want to use AWS Services.
- How do Availability Zones within AWS Regions contribute to disaster recovery and high availability?
    - Different availability zones have redundancy with the data that is stored and allows data to be saved in case of disaster.
- How do AWS Edge locations and Amazon CloudFront improve content delivery?
    - AWS Edge locations stores content in different availability zones which provides low latency for those accessing the content and cloudfront then figures out which location is best to get that content.
- What is an API in the context of AWS?
    - API is a programming interface in terms of AWS are like S3 apis for uploading content into the bucket or pulling content from the bucket.
- What is the primary method of interacting with AWS services?
    - The primary method of interacting with AWS is the web interface.
- What are the main ways to interact with AWS services?
    - There are 3 main ways to interact with AWS the web interface, CLI and through APIs.
- Why is automation important in cloud deployment?
    - Automation is important in the cloud deployment since there are repetitive tasks that are constantly being done. This can be automated through the usage of scripts and APIs.
- What is the primary advantage of using AWS Elastic Beanstalk over manual methods like the AWS Management Console?
    - AWS Elastic Beanstalk allows you to deploy the infrastructure without clicking through the interface whereas AWS management console you have to setup and configure everything manually by hand.
- What is AWS Elastic Beanstalk used for?
    - AWS Elastic Beanstalk is used to automatically deploy the structure of your AWS infrastructure.
- How does AWS CloudFormation help in managing AWS resources?
    - AWS CloudFormation helps manage AWS Resources since it makes infrastructure as code. Therefore infrastructure can be deployed as code.
- What are the main components of AWS Global Infrastructure?
    - The main components of AWS global infrastructure is the regions, availability zones, edge locations and direct connect locations.
- Which AWS services automatically run across multiple Availability Zones?
    - Most services run through AZs and take advantage of the global infrastructures like AWS Lambda, Elastic Beanstalk, Amazon RDS and etc.
- What is the recommended best practice for deploying infrastructure in AWS?

- What is Amazon EC2?
    - EC2 is a virtual machine that can be launched for various compute tasks.
- What is Amazon EC2 and its primary benefits?
    - EC2 has the primary advantage of it being scalable and with high availability.
- What is a Security Group in EC2?
    - A security group in EC2 is a way to maintain rules of which kinds of traffic the EC2 instance will either allow or deny.
- What are the four main purchasing options for EC2 instances, and what are their key characteristics?
    - On-Demand, Reserved, Spot and Savings Plan. On-Demand is for general computing with no long term commitments. The Saving plans is for at least 6 months of usage while reserve instances are also a commitment of at least 1 year. With Spot you can pay for current compute but can fluctuate with demand and for instances that don’t need consistent compute resources.
- How does EC2 pricing work?
    - EC2 pricing works depending instance type, region and the purchasing options.
- What is an Amazon Machine Image (AMI)?
    - It is the operating system that is running on the EC2 instances.
- How does EC2 integrate with other AWS services?
    - EC2 can interact with other AWS services like its RDS or S3 buckets for its data storage needs and content serving purposes.
- What are the different computing models available in AWS?
    - There are many types of compute services like EC2, AWS Lambda, Elastic Beanstalk, ECS, Fargate.
- What is an instance and its use cases?
    - An instance can be used for computing through the cloud or on premise.
- What are containers and their advantages?
    - Containers have the advantage of being OS independent.
- What is serverless computing and its use cases?
    - Serverless meaning don’t have to depend on the underlying server that it is being hosted on.
- When would you consider a hybrid deployment model?
    - If there is a specific use case of using special hardware that would be needed on premise but also want to use the services provided by AWS.
- What are some of the popular AWS computing services?
    - Some popular AWS compute services include EC2, AWS Lambda and ECS.
- What is AWS Lambda?
    - AWS Lambda is a serverless option to execute code without having to worry about the underlying server or infrastructure.
- What is Amazon ECS?
    - ECS is a container that allows you to deploy container images.
- How does AWS Fargate differ from Amazon EC2?
    - AWS Fargate allows you to deploy the application without worrying about the underlying OS.
- What are the benefits of using AWS Elastic Beanstalk?
    - The benefits of AWS Elastic Beanstalk is that you can deploy AWS infrastructure rapidly through code.
- How does EC2 demonstrate elasticity?
    - EC2 demonstrate elasticity since there are ways to scale it both by making the compute of the instance more powerful but also scaling horizontally by adding more instances.
- What level of control do users have over EC2 instances?
    - Users can have total control of the virtual machine and determine its OS and applications being run on the virtual machine.
- How does EC2 integrate with other AWS services?
    - EC2 instances integrate with other AWS services using other services like S3 or RDS for storage.
- What security features does Amazon EC2 provide?
    - EC2 has security groups which help it deny or allows incoming network traffic.
- What are the main architectural components of Amazon EC2?
    - EC2 instances, amazon machine images, instance types, the type of storage.
- What factors should you consider when choosing a region for your EC2 instance?
    - You should consider the compliance and legal laws.
- What is the purpose of a VPC in Amazon EC2?
    - The purpose of VPCs is to have an isolated network environment where resources are not shared with each other to ensure security and privacy.
- What are subnets and their role in EC2?
    - subnets are to divide the network into different segments and organize instances because on application. Also this allow for traffic control and routing between them.
- How do security groups protect your EC2 instances?
    - EC2 instances are protected by security groups since it allows control of inbound and outbound traffic.
- What are the steps to launch an EC2 instance?
    - Choose the Region, OS, Security group, VPC.
- What is the importance of tagging in EC2?
    - A way to keep EC2 instances and other AWS resources organized.
- Can you automate EC2 scaling?
    - One way to automate ec2 scaling is to set scaling policies and also setting things like alarms or scheduled scaling.
- What security features does EC2 offer?
    - There are a few security features like ACLs, Security groups and VPCs.
- What are the benefits of using AMIs?
    - AMIs allow you to restrict what users can deploy or use specific resources rather than just using the root account.

### AWS Certified Cloud Practitioner Exam - Domain 2 Study Guide: **Security and Compliance**

---

### **Overview of Domain 2:**

This domain focuses on understanding the core AWS services, concepts, and tools for security and compliance. It accounts for 25% of the exam and covers the following key areas:

1. **Defining the AWS shared responsibility model**
2. **Defining AWS Cloud security and compliance concepts**
3. **Identifying AWS access management capabilities**
4. **Identifying resources for security support**

---

### **1. AWS Shared Responsibility Model**

The AWS Shared Responsibility Model is a fundamental concept that delineates the security responsibilities between AWS and the customer.

- **AWS Responsibility (Security *of* the Cloud):**
    - AWS manages the physical infrastructure and hardware, including:
        - **Physical Security**: AWS data centers, networking, and hardware.
        - **Software Security**: The AWS Global Infrastructure, managed services, and foundational services (like EC2, S3, etc.).
- **Customer Responsibility (Security *in* the Cloud):**
    - Customers manage security **in** the cloud, including:
        - **Data Protection**: Encrypting data, managing access, and ensuring integrity.
        - **Identity and Access Management**: Setting up and managing users and permissions.
        - **Configuration Management**: Securing applications, operating systems, and network configurations.

### **2. AWS Security and Compliance Concepts**

### **Security Concepts:**

- **Identity and Access Management (IAM):**
    - **Users, Groups, and Roles**: Create and manage AWS users, groups, and roles to define permissions.
    - **Policies**: Attach policies to IAM entities to grant appropriate permissions.
    - **Multi-Factor Authentication (MFA)**: Add an extra layer of security.
- **Encryption:**
    - **Encryption at Rest**: Encrypt data stored in AWS services (e.g., S3, EBS, RDS) using AWS Key Management Service (KMS).
    - **Encryption in Transit**: Use TLS/SSL for secure data transmission.
- **Network Security:**
    - **Security Groups**: Act as a virtual firewall controlling inbound and outbound traffic for EC2 instances.
    - **Network Access Control Lists (NACLs)**: Provide an additional layer of security at the subnet level.

### **Compliance Concepts:**

- **AWS Compliance Programs**: AWS adheres to global compliance programs like SOC, ISO, and GDPR. Customers can leverage these compliance frameworks by using AWS services.
- **AWS Artifact**: A portal that provides on-demand access to AWS’s security and compliance reports.

### **3. AWS Access Management Capabilities**

- **IAM Best Practices:**
    - **Principle of Least Privilege**: Only grant permissions that are necessary for the task.
    - **IAM Policies**: Use managed policies to enforce security.
    - **Root Account**: Secure the root account and avoid using it for everyday tasks.
- **Federated Access**: Integrate on-premises Active Directory (AD) or other identity providers for federated access using AWS IAM roles.
- **Access Logs**:
    - **AWS CloudTrail**: Logs all API calls, including who made the call, which resources were used, and when.
    - **AWS Config**: Tracks configuration changes in your AWS resources and evaluates these changes against your configurations.

### **4. Resources for Security Support**

- **AWS Security Hub**: Provides a comprehensive view of your security state in AWS and helps you check your environment against security best practices.
- **AWS Trusted Advisor**: Offers real-time guidance to help you provision your resources following AWS best practices, focusing on cost optimization, performance, security, and fault tolerance.
- **AWS Inspector**: An automated security assessment service that helps improve the security and compliance of applications deployed on AWS.

### **Study Tips:**

- **Understand IAM deeply**: Know how to create policies, manage user permissions, and enforce security best practices.
- **Learn the Shared Responsibility Model**: Be clear on what AWS manages and what you are responsible for.
- **Practice with Security Tools**: Familiarize yourself with AWS security services like CloudTrail, Inspector, and Security Hub.
- **Review Compliance Services**: Explore AWS Artifact and understand the importance of compliance in cloud services.

 
# **Networking:**

- What is a VPC in AWS, and why is it important?
    - A cloud within the cloud in order to set security settings for your own internet access.
- What is a subnet, and how is it used in a VPC?
    - It allows one to control which ips have access to the internet making some public or private.
- What is an Internet Gateway, and what role does it play in a VPC?
    - VPC acts as a control for inbound and outbound connections in a network.
- What is a NAT Gateway, and why would you use it in a VPC?
    - NAT Gateway is useful to restricting inbound connections but allowing it access to the internet.
- What is a Route Table, and how does it function in a VPC?
    - Route table handles where the incoming traffic goes they are rules in which direct the traffic.
- What is a VPC Peering Connection, and what are its use cases?
    - Allows two VPCs to communicate with each other as if they were on the same network.
- What is a Security Group, and how does it enhance security in a VPC?
    - Security groups allow you to filter out inbound network traffic.
    - Security groups allows one to allow specific inbound and outbound network traffic.
- What is a Network ACL (Access Control List), and how does it differ from a Security Group?
    - ACL allows for more granular control of security controls the subnet level while security groups work on the instance level.
- How do you use Network ACLs to enhance security within a VPC?
    - Network ACLs work on the subnet level and help filter out incoming traffic. (firewall for subnets)
- What is an Elastic IP Address, and how is it used in a VPC?
    - An elastic IP can be useful to reassign it to another instance in an event that the initial instance has to be shutdown or restarted.
- What is a Virtual Private Gateway, and how does it function in a VPC?
    - A virtual private gateway can function as a VPN in order to access an instance from a specific site only. The performance however can suffer if the site is far from the location but can use direct connect for a private connection for better performance (bandwidth).
- What is Amazon Route 53, and what are its primary functions?
    - Amazon route 53 is a scalable DNS service to route users to internet applications.
- What is the purpose of DNS in the context of Route 53?
    - Turn domain names into numeric ip addresses so that computers can connect to each other.
- How does Route 53 provide high availability and reliability for DNS queries?
    - It does so by running infrastructure that is running AWS EC2 instances or load balancers.
- What is geolocation routing in Route 53, and what are its benefits?
    - It also provides geolocation to be able to do routing based on the geographic location of the user this allows for lower latency and better response rates.
- What is Amazon CloudFront, and what are its primary functions?
    - CloudFront is a content delivery network that stores content in caches around the world known as edge locations and allows to quickly serve content to viewers.
- What are the benefits of using Amazon CloudFront?
    - The benefits of using CloudFront is that users are able to access content with low latency and better performance.
- What is AWS Global Accelerator, and what is its purpose?
    - The purpose of the accelerator is to reduce latency by routing traffic through AWS global network. It also improves availability by minimizing downtime and simplify traffic management.
- What is the difference between Amazon CloudFront and AWS Global Accelerator?
    - Amazon cloudfront deals with content optimization by caching content in edge locations. Whereas AWS accelerator works on the network layer improving networking performance.
- What is edge location in the context of Amazon CloudFront?
    - An edge location is a place where content is cached in order to reduce latency for viewers to access content.
- What is AWS Direct Connect, and what are its primary benefits?
    - AWS direct connect allows you to use its own network which allows for high speed connections.
- What are common use cases for AWS Direct Connect?
    - Some of the common use cases for AWS direct connect includes low latency, cloud or big data analytics.
- What is AWS VPN, and how does it differ from AWS Direct Connect?
    - VPN is amazons private network which allows a secure connection between on premise sites and AWS services.
- What types of AWS VPN connections are available?
    - There is site to site VPN, client VPN, AWS VPN CloudHub, Transit Gateway.
- What is a Transit Gateway, and how does it benefit network connectivity?
    - Transit gateway is for connecting multiple vpcs and on premise networks.

# Storage

- What is object storage typically used for in cloud computing?
    - Object storage is usually good for storing images, videos or audio files any type of unstructured data types.
- How does Amazon S3 handle durability and availability for object storage?
    - One way that amazon makes availability for object storage is by having multiple availability zones and this replication can be done in order to safe guard against any time a specific availability zone goes down.
- What are some typical use cases for Amazon S3?
    - Typical use cases are for storing images, videos or audio files.
- What is the main difference between Amazon S3 Standard and Amazon S3 Standard-IA storage classes?
    - The standard S3 is for frequent reading and access while the IA storage class is for infrequent access thus the cost is lower.
- What is the Amazon S3 Glacier storage class used for?
    - Long term data storage since it has really low storage costs.
- How does Amazon S3 Intelligent-Tiering work, and what are its benefits?
    - S3 Intelligent Tiering monitors which objects are accessed and how frequently and places them depending on their access. If an object isnt being accessed in 30 days its placed in an infrequent tier and if accessed again its placed in a more frequent one.
- Explain the use case for Amazon S3 One Zone-IA.
    - Is a cost effective class for infrequent accessed data in various multi AZ storage.
- What is Amazon Elastic Block Store (Amazon EBS) and what are its primary use cases?
    - Supports backups and can be resized. It allows for encryption and possible to retain data even if ec2 instance is stopped or terminated.
- What are the main types of EBS volumes and their characteristics?
    - There is general purpose SSD for lower cost for small or medium databases. There is provisioned for higher performance and larger database. There is HDD volumes for big data, data warehouses or ETL workloads. Cold HDD for less frequent accessed data.
- What is the difference between Amazon EBS and instance store?
    - EBS storage will keep the data retained even after the EC2 instance has been terminated or stopped whereas the Instance store is temporary and will go down with the EC2 instance.
- What are some common use cases for instance store volumes?
    - Instance storage is mostly for caching data or applications that need low latency.
- Can you attach an EBS volume to multiple EC2 instances at the same time?
    - No. However the EBS volume can be attached and detached to different instances.
- What is the maximum size of a single Amazon EBS volume?
    - The max size for a single Amazon EBS volume is 64 TiB.
- How do you ensure the durability of data stored in Amazon EBS?
    - Amazon ensures durability of its data in EBS by having replication within availability zones, snapshots and monitoring through cloudwatch.
- What is Amazon EBS Snapshots and how are they used?
    - Snapshots are taking a backup of the previous state that can be used to restore data.
- Can you change the volume type of an existing Amazon EBS volume?
    - Yes. It is possible to resize the volume by stopping the EC2 instance.
- What is Amazon Elastic File System (Amazon EFS) and what are its primary use cases?
    - EFS is for scalable file storage can can be accessed from multiple instances.
- What are the key features of Amazon EFS?
    - Key features include multiple instances being able to access it all at the same time. IT also has NFS interface making it compatible with many applications.
- What is Amazon FSx and what file systems does it support?
    - FSx supports NTFS, SMB, AD, HPC (high performance computing).
- What are common use cases for Amazon FSx for Windows File Server?
    - The common use cases for amazon FSX is if applications need a native windows file system included.
- Can Amazon EFS be accessed from on-premises environments?
    - Yes EFS can be assessed by on-premise environment through AWS Direct Connect and AWS VPN.
- What is the difference between Amazon EFS and Amazon FSx for Windows File Server?
    - Amazon EFS is fully managed file system that supports the NFS it is designed for linux based workloads. Where has FSx is for windows file server.
- What are the performance modes available in Amazon EFS?
    - There are two difference performance modes: The general performance mode which has low latency and throughput while the max performance mode has higher I/O mode. 

# Databases:

- What is Amazon RDS, and what are its key features?
    - Relational Databases have a unique primary key. RDS are known to hold tables that have relationships to each other tables.
- What are the benefits of Amazon RDS?
    - Relational databases  have the benefit of being easy to setup, scalable and performance.
- What is Amazon DynamoDB, and what are its use cases?
    - Dynamo DB is a NoSQL database service that his scalable, fully managed and has built in security.
- What is Amazon Aurora, and how does it differ from other RDS engines?
    - Aurora has advanced features like serverless operation and has is compatible with MySQL and PostgreSQL making it easier to migrate.
- What is Amazon Redshift, and what is it used for?
    - It is designed for large scale data querying and analytics enabling organizations to do business intelligence and analytics.
- What is AWS Database Migration Service (DMS), and what are its benefits?
    - This provides benefits such as minimal downtown as well as cost savings to pay for resources that you only use.
- What is the Schema Conversion Tool (SCT) used for in AWS database migrations?
    - Its a tool to convert the database schema from the source database engine to the target engine.
- What are the common steps involved in a database migration using AWS DMS?
    - Identifying the source and target database. Use the AWS Schema conversion tool. Plan for the downtime that will occur and than create the target database. Setup IAM roles and start executing the migration task.
- What are the benefits of using AWS managed databases over EC2-hosted databases?
    - AWS managed databases will have the ease of not having to manage the database security or updates. While EC2 hosted databases will have the database attached to the instance or shared to other EC2 instances.
- What are some of the AWS managed database services available?
    - AWS Auora, MySQL, Postgresql, mariaDB, Oracle, Microsoft SQL server.
- How does Amazon Aurora differ from Amazon RDS?
    - It is a PostgreSQL compatible relational database that is faster than mysql or postgresql. Also has fault tolerance that automatically replicates data across multiple availability zones.
- Why might you choose Amazon DynamoDB for your application?
    - The benefits of Amazon DynamoDB is for managed service, and automatic scaling.
- What are the benefits of using Amazon Redshift for data warehousing?
    - Some advantages to amazon redshift is high performance, scalability and cost efficiency.

### [Domain 2: Security and Compliance](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/domain2-securitycompliance.md)
- 2.1. Understand the AWS shared responsibility model.
- 2.2. Understand AWS Cloud security, governance, and compliance concepts.
- 2.3. Identify AWS access management capabilities.
- 2.4. Identify components and resources for security.

#### [Domain 3: Cloud Technology and Services](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/domain3-cloudtechnology.md)
- 3.1. Define methods of deploying and operating in the AWS Cloud.
- 3.2. Define the AWS global infrastructure.
- 3.3. Identify AWS compute services.
- 3.4. Identify AWS database services.
- 3.5. Identify AWS network services.
- 3.6. Identify AWS storage services.
- 3.7. Identify AWS artificial intelligence

#### [Domain 4: Billing, Pricing and Support](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/domain4-billing.md)
- 4.1. Compare AWS pricing models.
- 4.2. Understand resources for billing, budget, and cost management.
- 4.3. Identify AWS technical resources and AWS Support options.
