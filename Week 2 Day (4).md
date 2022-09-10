<h3> AWS CloudFormation </h3> 
AWS CloudFormation is a service that helps us model and set up our AWS resources so that we can spend less time managing those resources and more time focusing on our applications that run in AWS. We create a template that describes all the AWS resources that we want (like Amazon EC2 instances or Amazon RDS DB instances), and CloudFormation takes care of provisioning and configuring those resources for us. We don't need to individually create and configure AWS resources and figure out what's dependent on what; CloudFormation handles that.

<h3> Infrastructure as a Code/ Infrastructure Management </h3>
For a scalable web applications that also includes a backend database, we might use an Auto Scaling group, an Elastic Load Balancing load balancer, and an Amazon Relational Database Service database instance. We might use each individual service to provision these resources and after we create the resources, we would have to configure them to work together. All these tasks can add complexity and time before we even get our application up and running.


- On AWS CloudFormation we have two Options either we can use YAML or JSON format to write/upload our code and create resources. We can use existing templates and make changes as we needed. We can handle the AWS services logically through CloudFormation.

We can create a CloudFormation template or modify an existing one. A template describes all our resources and their properties. When we use that template to create a CloudFormation stack, CloudFormation provisions the Auto Scaling group, load balancer, and database for us. After the stack has been successfully created, our AWS resources are up and running. We can delete the stack just as easily, which deletes all the resources in the stack. By using CloudFormation, We easily manage a collection of resources as a single unit.

<h3> Replication Of Infrastructure </h3>

If our application requires additional availability, we might replicate it in multiple regions so that if one region becomes unavailable, our users can still use our application in other regions. The challenge in replicating the application is that it also requires us to replicate our resources. Not only do we need to record all the resources that our application requires, but we must also provision and configure those resources in each region.

Reuse our CloudFormation template to create our resources in a consistent and repeatable manner. To reuse our template, describe our resources once and then provision the same resources over and over in multiple regions

<h3> AWS Elastic Beanstalk </h3>

Elastic Beanstalk, help us quickly deploy and manage applications in the AWS Cloud without having to learn about the infrastructure that runs those applications. Elastic Beanstalk reduces management complexity without restricting choice or control. We simply upload our application, and Elastic Beanstalk automatically handles the details of capacity provisioning, load balancing, scaling, and application health monitoring.

Elastic Beanstalk supports applications developed in Go, Java, .NET, Node.js, PHP, Python, and Ruby. When we deploy our application, Elastic Beanstalk builds the selected supported platform version and provisions one or more AWS resources, such as Amazon EC2 instances, to run our application.

We can interact with Elastic Beanstalk by using the Elastic Beanstalk console, the AWS Command Line Interface (AWS CLI), or eb, a high-level CLI designed specifically for Elastic Beanstalk.

We can also perform most deployment tasks, such as changing the size of our fleet of Amazon EC2 instances or monitoring our application, directly from the Elastic Beanstalk web interface (console).

To use Elastic Beanstalk, we create an application, upload an application version in the form of an application source bundle (for example, a Java .war file) to Elastic Beanstalk, and then provide some information about the application. Elastic Beanstalk automatically launches an environment and creates and configures the AWS resources needed to run our code. After our environment is launched, we can then manage our environment and deploy new application versions. The following diagram illustrates the workflow of Elastic Beanstalk.

<h3> Retreive Information of Deployed Application </h3>
After we create and deploy our application, information about the application—including metrics, events, and environment status—is available through the Elastic Beanstalk console, APIs, or Command Line Interfaces, including the unified AWS CLI.

