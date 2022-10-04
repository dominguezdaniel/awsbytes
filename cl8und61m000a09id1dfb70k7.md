## AWS IoT SiteWise increasing quota limit for Assets and Asset Models

AWS IoT SiteWise has increased quota limits for Assets and Asset Models to support larger and more complex equipment representations, and allow customers to perform bulk operations on resources.

The increase in asset model limits enables customers to create larger and more complex Asset and Asset Model hierarchies without requesting a limit increase.

The following quotas were increased: number of parent asset models per child asset model, number of child assets per parent asset, number of asset models per hierarchy tree, number of asset models, number of asset model hierarchy definitions per asset model and depth of asset model hierarchy tree. Additionally, we removed the quota limit for number of parent asset models per child asset model. For example, in the past a customer who needed to create more than 200 properties per asset model would have been required to request a quota limit increase. With the new changes customers can create up to 500 properties per asset model without requesting a limit increase.

The AWS IoT SiteWise quota increase on Asset Model APIs also enables developers who require higher rates to perform bulk operations on asset models, assets, and asset hierarchies. For example, previously, an application developer was able to retrieve information from 30 assets in 1 second with the DescribeAsset API. Now, the developer can retrieve information from 100 assets in 1 second.

For more details on the new quota limits for Asset Models refer to [AWS IoT SiteWise quotas](https://docs.aws.amazon.com/iot-sitewise/latest/userguide/quotas.html).

AWS IoT SiteWise is a managed service to collect, store, organize and monitor data from industrial equipment at scale. To learn more, please visit the [AWS IoT SiteWise website](https://aws.amazon.com/iot-sitewise/) or the [developer guide](https://docs.aws.amazon.com/iot-sitewise/).

> Source: 