
<h2> Coursera Modules </h2>

<h2> MODULE 1 </h2>

<h3> Cloud Computing </h3>

Cloud computing is on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, we can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider such as AWS, Azure, google cloud.

AWS offers numerous services which are required commonly across all the businesses. For example My SQL, Mongo DB databases.

<h3> Client Server Model </h3>
Basically, A client can be a web browser or an application through which a user/person interacts to make requests to servers. A server can be on premisis or a public cloud running as EC2 on AWS or on any other cloud provider i.e Azure, Google cloud etc.  

A client (web browser) makes a request for a file (i.e picture, video etc.) to server and then server evaluates the details and respond the request accordingly. 

<h3> Deployment Models </h3>

There are three cloud computing deployment models.

- Cloud-based
- On-premises
- Hybrid. 

<h3> Cloud-based Deployment </h3>

- Run whole application on cloud.
- We can migrate our application to cloud.
- We can build new applications on cloud.

<h3> Hybrid Deployment </h3>

Cloud-based resources are connected to on-premises infrastructure.  For example, we have legacy applications that are better maintained on premises, banks, military or government regulations require our business to keep certain records on premises.

<h3> On Premisis Deployment </h3>
It is a private cloud deployment. Resources are deployed on premises by using virtualization technologies and resource management tools.

<h3> Advantages of Cloud Computing </h3>

<h3> Accessability </h3>
We can deploy our application to different parts of the world .If we are located in a different part of the world than our customers, customers are able to access our applications with minimal delays.

<h3> Better Performance & Felxibility </h3>
flexibility provides us with more time to experiment and innovate. When computing in data centers, it may take weeks to obtain new resourceswhich we need. Cloud computing enables us to access new resources within short time.

<h3> Capacity Guess </h3>
We dont need to speculate that how much infrastructure capacity we will need before deploying an application.
For instance, we can launch Amazon EC2 instances when needed, and pay only for the compute time that we use.


<h3> No headache of maintaining and running data centers </h3>

Computing in data centers requires us to spend more money and time managing infrastructure and servers on the other hand, cloud computing allows us to focus less on these tasks and more on our applications and clients.



<h2> MODULE 2 </h2>

<h3> EC2 </h3>

- Amazon EC2 or Elastic compute cloud allows user to rent virtual computer on which they can run their own applications.
- EC2 provides scalable deployment of an application through a service (Auto scaling); in which a user can boot a Amazon machine image to configure a virtual machine.
- A user can create as many virtual machines as he needs and paying by a second of active servers.

<h3> Traditional Approach </h3>

- Costs upfront to purchase hardware.
- Wait for the servers to be delivered.
- Installing servers in our data centers.
- Setting of servers configuration.

<h3> Using AWS EC2 </h3>

- Launch Amazon EC2 instance(s) within minutes.
- Pay for server capacity that we need or want.
- Pay only for server capacity that we need or want. no cost for the terminated/stopped instances.
- Stop using it when we have finished running a workload.


<h3> Steps to Use EC2 </h3>

<h3> Launch </h3>

First, we launch an instance by selecting a template with basic configurations for our instance. The configurations can be related to OS, application, server, instance type.

<h3> Connect </h3>

After that we connect to the instance which can be done in different ways. Oour programs and applications have multiple different methods to connect directly to the instance and exchange data i.e login/ accessing through PC.

<h3> Use </h3>

After connecting to the instance we can run commands/scripts to install software, add storage, copy and organize files etc.


<h3> Instances Types </h3>

There are several types of EC2 instances.

<h3> General purpose instances </h3>

General purpose instances provide a balance of compute, memory, and networking resources. We can use them to handle variety of workloads such as.

application servers

gaming servers

backend servers for enterprise applications

small and medium databases

<h3> Compute optimized instances </h3>

Compute optimized instances are ideal for compute-bound applications that benefit from high-performance processors.
we use them in  areas like web, application, and gaming servers.

