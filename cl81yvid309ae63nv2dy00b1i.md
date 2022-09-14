## AWS Cloud Development Kit (CDK) announces CDK Construct tree view in the AWS CloudFormation console

Customers using CDK want a simple way to map the resources synthesized in a CloudFormation template back to the source CDK Construct. In an effort to display all resources in a CloudFormation template the Management Console loses the hierarchical nature of CDK Constructs, which customers are used to today. CDK Construct tree view in the CloudFormation console is intended for the customers who want to observe the context from which the resources were created to the CloudFormation console, in order to provide a better, focused experience.

Tree view capability will automatically organize the resources that were synthesized by AWS CDK Constructs: the top level will be the AWS CDK Construct (by name) and all resources will be placed as a second level under the Construct that generated them. As a user, the Constructs tree view will allow you to easily identify the hierarchy of the resources and their logical location in the application: each resource is placed in an app-logical context, which is presented as a tree view in CloudFormation Console.

CDK Construct tree view in the CloudFormation console is generally available in all public AWS Regions where CloudFormation is available. For more information, refer to the AWS Region table.

To get started with AWS CDK, see the following resources:

Get started with the AWS CDK in all supported languages by taking [CDK Workshop](https://cdkworkshop.com/).

Read our [Developer Guide](https://docs.aws.amazon.com/cdk/latest/guide/home.html) and [API Reference](https://docs.aws.amazon.com/cdk/api/latest/docs/aws-construct-library.html).

Find useful constructs published by AWS, partners and the community in [Construct Hub](https://constructs.dev/).

Connect with the community in the [cdk.dev](https://cdk.dev/) Slack workspace.

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/aws-cloud-development-kit-cdk-announces-cdk-construct-tree-view-cloudformation-console/