## Amazon DocumentDB (with MongoDB compatibility)

The storage space allocated to your [Amazon DocumentDB (with MongoDB compatibility)](https://aws.amazon.com/documentdb/) cluster will now dynamically decrease when you delete data from the cluster. 

Amazon DocumentDB is a database service that is purpose-built for JSON data management at scale, fully managed and integrated with AWS, and enterprise-ready with high durability. Previously, when Amazon DocumentDB data was removed, such as by dropping a collection, the overall allocated space remained the same. The free space was reused automatically when data volume increased in the future.

Now, with dynamic resizing, the allocated storage space automatically increases up to a maximum size of 64 Tebibyte (TiB) when you need more storage and decreases automatically when you delete data. You only pay for the storage you use. Dynamic resizing for storage space is now being enabled for all Amazon DocumentDB v4.0 clusters in all regions. 

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

All new Amazon DocumentDB v4.0 clusters will have this feature enabled by default.

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/aws-support-improved-create-case-experience/