<h3> Memory optimized instances </h3>
  
Memory optimized instances are designed to deliver fast performance for workloads that process large datasets in memory.
Exmple: We can handle a workload that requires large amounts of data to be preloaded before running an application such as high-performance database or a workload that involves performing real-time processing of a large amount of unstructured data.

<h3> Accelerated computing instances </h3>

Accelerated computing instances use hardware accelerators, or coprocessors, to perform some functions more efficiently than is possible in software running on CPUs
Examples:  floating-point number calculations, graphics processing, and data pattern matching.

<h3> Storage optimized instances </h3>

Storage optimized instances are designed for workloads that require high, sequential read and write access to large datasets on local storage.
Examples:  Distributed file systems, data warehousing applications, and high-frequency online transaction processing system.

<h3> Instances Pricing Model </h3>

<h3> On-Demand </h3>

The Instances are ideal for short-term, irregular workloads that cannot be interrupted. No upfront costs or minimum contracts apply.

<h3> Reserved Instances </h3> 

Reserved Instances are a billing discount applied to the use of On-Demand Instances in our account. We can purchase Standard Reserved and Convertible Reserved Instances for a 1-year or 3-year term

<h3> Dedicated Hosts </h3> 

Dedicated Hosts are physical servers with Amazon EC2 instance capacity that is fully dedicated to our use. 
We can buy On-Demand Dedicated Hosts and Dedicated Hosts Reservations.

<h3> Spot Instances </h3> 

Spot Instances are ideal for workloads with flexible start and end times, or that can withstand interruptions. Spot Instances use unused Amazon EC2 computing capacity and offer us cost savings at up to 90% off of On-Demand prices.
The are highly cost effective but these instances can be taken down by AWS and assigned it to the next high bid client.

<h3>Scalability </h3> 
Amazon EC2 Auto Scaling helps us maintain application availability and allows us to automatically add or remove EC2 instances according to the conditions we define. 
As a result, we pay for only the resources we use. We don’t have to worry about a lack of computing capacity to meet our customers needs.


<h3> AWS EC2 Autos Scaling  </h3> 
When we access a website that wouldn’t load and frequently timed out, the website might have received more requests than it was able to handle (overloaded). 
Amazon EC2 Auto Scaling enable us to automatically add or remove Amazon EC2 instances in response to changing application demand. By automatically scaling our instances in and out as needed.

There are 2 type of autocaling is being used by AWS EC2 Autoscaling. 

- Predictive Scaling responsds to predictive demand.
- Dynamic Scaling responds to demand.


<h3> Scaling Amazon EC2 </h3>

Additioon of Amazon EC2 Auto Scaling to an application can add new instances to the application when necessary and terminate them when no longer needed.
If we are preparing to launch an application on Amazon EC2 instances. When configuring the size of our Auto Scaling group, we might set the minimum number of Amazon EC2 instances at one. This means that at all times, there must be at least one Amazon EC2 instance running.

When we create an Auto Scaling group, we can set the minimum number of Amazon EC2 instances. The minimum capacity is the number of Amazon EC2 instances that launch immediately after we have created the Auto Scaling group. In this example, the Auto Scaling group has a minimum capacity of one Amazon EC2 instance.

Next, we can set the desired capacity at two Amazon EC2 instances even though our application needs a minimum of a single Amazon EC2 instance to run.

we can set in an Auto Scaling group is the maximum capacity. For example, we might configure the Auto Scaling group to scale out in response to increased demand, but only to a maximum of four Amazon EC2 instances.

We pay for only the instances we use, when we use them. We now have a cost-effective architecture that provides the best customer experience while reducing expenses.

<h3> Elastic Load Balancer </h3>

Elastic Load Balancing is the AWS service that automatically distributes incoming application traffic across multiple resources. So therefore we can utilize maximum (optimum) use of our resources by distributing the workloads to across multiple instances.

