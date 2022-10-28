# Amazon Aurora supports cluster export to S3

[Amazon Aurora](https://aws.amazon.com/aurora/) now supports exporting database clusters directly to S3 in Apache Parquet format without creating a snapshot first. Customers can also initiate an export to S3 directly from the Aurora database cluster, saving them time, cost and the extra overhead of creating/retaining snapshots to export data to S3.

Exporting data to S3 from an Aurora cluster does not impact the performance of the Aurora database. The exported data in Apache Parquet format is portable, so customers can analyze their data with query services such as [Amazon Athena](https://aws.amazon.com/athena/) or big data processing frameworks such as Apache Spark. To get started, visit the [Amazon RDS Management Console](https://console.aws.amazon.com/rds/home) or use the AWS CLI  to export your Aurora database clusters directly to S3 without taking a manual snapshot.

Amazon Aurora is designed for unparalleled high performance and availability at global scale with full MySQL and PostgreSQL compatibility. It provides built-in security, continuous backups, serverless compute, up to 15 read replicas, automated multi-Region replication, and integrations with other AWS services. To get started with Amazon Aurora, take a look at our getting started page.

Support for database cluster exports into S3 is available in Asia Pacific (Hong Kong), Asia Pacific (Mumbai), Asia Pacific (Osaka), Asia Pacific (Seoul), Asia Pacific (Singapore), Asia Pacific (Sydney), Asia Pacific (Tokyo), Canada (Central), Europe (Frankfurt), Europe (Ireland), Europe (London), Europe (Paris), Europe (Stockholm), South America (São Paulo), US East (Ohio), US East (N. Virginia), US West (N. California), and US West (Oregon).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/10/amazon-aurora-cluster-export-s3/