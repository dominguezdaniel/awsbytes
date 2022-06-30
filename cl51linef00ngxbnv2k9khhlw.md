## AWS Glue Streaming ETL now supports auto-decompression

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

[AWS Glue](https://aws.amazon.com/glue/) streaming ETL (Extract Transform and Load) can now detect compressed data streaming from Amazon Kinesis, Amazon Managed Streaming for Apache Kafka (Amazon MSK), and self managed Apache Kafka. It can then automatically decompresses this data without customers having to write code, saving them development hours. AWS Glue Streaming ETL jobs continuously consume data from streaming sources, cleans and transforms the data in-flight, and makes it available for analysis in seconds. Customers compress data prior to streaming in-order to improve performance and to avoid throttling limits by Amazon Kinesis and Amazon MSK. Prior to this feature, customers had to write user defined functions to uncompress data from a stream, which is time consuming.

With this new feature, AWS Glue streaming ETL automatically detects if data is compressed in a stream and decompresses the data without customers having to write any code. AWS Glue streaming ETL supports auto-decompression for BZIP, GZIP, SNAPPY, XZ, ZSTD, and DEFLATE compression types and is supported on AVRO, JSON, CSV, and other file formats. To learn more, visit our [documentation](https://docs.aws.amazon.com/glue/latest/dg/add-job-streaming.html).

This feature is available in the same [AWS Regions](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/) where AWS Glue is available.

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/aws-glue-streaming-etl-support-auto-decompression/