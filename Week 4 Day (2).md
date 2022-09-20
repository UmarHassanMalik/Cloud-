
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
