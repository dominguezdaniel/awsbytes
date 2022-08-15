## AWS IoT SiteWise now supports bulk import of historical measurement data

AWS IoT SiteWise now supports bulk import of historical measurements from sensors with the launch of three new APIs. The new bulk import APIs help customers to ingest historical data from their operations stored in diverse systems such as historians and time series databases in AWS IoT SiteWise.

With the bulk import APIs, industrial customers can perform file-based bulk data ingestion in order to ensure all their historical data for their assets is available in AWS IoT SiteWise. Once their data is in AWS IoT SiteWise customers can visualize it from applications such as AWS IoT SiteWise Monitor, Grafana, or retrieve it using AWS IoT SiteWise APIs to be consumed by other analytical applications. 

To start a bulk import, customers will upload to Amazon S3 a CSV file with their historical data organized in a predefined format. Once the CSV file is uploaded, customers can start the asynchronous import using the CreateBulkImportJob API. Customers can monitor the progress of their job by using the DescribeBulkImportJob, and ListBulkImportJob APIs.

For more information visit the documentation for [CreateBulkImportJob](https://docs.aws.amazon.com/iot-sitewise/latest/APIReference/API_CreateBulkImportJob.html), [DescribeBulkImportJob](https://docs.aws.amazon.com/iot-sitewise/latest/APIReference/API_DescribeBulkImportJob.html), and [ListBulkImportJob](https://docs.aws.amazon.com/iot-sitewise/latest/APIReference/API_ListBulkImportJobs.html). 

AWS IoT SiteWise is a managed service that enables customers to collect, store, organize and monitor data from industrial equipment at scale. To learn more, please visit the [AWS IoT SiteWise website](https://aws.amazon.com/iot-sitewise/) or the [developer guide](https://docs.aws.amazon.com/iot-sitewise/).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/08/aws-iot-sitewise-supports-bulk-import-historical-measurement-data/