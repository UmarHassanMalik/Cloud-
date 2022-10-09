<h3> AWS Solution Architect Associate </h3>

![image](https://user-images.githubusercontent.com/58930229/194708335-30cc1b79-9ee3-40c5-9a37-fe30db7f1c31.png)

<h3> Solution Architect Associate </h3>

- Finding Creative solution by leveraging cloud services 
- Deomonstrate about how much knowledge we possess in various domains.
- More about what we are going to implement.


<h3> What we consider </h3>

- Architecture 
- Pricing 
- Constant Learning 
- Security 

<h3> Value that AWS Solution Architect hold </h3>

- Most popular AWS certification.
- Highly demanded in startups.
- More job opportunities.
- Most flexible future learning path

<h3> Object Storage </h3>

Data storage arhcitecture manages data as objects 

- File storage manages data as files or hierarchy.
- Block storage manages data as blocks within sectors

<h3> S3 Object </h3>

- It contains key, value, version ID and metadata.
- We can store data upto 5 Terabytes.

<h3> S3 Buckets </h3>

- S3 bucket hold objectw. 
- Its a universal namespace so their name must be unique.

<h3> Storage Classes </h3> 

- Fast Availabilty (99.99%), durability and replicated across various zones.
- Intelligent Tiering. 
- Standard Infrequently Accessed. 
- One Zone IA
- Glacier - long term cheap storage.

![image](https://user-images.githubusercontent.com/58930229/194708262-ec9ba5d8-75bd-4a75-b42d-0c8945309020.png)

<h3> S3 Security </h3>

- Access control list can be configured by using bucket policies. 

<b> Encryption </b> 

- Server side encryption -  encrypt object data. 
- SSE-AES, SSE-KMS, SSE-C.
- S3 managed keys.
- Client side encryption - we encrypt our files before uploading to S3.

<h3> Data Consistency </h3>

- Read After Write Consistency. 
- Eventual consistency. 

<h3> Cross Region Replication CRR </h3> 

- When enabled --- replicates an object to another region 
- Durablitiy -- Disaster recovery.

<h3> MFA Delete </h3>

- Ensures that users cannot delete MFA unless they provide their MFA code.
- Bucket S3 versioning must be turned on. 
- AWS cli must be used to turn on MFA.

<h3> Snowball </h3>
 
- Generally it costs thousands of dollars to transfer 100TB over high speed internet. 
- Snowball reduces this cost by 1/5th.
- Reduce transfer time by less than a week.

<b> We can use snowball edge having more storage and several properties like processing etc. </b>

<b> Snowmobile can transfer upto 100PB per snowmobile </b>

![image](https://user-images.githubusercontent.com/58930229/194718919-afc2865f-412d-47a8-9daa-abf2d74ee064.png)

<h3> Virtual Private Cloud (VPC) </h3>

- Region Specific. 
- Can create 5 VPC per region.
- 200 VPC subnets per VPC.
- IP4 Cidr Block.
- DNS hostnames.


<h3> VPC Features </h3>

- AWS has default VPC with default settings.

<b> Example </b> 

- Default DHCP 
- Default Security group.
- Default network access control list.
- VPC size /16 IPv4 CIDR Block.
- Has route table. 
- Default subnet /20 in each zone.

<h3> VPC Peering </h3>

- Allows us to connect to another VPC over a irect network route using a private network address.

<h3> Route Tables </h3> 

- It determines where our traffic is directed. 
- Each subnet should be associated with it.

<h3> IGW Internet Gateway </h3> 

- Allows VPC to connect to the internet.
- NAT translation.
- Target VPC route tables to connect to internet routeable traffic.

<h3> Bastions </h3>
 
 They are EC2 instances in a private subnet and security hardened. They give access to EC2 instances via SSH/RCP.
 
 <h3> Direct Connect </h3>
 
 Its a very fast network. its an AWS solution for building dedicated netowrk from on-premises locations.
 
 ![image](https://user-images.githubusercontent.com/58930229/194720993-455cd9b1-fa67-46b4-ac9c-965ed4dfd288.png)
 
 
<h3> VPC Endpoints </h3>

- It allows us to connect to different AWS services privately. 
- Highly scaled.
- Redundant.
- High availability.

Interface Endpoints

- Elastic network interfaces with private IP addresses.

Gateway Endpoints

- It targets a specific route in the route table.

<h3> Flow Logs </h3>

It captures traffic information in and out of network interfaces with in VPC.

It can be created for 

- Subnets
- VPC. 
- Network interface.

![image](https://user-images.githubusercontent.com/58930229/194722409-b7d99389-bb8e-4a3b-a59d-667d036d10b8.png)


<h3> NACL </h3>

Network Access control list contains set of rules which allows or deny network traffic into or out of a subnet.

<h3> Security Groups </h3>

Security Groups contains set of rules that controls inbound and outbound traffic of EC2 Instances.
It has no deny rules. Acts as a virtual firewall at instance level.

<h3> NAT </h3>

Network address translation remaps the Private IP addresses in a private network to gain the outbound access to the internet.

<h3> Identity Access Management (IAM) </h3>

I am allows management of access of users and resources which includes;

- User
- Roles
- Groups
- Policies
- MFA 
- Permissions

<h3> Amazon Cognito </h3>

Decentralized Managed Authentication.
Signup Sign in integration with our apps.
Providers  - Google -Facebook.

- Cognito User Profiles
- Cognito Identity Pools
- Cognito Sync.

Web Identity Federation 

Identity Security information exchange between identity providers.
Identity providers (IDP) could be; Google, facebook, github, linkedIn etc.

Types of Providers 

SAML  Security assertion markup language. (Single Sign on)

User Pools

User directories to manage the actions for web and mobile apps. like

- Signin
- Sign up 
- Confirmation
- Recovery

<h3> AWS CLI </h3>
 
 AWS CLI let us iteract with AWS services from anywhere through command line interface. 
 
 For Example we can;
 
- Launch, start, stop, terminate EC2 Instance
- Create, list buckets, upload data. 
- Update security groups, create/update subnets. 
- Setting up VPS, create and terminate.

<h3> AWS SDK </h3>

AWS Software Development kit is used for controlling AWS services through different programming languages.
It is a set of API libraries that let us integrate AWS Services to our application.
Installed via python script.
Programatic access must be enabled per user via IAM to access CLI or SDK.

<h3> AWS Cloud9 </h3> 

 AWS Cloud9 allows us to write and debug a code with just a browser. 
 
 <h3> Domain Name System DNS </h3>
 
 It is a service which handles converting a domain name into a routable IP address.
 
- IPV4 (192.168.150.15)
- IPV6 (2001:db8:3333:4444:5555:6666:7777:8888)
 
 Top Level domains. example.com
 Second level domains. example.com.uk
 
 Record DNS:  It converts domain names with IP addresses.
 CNAME Records: It converts a domain name into another domain name.
 
 TTL: The time in which DNS record will be cached.
 
 <h3> Route53 </h3>
 
It is a cloud based highly scaleable and available DNS. It allows us to register, manage domains and create routing rules.
 
- Route Traffic to our web app.
- Route traffic to an instance.
- Route traffic to an API Gateway.
- Route traffic to a cloudfront.
- Route traffic to an elastic IP.
 
Alias Record
 
Record Set
 
<h3> Routing Policies </h3>
 
- Simple Routing 
 
- Weighted Routing --- Split up traffic based on different weight defined
 
- Latency Based Routing ---directs based on lowest network latency possible for our end user (bassed on region).
 
- Failover Routing --- allows us to create a primary site in one location and a secondary recovery site on another location.
 
- Geolocation Routing --- Directs traffic based on geo-graphical location where the request generated.
 
- Geo Proximity Routing --- select customs region and set custom co ordinates. 
 
- Multi Value Answer Routing
 
 Traffic Flow ---- Visual Editor to create routing configurations for resources using existing routing types.
 
 Health Checks --- A health check can initial a failover if the status is unhealthy. Monitor endpoints.
 
 
 <h3> Amazon EC2 </h3>
   Amazon EC2 or Elastic compute cloud allows user to rent virtual computer on which they can run their own applications. EC2 provides scalable deployment of an application through a service (Auto scaling); in which a user can boot a Amazon machine image to configure a virtual machine. A user can create as many virtual machines as he needs and paying by a second of active servers.

<h3> Features of EC2</h3>

- Virtual computing environment. 
- Configuration of CPU, memory, storage, and networking capacity for our instances, known as instance types, with diverse configuration options.
- Elastic IP addresses.
- Multiple physical locations for our resources, with different availability timezones and regions.  
- Security; such as firewalls and managing IP addresses ranges, ports and protocols through security groups. Secure login information, with private and public key.  
- Creating our own private network, through virtual private cloud service.  
- Persistant storage options i.e Elastic block storage.

<h3> Instances Types </h3>

Amazon provides variety of Instances types which are optimized for difference use cases. Instances types contains diverse combinations and types of CPU, memory , network
capacity with flexibility that gives us mixture of different resources to run our application.

- General Purpose
- Compute Optimized
- Memory Optimized
- Storage Optimized
- Accelerated Computing

<h3> Placement Groups </h3>

Placement Groups let us choose the logical placement of our instances to optimize for communication, performance and durability. Properties based on:

- Cluster 
- Partition 
- Spread


<h3> EC2 Pricing Model </h3>

- On Demand 
- Reserve
- Spot
- Dedicated

<h3> Dedicated Host Instances </h3>

- Multi Tenant --- virtual isolation
- Single Tenant --- Physical isolation

<h3> AWS AMI </h3>
 Amazon Machine Image provides an information required to launch an instance.
 It contains; 

- Volumes, EBS snapshot.
- Operating System, servers information.
- Some are region specific, variation across regions.
- Architecture (32,64).
 
 ![image](https://user-images.githubusercontent.com/58930229/194774184-ff8b751f-bf96-40ed-af2d-38906263b097.png)
 
 <h3>Amazon EC2 Autoscaling Groups</h3>
  
Amazon EC2 Auto Scaling helps us ensure that we have the correct number of Amazon EC2 instances available to handle the load for our application. You create collections of EC2 instances, called Auto Scaling groups. We can specify the minimum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that our group never goes below this size. We can specify the maximum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that our group never goes above this size.  
 
 It occurs via;
 
 Capacity. 
 
 Health check replacements.
 
 Scaling policies.
 
 <h3> Elastic Load Balancer </h3>
 
Distribute network traffic to improve application scalability.

<b> ELB Types </b>
- Application Load balancer
- Gateway Load balancer
- Network Load balancer



 



