## Multi-tenancy Models

Given that most SaaS products are offered as a subscription, it is vital to understand this concept clearly as it can often be the difference between having a highly profitable and an easy-to-manage product, and a failed product or venture.

Multi-tenancy is a principle in software architecture where a single instance of the software serves multiple tenants or customers. The realization of this concept in software design is probably one of more complex tasks in implementing and operating a cloud-based product.

Let's start by examining three basic models of a multi-tenant application. The following figure illustrates these models:

![m2.JPG](https://cdn.hashnode.com/res/hashnode/image/upload/v1644593350075/ynMqwt63Q.jpeg)

In the first model, (A) Shared Nothing architecture, each customer has a separate copy of the application and the database for their exclusive use. In some cases, the hardware infrastructure is also separated out for each customer. Large enterprises may insist on this separation mainly due to security concerns but also due to service-level concerns associated with resource sharing. This is essentially application hosting rather than application multi-tenancy.

The second model, (B) Shared Application architecture, shares the same application instance but the data is separated for each customer. 

And in the third model, (C) Shared Everything architecture, both the application and the database instances are shared resources among all the customers.

In real life, it is fairly common for customers to request a dedicated application and infrastructure stack. Most smaller companies and start-ups give in under pressure, especially if it is a major customer. However, this can be a very expensive option to sustain over a period of time. Before you know it, you are maintaining several different versions of the application and technology stacks, multiple database schema, operational and support-related overheads across a set of customers. This makes application maintenance, QA/testing effort, upgrades/releases, and customer support impossibly complex or expensive or both. You are no longer an SaaS application provider!

It is very common and reasonable to expect a majority of customers to request that their data be kept separated from other customers. It is also common for smaller businesses and price-sensitive customers to not care how and where you store their data, as long as they are satisfied by the security measures you have implemented. In all cases, it is imperative to use encryption for the securing of sensitive data-at-rest.

Hence, in reality you end up with a mix of models where the concern is more focused on data security rather than shared infrastructure or application code (as long as you can provide a certain level of application customizability per customer and meet their service-level requirements).

In this scenario, apart from security considerations some of the challenges that arise are listed as follows: 

- Increased costs of development: Isolating each customer's data in a separate database is easier and faster to build, while using a shared approach requires a larger development effort and initial costs, but can result in being able to serve more tenants per server at a lower overall operational cost.

- Isolating each tenant's database can give you more flexibility in handling each customer's individual requirements (but there could be severe complications when you release product upgrades, especially if your database schema is not designed to handle such changes).

- Regulatory considerations can directly impact your design and leave you with no choice in terms of using a shared approach.

- Backups and restores are simpler operations in the case of isolated databases. In the shared database approach, the impact of servicing a particular tenant's backup or restore request will impact other active customers. 

These kinds of issues can lead to SLA-related issues and other management overheads related to explaining and issuing appropriate communications to all other customers, and so on. 

Normally, businesses charge their customers differently based on whether a customer requests a separate database instance, or a fully segregated infrastructure for their exclusive use only. Suppose you have grouped your customers into three categories such as Platinum, Gold, and Silver. Your Platinum class customers are your biggest and the best. They are willing to pay a premium for additional features and/or better service levels. Let's say, you decide to provision separate infrastructure and database instances, for such customers. 

Simultaneously, you decide to share the infrastructure and use a single database instance for all your regular, or Silver class, customers. Imagine the operational complexity of a situation where one of your Platinum class customers (Shared Nothing) wants to downgrade their subscription level to the Silver class (Shared Everything) the following year!

><div class="csl-entry">Sarkar, A. and Shah, A. (2018) <i>Learning AWS.</i> 2nd edn. Packt Publishing. Available at: https://www.perlego.com/book/578848/learning-aws-pdf (Accessed: 25 September 2021).</div>