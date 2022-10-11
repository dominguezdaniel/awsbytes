# AWS announces AWS SAM serverless connectors

Serverless application developers can now use the new AWS::Serverless::Connector resource available in AWS Serverless Application Model (AWS SAM) to simplify granting the appropriate level of access to the resources in their application’s infrastructure. With AWS::Serverless::Connector resources, developers describe how data and events need to flow between two resources and the type of access required. AWS SAM will compose purpose-built AWS Identity and Access Management (AWS IAM) policies in order to facilitate the interaction defined by the developer in the connector resource.

By using the AWS::Serverless::Connector resource, serverless application developers can quickly compose or update well-scoped IAM policies to their application, speeding up application development while reducing the IAM expertise required. The AWS::Serverless::Connector resource will transform into purpose-built IAM policies, using Read or Write permissions specified by the developer to compose the IAM policies from pre-defined sets of policy actions. Customers can use their existing policy review processes by reviewing a AWS CloudFormation change set or processed CloudFormation template prior to deployment.

You can use the AWS::Serverless::Connector resource in your [Serverless Application Model (SAM)](https://aws.amazon.com/serverless/sam/) template or via the [AWS Serverless CloudFormation Transform].

To get started, please see [documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/managing-permissions-connectors.html) on creating a AWS::Serverless::Connector resource in your AWS SAM template.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-sam-serverless-connectors/