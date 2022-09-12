
<h2> EBS VS Instance Store </h2>


<h3> Instance Store (EC2) </h3> 

Elastic Compute Cloud comes with a direct block storage feature called as instance store. We can play with and store our data for testing purposes/ short time temporary usage within EC2 (instance store). The reason is; This data storage is not persistent. So if the instance restarts, fails, terminates or the hard failure occurs the data stored will be lost. 


<h3> Elastic Block Storage </h3>
EBS provides more traditional file system capabilities. EBS storage is organized into volumes and once an EBS volume is attached to a server it is treated like a local disk drive. The data on EBS volumes can continue to exist after the virtual server it is attached to is shut down. It should be noted that EC2 virtual instances can be configured to delete EBS volumes on shutdown; if you want to save your EBS volume after shutdown be sure to configure your instance accordingly.

EBS volumes are available in either standard or provisioned IOPs versions. The standard version is suitable for applications that need only moderate I/O performance or have intermittent need for high numbers of I/O operations. Provisioned EBS volumes are suited for applications that require consistent levels of I/O throughout, such as databases. With provisioned IOPs you can purchase varying levels of I/O performance depending on your needs.

| EBS     | Instance Store |
| ----------- | ----------- |
|        Persistant Data Storage     |    Non Persistant Data Storage        |  
| Creates replicas in its availability zone |   No replication of data  |
| Upgrade/ Modify the volume type change in demand    |     HDD / SSD  | 
| Snapshot for disaster recovery, data migration & backup support |  No such feature/support | 
| Availability 99.99% |  N/A     |


<h3> Conclusion </h3>
The best practice is to use a storage service like EBS for persistent storage as per our demand. So therefore, it will allow us to store and handle the data for a long period of time. Amazon EBS, the DeleteOnTermination attribute for an instance's root volume is set to true by default. If this attribute is not changed, then the instance's root volume is deleted when the instance terminates. To change the DeleteOnTermination attribute to false.




 

