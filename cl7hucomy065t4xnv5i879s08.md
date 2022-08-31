## AWS announces open-sourced credentials-fetcher to simplify Microsoft AD access from Linux containers

AWS announces the general availability of the credentials-fetcher open source project. As you modernize your .NET applications to Linux containers, you no longer need to worry about Microsoft Active Directory (AD) dependency. You can use credentials-fetcher to access AD from services hosted on Linux containers using the service account authentication model. This package makes it possible to create kerberos tickets specific to group managed service accounts (gMSAs) in applications running on Linux containers. As part of our launch, we have packaged credential-fetcher in RPM format and added it to Fedora Linux. You can install this package by using dnf install credentials-fetcher.

A group managed service account is a managed account that provides automatic password management, service principal name (SPN) management, and the ability to delegate management to administrators over multiple servers or instances. Through this release, credential-fetcher unblocks a range of modernization use cases around identity management using Microsoft AD.

To contribute to this open-source project visit the project [GitHub repository](https://github.com/aws/credentials-fetcher).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/aws-open-sourced-credentials-fetcher-simplify-microsoft-ad-access-linux-containers/