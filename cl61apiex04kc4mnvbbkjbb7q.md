## Amazon DocumentDB (with MongoDB compatibility) now supports fast database cloning

Amazon DocumentDB (with MongoDB compatibility) now allows you to create clones to enable fast creation of a new cluster that uses the same DocumentDB cluster volume and has the same data as the original.

Database cloning is faster than restoring a snapshot and requires no additional space at the time of creation. With this launch you can, for example, create a cloned DocumentDB cluster from a provisioned DocumentDB cluster to get quick access to production data for development and testing. You can use the clone to verify database changes, test different parameters, and run analytic queries on production data without providing direct access to the production database or impacting its performance. You only pay for additional storage if you make data changes in the cloned DB cluster.

Read more about database cloning in the [DocumentDB documentation](https://docs.aws.amazon.com/documentdb/latest/developerguide/db-clusters.html). To create a database clone, visit the [Amazon Web Services Management Console](http://console.aws.amazon.com/docdb/home) or download the latest Amazon Web Services SDK or CLI.

[Amazon DocumentDB (with MongoDB compatibility)](https://aws.amazon.com/documentdb/) is a scalable, highly durable, and fully managed database service for operating mission-critical MongoDB workloads.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-documentdb-mongodb-fast-database-cloning/