## Amazon SageMaker Data Wrangler launches new advanced settings for Amazon Athena data sources

[Amazon SageMaker Data Wrangler](https://aws.amazon.com/sagemaker/data-wrangler/) reduces the time that it takes to aggregate and prepare data for machine learning (ML) from weeks to minutes in Amazon SageMaker Studio, the first fully integrated development environment (IDE) for ML. With SageMaker Data Wrangler, you can simplify the process of data preparation and feature engineering, and complete each step of the data preparation workflow, including data selection, cleansing, exploration, and visualization, from a single visual interface. You can import data from multiple data sources such as Amazon Simple Storage Service (Amazon S3), Amazon Redshift, Snowflake, and [26 Federated Query data sources](https://docs.aws.amazon.com/athena/latest/ug/athena-prebuilt-data-connectors.html) supported by Amazon Athena. Starting today, customers importing data from Athena data sources can configure S3 query output location and data retention period to control where and how long Athena stores the intermediary data.

[Amazon Athena](https://aws.amazon.com/athena/) is an interactive query service that makes it easy to browse Glue Data Catalog, and analyze data directly in Amazon S3 and [26 Federated Query data sources](https://docs.aws.amazon.com/athena/latest/ug/athena-prebuilt-data-connectors.html) using standard SQL. Data Wrangler supports Athena workgroup to provide a custom S3 query output location. Starting today, you can specify a custom S3 location for Athena query outputs or continue to use the existing default bucket in Data Wrangler. You now have a default data retention period of 5 days for the Athena query output to control storage cost. You can change this data retention period to match your need and your organization’s data security guideline. Once you import the data through Athena, you can use Data Wrangler visual interface to join data from multiple sources, explore and analyze your data with [Data Quality and Insights report](https://docs.aws.amazon.com/sagemaker/latest/dg/data-wrangler-data-insights.html) and other built-in visualizations to identify potential errors and extreme values. You can quickly cleanse your data and engineer features with 300+ built-in data transformations. You can create a job to process a larger dataset, or kick off a SageMaker Autopilot training job directly from Data Wrangler to automatically find the best model for your business problem using the prepared data.

These features are generally available in the all the AWS Regions that Data Wrangler currently support at no additional charge. To get started with SageMaker Data Wrangler, visit the [blog](https://aws.amazon.com/blogs/machine-learning/configure-a-custom-amazon-s3-query-output-location-and-data-retention-policy-for-amazon-athena-data-sources-in-amazon-sagemaker-data-wrangler/) and the [AWS documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/data-wrangler.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/09/amazon-sagemaker-data-wrangle-launches-advanced-settings-amazon-athena-data-sources/