## Amazon EventBridge now supports receiving events from GitHub, Stripe and Twilio using Webhooks

Amazon EventBridge now supports integrations with GitHub, Stripe, and Twilio via webhooks using Quicks Starts. You can subscribe to events from these SaaS applications and receive them on an Amazon EventBridge event bus for further processing. With Quick Starts, you can use AWS CloudFormation templates to create HTTP endpoints for your event bus that are configured with security best practices for GitHub, Stripe, and Twilio. You can configure your GitHub, Stripe, and Twilio webhooks from the respective accounts; simply select the types of events you want to send to the newly generated endpoint and begin securely receiving events on your event bus.

EventBridge is a serverless event bus that enables you to build scalable event-driven applications by routing events between your own applications, third-party SaaS applications, and other AWS services. You can set up routing rules on an event bus to determine where to send your data, allowing downstream applications to react to relevant changes in your applications as they occur. Amazon EventBridge can make it easier to build event-driven applications by facilitating event ingestion, delivery, security, authorization, and error handling.

You can get started by navigating to the ‘Developer Resources’ section of the AWS Management Console under a new ‘Quick starts’ menu item. Quick Starts are automated deployments intended for developers who want to quickly set up a trial or production environment according to AWS best practices and start using EventBridge functionality within minutes. The Quick Starts for GitHub, Stripe and Twilio integration using webhooks have their own section titled ‘Inbound webhooks using Lambda Function URLs’.

Quick Starts are available in the following regions: US East (Ohio and N.Virginia), US West (Oregon and N.California), Canada (Central), Europe(Stockholm, Ireland, Frankfurt, London and Milan), Asia Pacific (Mumbai, Tokyo, Seoul, Singapore, Hong Kong, Osaka and Jakarta), Middle East (Bahrain) and South America (São Paulo). 

To get started, use the following resources:

[AWS Management Console](https://console.aws.amazon.com/events/home)

[Receiving events from a SaaS partner with Amazon EventBridge](Receiving events from a SaaS partner with Amazon EventBridge)

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/amazon-eventbridge-supports-receiving-events-github-stripe-twilio-using-webhooks/