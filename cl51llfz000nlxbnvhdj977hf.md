## Amazon RDS increases concurrent copy limit to 20 snapshots per destination region

[Amazon RDS](https://aws.amazon.com/rds/) now allows you to have up to 20 concurrent snapshot copy requests per destination region per account, an increase from the former limit of five concurrent copies per destination region per account.

The new limit applies to snapshots of Microsoft SQL Server, Oracle engines, Amazon RDS for PostgreSQL, Amazon RDS for MySQL, and Amazon RDS for MariaDB engines in AWS Regions where Amazon RDS is available. This feature has been enabled on your account and no further action is needed from you.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

For more information on copying RDS snapshots, please refer to the documentation [guide](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_CopySnapshot.html).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/amazon-rds-increases-concurrent-copy-limit-snapshots-destination-region/