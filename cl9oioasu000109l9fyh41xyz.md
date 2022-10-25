# CDK For Kubernetes (CDK8s) announces general availability of CDK8s+ and manifest validation support

CDK For Kubernetes Plus (CDK8s+) is a multi-language class library for defining Kubernetes applications using high level intent based constructs. Customers defining Kubernetes application indicate that maintainability of Kubernetes manifests is challenging; CDK8s+ aims to lower the entry barrier and improve maintainability of Kubernetes manifests by offering a hand crafted construct for each core Kubernetes object, exposing a richer API with reduced complexity. With this launch, CDK8s+ is now generally available and stable for use. This means that the API will remain unchanged and fully supported (no breaking changes), at least until the next major version. CDK8s+ is vended as a separate library for each Kubernetes spec version, all those libraries are now generally available and stable to use.

Customers also want to validate their manifest by applying either community or organizational policies. CDK8s now supports integration with third-party tools that facilitate this, and can perform validation as part of the synthesis process. This supports manifests produced by CDK8s adhering to the necessary policies.

For more information, read our [announcement blog](announcement blog) or visit [cdk8s.io](https://cdk8s.io/).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/10/cdk-kubernetes-cdk8s-availability-manifest-validation-support/