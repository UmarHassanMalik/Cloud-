
<h2> AWS Migration Strategies </h2> 

In this document I will share 6 AWS migrating strategies. These strategies are implemented by the customers to migrate to the cloud.

These are following 6 Migration strategies.

<h3> Rehosting </h3>

- Most basic ways of migrating to the AWS Cloud is simply to Re-Host something, and this is sometimes called, “Lift and Shift”.
- This approach is great for organizations that need to migrate quickly, for example, data center leases that are about to expire.
- Easier to optimize/re-architect them once they’re already running in the AWS Cloud.

<h3> Re-platform </h3>

- Re-Platform which is sometimes called Lift and Reshape, because you can potentially take advantage of some of the special capabilities of the AWS cloud.
- For example migrating our application to a fully managed platform like AWS elastic beanstalk.
- Deploying MySQL database by using amazon RDS. 

<h3> Re-purchase </h3>

- This involves abandoning the existing software that you have and migrating to a cloud-first application.
- We can transfer our software license from an on-premises server to AWS.
- Or we can completely replacing our current application with SaaS options.

<h3> Re-architect  </h3>

- This is the most advanced application migration strategy.
- We simply redesign our application in a more cloud-native manner.
- In general we create a serverless version of a legacy application.
- for example migrating our on-premises Oracle database to Amazon Aurora PostgreSQL
- We can convert our monolithic application into smaller micro-services and by using the services like Amazon Elastic Kubernetes Service, AWS Lambda, or AWS Fargate

<h3> Retire  </h3>

- After discovering new softwares and applications, we decide that we dont need this application anymore This is just getting rid of them as we’re not going to use them anymore


<h3> Retain  </h3>

- We can decide to keep the application and evaluating them later if needed.
- Examples are Legacy applications that do not have a business justification for migrating to the cloud.
- Unsupported OS and applications.

![image](https://user-images.githubusercontent.com/58930229/191357207-6cb1062a-6e85-4957-ab27-add4f2f56845.png)

<h2> AWS Snow Family </h2>

- AWS Snow Family helps physically transport up to exabytes of data into and out of AWS.
- AWS Snow Family, comprised of AWS Snowcone, AWS Snowball, and AWS Snowmobile, offers a number of physical devices and capacity points, most with built-in computing capabilities.
- Snow Family devices are owned and managed by AWS and integrate with AWS security, monitoring, storage management, and computing capabilities.
- AWS Snow Family helps customers that need to run operations in austere, non-data center environments, and in locations where there’s a lack of consistent network connectivity.

<h3>Features </h3>

<b>Simple management and monitoring <b> 

- AWS OpsHub provides complimentary graphical user interface available to makes it easy to setup and manage Snow devices.
-  It instantly deploys edge computing workloads and migrate data to the cloud.

<b> NFS endpoint </b>
  
- Applications can work with Snow Family devices as an NFS mount point. NFS v3 and v4.1 are supported. 
- Snow devices with your existing on-premises servers and file-based applications  
  
<b> On-board computing </b>

- Computing resources to collect and process data at the edge   
- Amazon EC2 instances with processing and storage available to support our applications.
  
<b> Encryption </b>

- Data moved to AWS Snow Family devices is automatically encrypted with 256-bit encryption keys that are managed by the AWS Key Management Service.
- Data stays secure during transit
  
<b> Anti-tamper & Tamper-evident </b>

- Trusted Platform Module provides a hardware root of trust. 
- Each device is inspected after each use to ensure the integrity of the device.
- Preserve the confidentiality of our data.  
  
<b> End-to-end tracking </b>

- Each device uses an E-Ink shipping label for easy tracking and automatic label updates for return shipping using Amazon Simple Notification Service through text messages and console.  
  
<b>Secure erasure </b>

- Once the data migration job is complete and verified, AWS performs a software erasure of the device.
  
  <h2> AWS Snow Family service models </h2>
  
  <h3> AWS Snowcone </h3>
  
- AWS Snowcone is portable, rugged, and secure that provides edge computing and data transfer devices.
- Snowcone can be used to collect, process, and move data to AWS, either offline by shipping the device, or online with AWS DataSync.
- Snowcone devices are small and weigh 4.5 lbs. (2.1 kg), so you can carry one in a backpack or fit it in tight spaces for IoT, vehicular, or even drone use cases.
- AWS Snowcone stores data securely in edge locations, and can run edge computing workloads that use AWS IoT Greengrass or EC2 instances.
  
  <h3> AWS Snowball </h3>
  
- AWS Snowball is available as a Compute Optimized device or a Storage Optimized device.
- All devices are suited for extreme conditions, tamper proof, and highly secure.  
- It is compute optimied and storage optimized.   
  
  <h3> AWS Snowmobile </h3>
  
- This is an Exabyte-scale data migration device used to move extremely large amounts of data to AWS.
- AWS Snowmobile moves up to 100 PB of data in a 45-foot long ruggedized shipping container. 
- Ideal for multi-petabyte or Exabyte-scale digital media migrations and data center shutdowns.
  

<h3> Feature Comparison Matrix </h3>  
  
  
 ![image](https://user-images.githubusercontent.com/58930229/191364570-7e918ec3-5351-4729-a06b-dfcd281e2bb0.png)

  
  
  
