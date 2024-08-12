## Domain 3: Cloud Technology and Services (34% of scored content)

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/3-cloudtech.png)

#### 3.1: Define methods of deploying and operating in the AWS Cloud
#### Knowledge of:
- Different ways of provisioning and operating in the AWS Cloud
- Different ways to access AWS services
- Types of cloud deployment models
- Connectivity options
#### Skills in:
- Deciding between options such as programmatic access (for example, APIs, SDKs, CLI), the AWS Management Console, and infrastructure as code (IaC)
- Evaluating requirements to determine whether to use one-time operations or repeatable processes
- Identifying different deployment models (for example, cloud, hybrid, on-premises)
- Identifying connectivity options (for example, AWS VPN, AWS Direct Connect, public internet)

#### 3.2: Define the AWS global infrastructure
#### Knowledge of:
- AWS Regions, Availability Zones, and edge locations
- High availability
- Use of multiple Regions
- Benefits of edge locations
- AWS Wavelength Zones and AWS Local Zones
#### Skills in:
- Describing relationships among Regions, Availability Zones, and edge locations
- Describing how to achieve high availability by using multiple Availability Zones
- Recognizing that Availability Zones do not share single points of failure
- Describing when to use multiple Regions (for example, disaster recovery, business continuity, low latency for end users, data sovereignty)
- Describing at a high level the benefits of edge locations (for example, Amazon CloudFront, AWS Global Accelerator)

#### 3.3 Identify AWS compute services
#### Knowledge of: AWS compute services
#### Skills in:
- Recognizing the appropriate use of different EC2 instance types (for example, compute optimized, storage optimized)
- Recognizing the appropriate use of different container options (for example, Amazon ECS, Amazon EKS)
- Recognizing the appropriate use of different serverless compute options (for example, AWS Fargate, Lambda)
- Recognizing that auto scaling provides elasticity
- Identifying the purposes of load balancers

#### 3.4: Identify AWS database services
#### Knowledge of:
- AWS database services
- Database migration
#### Skills in:
- Deciding when to use EC2 hosted databases or AWS managed databases
- Identifying relational databases (for example, Amazon RDS, Amazon Aurora)
- Identifying NoSQL databases (for example, DynamoDB)
- Identifying memory-based databases
- Identifying database migration tools (for example AWS Database Migration Service [AWS DMS], AWS Schema Conversion Tool [AWS SCT])

#### 3.5: Identify AWS network services
#### Knowledge of: AWS network services
#### Skills in:
- Identifying the components of a VPC (for example, subnets, gateways)
- Understanding security in a VPC (for example, network ACLs, security groups)
- Understanding the purpose of Amazon Route 53
- Identifying edge services (for example, CloudFront, Global Accelerator)
- Identifying network connectivity options to AWS (for example AWS VPN, Direct Connect)

#### 3.6: Identify AWS storage services
#### Knowledge of: AWS storage services
#### Skills in:
- Identifying the uses for object storage
- Recognizing the differences in Amazon S3 storage classes
- Identifying block storage solutions (for example, Amazon Elastic Block Store [Amazon EBS], instance store)
- Identifying file services (for example, Amazon Elastic File System [Amazon EFS], Amazon FSx)
- Identifying cached file systems (for example, AWS Storage Gateway)
- Understanding use cases for lifecycle policies
- Understanding use cases for AWS Backup

#### 3.7: Identify AWS artificial intelligence and machine learning (AI/ML) services and analytics services
##### Knowledge of:
- AWS AI/ML services
- AWS analytics services
##### Skills in:
- Understanding the different AI/ML services and the tasks that they accomplish (for example, Amazon SageMaker, Amazon Lex, Amazon Kendra)
- Identifying the services for data analytics (for example, Amazon Athena, Amazon Kinesis, AWS Glue, Amazon QuickSight)

