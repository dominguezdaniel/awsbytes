## AWS PrivateLink announces enhanced tagging capability for service owners

You can now use tags to better track and manage your AWS PrivateLink-powered VPC Endpoint Services. AWS PrivateLink is a fully-managed private connectivity solution that enables customers to connect to other services hosted on AWS using a secure and scalable method while keeping network traffic private.

Until now, service owners were able to tag their PrivateLink-based services and consumers could tag their PrivateLink endpoints. With today’s launch, you can now tag the customer principals (accounts/users/roles) that use your service. Similarly, you can also tag the endpoint-connections created by your customers. The tags are visible only to the account hosting the service and not to other accounts that may use the service. You can use tags to store customer metadata to inform business logic, and to tie-back accounts and endpoint-connections to customers during troubleshooting.

There are no added charges for the feature. Enhanced tagging is available via the AWS Console, CLI and SDK in all public AWS Regions and GovCloud Regions. To learn more, visit [AWS PrivateLink](https://docs.aws.amazon.com/vpc/latest/privatelink/vpce-interface.html) in Amazon VPC Developer Guide.

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/aws-privatelink-announces-enhanced-tagging-capability-service-owners/