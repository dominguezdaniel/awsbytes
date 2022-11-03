# AWS Copilot adds support for AWS App Runner’s privately accessible services and more

AWS announced the general availability of AWS Copilot version 1.23 with support for AWS App Runner private services. App Runner makes it easier for developers to quickly deploy containerized web applications and APIs to the cloud, at scale, and without having to manage infrastructure. By default, App Runner services are accessible publicly over the internet. Now, with private services you can restrict network access to your internal websites, APIs, and applications to originate from within your Amazon VPC.

With AWS Copilot, you can quickly get started and deploy to Amazon ECS or AWS App Runner with a single command and a Dockerfile. Copilot provides a developer-focused interface and workflows, where users can focus on application architecture by choosing common application and services patterns. Copilot provisions and keeps up to date the necessary AWS infrastructure in your account, using the best-practices and infrastructure-as-code artifacts. Now, you have the option of toggling the request-driven Copilot services, powered by App Runner, to be private. Simply specify http.private: true in the Copilot service manifest and run copilot deploy command. Copilot will take care of configuring AWS App Runner services to accept traffic only from within Amazon VPC provisioned for your Copilot environment.

In addition, the new release adds support for Amazon Aurora Serverless v2 and makes it easier to enable Amazon VPC flow logs to monitor the network. For the full list of features in the new release see the [release notes](https://github.com/aws/copilot-cli/releases).

Download the new AWS Copilot v1.23 release [directly from our GitHub](https://github.com/aws/copilot-cli/releases) page or follow a [Getting Started Guide](https://aws.amazon.com/containers/copilot/).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/11/aws-copilot-aws-app-runners-privately-services/