#### 3.8: Identify services from other in-scope AWS service categories.
#### Knowledge of:
- Application integration services of Amazon EventBridge, Amazon Simple Notification Service (Amazon SNS), and Amazon Simple Queue Service (Amazon SQS)
- Business application services of Amazon Connect and Amazon Simple Email Service (Amazon SES)
- Customer engagement services of AWS Activate for Startups, AWS IQ, AWS Managed Services (AMS), and AWS Support
- Developer tool services and capabilities of AWS AppConfig, AWS Cloud9, AWS CloudShell, AWS CodeArtifact, AWS CodeBuild, AWS CodeCommit, AWS CodeDeploy, AWS CodePipeline, AWS CodeStar, and AWS X-Ray
- End-user computing services of Amazon AppStream 2.0, Amazon WorkSpaces, and Amazon WorkSpaces Web
- Frontend web and mobile services of AWS Amplify and AWS AppSync
- IoT services of AWS IoT Core and AWS IoT Greengrass
#### Skills in:
- Choosing the appropriate service to deliver messages and to send alerts and notifications
- Choosing the appropriate service to meet business application needs
- Choosing the appropriate service for AWS customer support
- Choosing the appropriate option for business support assistance
- Identifying the tools to develop, deploy, and troubleshoot applications
- Identifying the services that can present the output of virtual machines (VMs) on end-user machines
- Identifying the services that can create and deploy frontend and mobile services
- Identifying the services that manage IoT devices

# Q&A:

**Networking:**

1. **What is a VPC in AWS, and why is it important?**
   A VPC (Virtual Private Cloud) in AWS is a logically isolated network where you can launch resources securely, crucial for controlling network configuration and security.

2. **What is a subnet, and how is it used in a VPC?**
   A subnet is a range of IP addresses within a VPC. It divides the VPC into smaller networks, used to group resources based on security and operational needs.

3. **What is an Internet Gateway, and what role does it play in a VPC?**
   An Internet Gateway allows resources within a VPC to communicate with the internet, enabling inbound and outbound traffic.

4. **What is a NAT Gateway, and why would you use it in a VPC?**
   A NAT Gateway enables instances in a private subnet to access the internet without exposing them to incoming internet traffic.

5. **What is a Route Table, and how does it function in a VPC?**
   A Route Table contains rules that determine the path network traffic takes within the VPC, directing traffic to various destinations like subnets and gateways.

6. **What is a VPC Peering Connection, and what are its use cases?**
   A VPC Peering Connection allows you to connect two VPCs privately, useful for sharing resources across different VPCs or accounts without traversing the public internet.

7. **What is a Security Group, and how does it enhance security in a VPC?**
   A Security Group acts as a virtual firewall, controlling inbound and outbound traffic to instances, enhancing security by allowing only specific types of traffic.

8. **What is a Network ACL (Access Control List), and how does it differ from a Security Group?**
   A Network ACL is a layer of security that controls traffic at the subnet level, unlike Security Groups, which operate at the instance level. It provides an additional layer of security by filtering traffic entering and leaving subnets.

9. **How do you use Network ACLs to enhance security within a VPC?**
   Network ACLs are used to define rules that allow or deny specific traffic to and from subnets, providing more granular control over network traffic.

10. **What is an Elastic IP Address, and how is it used in a VPC?**
    An Elastic IP Address is a static public IP that you can associate with resources in a VPC, useful for remapping instances or other resources in case of failure.

11. **What is a Virtual Private Gateway, and how does it function in a VPC?**
    A Virtual Private Gateway is a VPN concentrator on the AWS side of a VPN connection, enabling secure connectivity between your on-premises network and your VPC.

12. **What is Amazon Route 53, and what are its primary functions?**
    Amazon Route 53 is a scalable DNS web service that routes end-user requests to appropriate AWS services, ensuring high availability and reliability.

13. **What is the purpose of DNS in the context of Route 53?**
    DNS in Route 53 translates domain names into IP addresses, allowing users to access AWS resources using easy-to-remember domain names.

14. **How does Route 53 provide high availability and reliability for DNS queries?**
    Route 53 uses a global network of DNS servers and health checks to ensure reliable routing of user requests to healthy endpoints.

15. **What is geolocation routing in Route 53, and what are its benefits?**
    Geolocation routing directs traffic based on the geographic location of the user, optimizing performance and compliance with regional regulations.

16. **What is Amazon CloudFront, and what are its primary functions?**
    Amazon CloudFront is a Content Delivery Network (CDN) that delivers content to users with low latency by caching it at edge locations worldwide.

17. **What are the benefits of using Amazon CloudFront?**
    Amazon CloudFront improves website load times, reduces bandwidth costs, and increases security by serving content from the nearest edge location to the user.

18. **What is AWS Global Accelerator, and what is its purpose?**
    AWS Global Accelerator is a networking service that optimizes the performance and availability of your applications by routing traffic through AWS global infrastructure.

