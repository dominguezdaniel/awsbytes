# AWS CloudFormation StackSets increases limits on three service quotas

Today, [AWS CloudFormation StackSets](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/what-is-cfnstacksets.html) increased the default for three service quotas: number of stack instances per stack set, number of stack sets per management account, and number of concurrent stack instance operations in a single AWS Region per management account. You can now (1) deploy up to 100,000 stack instances per stack set (previously 2,000), (2) create up to 1,000 stack sets in your management account (previously 100), and (3) run up to 10,000 concurrent stack instance operations in a single Region per management account (previously 3,500). See [AWS CloudFormation quotas](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cloudformation-limits.html) for the latest service quotas.

StackSets extends the functionality of CloudFormation stacks, and enables you to create, update, or delete stacks across multiple AWS accounts and Regions with a single operation. With this launch, you can scale your stack instance deployments from a single management account by 40x, and minimize creation of management accounts to support multiple stack sets by 9x. You can use StackSets for bootstrapping AWS account, baselining configuration, deploying cross account data collection systems, setting up disaster recovery, and solving other use cases for multi-accounts and regions.

These new StackSets limits are now active in your AWS accounts for AWS Regions where CloudFormation is available. To get started with AWS CloudFormation StackSets, refer to [StackSets getting started page](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/stacksets-getting-started.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-cloudformation-stacksets-increases-limits-three-service-quotas/