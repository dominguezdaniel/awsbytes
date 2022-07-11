## Amazon CloudFront supports header names of up to 1024 characters in CloudFront policies

Amazon CloudFront now supports a maximum of 1024 characters across all header names in cache, origin request, and origin response policies. With 1024 characters, customers now have 512 extra characters to add header metadata to their policies.

A CloudFront policy allows customers to apply the same specific combination of settings across many distribution behaviors. Previously, customers could add a maximum of 512 characters as the CloudFront or custom header names in a policy. With the increased character limit, customers can now, for example, add additional headers to a cache policy to configure a more granular cache key, or customers can leverage additional headers as inputs to implement user authentication. All the headers are available to use in Lambda@Edge, CloudFront Functions, or application logic at the Origin.

The increased length of all header names is available for immediate use worldwide. There is no additional fee for using this feature, and customers can continue configuring headers in policies using the CloudFront Console, APIs, SDK, and CLI. For more information, refer to the [CloudFront Developer Guide](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/working-with-policies.html) and [API documentation](https://docs.aws.amazon.com/cloudfront/latest/APIReference/Welcome.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-cloudfront-header-names-1024-characters-cloudfront-policies/