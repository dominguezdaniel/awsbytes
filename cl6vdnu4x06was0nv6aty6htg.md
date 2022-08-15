## Optimize resources across your organization using AWS Compute Optimizer from a designated account

[AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/) is a service that recommends optimal AWS resources for your workloads to reduce costs and improve performance by using machine learning to analyze historical utilization metrics. Starting today, you can designate a member account in your organization to retrieve Compute Optimizer recommendations and manage Compute Optimizer preferences, giving you greater flexibility to identify resource optimization opportunities centrally.

You can centrally manage and govern your environment as you grow and scale your AWS resources with [AWS Organizations](https://aws.amazon.com/organizations/), giving you the ability to programmatically create new accounts and allocate resources, consolidate your billing, create groups of accounts to organize your workflows, and apply policies to these groups for governance. Compute Optimizer continuously analyzes the resource utilization of your Amazon EC2 instances, Amazon EBS volumes, and AWS Lambda functions for all accounts within the organization, helping identify rightsizing opportunities to reduce costs and improve performance.

To get started, you can designate a member account as the delegated administrator for Compute Optimizer using the Compute Optimizer console. After the account is registered as the delegated administrator, you can use that account to set up Compute Optimizer to identify resource optimization opportunities for all accounts within the organization.

The feature is available in all regions where Compute Optimizer and AWS Organizations are available. For more information, visit the [User Guide](https://docs.aws.amazon.com/compute-optimizer/latest/ug/delegate-administrator-account.html).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/08/optimize-resources-organization-aws-compute-optimizer-designated-account/