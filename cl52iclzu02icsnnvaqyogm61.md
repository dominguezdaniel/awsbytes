## AWS SAM Accelerate is now generally available - quickly test code changes against the cloud

The [AWS Serverless Application Model (SAM)](https://aws.amazon.com/serverless/sam/) announces general availability of AWS SAM Accelerate. The AWS SAM Command Line Interface (CLI) is a developer tool that makes it easier to build, locally test, package, and deploy serverless applications. AWS SAM Accelerate is a new capability of AWS SAM CLI that makes it easier for developers to test code changes against a cloud-based environment, reducing the time from local iteration to production-readiness.

AWS SAM Accelerate allows developers to bring their rapid iteration workflows to serverless application development, achieving the same levels of productivity they're used to when testing locally, while testing against a realistic application environment in the cloud. AWS SAM Accelerate synchronizes infrastructure and code changes on a developer's local workspace with a cloud environment in near real time: code changes are updated in seconds in AWS Lambda; API definition changes in Amazon API Gateway; state machine updates to AWS Step Functions; and infrastructure changes are deployed via infrastructure-as-code tooling such as CloudFormation. AWS SAM Accelerate also supports synchronizing resources defined in CloudFormation Nested Stacks.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/5m15zsqp4eb1szj9b681.png)](https://k21technologies.samcart.com/referral/gBBzLUFj/wZNqvQpM5mBn2g53)

To learn more about SAM Accelerate, please read details in the [documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/accelerate.html). To get started, you can install the SAM CLI by following the instructions in the [documentation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/aws-sam-accelerate-test-code-against-cloud/