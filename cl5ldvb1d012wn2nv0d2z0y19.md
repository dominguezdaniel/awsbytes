## AWS announces AWS AppConfig Extensions

AWS announces [AWS AppConfig](https://aws.amazon.com/systems-manager/features/appconfig/) Extensions, a new capability that allows customers to enhance and extend the capabilities of feature flags and dynamic runtime configuration data. AWS AppConfig, a capability of [AWS Systems Manager](https://aws.amazon.com/systems-manager/), allows customers to configure, validate, and deploy configuration data to more safely and quickly update application behavior. The [AppConfig Extensions framework](https://aws.amazon.com/blogs/mt/announcing-aws-appconfig-extensions/) exposes action points along the lifecycle of feature flags and configuration data; customers can hook new functionality onto each action point. Action points are exposed during the creation, validation, deployment, and rollback of feature flag and configuration data.

Available extensions at launch include AppConfig Notification extensions that pushes messages about configuration updates to [EventBridge](https://aws.amazon.com/eventbridge/), [SNS](https://aws.amazon.com/sns/), or [SQS](https://aws.amazon.com/sqs/). There is also a Jira extension, which allows a customer to track Feature Flag changes in AppConfig as individual issues in Atlassian’s Jira.

Furthermore, customers can create their own extensions. For example, a customer may want to extend AppConfig’s built in automatic rollback functionality by calling a Lambda function if a rollback occurs. Another example would be a customer pulling configuration data from another source, like a database or a git repository, to be merged into other AppConfig data prior to deployment. These are possible through a customer authoring their own extension. In addition to customer-authored and current AWS-authored extensions, more extensions are planned in the future.

AWS AppConfig Extensions are available at no extra cost for AppConfig users, and are available in all AWS Regions.

To get started, read our documentation on [AppConfig Extensions](https://docs.aws.amazon.com/appconfig/latest/userguide/working-with-appconfig-extensions.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/aws-announces-appconfig-extensions/