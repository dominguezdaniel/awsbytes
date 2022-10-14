# AWS SAM CLI Pipelines now supports Open ID Connect Protocol

The [AWS Serverless Application Model (SAM)](https://aws.amazon.com/serverless/sam/) Command Line Interface (CLI) announces general availability of Open ID Connect (OIDC) support in SAM CLI Pipelines. The AWS SAM CLI is a developer tool that makes it easier to build, test, package, and deploy serverless applications. SAM Pipelines make it easier to create continuous integration and deployment (CI/CD) pipelines for serverless applications with Jenkins, GitLab, GitHub Actions, Atlassian Bitbucket Pipelines, and AWS CodePipeline. SAM Pipelines comes pre-packaged with a set of default pipeline templates for all supported systems that showcase AWS best practices for secure, multi-account, and multi-region deployments.

With this launch, SAM Pipelines can be configured to support OIDC authentication from providers supporting OIDC, such as GitHub Actions, GitLab and BitBucket. SAM Pipelines will use the OIDC tokens to configure the AWS Identity and Access Management (IAM) identity providers, simplifying the setup process.

To learn more about this feature, please see the documentation. To get started, you can install the SAM CLI by following the instructions in the [documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-sam-cli-pipelines-open-id-connect-protocol/