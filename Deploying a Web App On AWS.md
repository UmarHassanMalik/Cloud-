
<h3> Use Case of Deploying a Web App on AWS </h3>
  
  
 <h3> Application Introduction & Features <h3>
  
- Lawyer hiring application is an online web application which will be accessible to 
everyone that will aid client to hire a lawyer online. 
  
- The aim of this project is to make lawyer hiring process online, simple, fair, accessible to everyone and easy to manage client documents.
  
- Lawyer and client will discuss their case in case message board. They can share documents and communicate through voice and text chat. 
  
<h3> Brief Summary </h3>
  
  A person can search lawyer on the basis of his location (nearby), lawyer type, city 
wise, He can hire the lawyer from remote location through this web application. 
Application will provide the details of lawyers registered on the web application. 
Application will provide platform (Case Message Board) to exchange documents between 
lawyer and client online. System will provide some basic knowledge of hiring lawyer and 
law system of Pakistan to clients. Client can see the details about lawyers provided by 
lawyers. (e.g., area of expertise, courts, cities). All the exchanges between lawyer and client 
will be monitored by admin and can settle any misunderstanding between client and 
lawyer.
  
 <h3> Application Stack/Technologies <h3>
  
  
  <h3> Environment </h3> 
    
 <b>  Using AWS Elastic Beanstalk </b>
 
By Using AWS Elastic Beanstalk. It provisions and manages the underlying infrastructure such as AWS EC2 instances and their components which are web servers, operating system, frameworks and languages for us. 

 <b>Why are we Using Amazon RDS </b>
 
As we are using MySQL so we have stored relational and structured data stored in our database. So Amazon RDS is best suited for the apps which have structured/relational data is being stored. 
  

<b> AWS Autoscaling in EBS </b>

AWS Auto Scaling monitors our applications and automatically adjusts capacity to maintain steady, predictable performance at the lowest possible cost. Using AWS Auto Scaling, it’s easy to setup application scaling for multiple resources across multiple services in minutes. 

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
