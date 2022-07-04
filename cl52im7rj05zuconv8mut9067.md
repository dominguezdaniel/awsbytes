## Amazon Connect Customer Profiles now provides confidence scores

[Amazon Connect Customer Profiles](https://aws.amazon.com/connect/customer-profiles/) now allows you to automatically merge duplicate customer records on confidence scores. Each time the identity resolution feature finds duplicate records, it provides a confidence score on a scale of zero to one to represent the accuracy of a match, where a score of one represents most accurate match and zero represents least accurate match. You can select a threshold anywhere between zero to one to automatically merge duplicate records into a unified customer profile.

When a customer contacts your customer service department, Customer Profiles provides your agents and interactive voice response (IVR) solutions with up to date information about the customer, enabling faster and more personalized customer service. Customer Profiles brings together customer information (e.g, address, purchase history, contact history) from multiple applications such as Salesforce, Amazon S3, and ServiceNow into a unified customer profile.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

With Amazon Connect Customer Profiles, you only pay for what you use based on the number of [customer profiles](https://aws.amazon.com/connect/pricing/). There are no required up-front payments, long-term commitments, or minimum monthly fees. To learn more, see the [API reference guide](https://docs.aws.amazon.com/customerprofiles/latest/APIReference/API_CreateDomain.html), help [documentation](https://docs.aws.amazon.com/connect/latest/adminguide/use-identity-resolution.html), visit our [webpage](https://aws.amazon.com/connect/customer-profiles/) or read the [blog post](https://aws.amazon.com/blogs/contact-center/how-to-consolidate-similar-profiles-using-amazon-connect-customer-profiles-identity-resolution/).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/06/amazon-connect-customer-profiles-confidence-scores-help-merge-duplicate-customer-records/