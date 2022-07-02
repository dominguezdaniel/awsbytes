## Amazon WorkMail now supports invoking Lambdas to fetch availability (free/busy)

Amazon WorkMail now supports invoking AWS Lambda for user availability, through Custom Availability Provider Lambdas (CAP Lambdas). CAP Lambdas are a new way for WorkMail to get availability information from external availability sources. A customer can use these CAP Lambdas to give WorkMail access to availability information for users on other calendaring providers they own, even if their endpoints are private, or if they do not have an Exchange Web Services (EWS) endpoint.

Users can schedule meetings and see other users’ availability through clients like Outlook. When a customer uses WorkMail alongside other calendaring solutions, WorkMail users could only fetch availability information from users on that calendaring solution if they support a public EWS endpoint.

With the support for CAP Lambdas, it is now possible to fetch availability from any service providing calendar availability. Administrators can configure for which email address domains a CAP Lambda will be invoked. The Lambda is called by WorkMail to retrieve the availability information, and WorkMail returns the result completely transparently to the user.

CAP Lambdas also give the administrator greater security controls when they do not want to expose the endpoints of their other calendaring solutions to the public. By provisioning a CAP Lambda function in a customer-owned virtual private cloud (VPC), the VPC can act as a tunnel to the customer’s internal network, allowing the Lambda access to their private availability endpoint. This also means that customers’ availability endpoints (EWS or otherwise) do not have to be open to the public internet for WorkMail to be able to connect, and access can be managed more strictly.

Administrators can set up either EWS-based or CAP Lambda-based availability configurations. One of these can be set for each domain their organization needs to get calendar availability from. Availability configurations can be set up in two ways: through the WorkMail Console UI or directly through the new availability configurations API. To configure a CAP Lambda, the customer first needs to deploy one using the AWS Lambda service. Customers are free to implement their own CAP Lambda, or use an example from the aws-samples git repository. Detailed instructions on the setup can be found in the [Configure custom availability providers on Amazon WorkMail](https://docs.aws.amazon.com/workmail/latest/adminguide/enable_interop_wm.html#Configuring_CAP) documentation page.

[![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/r71m2wk06x3ib803b96l.png)](https://serverspace.io/ref/466650)

To learn more, see [Configure custom availability providers on Amazon WorkMail](https://docs.aws.amazon.com/workmail/latest/adminguide/enable_interop_wm.html#Configuring_CAP). To learn more about Amazon WorkMail, or to start your trial, see [Amazon WorkMail](https://aws.amazon.com/workmail/).

---

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-workmail-supports-invoking-lambdas-fetch-availability-free-busy/