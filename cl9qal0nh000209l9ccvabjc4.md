# Introducing AWS Toolkit for .NET Refactoring, a new Visual Studio extension

The AWS Toolkit for .NET Refactoring is a new extension for Microsoft Visual Studio 2019 and Microsoft Visual Studio 2022. The extension helps transform your legacy .NET Framework applications to a modern, cloud-optimized architecture letting you fully leverage the benefits of reduced cost, increased up time, and improved scalability. It extends the functionality of Porting Assistant for .NET with new features, such as testing on AWS environments directly from Visual Studio IDE.
The AWS Toolkit for .NET Refactoring accelerates legacy .NET application transformation through the following capabilities:

Compatibility Assessment

The AWS Toolkit for .NET Refactoring extension scans your legacy .NET Framework application to identify Windows dependencies and API and package incompatibilities with newer, cross-platform .NET versions (.NET Core 3.1, .NET 5, .NET 6).

Porting Assistance

Where possible, the AWS Toolkit for .NET Refactoring extension kickstarts code modifications by making changes to project reference files and web.config files (Internet Information Services (IIS) and Active Directory (AD)) for cross-platform .NET and Linux compatibility.

Application validation on AWS

The AWS Toolkit for .NET Refactoring extension enables you to validate refactoring code changes by deploying to AWS directly from Visual Studio. The toolkit generates the required containerization artifacts to help you test your ported code on Amazon Elastic Container Service (ECS) via AWS Fargate through an endpoint URL, without leaving the Visual Studio IDE.

The AWS Toolkit for .NET Refactoring is available as an extension for [Visual Studio 2019](https://marketplace.visualstudio.com/items?itemName=AWSTR.refactoringtoolkit2019) and [Visual Studio 2022](https://marketplace.visualstudio.com/items?itemName=AWSTR.refactoringtoolkit2022). To learn more, please visit our [documentation](https://docs.aws.amazon.com/tk-dotnet-refactoring/latest/userguide/what-is-tk-dotnet-refactoring.html) and [blog](https://aws.amazon.com/blogs/modernizing-with-aws/aws-toolkit-for-net-refactoring-launch/). The extension is also available as part of license included Visual Studio Amazon Machine Images (AMIs) on Amazon EC2.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-toolkit-net-refactoring-visual-studio-extension/