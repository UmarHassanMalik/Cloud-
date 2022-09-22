<h3> Control Traffic to subnets by Using Network Access Control List </h3>

ACLs allows or denies specific inbound or outbound traffic at the subnet level. We can use the default network ACL for our VPC, or we can create a custom network ACL for our VPC with rules that are similar to the rules for our security groups in order to add an additional layer of security to our VPC.

- In below diagram we can see each subnet has a network ACL.
- When traffic enters the VPC the router sends the traffic to its destination.
- Network ACL A determines which traffic destined for subnet 1 is allowed to enter subnet 1, and which traffic destined for a location outside subnet 1 is allowed to leave subnet 1
- Network ACL B determines which traffic is allowed to enter and leave subnet 2.

![image](https://user-images.githubusercontent.com/58930229/191839477-6433be47-6936-4966-9624-b628825c6f1f.png)


<h3> Network ACL basics </h3> 

- VPC automatically comes with a modifiable default network ACL.
- Create a custom network ACL and associate it with a subnet by adding some rules.
- Each subnet in VPC must be associated with a network ACL.
- We can associate a network ACL with multiple subnets. However, a subnet can be associated with only one network ACL at a time. 
- When we associate a network ACL with a subnet, the previous association is removed.
- A network ACL has inbound rules and outbound rules. Each rule can either allow or deny traffic. Each rule has a number 1 from to 32766
- The rules are evaluated in order, starting with the lowest numbered rule, when deciding whether allow or deny traffic.
- Network ACLs are stateless.

<h3> Network ACL rules </h3>

<b>Rule number </b>

- Rules are evaluated starting with the lowest numbered rule. When a rule is matched with traffic, its applied.


<b>Type </b>

- Traffic type such as HTTPS, SSH. We can set custom ranges.

<b>Protocol </b>

- We can specify any protocol that has a standard protocol number as given in IETF/IANA.

<b>Port Range </b>

- The listening port or port range for the traffic. Such as 443 for HTTPS.


<b>Source </b>

- Source of the traffic such as Classless inter-domain routing range.


<b>Destination </b>

- The destination for the traffic, CIDR range.

<b>Allow/Deny </b>

- Controlling the traffic either allow or deny.
