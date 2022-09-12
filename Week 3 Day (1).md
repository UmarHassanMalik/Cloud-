
<h2> EBS VS EC2 </h2>


<h3> EC2 </h3> 

Elastic Compute Cloud comes with a direct block storage feature called as instance store. We can play with and store our data for testing purposes/ short time temporary usage within EC2 (instance store). The reason is; This data storage is not persistent. So if the instance fails, terminates or the hard failure occurs the data stored will be lost. 


<h3> Elastic Block Storage </h3>
EBS provides more traditional file system capabilities. EBS storage is organized into volumes and once an EBS volume is attached to a server it is treated like a local disk drive. The data on EBS volumes can continue to exist after the virtual server it is attached to is shut down. It should be noted that EC2 virtual instances can be configured to delete EBS volumes on shutdown; if you want to save your EBS volume after shutdown be sure to configure your instance accordingly.

EBS volumes are available in either standard or provisioned IOPs versions. The standard version is suitable for applications that need only moderate I/O performance or have intermittent need for high numbers of I/O operations. Provisioned EBS volumes are suited for applications that require consistent levels of I/O throughout, such as databases. With provisioned IOPs you can purchase varying levels of I/O performance depending on your needs.

<h3> Conclusion </h3>
Amazon EBS, the DeleteOnTermination attribute for an instance's root volume is set to true by default. If this attribute is not changed, then the instance's root volume is deleted when the instance terminates. To change the DeleteOnTermination attribute to false




 

