## Scaling From One Million to Ten Million Users

As you approach a million users, you are going to have to implement further along the lines of what we have discussed so far including multi-AZ deployments, elastic load balancing between tiers, auto scaling, SOA, serving content smartly (S3, CloudFront), caching DB data, and moving state information off tiers that auto scale. As you grow your user base in the range of 5 to 10 million you will need to focus a lot more on the data tier. 

This would be the time to think about database federation, that is, splitting the DB into multiple DBs based on the function/purpose, sharding (splitting a dataset into multiple parts), and moving some of the functionalities to other types of specialized DBs (such as NoSQL and graph databases).

However, note that database federation will make it harder to do cross-functional queries and it will not help in situations where you have individual functions or tables that are huge. In some ways, database federation is essentially delaying sharding and/or a shift to using NoSQL databases. Sharding brings in horizontal scaling but makes it more complex at the application level. This approach essentially has no practical limit on scalability. 

Typically, the data is sharded by function or key space; and the strategy can be implemented with both RDBMS and NoSQL databases. However, shifting over to using NoSQL databases solves the scale problem in the longer term. By leveraging managed services like DynamoDB, the move to NoSQL databases can be a lot simpler than managing your own NoSQL database clusters.

Moving to beyond ten million users requires you to deeply analyze your entire stack, and possibly look at custom solutions to solve your scalability issues. You should explore more fine-tuning of your application, move to services architecture for most of the features/functionalities, move from multi-AZ to a multi-region deployment, and look for opportunities to leverage AWS ECS and AWS Lambda services wherever you can.

><div class="csl-entry">Sarkar, A. and Shah, A. (2018) <i>Learning AWS.</i> 2nd edn. Packt Publishing. Available at: https://www.perlego.com/book/578848/learning-aws-pdf (Accessed: 25 September 2021).</div>