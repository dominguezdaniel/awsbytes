# Amazon Virtual Private Cloud (VPC) now supports the transfer of Elastic IP addresses between AWS accounts

AWS is announcing Elastic IP transfer, a new Amazon VPC feature that allows you to transfer your Elastic IP addresses from one AWS Account to another, making it easier to move Elastic IP addresses during AWS Account restructuring. 

Prior to this, when moving applications to a new AWS Account, you had to allocate new Elastic IP addresses for your applications requiring you to allowlist the new Elastic IP addresses in your connectivity resources, such as routers and firewalls, which slowed down migrations. With Elastic IP transfer, you are now able to re-use the same Elastic IP addresses for your applications even after you move them to a new AWS Account, eliminating the need to allowlist connectivity resources and accelerating your migrations.
Additionally, if you are using Amazon VPC IP Address Manager (IPAM), you can now track your Elastic IP transfers using IPAM.

Elastic IP transfer is available in all AWS commercial and AWS GovCloud (US) regions at no additional cost. For more information, please visit the [VPC user guide](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-eips.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/amazon-virtual-private-cloud-vpc-transfer-elastic-ip-addresses-between-aws-accounts/