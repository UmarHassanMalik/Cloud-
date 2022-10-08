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



 
 
 
 
 






