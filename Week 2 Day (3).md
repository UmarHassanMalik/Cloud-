<h2> Different Ways to Interact with AWS services </h2>

There are following different ways to interact with AWS services.

- AWS Console. 
- AWS CLI .
- AWS SDKs .
- CloudFormation.

AWS Console: 

The AWS console is a web based GUI that provides the ability to interact with the services available within AWS. For example, I could use the console to launch an EC2 instance (i.e. a virtual machine), view information about that instance such as the IP address that has been assigned to that instance and then terminate that instance once I am finished with it.

From here, we can search for the service that we are interested in, as well as see the recently used services (in my example, I have been using EC2, VPC and IAM). One other useful feature of the AWS console is the ability to pin commonly used services to the menu bar at the top of the screen. To do this, click on the pin button in the menu bar - we can see from the above screenshot that I have pinned EC2, S3, CloudFormation and EKS to my menu bar.

We can also set the console to the AWS region that we are working in. In my screenshot, we can see at the top right of the screen that I am working in the London (eu-west-2) region. Note that some AWS services (such as IAM) are not region specific, therefore we will see ‘Global’ in the top right of the menu bar when working with these services.

![image](https://user-images.githubusercontent.com/58930229/189300495-be453fe2-d974-4566-8889-b0703bd00036.png)

AWS CLI:

The AWS console is a great way to get started with AWS and get up to speed with the services available, but once we start to get more familiar with the platform, we’re likely to find the console a bit limiting in terms of speed and repeatability. One of the more advanced ways in which we can interact with AWS is using the AWS CLI.

The AWS CLI allows us to manage our AWS environment using a terminal rather than a graphical interface. This is not only quicker than clicking around a GUI, but it also means that we can perform a level of automation by scripting CLI commands. For example, we could create a script that contains all the commands necessary to create an EC2 instance, or create a new S3 bucket.


![image](https://user-images.githubusercontent.com/58930229/189301749-d529838f-cdb3-4564-9429-b17d0158f322.png)




