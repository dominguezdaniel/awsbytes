## Amazon S3 on Outposts now supports presigned URLs

[Amazon S3 on Outposts](https://aws.amazon.com/s3/outposts/) now supports presigned URLs for granting time-limited access to objects stored locally on an Outpost. S3 on Outposts bucket owners can now more easily share objects with individuals in their Virtual Private Cloud (VPC).

Prior to presigned URLs, to share objects with other users, bucket owners would assign IAM policies to buckets. Now, with presigned URLs, bucket owners have a time-limited way to grant the ability to share, upload, or delete objects with other individuals in their VPC. Bucket owners can grant time-limited access with the presigned URL by choosing a custom expiration time that can be as low as one second and up to seven days, using the AWS CLI and SDKs.

Amazon S3 on Outposts delivers object storage to your on-premises AWS Outposts rack environment to help you meet your low latency, local data processing, and data residency needs. Using the S3 APIs and features, S3 on Outposts makes it easier to store, secure, tag, retrieve, report on, and control access to the data on your Outposts. AWS Outposts rack, as part of the AWS Outposts Family, is a fully managed service that extends AWS infrastructure, services, and tools to virtually any data center, co-location space, or on-premises facility for a truly consistent hybrid experience.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

Presigned URLs are now available at no additional cost in all AWS Regions where [AWS Outposts rack is available](https://aws.amazon.com/outposts/rack/faqs/). To get started with presigned URLs or learn more, visit the [S3 on Outposts page](https://aws.amazon.com/s3/outposts/), or read our [documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/S3OutpostsPresignedURL.html).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/amazon-s3-outposts-presigned-urls/