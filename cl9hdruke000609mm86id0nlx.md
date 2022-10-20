# Amazon Aurora MySQL supports faster export to S3

AWS announced up to 10x faster exports to Amazon S3 for snapshot exports for Amazon Aurora MySQL-Compatible Edition for MySQL 5.7 and 8.0. The performance improvement is automatically applied to all types of database snapshot exports, including manual snapshots, automated system snapshots, and snapshots created by the AWS Backup service.

With this capability, customers can export data up to 10x faster from an Amazon Aurora database and store it in an Amazon S3 bucket using AWS CLI or [AWS Management Console](http://console.aws.amazon.com/). After the data is exported, they can analyze the exported data using [Amazon Athena](https://aws.amazon.com/athena/) and/or other tools and services. The export process runs in the background and doesn't affect the performance of active database instances.

[Amazon Aurora](https://aws.amazon.com/rds/aurora/) is designed for unparalleled high performance and availability at global scale with full MySQL and PostgreSQL compatibility. It provides built-in security, continuous backups, serverless compute, up to 15 read replicas, automated multi-Region replication, and integrations with other AWS services. To get started with Amazon Aurora, take a look at our [getting started page](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_GettingStartedAurora.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/amazon-aurora-mysql-faster-export-s3/