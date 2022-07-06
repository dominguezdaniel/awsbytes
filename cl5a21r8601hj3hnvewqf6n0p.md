## Announcing quota management for Amazon Location Service

[Amazon Location Service](https://aws.amazon.com/location/) now supports quota management. Developers can create Amazon CloudWatch alarms that notify them when their usage of any API is close to their quota limit for that API. These alarms help developers ensure operational continuity, prevent service throttling, and protect from unintentional spend. Additionally, developers can use AWS Service Quotas to view, manage, and request quota increases, all in one user interface. For example, an eCommerce website can create a CloudWatch alarm to get notified when they have reached 80% usage on each of the Amazon Location APIs. When the alarm is [initiated](https://docs.aws.amazon.com/location/latest/developerguide/best-practices.html#quota-best-practice), they can request a quota increase to help scale their workloads, prevent their website from experiencing outages, and prevent a poor customer shopping experience.

Amazon Location Service is a location-based service that helps developers easily and securely add maps, points of interest, geocoding, routing, tracking, and geofencing to their applications without compromising on data quality, user privacy, or cost. With Amazon Location Service, you retain control of your location data, protecting your privacy and reducing enterprise security risks. Amazon Location Service provides a consistent API across high-quality location based service data providers (Esri and HERE), all managed through one AWS console.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5m15zsqp4eb1szj9b681.png)](https://k21technologies.samcart.com/referral/gBBzLUFj/wZNqvQpM5mBn2g53)

Amazon Location Service is available in the following AWS Regions: US East (Ohio), US East (N. Virginia), US West (Oregon), Europe (Frankfurt), Europe (Ireland), Europe (Stockholm), Asia Pacific (Singapore), Asia Pacific (Sydney) Region, and Asia Pacific (Tokyo).

To learn more, visit to the [Amazon Location Service Best Practices](https://docs.aws.amazon.com/location/latest/developerguide/best-practices.html#quota-best-practice) page.

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-location-service-quota-management/