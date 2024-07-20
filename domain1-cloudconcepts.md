## Domain 1: Cloud Concepts (24% of scored content)

![AWS Cloud Practitioner Domains](https://github.com/emiliedionisio/aws-cloud-practitioner-C02/blob/main/1-cloudconcepts.png)

#### 1.1: Define the benefits of the AWS Cloud
#### Knowledge of: Value proposition of the AWS Cloud
#### Skills in:
- Understanding the economies of scale (for example, cost savings)
- Understanding the benefits of global infrastructure (for example, speed of deployment, global reach)
- Understanding the advantages of high availability, elasticity, and agility

<!-- Type your questions and answers below -->

#### What is Cloud Computing?
Cloud computing is the on-demand delivery of IT resources over the internet with pay-as-you-go pricing. On-demand delivery indicates that AWS has the resources you need, when you need them. 

#### What are the three deployment models for cloud computing, their definitions, and uses?
- Cloud-based Deployment Model, you can migrate existing applications to the cloud, or you can design and build new applications in the cloud. You can build those applications on low-level infrastructure that requires your IT staff to manage them.
  - Run all parts of the application in the cloud.
  - Migrate existing applications to the cloud.
  - Design and build new applications in the cloud.
- On-premises deployment is also known as a private cloud deployment.  In this model, resources are deployed on premises by using virtualization and resource management tools.
  - Deploy resources by using virtualization and resource management tools.
  - Increase resource utilization by using application management and virtualization technologies.
- Hybrid deployment, cloud-based resources are connected to on-premises infrastructure. You might want to use this approach in a number of situations. For example, you have legacy applications that are better maintained on premises, or government regulations require your business to keep certain records on premises.
  - Connect cloud-based resources to on-premises infrastructure.
  - Integrate cloud-based resources with legacy IT applications.







--------
#### 1.2: Identify design principles of the AWS Cloud
#### Knowledge of: AWS Well-Architected Framework
#### Skills in:
- Understanding the pillars of the Well-Architected Framework (for example, operational excellence, security, reliability, performance efficiency, cost optimization, sustainability)
- Identifying differences between the pillars of the Well-Architected Framework

#### 1.3: Understand the benefits of and strategies for migration to the AWS Cloud
#### Knowledge of:
- Cloud adoption strategies
- Resources to support the cloud migration journey
#### Skills in:
- Understanding the benefits of the AWS Cloud Adoption Framework (AWS CAF) (for example, reduced business risk; improved environmental, social, and governance (ESG) performance; increased revenue; increased operational efficiency)
- Identifying appropriate migration strategies (for example, database replication, use of AWS Snowball)

#### 1.4: Understand concepts of cloud economics
#### Knowledge of:
- Aspects of cloud economics
- Cost savings of moving to the cloud
##### Skills in:
- Understanding the role of fixed costs compared with variable costs
- Understanding costs that are associated with on-premises environments
- Understanding the differences between licensing strategies (for example, Bring Your Own License [BYOL] model compared with included licenses)
- Understanding the concept of rightsizing
- Identifying benefits of automation (for example, provisioning and configuration management with AWS CloudFormation)
- Identifying managed AWS services (for example, Amazon RDS, Amazon Elastic Container Service [Amazon ECS], Amazon Elastic Kubernetes Service [Amazon EKS], Amazon DynamoDB)

# Q&A:

### AWS Skill Builder: AWS Cloud Practitioner Essentials (Modules 1-3)

**Domain 1: Cloud Concepts**

1. **What is Cloud Computing?**
   - Cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, and more—over the internet ("the cloud"). This allows for flexible resources, faster innovation, and economies of scale.

2. **What are the three deployment models for cloud computing, their definitions, and uses?**
   - **Public Cloud**: Services are delivered over the public internet and shared across multiple organizations. Example: AWS.
   - **Private Cloud**: Services are maintained on a private network and used exclusively by one organization. Example: AWS Outposts.
   - **Hybrid Cloud**: Combines public and private clouds, allowing data and applications to be shared between them. Example: Integrating on-premises data centers with AWS.

3. **What are the Benefits of cloud computing and their definitions?**
   - **Cost Efficiency**: Pay-as-you-go pricing model reduces the need for upfront investment.
   - **Scalability**: Ability to scale resources up or down based on demand.
   - **Flexibility**: Access to a wide range of services and applications.
   - **Security**: Enhanced security features and compliance certifications.
   - **Reliability**: High availability and disaster recovery options.

4. **What are the Amazon EC2 instance types and their definitions?**
   - **General Purpose**: Balanced resources (e.g., T3, M5).
   - **Compute Optimized**: High compute power (e.g., C5).
   - **Memory Optimized**: High memory capacity (e.g., R5, X1).
   - **Storage Optimized**: High storage throughput (e.g., I3).
   - **Accelerated Computing**: GPUs for intensive computing (e.g., P3).

5. **What is a Load Balancer?**
   - A Load Balancer distributes incoming traffic across multiple EC2 instances to ensure no single instance is overwhelmed and to improve fault tolerance and availability.

6. **What is the primary purpose of AWS Regions in the global infrastructure?**
   - AWS Regions provide geographical distribution of data centers to ensure redundancy, reduce latency, and enhance data sovereignty.

7. **Describe the function of Amazon CloudFront in AWS's architecture.**
   - Amazon CloudFront is a content delivery network (CDN) that caches copies of content in edge locations to deliver data to users with low latency and high transfer speeds.

8. **How do AWS Edge locations enhance the performance of Amazon CloudFront?**
   - Edge locations are geographically distributed data centers that cache content closer to users, reducing latency and improving the speed of content delivery.

9. **Explain how Amazon Route 53 integrates with AWS Edge locations to enhance user experiences.**
   - Amazon Route 53 is a scalable DNS service that routes user requests to the nearest edge location, improving the speed and reliability of content delivery.

10. **What are the advantages of using AWS Outposts for local data processing needs?**
    - AWS Outposts extend AWS infrastructure and services to on-premises locations, providing consistent hybrid cloud experiences, low-latency processing, and local data residency.

11. **How are AWS Lambda and AWS Outposts different in what they offer for cloud computing?**
    - **AWS Lambda** is a serverless compute service that executes code in response to events without managing servers.
    - **AWS Outposts** are physical servers located on-premises that extend AWS infrastructure to the local data center for local data processing.

12. **What is high availability?**
    - High availability refers to systems designed to remain operational and accessible with minimal downtime, often through redundant infrastructure and failover mechanisms.

13. **What are the benefits of AWS having a global infrastructure with multiple regions?**
    - Improved fault tolerance, reduced latency, enhanced data sovereignty, and better disaster recovery capabilities.

14. **What is an AWS Region?**
    - An AWS Region is a geographical area with multiple isolated locations known as Availability Zones that provides services and resources.

15. **Why is data sovereignty important in AWS Regions?**
    - Data sovereignty ensures that data remains within specific legal jurisdictions to comply with local regulations and laws.

16. **How do AWS Regions enhance disaster recovery capabilities?**
    - AWS Regions provide geographically separate locations, enabling data replication and failover to ensure continuity in case of a disaster.

17. **What are the four main factors to consider when choosing an AWS Region?**
    - **Latency**: Proximity to users.
    - **Data Residency**: Legal and regulatory requirements.
    - **Cost**: Regional pricing variations.
    - **Service Availability**: Availability of specific AWS services.

18. **What is an AWS Availability Zone?**
    - An Availability Zone is a distinct, isolated data center within a region that provides high availability and fault tolerance.

19. **What is the purpose of having multiple Availability Zones within an AWS Region?**
    - To provide redundancy, improve fault tolerance, and ensure high availability of services by isolating failures and distributing resources.

20. **How does AWS ensure low latency communication between Availability Zones?**
    - AWS uses high-bandwidth, low-latency network connections between Availability Zones within a region.

21. **Why is it important to run EC2 instances across multiple AZs?**
    - To ensure high availability and fault tolerance by distributing instances so that if one AZ fails, others can continue to operate.

22. **How do regional AWS services enhance high availability?**
    - Regional services can operate across multiple AZs, providing redundancy and failover capabilities.

23. **What is the purpose of Amazon CloudFront?**
    - Amazon CloudFront delivers content to users with low latency by caching it in edge locations around the world.

24. **What are edge locations in AWS?**
    - Edge locations are data centers that cache content close to end-users to reduce latency and improve delivery speed.

25. **What is AWS Outposts?**
    - AWS Outposts are fully managed servers and racks that extend AWS infrastructure to on-premises locations for consistent hybrid cloud experiences.

26. **How do Availability Zones within AWS Regions contribute to disaster recovery and high availability?**
    - AZs provide isolated infrastructure within a region to protect against failures and ensure continuity of services.

27. **How do AWS Edge locations and Amazon CloudFront improve content delivery?**
    - Edge locations cache content closer to users, reducing latency and improving speed and performance through CloudFront.

28. **What is an API in the context of AWS?**
    - An API (Application Programming Interface) allows interaction with AWS services and resources programmatically.

29. **What is the primary method of interacting with AWS services?**
    - The primary method is through the AWS Management Console, AWS CLI, or SDKs.

30. **What are the main ways to interact with AWS services?**
    - AWS Management Console, AWS CLI, and AWS SDKs.

31. **Why is automation important in cloud deployment?**
    - Automation reduces manual intervention, minimizes human errors, and ensures consistent and repeatable deployments.

32. **What is the primary advantage of using AWS Elastic Beanstalk over manual methods like the AWS Management Console?**
    - AWS Elastic Beanstalk automates deployment, scaling, and management of applications, simplifying the process compared to manual configuration.

33. **What is AWS Elastic Beanstalk used for?**
    - AWS Elastic Beanstalk is used for deploying and managing applications without needing to manage the underlying infrastructure.

34. **How does AWS CloudFormation help in managing AWS resources?**
    - AWS CloudFormation allows users to define and provision infrastructure using templates, automating the creation and management of AWS resources.

35. **What are the main components of AWS Global Infrastructure?**
    - Regions, Availability Zones, Edge Locations, and Data Centers.

36. **Which AWS services automatically run across multiple Availability Zones?**
    - Services like Amazon RDS, Amazon S3, and Amazon EC2 can be configured to run across multiple AZs.

37. **What is the recommended best practice for deploying infrastructure in AWS?**
    - Utilize multiple Availability Zones and regions for high availability and disaster recovery.

### AWS Educate: Getting Started with Compute Lab

**Domain 1: Compute Services**

1. **What is Amazon EC2?**
   - Amazon EC2 (Elastic Compute Cloud) is a scalable compute service that provides resizable virtual servers in the cloud.

2. **What is Amazon EC2 and its primary benefits?**
   - Amazon EC2 offers scalable compute capacity with benefits like flexibility, cost-effectiveness, and the ability to scale resources based on demand.

3. **What is a Security Group in EC2?**
   - A Security Group acts as a virtual firewall to control inbound and outbound traffic for EC2 instances.

4. **What are the four main purchasing options for EC2 instances, and what are their key characteristics?**
   - **On-Demand Instances**: Pay for capacity by the hour with no long-term commitment.
   - **Reserved Instances**: Reserve capacity with a discount for a 1 or 3-year term.
   - **Spot Instances**: Bid for unused capacity at reduced rates.
   - **Savings Plans**: Flexible pricing model with savings over On-Demand pricing.

5. **How does EC2 pricing work?**
   - EC2 pricing is based on instance type, pricing model, and usage time. Additional costs may include storage and data transfer.

6. **What is an Amazon Machine Image (AMI)?**
   - An AMI is a pre-configured template that includes an operating system, application server, and applications required to launch
