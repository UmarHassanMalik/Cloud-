
<h3> Use Case of Deploying a Web App on AWS (JS, PHP (Laravel), MySQL based Web App) </h3>
  
  
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
    
    
    
    
    
    ![image](https://user-images.githubusercontent.com/58930229/199098310-f8ac0589-4895-4071-b6da-20a43485cdf3.png)
