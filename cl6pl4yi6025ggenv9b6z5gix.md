## Amazon Cognito enables native support for AWS WAF

You can now enable AWS WAF protections for Amazon Cognito, making it even easier to protect Amazon Cognito user pools and hosted UI from common web exploits. 

[Amazon Cognito](https://aws.amazon.com/cognito/) is a service that makes it easy to add authentication, authorization, and user management to your web and mobile apps. Amazon Cognito provides authentication for applications with millions of users and supports sign-in with social identity providers such as Apple, Facebook, Google, and Amazon, and enterprise identity providers via standards such as SAML 2.0 and OpenID Connect.

[AWS WAF](https://aws.amazon.com/waf/) is a web application firewall that helps to protect your web applications from common web exploits and malicious bots that could affect application availability, compromise security, or consume excessive resources. AWS WAF gives you control over which traffic to allow or block to your web applications by defining customizable web security rules.

Amazon Cognito provides built-in protection for securing your public-facing applications such as a compromised credentials check and adaptive authentication. For additional protection, you can now use AWS WAF to protect Amazon Cognito user pools from web-based attacks and unwanted bots. Amazon Cognito’s integration with AWS WAF enables you to define rules that enforce rate limits, gain visibility into the web traffic to your applications, and allow or block traffic to Cognito user pools based on business or security requirements, and optimize costs by controlling bot traffic.
Support for AWS WAF on Amazon Cognito is available in all AWS Regions globally where Amazon Cognito user pools are available. To learn more, see Using [AWS WAF to protect Amazon Cognito User Pools](https://docs.aws.amazon.com/cognito/latest/developerguide/user-pool-waf.html), and to get started, visit the [Amazon Cognito console](https://console.aws.amazon.com/cognito/home).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/amazon-cognito-enables-native-support-aws-waf/