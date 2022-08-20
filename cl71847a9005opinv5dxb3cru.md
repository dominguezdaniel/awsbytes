## Amazon DynamoDB now supports bulk imports from Amazon S3 to new DynamoDB tables

Amazon DynamoDB now makes it easier for you to migrate and load data into new DynamoDB tables by supporting bulk data imports from Amazon S3. Now, you can import data directly into new tables to help you migrate data from other systems, load test data to help you build new applications, facilitate data sharing between tables and accounts, and simplify your disaster recovery and business continuity plans.

The new DynamoDB import from S3 feature simplifies the import process so you do not have to develop custom solutions or manage instances to perform imports. DynamoDB bulk import also does not consume your table’s write capacity so you do not need to plan for additional capacity during the import process. Bulk import supports CSV, DynamoDB JSON and Amazon Ion as input formats. Combined with the DynamoDB to Amazon S3 export feature, you can now more easily move, transform, and copy your DynamoDB tables from one application, account, or region to another. You can get started with DynamoDB import with just a few clicks in the AWS Management Console or API calls.

Pricing for DynamoDB import is based on the uncompressed file size in Amazon S3. For information about pricing, see [Amazon DynamoDB pricing](https://aws.amazon.com/dynamodb/pricing/).

To learn more about data import, see [Import from S3](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/S3DataImport.HowItWorks.html) documentation and [Amazon DynamoDB can now import Amazon S3 data into a new table](https://aws.amazon.com/blogs/database/amazon-dynamodb-can-now-import-amazon-s3-data-into-a-new-table/) blog post.

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/08/amazon-dynamodb-supports-bulk-imports-amazon-s3-new-dynamodb-tables/