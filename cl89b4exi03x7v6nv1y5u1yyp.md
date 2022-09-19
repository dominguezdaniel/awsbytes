## Amazon SNS now supports message signatures based on SHA256 hashing

[Amazon Simple Notification Service (Amazon SNS)](https://aws.amazon.com/sns/) now supports message signature based on SHA256 hashing, which provides security improvements over SHA1. To choose the hashing algorithm, either SHA256 or SHA1, you can use the SetTopicAttributes API action. Amazon SNS signs the messages delivered from your topic, so that the subscribed HTTP endpoints can verify the authenticity of the messages.

Amazon SNS is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. The A2A pub/sub functionality provides topics for high-throughput, push-based, many-to-many messaging between distributed systems, micro-services, and event-driven serverless applications. The A2P functionality enables you to send messages to users at scale via SMS, mobile push, and email.

Amazon SNS supports both SHA256 and SHA1 in all public AWS Regions  and AWS GovCloud (US).

To get started, see the following resources:

[Sign Amazon SNS messages with SHA256 hashing for HTTP subscriptions](https://aws.amazon.com/blogs/security/sign-amazon-sns-messages-with-sha256-hashing-for-http-subscriptions/) blog post.

[Verifying the signatures of Amazon SNS messages](https://docs.aws.amazon.com/sns/latest/dg/sns-verify-signature-of-message.html) in the Amazon SNS Developer Guide.

[SetTopicAttributes](https://docs.aws.amazon.com/sns/latest/api/API_SetTopicAttributes.html) and [GetTopicAttributes](https://docs.aws.amazon.com/sns/latest/api/API_GetTopicAttributes.html) in the Amazon SNS API Reference.

[Amazon SNS message format](https://docs.aws.amazon.com/sns/latest/dg/sns-message-and-json-formats.html) in the Amazon SNS Developer Guide.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/09/amazon-sns-supports-message-signatures-based-sha256-hashing/