A load balancer acts as a single point of contact for all incoming web traffic to our Auto Scaling group. This means that as we add or remove Amazon EC2 instances in response to the amount of incoming traffic, these requests route to the load balancer first. Then, the requests spread across multiple resources that will handle them. For example, if we have multiple Amazon EC2 instances, Elastic Load Balancing distributes the workload across the multiple instances so that no single instance has to carry the bulk of it. 

ELB and Autoscaling together on EC2 can provide high performance and availability of our applications.

Handles the instances effectively on high and low demand periods.

<h3> Application Architecture </h3>

<h3> Monolithic Architecture </h3>

In this architecture, applications are made of multiple components. The components communicate with each other to transmit data, fulfill requests, and keep the application running. 
In monolithic applications we have an application with tightly coupled components. These components might include databases, servers, the user interface, business logic layer etc.

In this architecture we have single point of failure if one component fails the whole application will fail.
  
<h3> Micro Services Architecture </h3>  

A microservices architecture is a type of application architecture where the application is developed as a collection of services. It provides the framework to develop, deploy, and maintain microservices architecture diagrams and services independently.

In a microservices approach, application components are loosely coupled. In this case, if a single component fails, the other components continue to work because they are communicating with each other. The loose coupling prevents the entire application from failing. 

<h3> Amazon Simple Notification Service (Amazon SNS) </h3>
Amazon Simple Notification Service (Amazon SNS) is a publish/subscribe service. Using Amazon SNS topics, a publisher publishes messages to subscribers. 

In Amazon SNS, subscribers can be web servers, email addresses, AWS Lambda functions, or several other options.

<h3> Amazon Simple Queue Service (Amazon SQS)  </h3> 

Using Amazon SQS, we can send, store, and receive messages between software components, without losing messages or requiring other services to be available. In Amazon SQS, an application sends messages into a queue. A user or service retrieves a message from the queue, processes it, and then deletes it from the queue.

<h3> Serverless Computing </h3>
The term “serverless” means that your code runs on servers, but you do not need to provision or manage these servers. With serverless computing, you can focus more on innovating new products and features instead of maintaining servers.

Another benefit of serverless computing is the flexibility to scale serverless applications automatically. Serverless computing can adjust the applications' capacity by modifying the units of consumptions, such as throughput and memory. 

The service on AWS is known as AWS lambda.

<h3> AWS Lambda </h3>
AWS Lambda is a service that lets you run code without needing to provision or manage servers. 

While using AWS Lambda, you pay only for the compute time that you consume. Charges apply only when your code is running. You can also run code for virtually any type of application or backend service, all with zero administration.

<h3> Working </h3>

upload the code to Lambda. 

Set code to trigger from an event source, such as AWS services, mobile applications, or HTTP endpoints.

Lambda runs the code only when triggered.

Pay only for the compute time that we use. In the previous example of resizing images, we would pay only for the compute time that we use when uploading new images. Uploading the images triggers Lambda to run code for the image resizing function.

<h3> Containers </h3>
Contaienrs are virtual instances at operating system level that provide us with a standard way to package our application's code and dependencies into a single object. We can also use containers for processes and workflows in which there are essential requirements for security, reliability, and scalability.

In AWS, we can also build and run containerized applications.

<h3> Amazon Elastic Container Service (Amazon ECS) </h3>

Amazon Elastic Container Service (Amazon ECS) is a highly scalable, high-performance container management system that enables us to run and scale containerized applications on AWS. 




<h2> MODULE 3 </h2>

<h3> Regions </h3>

Compliance with data governance and legal requirements

Depending on your company and location, you might need to run your data out of specific areas. For example, if your company requires all of its data to reside within the boundaries of the UK, you would choose the London Region. 

Proximity to customers

Selecting a Region that is close to your customers will help you to get content to them faster. For example, your company is based in Washington, DC, and many of your customers live in Singapore. You might consider running your infrastructure in the Northern Virginia Region to be close to company headquarters, and run your applications from the Singapore Region.

