Problem Statement: 

You're the cloud engineer for a virtual coffee shop chain that wants to move their operations to the cloud. They need a scalable and cost-effective solution to ensure their website and backend are always up and running.

Guidelines/Goals:

Create a Virtual Private Cloud (VPC):

Set up a VPC with IPv4 CIDR block and divide it into subnets (public and private).
You might also need to create an Internet Gateway and attach to your vpc.
Launch EC2 Instances:

Launch an EC2 instance for the website using Amazon Linux 2 AMI.
Launch another EC2 instance for the backend using Amazon Linux 2 AMI.
Choose appropriate instance types based on the instance's purpose.
Configure Security Groups and Network ACLs:

Create security groups for each instance to control inbound and outbound traffic.
Set up Network ACLs to provide additional layer of security.