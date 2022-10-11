# Amazon EC2 now offers an automated connection set-up solution between EC2 instance and RDS Database

Starting today, in [Amazon Elastic Compute Cloud (Amazon EC2)](https://aws.amazon.com/pm/ec2/), you have the option to automatically set up connectivity between the EC2 instances and an [Amazon Relational Database Services (Amazon RDS)](https://aws.amazon.com/rds/) or [Amazon Aurora](https://aws.amazon.com/rds/aurora/) database. Once you have provisioned EC2 instances, you can select a RDS db instance or cluster, and with a single click, complete connectivity configurations to allow traffic from the EC2 instance to the RDS database. Amazon EC2 follows the connectivity best practices and automatically sets up security groups on your behalf, helping to establish a secure connection.

This feature provides a simplified and secure mechanism to complete the connection setup between an EC2 instance and RDS database. If done manually, establishing a connection between your application and database requires tasks such as setting up a VPC, security groups, and ingress/egress rules. The automated solution helps improve productivity for new users and application developers, who can now seamlessly connect EC2 instances to databases in a simplified and automated way.

Amazon EC2 automated connection set-up solution is generally available in all public AWS regions. 

Learn more about setting up connectivity to a your RDS or Aurora databases in the [Amazon EC2 User Guide](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/connect-instance-to-resources.html).

> Source: 