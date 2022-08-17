## Amazon EKS announces cluster-level cost allocation tagging

Amazon Elastic Kubernetes Service (EKS) now makes it easier for customers to understand how their Amazon EC2 costs are driven by individual EKS clusters. Customers who choose to use multiple EKS clusters to segment their workloads to improve their resilience and/or security posture now get breakdowns of their EC2 costs by EKS cluster using AWS Cost and Usage reporting with minimal additional effort.

With this launch, all EC2 instances which join an EKS cluster are automatically tagged with an [AWS-generated cost allocation tag](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/aws-tags.html). Any EC2 instance used in an EKS cluster will be tagged automatically without any additional action required, regardless of whether they are provisioned using EKS managed node groups, Karpenter, or directly via EC2. This tag can be used to allocate EC2 costs to individual EKS clusters through AWS Billing and Cost Management so that they can be easily incorporated into existing finance workflows that leverage these common AWS tools.

See the [Tagging your Amazon EKS resources](https://docs.aws.amazon.com/eks/latest/userguide/eks-using-tags.html) page in the Amazon EKS documentation for more details. To learn more about Amazon EKS, visit our [product page](https://aws.amazon.com/eks/).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/amazon-eks-cluster-level-cost-allocation-tagging/