Available services within a Region

Sometimes, the closest Region might not have all the features that you want to offer to customers. AWS is frequently innovating by creating new services and expanding on features within existing services. However, making new services available around the world sometimes requires AWS to build out physical hardware one Region at a time. 

Pricing

Suppose that you are considering running applications in both the United States and Brazil. The way Brazil’s tax structure is set up, it might cost 50% more to run the same workload out of the São Paulo Region compared to the Oregon Region. You will learn in more detail that several factors determine pricing, but for now know that the cost of services can vary from Region to Region.
  
<h3> Availability Zone </h3>  

An Availability Zone is a single data center or a group of data centers within a Region. Availability Zones are located tens of miles apart from each other. This is close enough to have low latency (the time between when content requested and received) between Availability Zones. However, if a disaster occurs in one part of the Region, they are distant enough to reduce the chance that multiple Availability Zones are affected.

<h3> Edge Locations </h3>

For example if our company’s data is stored in Brazil, and you have customers who live in UK. To provide content to these customers, you don’t need to move all the content to one of the UKs Regions.
Instead of requiring your customers to get their data from Brazil, you can cache a copy locally at an edge location that is close to your customers in UK.

<h3> Ways to Interact with AWS Services </h3>

<h3> AWS Management Console </h3>

The AWS Management Console is a web-based interface for accessing and managing AWS services
  
<h3> AWS Command Line Interface</h3>

To save time when making API requests, you can use the AWS Command Line Interface (AWS CLI). AWS CLI enables you to control multiple AWS services directly from the command line within one tool. AWS CLI is available for users on Windows, macOS, and Linux. 

<h3>Software development kits (SDKs)</h3>

Another option for accessing and managing AWS services is the software development kits (SDKs). SDKs make it easier for you to use AWS services through an API designed for your programming language or platform. SDKs enable you to use AWS services with your existing applications or create entirely new applications that will run on AWS.

<h3>AWS Elastic Beanstalk</h3>

Provides code and configuration settings, and Elastic Beanstalk deploys the resources necessary to perform the following tasks:

Adjust capacity

Load balancing

Automatic scaling

Application health monitoring

<h3> AWS CloudFormation </h3>

It facilitate us with infrastructure as code  environment by writing lines of code instead of using the AWS Management Console to individually provision resources.

AWS CloudFormation provisions your resources in a safe, repeatable manner, enabling you to frequently build your infrastructure and applications without having to perform manual actions or write custom scripts. It determines the right operations to perform when managing your stack and rolls back changes automatically if it detects errors.


<h2> MODULE 4 </h2>

<h3> Amazon Virtual Private Cloud </h3>

A networking service that you can use to establish boundaries around your AWS resources is Amazon Virtual Private Cloud (Amazon VPC).
  
Amazon VPC enables you to provision an isolated section of the AWS Cloud. In this isolated section, you can launch resources in a virtual network that you define. Within a virtual private cloud (VPC), you can organize your resources into subnets. A subnet is a section of a VPC that can contain resources such as Amazon EC2 instances.
  
<h3> Internet gateway </h3>
  
To allow public traffic from the internet to access your VPC, you attach an internet gateway to the VPC.
  
<h3> AWS Direct Connect </h3>
  
AWS Direct Connect is a service that enables you to establish a dedicated private connection between your data center and a VPC.  

<h3>Subnets</h3>

A subnet is a section of a VPC in which you can group resources based on security or operational needs. Subnets can be public or private.

**Public subnets** contain resources that need to be accessible by the public, such as an online store’s website.

**Private subnets** contains resources that should be accessible only through your private network, such as a database that contains customers’ personal information and order histories. 

**Network Traffic in a VPC** 

When a customer requests data from an application hosted in the AWS Cloud, this request is sent as a packet. A packet is a unit of data sent over the internet or a network. 

