## Monitor Amazon EMR Serverless applications in near real-time with CloudWatch metrics

[Amazon EMR Serverless](https://aws.amazon.com/emr/serverless/) is a serverless option in [Amazon EMR](https://aws.amazon.com/emr/) that makes it easy for data analysts and engineers to run open-source big data analytics frameworks without configuring, managing, and scaling clusters or servers. 

Today, we are excited to launch live monitoring of EMR Serverless capacity usage using Amazon Cloudwatch metrics. With this feature, you can track how much CPU, memory, or disk space is currently being used by an EMR serverless application, how resources have been added or removed over time to run the application, or how many drivers and executors have been running at any time. You can get a single view to monitor application capacity usage in a Cloudwatch dashboard. To get started, use the EMR Serverless Cloudwatch dashboard template provided in [emr-serverless-samples git repo](https://github.com/aws-samples/emr-serverless-samples) and deploy it.

Amazon CloudWatch metrics for EMR Serverless are available in all AWS regions where EMR Serverless is available. To learn more and get started, see the documentation [here](https://docs.aws.amazon.com/emr/latest/ManagementGuide/UsingEMR_ViewingMetrics.html).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/monitor-amazon-emr-serverless-applications-near-real-time-cloudwatch-metrics/