<h2> Amazon S3 </h2>

Amazon Simple Storage Service (Amazon S3) is a scalable, high-speed, web-based cloud storage service. The service is designed for online backup and archiving of data and applications on Amazon Web Services (AWS). Amazon S3 was designed with a minimal feature set and created to make web-scale computing easier for developers.

<h3>  Features of S3 </h3>

- Storage Management
 
  Amazon S3 has storage management features that we can use to manage costs, meet regulatory requirements, reduce latency, and save multiple distinct copies of our data for   compliance requirements.


- Access Management
 
  Amazon S3 provides features for auditing and managing access to our buckets and objects. By default, S3 buckets and the objects in them are private. We have access only to   the S3 resources that we create. To grant granular resource permissions that support our specific use case or to audit the permissions of our Amazon S3 resources, we can   use the following features.

- Data Processing

  To transform data and trigger workflows to automate a variety of other processing activities at scale, we can use the following features.
   
- Storing Logging & Monitoring (Both Automated and Manual Monitoring Tools)

  Amazon S3 provides logging and monitoring tools that we can use to monitor and control how our Amazon S3 resources are being used
  
- Analytics and insights

  Amazon S3 offers features to help us gain visibility into our storage usage, which empowers us to better understand, analyze, and optimize our storage at scale.
  
- Analytics and insights

  Amazon S3 offers features to help us gain visibility into our storage usage, which empowers us to better understand, analyze, and optimize our storage at scale.

- Strong consistency

  Amazon S3 provides strong read-after-write consistency for PUT and DELETE requests of objects in our Amazon S3 bucket in all AWS Regions. This behavior applies to both     writes of new objects as well as PUT requests that overwrite existing objects and DELETE requests. In addition, read operations on Amazon S3 Select, Amazon S3 access       control lists (ACLs), Amazon S3 Object Tags, and object metadata (for example, the HEAD object) are strongly consistent.
  
<h3>  S3 Working </h3>
Amazon S3 is an object storage service that stores data as objects within buckets. An object is a file and any metadata that describes the file. A bucket is a container for objects.

To store our data in Amazon S3, ywe first create a bucket and specify a bucket name and AWS Region. After that we upload our data to that bucket as objects in Amazon S3. Each object has a key (or key name), which is the unique identifier for the object within the bucket.

S3 provides features that we can configure to support our specific use case. e.g we can use S3 Versioning to keep multiple versions of an object in the same bucket, which allows us to restore objects that are accidentally deleted or overwritten.

Buckets and the objects in them are private and can be accessed only if we explicitly grant access permissions. We can use bucket policies, AWS Identity and Access Management (IAM) policies, access control lists (ACLs), and S3 Access Points to manage access.
  