It enters into a VPC through an internet gateway. Before a packet can enter into a subnet or exit from a subnet, it checks for permissions. These permissions indicate who sent the packet and how the packet is trying to communicate with the resources in a subnet.


<h3>Network Access Control Lists (ACLs)</h3>

A network access control list (ACL) is a virtual firewall that controls inbound and outbound traffic at the subnet level.

**Stateless Packet Filtering**
Network ACLs perform stateless packet filtering. They remember nothing and check packets that cross the subnet border each way: inbound and outbound. 

<h3>Security Groups</h3>
A security group is a virtual firewall that controls inbound and outbound traffic for an Amazon EC2 instance.
  
By default, a security group denies all inbound traffic and allows all outbound traffic. You can add custom rules to configure which traffic to allow or deny.

**Stateful Packet Filtering**
Security groups perform stateful packet filtering. They remember previous decisions made for incoming packets.


<h3> Domain Name System (DNS)</h3>

Suppose that AnyCompany has a website hosted in the AWS Cloud. Customers enter the web address into their browser, and they are able to access the website. This happens because of Domain Name System (DNS) resolution. DNS resolution involves a DNS server communicating with a web server.

<h3> Amazon Route 53 </h3>
Amazon Route 53 is a DNS web service. It gives developers and businesses a reliable way to route end users to internet applications hosted in AWS. 

Amazon Route 53 connects user requests to infrastructure running in AWS (such as Amazon EC2 instances and load balancers). It can route users to infrastructure outside of AWS.


<h3> MODULE 5 </h3>

<h3> Instance stores </h3>
Block-level storage volumes behave like physical hard drives.

An instance store provides temporary block-level storage for an Amazon EC2 instance. An instance store is disk storage that is physically attached to the host computer for an EC2 instance, and therefore has the same lifespan as the instance. When the instance is terminated, you lose any data in the instance store.

<h3> Amazon Elastic Block Storage  </h3>
Amazon Elastic Block Store (Amazon EBS) is a service that provides block-level storage volumes that you can use with Amazon EC2 instances. If you stop or terminate an Amazon EC2 instance, all the data on the attached EBS volume remains available.
  
<h3> Amazon EBS Snapshots </h3>
An EBS snapshot is an incremental backup. This means that the first backup taken of a volume copies all the data. For subsequent backups, only the blocks of data that have changed since the most recent snapshot are saved.

<h3> Object Storage </h3>
  
In object storage, each object consists of data, metadata, and a key.

The data might be an image, video, text document, or any other type of file. Metadata contains information about what the data is, how it is used, the object size, and so on. An object’s key is its unique identifier
  
<h3> Amazon Simple Storage Service </h3>
  
Amazon Simple Storage Service (Amazon S3) is a service that provides object-level storage. Amazon S3 stores data as objects in buckets.

You can upload any type of file to Amazon S3, such as images, videos, text files, and so on. For example, you might use Amazon S3 to store backup files, media files for a website, or archived documents. Amazon S3 offers unlimited storage space. The maximum file size for an object in Amazon S3 is 5 TB.
  
 ** Storage Classes**
  
- Amazon S3 Standard
- Amazon S3 Standard-Infrequent Access (S3 Standard-IA)
- Amazon S3 Intelligent-Tiering
- Amazon S3 Glacier Instant Retrieval
- Amazon S3 Glacier Flexible Retrieval
- Amazon S3 Glacier Deep Archive
- Amazon S3 Outposts
  
 <h3> File Storage </h3>
  
In file storage, multiple clients (such as users, applications, servers, and so on) can access data that is stored in shared file folders. In this approach, a storage server uses block storage with a local file system to organize files. Clients access data through file paths.
  
  **Amazon Elastic File System ** is a scalable file system used with AWS Cloud services and on-premises resources. As you add and remove files, Amazon EFS grows and shrinks automatically. It can scale on demand to petabytes without disrupting applications. 
  
