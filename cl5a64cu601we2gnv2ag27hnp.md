## Amazon SageMaker Feature Store now supports feature metadata and search

[Amazon SageMaker Feature Store](https://aws.amazon.com/sagemaker/feature-store/) is a fully managed, purpose-built repository to store, update, search, and share machine learning (ML) features. The service provides feature management capabilities such as enabling easy feature reuse, low latency serving, time travel, and ensuring consistency between features used in training and inference workflows. A feature group is a logical grouping of ML features whose organization and structure is defined by a feature group schema. Until today, customers could add metadata tags only to feature groups which in turn enabled easy search and discovery of a feature group. To search for a specific feature however was more complicated. Customers needed to know which feature group the feature belongs and then scan for the relevant feature in the feature group, leading to additional overhead while searching for features.

Amazon SageMaker Feature Store is announcing the ability to add custom metadata at a feature level and the ability to directly search for features in addition to feature groups. The custom metadata fields include description and parameters to help make features discoverable. You can use the UpdateFeatureMetadata API to add or update metadata for a feature, and use the DescribeFeatureMetadata API to view all metadata for a feature. You can also update and view feature metadata in SageMaker [Studio](https://aws.amazon.com/sagemaker/studio/), an integrated development environment for ML.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5m15zsqp4eb1szj9b681.png)](https://k21technologies.samcart.com/referral/gBBzLUFj/wZNqvQpM5mBn2g53)

Using either the Feature Store user interface in SageMaker Studio or the Search API, you can search for features across feature groups within the same AWS account, and discover features relevant for your use case by performing a text based search of the feature metadata attributes.

To learn more, please view the documentation [here](https://docs.aws.amazon.com/sagemaker/latest/dg/feature-store-search-metadata.html). To get started, log into the [Amazon SageMaker console](https://console.aws.amazon.com/sagemaker/home).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-sagemaker-feature-supports-metadata-search/