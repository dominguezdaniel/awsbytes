## AWS Config now supports 20 new resource types

AWS Config now supports 20 new resource types including Amazon SageMaker, Amazon Route 53, Amazon Elastic Kubernetes Service (Amazon EKS), AWS Global Accelerator, AWS Glue, and others. For the full list of newly supported resource types see [1].

With this launch, you can now use AWS Config to monitor configuration data for the newly supported resource types in your AWS account. AWS Config provides a detailed view of the configuration of AWS resources in your AWS account, including how resources were configured and how the configuration changes over time.

Get started by enabling AWS Config in your account using the AWS Config console or the AWS Command Line Interface (AWS CLI). Select the newly supported resource types for which you want to track configuration changes. If you previously configured AWS Config to record all resource types, then the new resources will be automatically recorded in your account. AWS Config support for the new resources is available to AWS Config customers in all regions where the underlying resource type is available. To view a complete list of all supported types, see supported resource types page.

[1] Newly supported resource types:

1. AWS::EC2::TransitGatewayRouteTable
2. AWS::EC2::TransitGatewayAttachment
3. AWS::KMS::Alias
4. AWS::GlobalAccelerator::Listener
5. AWS::GlobalAccelerator::EndpointGroup
6. AWS::GlobalAccelerator::Accelerator
7. AWS::SageMaker::NotebookInstance
8. AWS::SageMaker::NotebookInstanceLifecycleConfig
9. AWS::SageMaker::EndpointConfig
10. AWS::Glue::Job
11. AWS::DMS::ReplicationInstance
12. AWS::DMS::ReplicationTask
13. AWS::DMS::Certificate
14. AWS::Athena::WorkGroup
15. AWS::Athena::DataCatalog
16. AWS::Detective::Graph
17. AWS::SES::ConfigurationSet
18. AWS::EKS::FargateProfile
19. AWS::Route53::HostedZone
20. AWS::Route53::HealthCheck

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/08/aws-config-supports-20-new-resource-types/