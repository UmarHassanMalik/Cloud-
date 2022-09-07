

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
| ----------- | ----------- |   ----------- | 
|US East (Northern Virginia) |    us-east-1       |    6 | 
|US East (Ohio)  |  us-east-2    |  	3 |


<h3> Availability Zones ID </h3>
To ensure that resources are distributed across the Availability Zones for a Region, we independently map Availability Zones to codes for each AWS account. For example, the Availability Zone us-east-1a for your AWS account might not be the same physical location as us-east-1a for another AWS account.

To coordinate Availability Zones across accounts, you must use the AZ ID, which is a unique and consistent identifier for an Availability Zone. For example, use1-az1 is an AZ ID for the us-east-1 Region and it has the same physical location in every AWS account. You can view the AZ IDs for your account to determine the physical location of your resources relative to the resources in another account. For example, if you share a subnet in the Availability Zone with the AZ ID use1-az2 with another account, this subnet is available to that account in the Availability Zone whose AZ ID is also use1-az2.

<h3> Example </h3>

| Parent Region      | Zone Name |  	Location (metro area) |
| ----------- | ----------- |   ----------- | 
|US East (N. Virginia) |   us-east-1-atl-1a      |  	Atlanta| 
|US East (N. Virginia)  | us-east-1-bos-1a  |  Boston |
      

<h3> AWS Zones </h3>
An availability zone is a standalone data center or set of data centers within a Region. Each availability zone operates independently, so a failure in one won't affect others. In disaster recovery plans, enterprises use multiple availability zones to increase redundancy and reliability.
 
 <h3>  Wavelength Zones </h3>

AWS Wavelength enables developers to build applications that deliver ultra-low latencies to mobile devices and end users. Wavelength deploys standard AWS compute and storage services to the edge of telecommunication carriers' 5G networks. Developers can extend a virtual private cloud (VPC) to one or more Wavelength Zones, and then use AWS resources like Amazon EC2 instances to run applications that require ultra-low latency and a connection to AWS services in the Region.

 <h3> How to Identify/find Wavelength Zone? </h3>
 The code for a Wavelength Zone is its Region code followed by an identifier that indicates the physical location. For example, us-east-1-wl1-bos-wlz-1 in Boston.
 
<h3> Edge Locations </h3>
Edge locations are AWS data centers designed to deliver services with the lowest latency possible. Amazon has dozens of these data centers spread across the world. They're closer to users than Regions or Availability Zones, often in major cities, so responses can be fast and snappy.
 
 <h3> Edge Location List </h3>
 
 <b> North America </b>
 
Edge locations: Washington, DC (11); Chicago, IL (19); New York, NY (10); Atlanta, GA (10); Los Angeles, CA (9); Miami, FL (11); Dallas-Fort Worth, TX (11); Houston, TX (4); San Francisco, CA (6); Boston, MA (5); Denver, CO (3); Portland, OR (2); Seattle, WA (6); Toronto, Canada (3); Minneapolis, MN (4); Phoenix, AZ (2); Querétaro, Mexico (2); Montréal, Canada (2); Philadelphia, PA (1); Salt Lake City, UT (1); Vancouver, Canada (1); Nashville, TN (2); Detroit, MI (2)

<b> Europe </b>

Edge locations: Frankfurt am Main, Germany (17); London, UK (24); Paris, France (9); Milan, Italy (9); Rome, Italy (6); Berlin, Germany (5); Madrid, Spain (4); Marseille, France (4); Amsterdam, The Netherlands (4); Düsseldorf, Germany (3); Hamburg, Germany (3); Manchester, UK (5); Munich, Germany (4); Vienna, Austria (3); Stockholm, Sweden (3); Copenhagen, Denmark (2); Dublin, Ireland (2); Helsinki, Finland (3); Athens, Greece (1); Brussels, Belgium (1); Budapest, Hungary (1); Lisbon, Portugal (1); Oslo, Norway (2); Bucharest, Romania (1); Palermo, Italy (1); Prague, Czech (1); Sofia, Bulgaria (1); Warsaw, Poland (1); Zagreb, Croatia (1); Zurich, Switzerland (1)


<b> Asia </b>

Edge locations: Tokyo, Japan (20); New Delhi, India (7); Seoul, Korea (6); Chennai, India (7); Singapore (6); Osaka, Japan (7); Mumbai, India (10); Bangalore, India (4); Hyderabad, India (3); Taipei, Taiwan (3); Bangkok, Thailand (10); Kolkata, India (2); Jakarta, Indonesia (2); Kuala Lumpur, Malaysia (2); Manila, Philippines (1)


 <b> Australia & New Zealand </b>
 
Edge locations: Sydney, Australia (6); Auckland, New Zealand (3); Melbourne, Australia (2); Perth, Australia (1)

<b> South America </b>

Edge locations: São Paulo, Brazil (7); Rio De Janeiro, Brazil (2); Bogota, Colombia (2); Buenos Aires, Argentina (2); Santiago, Chile (1)


<b> Middle East </b>

Edge location: Tel Aviv, Israel (2); Manama, Bahrain (2); Dubai, UAE (1); Fujairah, UAE (1)

<b> Africa </b>

Edge locations: Cape Town, South Africa (1); Johannesburg, South Africa (1); Nairobi, Kenya (1)

<b> China </b>

Edge locations: Shanghai, China (1); Shenzhen, China (1); Zhongwei, China (1); Beijing, China (1); Hong Kong, China (4)


<h3> Characteristics of Edge Locations </h3>

- Host Amazon EC2 instances are closer to users

- Help lower latency and improve performance for users.

- Cache frequently changing data without reaching the origin server

- Refresh data changes daily. 
 
