AWS Regions, Availability Zones, Edge Locations(About, List, characteristics)

<h3>  AWS Regions </h3>

 A region has many zones.An AWS Region is a cluster of data centers in a specific geographic area, such as the Northeastern United States or Western Europe. AWS Regions are large and widely dispersed into separate geographic locations.
 It is a best practice to choose a region that is geographically close to users. This will help us to avoid latency

- Each Region is a separate geographic area.
- Availability Zones are multiple, isolated locations within each Region.
- AWS Outposts brings native AWS services, infrastructure, and operating models to virtually any data center, co-location space, or on-premises facility.
- Wavelength Zones allow developers to build applications that deliver ultra-low latencies to 5G devices and end users. Wavelength deploys standard AWS compute and storage  services to the edge of telecommunication carriers' 5G networks.
- Local Zones provide us the ability to place resources, such as compute and storage, in multiple locations closer to the end users.

<h3> Example </h3>

| Region      | Region Code |  Total Availability Zones |
| ----------- | ----------- |  
|US East (Northern Virginia) |    us-east-1       |    6 | 
|US East (Ohio)  |  us-east-2    |  	3 |
      

<h3> AWS Zones </h3>
An AZ is a standalone data center or set of data centers within a Region. Each AZ operates independently, so a failure in one won't affect others. In disaster recovery plans, enterprises use multiple availability zones to increase redundancy and reliability.

