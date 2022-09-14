
<h2> Amazon Dynamo DB </h2>
DynamoDB is a fully managed & hosted NoSQL database on Amazon Web Services.

<h3> Features </h3>

- DynamoDB offloads the administrative burdens of operating and scaling a distributed database so that we don't have to worry about hardware provisioning.

- Scalable and provides excellent performance.

- Setup and configuration.

- Software patching, or cluster scaling.

- Eliminates the operational burden and complexity involved in protecting sensitive data.

- High availability and durability.

<h2> Amazon Redshift </h2>
Amazon Redshift Serverless provides data warehouse capacity and intelligent scaling with simple configuration and management.
We can access and analyze data without setting up a provisioned data warehouse.

Initially, we create a data warehouse is to launch a set of nodes, called an Amazon Redshift cluster. After we provision our cluster, we can upload our data set and then perform data analysis queries. Regardless of the size of the data set, Amazon Redshift offers fast query performance using the same SQL-based tools and business intelligence applications.

<h2> Amazon DMS </h2>
AWS DMS is an AWS cloud service created to migrate data in a variety of ways: to the AWS cloud, from on-premises or cloud hosted data stores. AWS DMS can migrate all kinds of data ranging from relational databases, data warehouses, NoSQL databases, and other types of data stores. It is quite versatile and can handle one-time data migration or perform continual data replication with ongoing changes, syncing the source and target.

<h3> Advantages </h3>

- AWS DMS provides automated management of the infrastructure associated with our migration server. This covers hardware, software, software patching, and error reporting.

- AWS DMS reassures with automatic failover. A backup replication server swings into action if the main replication server fails and takes over with hardly any interruption of service.

- AWS DMS enables heterogeneous data migration from any supported data source to any supported target.

- AWS DMS covers a wide range of targets including Oracle, Microsoft SQL Server, PostgreSQL, MySQL, Amazon Redshift, SAP ASE, Amazon S3, and Amazon DynamoDB.

- Almost all DBMS engines like Oracle, Microsoft SQL Server, MySQL, MariaDB, PostgreSQL, Db2 LUW, SAP, MongoDB, and Amazon Aurora are supported as sources by AWS DMS.

<h2> Comparing Amazon RDS & Dynamo DB </h2> 

| RDS     | Dynamo DB |  
| ----------- | ----------- | 
|  Amazon RDS stands for "Relational Database Service", tt is  mostly used for structured and relational data (SQL)          |   DynamoDB is the option that AWS offers for non-relational (NoSQL) databases         |
| There are two SSD backed options for storage in Amazon RDS. A high-performance choice for OLTP applications and another cost-effective solution for general-purpose use.    | DynamoDB is known for high-performance as it can cope with more than 10 trillion requests within a single day with peaks greater than 20 million requests per second.    |
|    That varies with database engine       |   It provides 256 tables per unit       |
|    Amazon RDS will update databases with the latest patches. We can exert optional control over when and if our database instance is patched.           |   No maintenance since DynamoDB is serverless.          |
|   A monthly charge for each database instance that is being launched. Option to reserve a DB instance for a One or three year term and receive discounts in pricing, compared to On-Demand instance pricing.        |  Charges for reading, writing, and storing data in our DynamoDb tables, along with any optional features we choose to enable. There are specific billing options for each of DynamoDB’s capacity modes.          |
|  Amazon RDS Multi-AZ deployments synchronously replicates our data to a standby instance in a different Availability Zone.   Amazon RDS will automatically replace the compute instance powering our deployment in the event of a hardware failure.      |  DynamoDB global tables replicate our data automatically across 3 Availability Zones of our choice of AWS Regions and automatically scale capacity to accommodate our workloads             |
