<h1> Amazon EC2 <h1>
  
  <h3> Introduction</h3>
  Amazon EC2 or Elastic compute cloud allows user to rent virtual computer on which they can run their own applications. EC2 provides scalable deployment of an application through a service (Auto scaling); in which a user can boot a Amazon machine image to configure a virtual machine. A user can create as many virtual machines as he needs and paying by a second of active servers.

<h3> Features of EC2</h3>

- Virtual computing environment. 
- Configuration of CPU, memory, storage, and networking capacity for our instances, known as instance types, with diverse configuration options.
- Elastic IP addresses.
- Multiple physical locations for our resources, with different availability timezones and regions.  
- Security; such as firewalls and managing IP addresses ranges, ports and protocols through security groups. Secure login information, with private and public key.  
- Creating our own private network, through virtual private cloud service.  
- Persistant storage options i.e Elastic block storage. 
  
<h3> Amazon Instances Types</h3> 
Amazon provides variety of Instances types which are optimized for difference use cases. Instances types contains diverse combinations and types of CPU, memory , network
capacity with flexibility that gives us mixture of different resources to run our application.

These are following instances types.

<h3> General Purpose</h3> 
 There are different types of series in every instance type for example T4g T3a T2 T3 belongs to "T" series similiarly there are other series like "M" "A" and dedicated Mac series for those who wants to deploy MAC, Iphone applications. Every series offers different features in memory, size, bandwidth, CPU usage, network storage their cost varies as the size   
General purpose instances provide a balance of compute, memory and networking resources, and can be used for a variety of diverse workloads. These instances are ideal for applications that use these resources in equal proportions such as web servers and code repositories.

<h3> Computer Optimized </h3>  
Compute Optimized instances are ideal for compute bound applications that benefit from high performance processors. Instances belonging to this family are well suited for batch processing workloads, media transcoding, high performance web servers, high performance computing (HPC), scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and other compute intensive applications. 

- Computer Optimized contains C and H series. 
  
<h3> Memory Optimized </h3>
Memory optimized instances are designed to deliver fast performance for workloads that process large data sets in memory.  
  
 - Memory Optimized contains R and X series instances.
  
<h3> Accelerated Computing </h3>
Accelerated computing instances use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.
  
- Accelerated computing contains P, G and F series instances.
  
  <h3> Storage Optimized </h3>
Storage optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage. They are optimized to deliver tens of thousands of low-latency, random I/O operations per second (IOPS) to applications.  

- Storage optimized instances contains L and D series instances. 

<h3>Amazon EC2 Autoscaling Groups:</h3>
Amazon EC2 Auto Scaling helps you ensure that you have the correct number of Amazon EC2 instances available to handle the load for your application. You create collections of EC2 instances, called Auto Scaling groups. You can specify the minimum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that your group never goes below this size. You can specify the maximum number of instances in each Auto Scaling group, and Amazon EC2 Auto Scaling ensures that your group never goes above this size  
  
  
  
  
  

  
  
  
  
  
