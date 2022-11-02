
<h3> Use Case of Deploying a Web App on AWS </h3>
  
  
 <h3> Application Introduction </h3>
  
- Lawyer hiring application is an online dynamic web application which will be accessible to 
everyone that will aid client to hire a lawyer online. 
  
- The aim of this project is to make lawyer hiring process online, simple, fair, accessible to everyone and easy to manage client documents.
  
- Lawyer and client will discuss their case in case message board. They can share documents and communicate through voice and text chat. 
  
<h3> Brief Summary </h3>
  
Client and Lawyer can create account through this system. Client can access lawyer 
profile through two different approaches. 1 Searching 2 by posting his legal case. Client 
can search lawyer by city, finding nearest by, category and so on. Client can send lawyer 
his legal case. Client can read information about laws in Pakistan. Client can see lawyer 
profile on this system. If legal case is accepted by lawyer, client will be able to share 
documents, voice call, and text message to his lawyer. Lawyer can also exchange 
documents with client. Lawyer can read legal post of clients. Lawyer and client can login 
and logout their accounts. Lawyer and client can manage their profile. They can edit their 
profile information (name, password etc.). Application will provide basic information 
about laws in Pakistan. Client will have job table showing lawyer status, title, action, date 
of legal issue post.
  
 <h3> Application Stack/Technologies <h3>
  
- PHP/Laravel.
- JavaScript (HTML,CSS).
- MySQL.  
  
  
  
  <h3>Services Use cases scnerio in our Project & Environment </h3> 
    
 <b>  Using AWS Elastic Beanstalk </b>
 
In this project LHS we are using AWS Elastic Beanstalk. It provisions and manages the underlying infrastructure such as AWS EC2 instances and their components which are web servers, operating system, frameworks and languages for us. First of all on an initial request by the user (In this case we have "Lawyer and Client") to the web server. The users will be directed to one the EC2 instance will be decided by the load balancer based on resources accomodaton, thresholds, region as configured by us etc.

 <b>Why are we Using Amazon RDS </b>
 
As we are using MySQL Our data is relational and structured stored in our database. So Amazon RDS is best suited for the applications which are using structured and relational databases.
  
In this project it will help us in: 

- Making our Application high available with throughput, and storage scalability. Take advantage of flexible pay-per-use pricing to suit various application usage patterns.
- Choosing Amazon RDS, instead of worrying about self-managing our databases, which can be time consuming, complex, and expensive.  
- We can even opt out Amazon aurora with MySQL compatiability as it has numerous advantages over traditional databases and services with high availability scalabilty,  Multi-AZ availability backed by a 99.99% uptime SLA and global replication with cross-Region, disaster recovery, fully managed, migration options & less cost as compared to traditional databases.

  <h3> S3 Buckets </h3>
  
As mentioned above clients and lawyers will exchange documents, photos/videos, audios on CMB (Case Message Board), this data can be stored in S3 bucket.
We can fetch and store the exclusive data of the user (Clients/Lawyers) to S3 buckets without compromising their privacy.    
  
<b> AWS Autoscaling in EBS </b>

As our clients and lawyers will grow or shrink from time to time. So we have to be careful regarding the resources and usage. Here, AWS Auto Scaling monitors our applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. 

Inshort it will help us in:

- Setup scaling quickly.
- Make smart scaling decisions.
- Automatically maintain performance.
- Pay only for what you need.


AWS Auto Scaling makes scaling simple with recommendations that will allow us to optimize performance, costs, or balance between them. If we're already using Amazon EC2 Auto Scaling to dynamically scale our Amazon EC2 instances which can be seen in the diagram. 

<b> Amazon SQS </b>

Amazon Simple Queue Service (SQS) lets us send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.

It will help us in: 

- Increasing application reliability and scale.
- Decoupling microservices and process event-driven applications.
- Ensuring the work is completed cost-effectively and on time.
- Maintaining message ordering with deduplication
    
    
    
    
    
<img width="1465" alt="Drawing (1)" src="https://user-images.githubusercontent.com/58930229/199448638-74dbb2ba-19f6-4a04-82d6-695d38220f2e.png">
