# Announcing certificate-based authentication for Amazon AppStream 2.0

Starting today, you can use certificate-based authentication with Amazon AppStream 2.0 fleets that are joined to Active Directory to remove the logon prompt for the domain password.

By using certificate-based authentication, you can rely on the security and logon experience features of your SAML 2.0 identity provider, such as passwordless authentication, to access AppStream 2.0 resources. Certificate-based authentication with AppStream 2.0 enables a single sign-on logon experience to access domain-joined desktop and application streaming sessions without separate password prompts for Active Directory.

AppStream 2.0 certificate-based authentication integrates with [AWS Private Certificate Authority (AWS Private CA)](https://aws.amazon.com/private-ca/) to automatically issue short-lived certificates when users sign in to their sessions. AWS Private CA is a highly available, pay-as-you-go private CA service without the upfront investment and ongoing maintenance costs of operating your own public key infrastructure (PKI) in the cloud. When you configure your private CA as a third-party root CA in Active Directory or as a subordinate to your Active Directory Certificate Services enterprise CA, AppStream 2.0 with AWS Private CA can enable rapid deployment of end user certificates to seamlessly authenticate users.

There are no additional AppStream 2.0 charges for using certificate-based authentication. AWS Private CA now offers separate pricing for short-lived certificate use cases, which can help lower the monthly cost of the CA and the price per certificate. See AWS Private CA Pricing for more information. Certificate-based authentication is available in all AWS Regions where AppStream 2.0 and AWS Private CA are offered. Learn more about how to get started with AppStream 2.0 certificate-based authentication by visiting the [AppStream 2.0 Administration Guide](https://docs.aws.amazon.com/appstream2/latest/developerguide/certificate-based-authentication.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/certificate-based-authentication-amazon-appstream-2-0/