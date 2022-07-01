## Amazon EC2 placement groups now support host-level spread on AWS Outposts rack

Now, you can use [Amazon EC2 placement groups](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html) to spread instances across distinct hosts on an [AWS Outposts rack](https://aws.amazon.com/outposts/rack/). Host-level spread placement groups distribute instances across hosts to reduce the likelihood of correlated failures, benefiting workloads that require High Availability (HA) like mission-critical databases.

AWS Outposts rack, a part of the [AWS Outposts family](https://aws.amazon.com/outposts/), is a fully managed service that offers the same AWS infrastructure, AWS services, APIs, and tools to virtually any on-premises datacenter or co-location space for a truly consistent hybrid experience. When you create a spread placement group that will be used in an Outpost, you can set an optional Spread Level parameter to “rack” or “host”, which determines how instances are distributed across the underlying hardware. If no Spread Level is defined, “rack” is selected by default. Spreading instances across distinct hosts is useful in Outposts environments when you want to protect against host failures that can occur within a rack. The number of instances you can launch into a host-level spread placement group is limited only by the number of hosts available in your Outpost.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

Host-level spread placement groups are available to all Outposts customers at no additional cost in all AWS Regions where Outposts rack is supported. To learn more about AWS Outposts, visit the [Outposts rack product page](https://aws.amazon.com/outposts/rack/). To learn more about EC2 placement groups on Outposts, visit the Outposts user guide.

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/amazon-ec2-placement-groups-support-host-level-spread-aws-outposts-rack/