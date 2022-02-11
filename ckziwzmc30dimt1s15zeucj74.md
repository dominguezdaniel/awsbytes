## Scaling From One to Half a Million Users

In the beginning, you can get started with a single EC2 instance that hosts your web service and the DB on the same instance. You can provision an EIP and use Route53 for DNS services. This should be sufficient to handle a typical website or service for a new business.

As your number of users increases to several hundreds or thousands, there are several easy-to-upgrade options available to scale your infrastructure. The simplest first step is to get a bigger EC2 instance (scale vertically). You can also leverage instance types (high I/O, memory, compute, storage intensive) based on your specific workloads. Additionally, increasing PIOP settings can give you the results you need to handle an increasing number of users. However, be aware that you will hit an upper limit in terms of how far you can scale this way. Additionally, having no redundancy or failover mechanisms as the number of users increases will become a major cause for worry. 

The first change to the architecture is to separate the DB from the web tier. This step can instantly improve overall scalability, as it enables the web and data tiers to be independently scaled. Web and data tiers don’t have the same requirements, so having the ability to scale them separately gives you more flexibility to align the architecture more closely to your workloads. Typically, you would start with a relational database because you are probably most familiar and comfortable with it. It is a well established and well-worn technology; there is lots of existing sample code available, active communities, many reference books, and tools to help you with anything you are likely to face. For most workloads, you aren’t going to break RDBMS down to several million users. There are well-documented patterns for scaling relational databases.

However, there may be exceptions where relational databases are not suitable for your first year of operations, and deploying a NoSQL database makes more sense. 

These use cases could be due to massive data volumes expected in the first year itself. Other reasons for deploying a NoSQL solution could be due to requirements such as super low-latency use cases, highly non-relational data, or unstructured data requiring schema-less data constructs, rapid ingestion of streaming data (thousands of records per second), and so on. In many applications, the functional and non-functional requirements will most likely be best served by having both SQL and NoSQL databases in your application.

At this stage, you will also need to decide between the self-managed database (on Amazon EC2) or a fully managed AWS database service (such as RDS, DynamoDB, Redshift, and Aurora). 

Though it is likely that you have sufficient familiarity with setting up and managing a database like MySQL, you may want to consider a MySQL-compatible RDS service such as Aurora instead to avoid managing your own database servers. Aurora automatically scales storage up to 64 TB and can have 15 read replicas currently. 

Additionally, the service comes with continuous (incremental) backups to Amazon S3 and six-way replication across three AZs. It is an economical, performant, and scalable alternative.

As the number of users goes over a thousand, you will want to consider a more distributed architecture for higher scalability and High Availability. 

For example, consider distributing the web tier across two AZs, and a multi-AZ DB deployment to enable replicated DBs across the two AZs. You can also include a classic elastic load balancer to distribute the load evenly and get HA out of the box. 

The load balancing service scales automatically and performs health checks on the instances registered with it. The ELB won't send traffic to unhealthy instances. You can also consider content-based routing with an application load balancer. Using these basic approaches can get us pretty far, especially with the ELB helping us to scale horizontally and upgrading instance types to scale vertically. 

As we move to handling traffic for tens of thousands of users, we can consider additional load balancing for various services and instances across multiple AZs. We can now add read replicas to reduce load on the master DB and allow more scalability in the data tier.

As you scale, don't lose sight of performance, efficiency, and costs involved. Consider lightening the load on your origin servers by leveraging CloudFront and S3—take the static content and put it in S3 buckets and front them with CloudFront. Amazon S3 object-based storage is an economical storage option that is great for static assets, is infinitely scalable, and can store objects up to 5 TB in size with optional encryption. CloudFront can cache content for faster delivery, lowers load on the origin, and can deal with both static and dynamic content. It also supports custom SSL certificates and low TTLs (as short as zero seconds, optimizing connection to the origin).

The service is optimized for AWS. With CloudFront, the ability to scale improves, reduces load on the origin, and improves response times significantly. These steps can make the web tier a lot more lightweight.

We can introduce DynamoDB at this stage. DynamoDB is a managed NoSQL database that is fully distributed and fault tolerant and supports provisioned throughput. You can provision the reads separately from the writes, and achieve fast predictable performance. You can also use DynamoDB to store session date data to create a stateless application. If the state information is removed from the web tier, it greatly increases your ability to scale it while maintaining a good customer experience. We should also start using ElastiCache at this stage. ElastiCache is a managed Memcached or Redis service that can scale from one to many nodes. It is a self-healing (replaces dead instances) and performant (single digit ms speeds) caching service. 

Note that the Memcached option is local to a single AZ, however, multi-AZ configurations are possible with Redis. For high access queries, you should not keep going back to the data tier. You can store the results in the cache instead for better user experience and scale the data tier in a more reasonable manner. 

><div class="csl-entry">Sarkar, A. and Shah, A. (2018) <i>Learning AWS.</i> 2nd edn. Packt Publishing. Available at: https://www.perlego.com/book/578848/learning-aws-pdf (Accessed: 25 September 2021).</div>