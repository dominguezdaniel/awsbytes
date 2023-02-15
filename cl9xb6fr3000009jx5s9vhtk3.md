# AWS Launch Wizard adds support for placing Microsoft SQL Server tempdb in an instance store

AWS Launch Wizard now supports for placing Microsoft SQL Server tempdb in instance store volumes during SQL Server deployment on Amazon EC2. With the launch, you can save time and effort by easily configuring tempdb by one click during deployment without needing to manually configuring it after deployment.

AWS Launch Wizard enables you to easily size, configure, and deploy SQL Server single node and high availability deployments on EC2. Customers usually choose to place SQL Server tempdb in non-volatile memory express (NVMe) solid state drives (SSD) instance store volumes to optimize performance. You can easily achieve it by selecting the tempdb check box in the Launch Wizard console and then specifying the EC2 instance type with NVMe SSD based on your needs. In addition, you can enable one-click monitoring of SQL Server with CloudWatch Application Insights to simplify monitoring. You can also choose to save the CloudFormation templates and associated configuration scripts to your Amazon S3 bucket for repeated deployments.

AWS Launch Wizard for SQL Server is available at no additional charge. You only pay for the AWS resources that are provisioned for running your SQL Server. To learn more about using AWS Launch Wizard, visit the [user guide](https://docs.aws.amazon.com/launchwizard/latest/userguide/launch-wizard-sql.html) or [AWS Launch Wizard page](https://aws.amazon.com/launchwizard/).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-launch-wizard-placing-microsoft-sql-server-tempdb-instance-store/