19. **What is the difference between Amazon CloudFront and AWS Global Accelerator?**
    CloudFront focuses on delivering static content through caching, while Global Accelerator improves performance and availability for dynamic, non-cacheable content.

20. **What is edge location in the context of Amazon CloudFront?**
    An edge location is a data center where CloudFront caches copies of your content, reducing latency by serving it closer to your users.

21. **What is AWS Direct Connect, and what are its primary benefits?**
    AWS Direct Connect provides a dedicated network connection from your premises to AWS, offering consistent, low-latency performance and reduced bandwidth costs.

22. **What are common use cases for AWS Direct Connect?**
    Common use cases include hybrid cloud deployments, data center migrations, and applications requiring stable, low-latency connections to AWS.

23. **What is AWS VPN, and how does it differ from AWS Direct Connect?**
    AWS VPN establishes secure, encrypted connections over the internet, while Direct Connect offers a private, dedicated network connection to AWS.

24. **What types of AWS VPN connections are available?**
    AWS offers Site-to-Site VPN, which connects on-premises networks to AWS, and Client VPN, which allows individual users to connect securely.

25. **What is a Transit Gateway, and how does it benefit network connectivity?**
    A Transit Gateway simplifies network architecture by allowing multiple VPCs, on-premises networks, and VPNs to connect through a single gateway.

**Storage:**

1. **What is object storage typically used for in cloud computing?**
   Object storage is used for storing unstructured data like files, images, and backups, providing scalability and easy access.

2. **How does Amazon S3 handle durability and availability for object storage?**
   Amazon S3 ensures durability by redundantly storing data across multiple devices and facilities, offering high availability with its built-in redundancy and failover mechanisms.

3. **What are some typical use cases for Amazon S3?**
   Typical use cases include data backup, content storage, media hosting, and big data analytics.

4. **What is the main difference between Amazon S3 Standard and Amazon S3 Standard-IA storage classes?**
   Amazon S3 Standard offers high availability and frequent access, while S3 Standard-IA (Infrequent Access) is optimized for less frequently accessed data at a lower cost.

5. **What is the Amazon S3 Glacier storage class used for?**
   Amazon S3 Glacier is used for long-term, archival storage of data that is rarely accessed but needs to be retained for regulatory or backup purposes.

6. **How does Amazon S3 Intelligent-Tiering work, and what are its benefits?**
   S3 Intelligent-Tiering automatically moves data between two access tiers based on changing access patterns, optimizing costs by minimizing storage charges.

7. **Explain the use case for Amazon S3 One Zone-IA.**
   Amazon S3 One Zone-IA is used for infrequently accessed data that does not require the resilience of multi-AZ storage, offering lower costs.

8. **What is Amazon Elastic Block Store (Amazon EBS), and what are its primary use cases?**
   Amazon EBS provides persistent block storage for EC2 instances, commonly used for databases, file systems, and applications requiring consistent performance.

9. **What are the main types of EBS volumes and their characteristics?**
   The main types include General Purpose SSD (gp2/gp3) for balanced performance, Provisioned IOPS SSD (io1/io2) for high-performance needs, and Magnetic volumes for cold data storage.

10. **What is the difference between Amazon EBS and instance store?**
    EBS provides persistent, durable storage that can be detached and reattached to instances, while instance store offers temporary, ephemeral storage tied to the lifecycle of an instance.

11. **What are some common use cases for instance store volumes?**
    Instance store volumes are commonly used for temporary data, caching, and buffers that do not require persistence after instance termination.

12. **Can you attach an EBS volume to multiple EC2 instances at the same time?**
    Yes, you can attach an EBS volume to multiple EC2 instances using EBS Multi-Attach, but only for specific volume types like io1/io2.

13. **What is the maximum size of a single Amazon EBS volume?**
    The maximum size of a single Amazon EBS volume is 16 TiB.

14. **How do you ensure the durability of data stored in Amazon EBS?**
    Data durability in EBS is ensured by automatically replicating it within its Availability Zone and using EBS Snapshots for backups.

15. **What is Amazon EBS Snapshots, and how are they used?**
    Amazon EBS Snapshots are incremental backups of EBS volumes that can be used to restore volumes to a specific point in time.

