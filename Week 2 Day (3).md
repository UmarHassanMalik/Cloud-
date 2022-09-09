<h2> Different Ways to Interact with AWS services </h2>

There are following different ways to interact with AWS services.

- AWS Console. 
- AWS CLI .
- AWS SDKs .
- CloudFormation.

<h3> AWS Console: </h3> 

The AWS console is a web based GUI that provides the ability to interact with the services available within AWS. For example, I could use the console to launch an EC2 instance (i.e. a virtual machine), view information about that instance such as the IP address that has been assigned to that instance and then terminate that instance once I am finished with it.

From here, we can search for the service that we are interested in, as well as see the recently used services (in my example, I have been using EC2, VPC and IAM). One other useful feature of the AWS console is the ability to pin commonly used services to the menu bar at the top of the screen. To do this, click on the pin button in the menu bar - we can see from the above screenshot that I have pinned EC2, S3, CloudFormation and EKS to my menu bar.

We can also set the console to the AWS region that we are working in. In my screenshot, we can see at the top right of the screen that I am working in the London (eu-west-2) region. Note that some AWS services (such as IAM) are not region specific, therefore we will see ‘Global’ in the top right of the menu bar when working with these services.

![image](https://user-images.githubusercontent.com/58930229/189300495-be453fe2-d974-4566-8889-b0703bd00036.png)

<h3> AWS CLI: </h3>

The AWS console is a great way to get started with AWS and get up to speed with the services available, but once we start to get more familiar with the platform, we’re likely to find the console a bit limiting in terms of speed and repeatability. One of the more advanced ways in which we can interact with AWS is using the AWS CLI.

The AWS CLI allows us to manage our AWS environment using a terminal rather than a graphical interface. This is not only quicker than clicking around a GUI, but it also means that we can perform a level of automation by scripting CLI commands. For example, we could create a script that contains all the commands necessary to create an EC2 instance, or create a new S3 bucket.


![image](https://user-images.githubusercontent.com/58930229/189301749-d529838f-cdb3-4564-9429-b17d0158f322.png)


All AWS CLI commands start with the aws keyword. we then generally specify the service we want to interact with, such as ec2, s3, rds and so on.

<h3> Examples </h3>

 To open the list of all S3 bucket instances I can use this command
- aws s3 ls

If I want to see the list of all EC2 instances in my account I can use the following command.
- aws ec2 describe-instances

To run a new instance I can use this command.
- aws ec2 run-instances --count 1 --image-id ami-a36f8dc4 --instance-type t2.micro --key-name MainKey


<h3> AWS SDKs </h3>
The real power of AWS lies in its programmability and ability to be automated. AWS provides a number of Software Development Kits (SDKs) that allows us to interact with the platform through code that we have developed ourself. SDKs are available for all the major programming languages, including Java, Python, Node.JS and Go.

We use this approach if we want to integrate AWS services into the applications that we are writing  for example, our code could write information to a database service within AWS, such as RDS or DynamoDB.


<h3> Cloud Formation </h3>

CloudFormation is a tool used to define infrastructure as code. The approaches we have discussed above all have their own pros and cons, but if we simply want to define the desired infrastructure within AWS, quickly and in a repeatable manner, CloudFormation is likely to be our best bet.

The idea behind CloudFormation is that we can model the AWS services we want to provision, such as EC2 instances, S3 buckets and so on, in a single script using a descriptive language. We can define this script locally and then when we are ready, upload it to AWS, at which point the platform will read the script and then provision the services and features that we have defined in the CloudFormatiom script.

One of the big advantages of using CloudFormation is that because our infrastructure is defined as code, We can treat our scripts the way we would treat any other code - checking it in to code repositories, using version control and so on. CloudFormation is also extremely flexible and powerful, allowing us to use many advanced features such as rolling back the ‘stack’ if there are issues, as well as the ability to detect ‘drift’ from the stack (i.e. if someone has come and manually changed something after the script has run)






