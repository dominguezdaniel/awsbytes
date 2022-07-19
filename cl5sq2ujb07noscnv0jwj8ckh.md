## AWS Lambda announces support for Attribute-Based Access Control (ABAC)

AWS Lambda announces support for [attribute-based access control (ABAC)](https://aws.amazon.com/identity/attribute-based-access-control/) for API actions that use Lambda function as the required resource. ABAC is an authorization strategy that defines access permissions based on tags which can be attached to IAM resources, such as IAM users and roles, and to AWS resources, like Lambda functions, to simplify permission management.

ABAC support for Lambda functions allows you to scale your permissions as your organization innovates and give granular access to developers without requiring a policy update when a user or project is added, removed or updated. With ABAC support for AWS Lambda, IAM policies can be used to allow or deny specific Lambda API actions when the IAM principal's tags match the tags on a Lambda function.

With this launch, AWS Lambda supports [ABAC](https://aws.amazon.com/identity/attribute-based-access-control/) only for Lambda APIs that use function, function version and function alias as the main resource type. Please review the full list of Lambda API actions and resource types [here](https://docs.aws.amazon.com/service-authorization/latest/reference/list_awslambda.html). AWS Lambda supports ABAC in all public [AWS Regions](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/) except for the AWS Govcloud (US) Regions and Amazon Web Services China (Beijing) Region, operated by Sinnet and Amazon Web Services China (Ningxia) Region, operated by NWCD.

To get started with ABAC for Lambda functions, see the following resources:

For information about attribute-based access control, see [What is ABAC for AWS](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_attribute-based-access-control.html) in the IAM User Guide.

For information about configuring ABAC with AWS Lambda, see [Control access using tags](https://docs.aws.amazon.com/lambda/latest/dg/attribute-based-access-control.html) in AWS Lambda Developer Guide

Read the AWS Compute blog [here](https://aws.amazon.com/blogs/compute/scaling-lambda-permissions-with-attribute-based-access-control).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/07/aws-lambda-support-abac/