16. **Can you change the volume type of an existing Amazon EBS volume?**
    Yes, you can change the volume type of an existing EBS volume without downtime by using Elastic Volumes.

17. **What is Amazon Elastic File System (Amazon EFS), and what are its primary use cases?**
    Amazon EFS is a scalable, fully managed file storage service for use with AWS Cloud services and on-premises resources, ideal for shared access to file data.

18. **What are the key features of Amazon EFS?**
    Key features include automatic scaling, high availability, durability, and support for thousands of concurrent connections.

19. **What are the key features of Amazon EFS?**
   Amazon EFS features include automatic scaling, high availability, durability, and support for thousands of concurrent connections across multiple instances.

20. **What is Amazon FSx, and what file systems does it support?**
   Amazon FSx is a fully managed service that supports file systems like Windows File Server and Lustre, optimized for performance-intensive workloads.

21. **What are common use cases for Amazon FSx for Windows File Server?**
   Common use cases include home directories, enterprise applications like Microsoft SharePoint, and workloads requiring Windows-native file system features.

22. **Can Amazon EFS be accessed from on-premises environments?**
   Yes, Amazon EFS can be accessed from on-premises environments using AWS Direct Connect or a VPN connection, allowing for seamless integration with on-premises resources.

23. **What is the difference between Amazon EFS and Amazon FSx for Windows File Server?**
   Amazon EFS is a scalable, shared file storage for Linux workloads, while FSx for Windows File Server is tailored for Windows environments with support for SMB protocol, NTFS, and Active Directory integration.

24. **What are the performance modes available in Amazon EFS?**
   Amazon EFS offers two performance modes: General Purpose, which is suitable for latency-sensitive use cases, and Max I/O, designed for applications that require high levels of throughput and IOPS.

**Databases:**

1. **What is Amazon RDS, and what are its key features?**
   Amazon RDS (Relational Database Service) is a managed service that makes it easy to set up, operate, and scale relational databases in the cloud, with automated backups, patching, and scaling.

2. **What are the benefits of Amazon RDS?**
   Benefits of Amazon RDS include automated database management, high availability, scalability, security features, and support for multiple database engines.

3. **What is Amazon DynamoDB, and what are its use cases?**
   Amazon DynamoDB is a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability, ideal for use cases like gaming, IoT, and real-time analytics.

4. **What is Amazon Aurora, and how does it differ from other RDS engines?**
   Amazon Aurora is a MySQL and PostgreSQL-compatible relational database that offers higher performance, scalability, and availability compared to standard RDS engines, with automatic replication across multiple Availability Zones.

5. **What is Amazon Redshift, and what is it used for?**
   Amazon Redshift is a fully managed data warehouse service that enables fast querying and analysis of large datasets, ideal for business intelligence and analytics.

6. **What is AWS Database Migration Service (DMS), and what are its benefits?**
   AWS DMS is a service that helps you migrate databases to AWS quickly and securely, with minimal downtime. It supports homogeneous and heterogeneous migrations.

7. **What is the Schema Conversion Tool (SCT) used for in AWS database migrations?**
   The Schema Conversion Tool (SCT) is used to convert your existing database schema to a format compatible with the target AWS database, essential for heterogeneous migrations.

8. **What are the common steps involved in a database migration using AWS DMS?**
   Common steps include creating a replication instance, connecting source and target databases, selecting the data to migrate, and starting the replication task.

9. **What are the benefits of using AWS managed databases over EC2-hosted databases?**
   AWS managed databases reduce the operational overhead by automating tasks like backups, patching, and scaling, allowing you to focus on application development.

10. **What are some of the AWS managed database services available?**
    Some AWS managed database services include Amazon RDS, Amazon DynamoDB, Amazon Aurora, Amazon Redshift, and Amazon DocumentDB.

11. **How does Amazon Aurora differ from Amazon RDS?**
    Amazon Aurora offers enhanced performance, scalability, and availability, with up to five times the throughput of MySQL and three times that of PostgreSQL compared to standard RDS.

12. **Why might you choose Amazon DynamoDB for your application?**
    You might choose Amazon DynamoDB for applications requiring low-latency data access at any scale, such as gaming, IoT, and real-time data processing.

13. **What are the benefits of using Amazon Redshift for data warehousing?**
    Amazon Redshift offers fast query performance, scalability, and integration with other AWS services, making it ideal for large-scale data analytics and business intelligence tasks.