<h3>  Amazon EBS </h3>

An Amazon EBS volume stores data in a single Availability Zone. 

To attach an Amazon EC2 instance to an EBS volume, both the Amazon EC2 instance and the EBS volume must reside within the same Availability Zone.
  
 <h3> Amazon EFS </h3>

Amazon EFS is a regional service. It stores data in and across multiple Availability Zones. 

The duplicate storage enables you to access data concurrently from all the Availability Zones in the Region where a file system is located. Additionally, on-premises servers can access Amazon EFS using AWS Direct Connect.


<h2> Module 6 </h2> 

<h3> Shared Responsibility Model </h3>
- AWS is responsible for some parts of your environment and you (the customer) are responsible for other parts. This concept is known as the shared responsibility model.
- Customer responsibilities ( security in the cloud)
   - maintain complete control over your content. 
   - You are responsible for managing security requirements for your content, including which content you choose to store on AWS
   - Services which you are using
- AWS responsibilities(security of the cloud)
  - protecting the global infrastructure that runs all of the services offered in the AWS Cloud
  - Specifically the physical infrastructure that hosts your resources


<h3> 5. IAM Groups </h3>
collection of IAM users
assign an IAM policy to a group, all users in the group are granted permissions specified by the policy.


<h3> 6. IAM Roles</h3>
An IAM role is an identity that you can assume to gain temporary access to permissions.  
IAM roles are ideal for situations in which access to services or resources needs to be granted temporarily, instead of long-term.  

<h3> 7. Multi-factor Authentication</h3>
You can enable MFA for the root user and IAM users. As a best practice, enable MFA for the root user and all IAM users in your account. By doing this, you can keep your AWS account safe from unauthorized access.


<h3> AWS Organizations </h3>
When you create an organization, AWS Organizations automatically creates a root, which is the parent container for all the accounts in your organization. 

In AWS Organizations, you can centrally control permissions for the accounts in your organization by using **service control policies (SCPs)**. SCPs enable you to place restrictions on the AWS services, resources, and individual API actions that users and roles in each account can access.

<h3> Organizational Units</h3>
Converting whole organizations into the Sub Parts or units for managing them indivisual.


<h3> Compliance</h3>
<h3> 1. AWS Artifact
- An audit or inspection will ensure that the company has met those standards.
- provides on-demand access to AWS security and compliance reports and select online agreements. AWS Artifact consists of two main sections: 
   - AWS Artifact Agreements
   review, accept, and manage agreements for an individual account and for all your accounts in AWS Organizations

   - AWS Artifact Reports
           - AWS Artifact Reports provide compliance reports from third-party auditors.
           -  These auditors have tested and verified that AWS is compliant with a variety of global, regional, and industry-specific security standards and regulations. 
           -  AWS Artifact Reports remains up to date with the latest reports released. 
<h3> Denial-of-Service Attacks</h3>
- A denial-of-service (DoS) attack is a deliberate attempt to make a website or application unavailable to users.

<h3> AWS Shield</h3>
AWS Shield is a service that protects applications against DDoS attacks. AWS Shield provides two levels of protection: Standard and Advanced.

1. ** AWS Shield Standard **
- AWS Shield Standard automatically protects all AWS customers at no cost. It protects your AWS resources from the most common, frequently occurring types of DDoS attack. 
- AWS Shield Standard uses a variety of analysis techniques to detect malicious traffic in real time and automatically mitigates it. 
2. ** AWS Shield Advanced **
- AWS Shield Advanced is a paid service that provides detailed attack diagnostics and the ability to detect and mitigate sophisticated DDoS attacks. 
- It also integrates with other services such as Amazon CloudFront, Amazon Route 53, and Elastic Load Balancing. Additionally, you can integrate AWS Shield with AWS WAF by writing custom rules to mitigate complex DDoS attacks.

