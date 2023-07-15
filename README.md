# Cloud-Project

# App deployment

# Quiz
## IAM Quiz
Which statement describes AWS Identity and Access Management (IAM) users?

1. IAM users are used to control access to a specific AWS resource.
2. IAM user names can represent a collection of indviduals.
3. Every IAM user for an account must have a unique name.
4. Every IAM user name is unique across all AWS accounts.

```Answer: 3```


How can you grant the same level of permissions to multiple users within an account?

1. Apply an AWS Identity and Access Management (IAM) policy to an IAM group.
2. Apply an AWS Identity and Access Management (IAM) Policy to an IAM role.
3. Create a resource-based policy.
4. Create an organization in AWS Organizations.

```Answer: 1```


Which statements describe AWS Identity and Access Management (IAM) roles? (Select TWO.)

1. They are uniquely associated to an individual.
2. They can only be used by accounts associated to the person who creates the role.
3. They can be assumed by individuals, applications, and services.
4. They provide temporary security credentials.
5. They provide permanent security credentials.

```Answer: 3, 4```


Which statement describes a resource-based policy?

1. It can be applied to any AWS resource.
2. It can be an AWS managed policy.
3. It is attached to a user or a group.
4. It is always an inline policy.

```Answer: 1```


How does AWS Identity and Access Management (IAM) evaluate a policy?

1. It checks for explicit allow statements before it checks for explicit deny statements.
2. It checks for explicit deny statements before it checks for explicit allow statements.
3. If there is no explicit deny statement or explicit allow statement, users will have access by default.
4. An explicit deny statement does not override an explicit allow statement.

```Answer: 2```


A team of developers needs access to several services and resources in a virtual private cloud (VPC) for 9 months. How can you use AWS Identity and Access Management (IAM) to enable access for them?

1. Create a single IAM user to the developer team and attach the required IAM policies.
2. Create an IAM user for each developer, and attach the required IAM policies to each IAM user.
3. Create an IAM user for each developer, put them all in an IAM group, and attach the required IAM policies to the IAM group.
4. Create a single IAM user for the developer team, place it in an IAM group, and attach the required IAM policies to the IAM group.

```Answer: 3```


How does identity federation increase security for an application that it built in Amazon Web Services (AWS)?

1. Users can use single sign-on (SSO) to access the application through an existing authenticated identity.
2. The application can synchronize user's user names and passwords in AWS identity and Access Management (IAM) with their social media accounts.
3. The browser can establish a trust relationship with the application to bypass the need for multi-factor authentication (MFA).
4. Users can use their AWS Identity and Access Management (IAM) accounts to log in to on-premises systems.	

```Answer: 1```

## Network Quiz

Which definition describes a virtual private cloud (VPC)?

1. A virtual private network (VPN) in the AWS Cloud.
2. An extension of an on-premises network into Amazon Web Services (AWS)
3. A logically isolated virtual network that you define in the AWS Cloud
4. A fully managed service that extends the AWS Cloud to customer premises

```Answer: 3```


A company's VPC has the CIDR block 172.16.0.0/21 (2048 addresses). It has two subnets (A and B). Each subnet mush support 100 usable addresses now, but this number is expected to rise to at most 254 usable addresses soon. Which subnet addressing scheme meets the requirements and follows AWS best practices?

1. Subnet A: 172.16.0.0/25 (128 addresses) Subnet B: 172.16.0.128/25 (1024 addresses)
2. Subnet A: 172.16.0.0/25 (128 addresses) Subnet B: 172.16.0.128/25 (128 addresses)
3. Subnet A: 172.16.0.0/23 (512 addresses) Subnet B: 172.16.0.128/23 (512 addresses)
4. Subnet A: 172.16.0.0/22 (1024 addresses) Subnet B: 172.16.0.128/22 (128 addresses)


```Answer: 3```


Which combination of actions enables direct internet access for IPv4 hosts in a virtual private cloud (VPC)? (Select THREE.)

1. Creating a route for 0.0.0.0/0 that points to the internet gateway
2. Enabling Domain Name System (DNS) resolution for the VPC
3. Configuring hosts to have or obtain an internet-routable address
4. Configuring the VPC domain name in a Dynamic Host Configuration Protocol (DHCP) options set
5. Creating a default route that points to the virtual private gateway
6. Configuring security groups and network access control lists (network ACLs) to permit internet traffic

```Answer: 1, 3, 6```


Several EC2 instances launch in a virtual private cloud (VPC) that has internet access. These instances should not be accessible from the internet, but they must be able to download updates from the internet. How should the instances launch?

1. With Elastic IP addresses, in a subnet with a default route to an internet gateway
2. With public IP addresses, in a subnet with a default route to an internet gateway
3. Without public IP addresses, in a subnet with a default route to an internet gateway
4. Without public IP addresses, in a subnet with a default route to a network address translation (NAT) gateway

```Answer: 4```

# IAM

# AWS Quicksight
