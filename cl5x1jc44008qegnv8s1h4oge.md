## AWS Lambda announces support for a new IAM condition key, lambda:SourceFunctionArn

AWS Lambda announces support for lambda:SourceFunctionArn. A new IAM condition key that can be used for IAM policy conditions that specify the ARN of the function from which a request is made. Starting today, when a function is invoked, Lambda will automatically add the new lambda:SourceFunctionArn condition key to the request context of all AWS API calls made by function code. You can use the Condition element in your IAM policy to compare the lambda:SourceFunctionArn condition key in the request context with values that you specify in your policy.

This capability allows you to implement advanced security controls for the AWS API calls taken by your Lambda function code. For example, you can write conditional policies using the new lambda:SourceFunctionArn together with existing condition keys such as aws:SourceIP or aws:SourceVPC to grant permissions to AWS API calls only if those originate from inside the customer’s VPC.

This feature is available in all public [AWS Regions](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/), Amazon Web Services China (Beijing) Region, operated by Sinnet and Amazon Web Services China (Ningxia) Region, operated by NWCD. To learn more about this feature, please refer to the Lambda [Developer Guide](https://docs.aws.amazon.com/lambda/latest/dg/lambda-intro-execution-role.html#permissions-executionrole-source-function-arn).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/aws-lambda-iam-condition-key-lambda-source-function-arn/