<h3> Additional Security Services</h3>
- ** AWS Key Management Service (AWS KMS) **
AWS Key Management Service (AWS KMS) enables you to perform encryption operations through the use of cryptographic keys. 
- ** AWS WAF **
   - AWS WAF is a web application firewall that lets us monitor network requests that come into our web applications. 
   - AWS WAF works together with Amazon CloudFront and an Application Load Balancer.
   
- ** Amazon Inspector **
Amazon Inspector helps to improve the security and compliance of applications by running automated security assessments. It checks applications for security vulnerabilities and deviations from security best practices, such as open access to Amazon EC2 instances and installations of vulnerable software versions. 
- ** Amazon GuardDuty **
Amazon GuardDuty is a service that provides intelligent threat detection for our AWS infrastructure and resources. It identifies threats by continuously monitoring the network activity and account behavior within our AWS environment.
If GuardDuty detects any threats, you can review detailed findings about them from the AWS Management Console. 





<h2> MODULE 7 </h2>

<h3> Amazon CloudWatch</h3>
- Amazon CloudWatch is a web service that enables you to monitor and manage various metrics and configure alarm actions based on data from those metrics.
- CloudWatch uses metrics to represent the data points for our resources. AWS services send metrics to CloudWatch. CloudWatch then uses these metrics to create graphs automatically that show how performance has changed over time.

<h3> CloudWatch Alarms</h3>
 CloudWatch Alarms that automatically perform actions if the value of our metric has gone above or below a predefined threshold. 
 
 <h3> AWS CloudTrail</h3>
 AWS CloudTrail records API calls for our account.
 In the CloudTrail Event History section, the owner applies a filter to display only the events for the “CreateUser” API action in IAM.
 
 <h3> CloudTrail Insights</h3>
 This optional feature allows CloudTrail to automatically detect unusual API activities in our AWS account. 
 
 <h3> AWS Trusted Advisor</h3>
 AWS Trusted Advisor is a web service that inspects our AWS environment and provides real-time recommendations in accordance with AWS best practices.
 When you access the Trusted Advisor dashboard on the AWS Management Console, you can review completed checks for cost optimization, performance, security, fault tolerance, and service limits.


   - The green check indicates the number of items for which it detected no problems

   - The orange triangle represents the number of recommended investigations

   - The red circle represents the number of recommended actions


<h2> MODULE 8 </h2>



<h3> AWS Free Tier</h3>
The AWS Free Tier enables you to begin using certain services without having to worry about incurring costs for the specified period. 
Three types of offers are available: 

- Always Free
AWS Lambda allows 1 million free requests and up to 3.2 million seconds of compute time per month. Amazon DynamoDB allows 25 GB of free storage per month.
- 12 Months Free

- Trials ( offers 750 free hours of usage over a 30-day period.)

<h3> Billing Dashboard</h3>
Use the AWS Billing & Cost Management dashboard to pay our AWS bill, monitor our usage, and analyze and control yur costs.

- Compare our current month-to-date balance with the previous month, and get a forecast of the next month based on current usage.

- View month-to-date spend by service.

- View Free Tier usage by service.

- Access Cost Explorer and create budgets.

- Purchase and manage Savings Plans.

- Publish AWS Cost and Usage Reports.

<h3> AWS Budgets</h3>
- In AWS Budgets,  we can create budgets to plan our service usage, service costs, and instance reservations.
- The information in AWS Budgets updates three times a day. This helps we to accurately determine how close our usage is to yur budgeted amounts or to the AWS Free Tier limits.

<h3> AWS Cost Explorer</h3>
- AWS Cost Explorer is a tool that enables us to visualize, understand, and manage our AWS costs and usage over time.
- AWS Cost Explorer includes a default report of the costs and usage for our top five cost-accruing AWS services. we can apply custom filters and groups to analyze our data. For example, we can view resource usage at the hourly level.

<h3> AWS Support Plans</h3>
- Basic

- Developer

