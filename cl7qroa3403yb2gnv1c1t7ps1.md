## Easily process your data while using Amazon Lookout for metrics

AWS announces that you can now filter your data by its dimensions while using [Amazon Lookout for Metrics](https://aws.amazon.com/lookout-for-metrics/). Amazon Lookout for Metrics uses machine learning (ML) to automatically monitor the metrics that are most important to businesses with greater speed and accuracy than traditional methods used for anomaly detection. The service also makes it easier to diagnose the root cause of anomalies like unexpected dips in revenue, high rates of abandoned shopping carts, spikes in payment transaction failures, increases in new user sign-ups, and many more.

With this launch you can now filter your data based on dimension values, giving you the ability to do data processing from within the AWS console or using the API. Additionally, filtering dimension values can reduce training time, and also decrease costs compared to processing all dimension values within your data.

Dimensions are categorical fields that create subgroups of measures based on their value. Previously, setting up your dataset with dimensions meant that we would use all of your data and segment it with each dimension value. Now, by enabling filters on dimensions, you can choose the specific labels you would want us to perform anomaly detection on. For example, if your dataset contained sales data with a column indicating which country each data point came from, you can now select a subset of countries that are more important to you without having to pre-process your data.

To learn more about this capability, see our [documentation page](https://docs.aws.amazon.com/lookoutmetrics/latest/dev/detectors-filters.html). You can use this capability in all Regions where Amazon Lookout for Metrics is publicly available. For more information about Region availability, see [AWS Regional Services](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/amazon-lookout-metrics-easily-process-data/