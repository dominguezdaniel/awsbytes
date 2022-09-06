## Amazon DynamoDB now supports up to 100 actions per transaction

[Amazon DynamoDB transactions](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/transaction-apis.html) enable coordinated, all-or-nothing changes to multiple items both within and across tables. The maximum number of actions in a single transaction has now increased from 25 to 100.

The previous limit of 25 actions per transaction would sometimes require writing additional code to break the transaction into multiple parts. The new limit of 100 actions per transaction means you should encounter this limit far less frequently. See the [best practices for transactions](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/transaction-apis.html#transaction-best-practices) documentation for more information.

To learn more about DynamoDB transactions, see our [developer guide on working with transactions](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/transactions.html). 

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/amazon-dynamodb-supports-100-actions-per-transaction/