# Amazon EMR release 6.8 now supports Apache Flink 1.15.1

AWS announces that Amazon EMR release 6.8 includes Apache Flink 1.15.1. This feature is available on EMR on EC2.

Apache Flink is an open source framework and engine for processing data streams. Apache Flink 1.15.1 on EMR 6.8 includes 62 bug fixes, vulnerability fixes, and minor improvements over Flink 1.15.0. Key features include:

Watermark alignment (Beta) across data sources : Event-time processing in Flink depends on special timestamped elements, called watermarks, that are inserted into the stream either by the data sources or by a watermark generator. A watermark with a timestamp t can be understood as an assertion that all events with timestamps < t have already arrived. 

Watermark alignment is useful when processing sources with different velocity of events e.g. when one source is idle or one source emits records relatively faster than others, you can enable watermark alignment for each source separately. Flink aligns watermarks by pausing the highest velocity source and continuing to read records from other sources until the watermarks are aligned.

SQL version upgrade : Introducing JSON plans which are JSON functions that make it easier to import and export structured data in SQL. Today, version upgrades can alter the topology of SQL queries which can introduce snapshot incompatibility across versions. This makes upgrading Flink versions challenging. With this feature, both the Table API and SQL will provide a way to compile and execute a plan ensuring the same topology for SQL queries throughout different versions, making it more reliable to upgrade to future versions. Users who want to give it a try can create a JSON plan that can then be used to restore a Flink job based on the old operator structure.
For more details, refer to the OSS Flink release docs.

Amazon EMR release 6.8 is generally available in all regions where Amazon EMR is available. See Regional Availability of Amazon EMR, and our release notes for more details.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/amazon-emr-release-6-8-supports-apache-flink-1-15-1/