- Business

- Enterprise On-Ramp

- Enterprise



<h2> MODULE 9</h2>



<h3> AWS Snow Family</h3>
The AWS Snow Family is a collection of physical devices that help to physically transport up to exabytes of data into and out of AWS. 
AWS Snowcone is a small, rugged, and secure edge computing and data transfer device. 

<h3> Snowball Edge Storage Optimized</h3>
devices are well suited for large-scale data migrations and recurring transfer workflows, in addition to local computing with higher capacity needs. Snowball Edge Storage Optimized provides 80 TB of HDD capacity for block volumes and Amazon S3-compatible object storage, and 1 TB of SATA SSD for block volumes.

<h3> Snowball Edge Compute Optimized</h3>
provides powerful computing resources for use cases such as machine learning, full motion video analysis, analytics, and local computing stacks. 

<h3> AWS Snowmobile</h3>
AWS Snowmobile is an exabyte-scale data transfer service used to move large amounts of data to AWS. 

we can transfer up to 100 petabytes of data per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi trailer truck.

# Migration and Innovation
<h3> AWS Cloud Adoption Framework (AWS CAF)</h3>
- Business Perspective => IT aligns with business needs and that IT investments link to key business results.
- People Perspective => upports development of an organization-wide change management strategy for successful cloud adoption.
- Governance Perspective =>  focuses on the skills and processes to align IT strategy with business strategy. This ensures that we maximize the business value and minimize risks.
- <b>Platform Perspective</b>  includes principles and patterns for implementing new solutions on the cloud, and migrating on-premises workloads to the cloud.
- <b> Security Perspective</b>  ensures that the organization meets security objectives for visibility, auditability, control, and agility. 
- <b>Operations Perspective</b> helps us to enable, run, use, operate, and recover IT workloads to the level agreed upon with our business stakeholders.

<h3> Migration Strategies</h3>
  
<b> Rehosting </b>
  
It involves moving applications without changes. 
  
<b> Replatforming </b>
  
 involves making a few cloud optimizations to realize a tangible benefit. Optimization is achieved without changing the core architecture of the application.
  
<b> Refactoring/re-architecting </b>
  
It involves reimagining how an application is architected and developed by using cloud-native features. Refactoring is driven by a strong business need to add features, scale, or performance that would otherwise be difficult to achieve in the application’s existing environment.
  
<b> Repurchasing </b>
  
involves moving from a traditional license to a software-as-a-service model. 
  
<b> Retaining </b>
  
consists of keeping applications that are critical for the business in the source environment. This might include applications that require major refactoring before they can be migrated, or, work that can be postponed until a later time.
  
<b> Retiring </b>
  
process of removing applications that are no longer needed.

<h2> MODULE 10 </h2>

<h3>AWS Well-Architected Framework</h3>
design and operate reliable, secure, efficient, and cost-effective systems in the AWS Cloud. It provides a way for us to consistently measure our architecture against best practices and design principles and identify areas for improvement.
<h3> Operational excellence </h3> 
 is the ability to run and monitor systems to deliver business value and to continually improve supporting processes and procedures.  
 
 

<h3> Cost optimization  </h3>
  
Cost optimization is the ability to run systems to deliver business value at the lowest price point. 
  
<h3> Sustainability </h3>
  
Sustainability is the ability to continually improve sustainability impacts by reducing energy consumption and increasing efficiency across all components of a workload by maximizing the benefits from the provisioned resources and minimizing the total resources required.

<h3> Security  </h3>
The Security pillar is the ability to protect inf
<h3> Reliability  </h3>
    - Recover from infrastructure or service disruptions

    - Dynamically acquire computing resources to meet demand

    -  Mitigate disruptions such as misconfigurations or transient network issues
<h3> Performance efficiency</h3>
 Performance efficiency is the ability to use computing resources efficiently to meet system requirements and to maintain that efficiency as demand changes and technologies evolve. 




