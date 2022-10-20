
<h2> SAAS </h2>

<h3> Understanding SAAS </h3> 

- SaaS can be used to define a service, business or delivery model. The problem is what it means to be SaaS is not unviversally understood. 
- There is some confusion that what it means to be SaaS but on the other hand there is some concensus on some core fundamentals of SAAS. There are variations like how different people see SaaS.
- The objective is to provide a collection of basic insights that provide customers with a clearer view of the options they should consider as they look to adopt a SaaS delivery model.


<h3> SAAS Business Model </h3>
 
- Running a business in a software as a service (SaaS) model based on goals and scope, can be difficult to define. The terminology and patterns that are used to distinguish SaaS vary based on their origin.
- Adoption of this delivery model is driven by some set of objectives.
- SAAS is about putting in place a mindset and model that targets a specific set of business objectives.

<h3> Key Business Objectives to Adopt a SAAS delivery Model </h3>

[![tvHuS4.md.png](https://iili.io/tvHuS4.md.png)](https://freeimage.host/i/tvHuS4)


<b> Agility </b>

- Successful startups companies are builtin to continually adapt to the market, customer, and competitive dynamics.
- Great companies always embrace themself with new trends, customers demands, pricing models.

<b> Innovation </b>

 - SaaS is about putting in place the foundational elements that allow us to innovate.
 - We focus and respond to customer needs in our SaaS model. which can vary from time to time.
 
<b> Frictionless onboarding </b> 

- This applies universally to business to business (B2B) and business-to-customer (B2C) customers.
- It doesnot matter which segment or type of customer we support, we still need to be focused on time to value for our customers. 
- The shift to a service-centric model requires the SaaS business to focus on all aspects of the customer experience, with specific emphasis on the repeatability and efficiency of the overall onboarding lifecycle
 
<b> Growth  </b> 

- SaaS companies are more focused to their growth. Inshort they adopt growth centric strategy.
- Aligning all the moving parts of the organization around agility and efficiency gives SaaS organizations the ability to target a growth model.
- The business will also view these as foundational to the long-term growth and success of our SaaS offering.

 
<b> Operational efficiency </b> 

- SaaS companies rely on operational efficiency to promote scale and agility.
- This means putting into place a culture and tooling that is focused on creating an operational footprint that promotes frequent and rapid release of new features.
- It also means having a single, unified experience that allows us to manage, operate, and deploy all customer environments collectively. 

<b> Market Response </b>

- SaaS relies on its agility to give the organization the ability to react and respond to market dynamics in near real-time.


<h3> SaaS Delivery Model Key Objectives Summary </h3> 

SaaS is a business and software delivery model that gives organizations the ability to offer their solutions in a low-friction, service-centric model that maximizes value for customers and providers. It relies on agility and operational efficiency as pillars of a business strategy that promotes growth, reach, and innovation.

<h3>SaaS A Service not a Product </h3>

In a service-centric model, we think more about how customers are onboarded to our service, how quickly they achieve value, and how rapidly we can introduce features that address customer needs. Details associated with how our service is built, operated, and managed are out of our customer’s view.

<b> Example </b> 

Suppose we’re in a restaurant, we certainly care about the food, but we also care about the service. How quickly does our server come to our table, how often do they refill our water, how fast does the food come—these are all measures of the service experience. This is the same mindset and value system that should shape how we think about building a SaaS service.

<h3> SaaS Impact to Our Business </h3>

This as-a-service model should have a heavy influence on how we build our teams and our service. Our backlog of work will now put these experience attributes on equal or higher footing than features and functions. The business will also view these as foundational to the long-term growth and success of our SaaS offering.

<h3> SaaS Authentication </h3>

SaaS adds new considerations to our application’s identity model. As each user is authenticated, they must be connected to a specific tenant context. This tenant context provides essential information about our tenant that is used throughout our SaaS environment. Example tokens, ID. It is used for user and tenant identity. Token from this identity process flows into the microservices of our application and create tenant aware logs, record metrics, meter billing, enforce tenant isolation etc.

  

<h3> Building SAAS Multi-tenant Solutions on AWS </h3>

Multi-tenancy is used to describe how resources are shared by tenants to promote agility and cost efficiency.

Suppose, for example if we have a microservice or an Amazon Elastic Compute Cloud (Amazon EC2) instance that is consumed by multiple tenants of our SaaS system. This service would be viewed as running in a multi-tenant model, because tenants are sharing use of the infrastructure that runs this service.

We can manage tenents (profiles) to distribute and partition tenant data, applying security policies in order to prevent cross-tenant access, SaaS implementation, highlighting the tradeoffs and considerations that can shape our approach to SaaS architecture.

![image](https://user-images.githubusercontent.com/58930229/196815516-f042f753-3abc-4b80-a42e-00d17b88a991.png)

<b> Tenancy Isolation </b>

- In **Silo Model** tenants sharing a few resources, with a boon to data security and a draw on efficiency. Likewise, the pool model is a more efficient use of resources at the expense of keeping tenants strictly separated.
- The **Bridge Model**, on the other hand, is a hybrid of the two.
- The **Pool Model** is much more common than the silo sees users sharing some or all infrastructure resources.

![image](https://user-images.githubusercontent.com/58930229/196816831-6167291a-3e2f-4485-b857-5ce313e1123f.png)

<h3> Conclusion </h3>

SaaS emphasis on the creating an environment that lets us manage and operate all of our SaaS tenants through a unified experience. This connects to the core idea that SaaS is first and foremost a business model. The SaaS architecture we build is meant to promote these foundational business goals.



<h2> PAAS </h2>

<h3> Understanding PaaS </h3>

PaaS, or Platform as a Service, leverages an internet-based cloud computing environment to provide complete application lifecycle support, from development to testing, deployment to management, and updating.

Platform as a Service frees organizations from the complexity and cost of acquiring and maintaining a range of tools and resources, such as AIM (Application Infrastructure Middleware), software licenses, and container orchestrators.

<b> Example </b>
Kubernetes, Heroku, OpenShift, Firebase etc.

<h3> Paas In General </h3>

Platform as a Service refers to a computing service in the cloud, where third-party cloud service providers employ virtualization technology to deliver a fully loaded, high-performing development platform to application developers over an Internet connection.

PaaS in cloud computing features a virtual infrastructure that includes servers, networking equipment, storage, and database. In addition to hardware tools, PaaS also incorporates a software layer with resources that enhance development capabilities and usability.

<h3> PaaS Architecture </h3>

Application developers can test, collaborate, design, develop, and roll out apps from anywhere, using the online GUI within the PaaS architecture. The GUI, or Graphic User Interface, also allows teams to streamline operations and work on multiple development projects simultaneously.

- GUI, that simplifies workload monitoring throughout the entire lifecycle of applications.
- Various software tools that are used for development, management, and deployment of applications.
- Cloud infrastructure, consist of virtual machines, firewalls, networking, storage, and the operating system.


<h3> Working of PaaS </h3>

PaaS  is ideally suited for software-related product development. It is purely a development-oriented cloud computing model that cannot accommodate non-development processes, unlike other cloud solutions such as IaaS and SaaS, which serve various purposes.

PaaS delivers a development platform with tools and resources that teams can access on the go simply by logging into the enterprise PaaS system from any Internet-enabled device. The simplicity and flexibility of the PaaS architecture give organizations more freedom to focus on business-critical issues.

 



<h2> IAAS </h2>

Infrastructure as a service is a type of cloud computing service that offers essential compute, storage, and networking resources on demand, on a pay-as-you-go basis.


<h3> Architecture </h3> 
 
Application developers can test, collaborate, design, develop, and roll out apps from anywhere, using the online GUI within the PaaS architecture. The GUI, or Graphic User Interface, also allows teams to streamline operations and work on multiple development projects simultaneously.
 
IaaS architecture aims to achieve optimal levels of efficiency, in the delivery of computing services to end users. This requires an architectural design that provides a highly available pool of cloud based IT resources and which also adequately delivers its resources in an elastic or scalable manner, especially during times of peak demand.
 

 <h3> Services of IaaS </h3>
 
**Compute:** Computing as a Service includes virtual central processing units and virtual main memory for the Vms that is provisioned to the end- users.
**Storage:** IaaS provider provides back-end storage for storing files.
**Network:** Network as a Service (NaaS) provides networking components such as routers, switches, and bridges for the Vms.
**Load balancers:** It provides load balancing capability at the infrastructure layer.

<h3> Working </h3>

IaaS points to an infrastructure either physical or virtual that is provided by the cloud provider. IaaS has lots of resources such as network, server, storage, virtualization, so it depends upon the customer to choose its resources wisely and as per need. Apart from the management of the infrastructures, it provides billing management too, where the user is billed as per the services rendered.

The organization identifies its need and requests the appropriate service. The user then pays for the resource and IaaS also offers billing management services.

<h3> IaaS Models </h3>
 
IaaS is offered in three models: public, private, and hybrid cloud. The private cloud implies that the infrastructure resides at the customer-premise. In the case of public cloud, it is located at the cloud computing platform vendor's data center, and the hybrid cloud is a combination of the two in which the customer selects the best of both public cloud or private cloud.
 
<b> Examples </b>
 
AWS , Azure, Digital Ocean, GCP etc.



<h2> Personal Project </h2>

<b>  Video Streaming & hosting, App </b>

<b> Functionality </b>

Provides comprehensive live streaming and online video hosting services. Streamers maintain their 100% ownership of their content.

<h3> Preferred Service Model for the Project </h3>

SaaS model is best suited for such project.  

<h3> Reasons for Opting this Model </h3>

- Adoptable for this kind of business needs and set of goals.
- Multi user access on scale and custom plans.
- Maintenance is usually included in monthly contract costs. New features & IT Integration costs are additional cost but only a fraction of overall cost is charged to the customer. 
- Infrastructure and development cost is absorbed in Monthly Contract costs.
- **Operation costs and overheads**: Our existing teams can be taught to run and manage the platform. This means we do not incur any operational overheads.
- Provide secure platforms that are usually pre-tested by QA specialists and/or third parties. The subscriber has no control or access to security features. 
- Ownership.
- The uploading, encoding and broadcasting of live & on-demand videos through a CDN and a customizable video player.
- Management of users and their access rights to videos with temporary access tokens.
- Monetization of content by subscription, by unit and associated promotion mechanisms (trial period, discount coupon.
- Management of orders, automatic invoicing and payment methods.
- For Multi tenant and microservices based environment we have PAAS open source tools for development of SaaS microservices, workflows & automation to meet our customer demands such as Kubernetes, openshift, docker etc.
- An API system (Rest and GraphQL) allowing interfacing with third-party software and all types of front-end interfaces and partner platforms.
- SaaS provides beneficial cost savings since it usually resides in a shared or multi-tenant environment, where the hardware and software license costs are low compared with the traditional model.   


