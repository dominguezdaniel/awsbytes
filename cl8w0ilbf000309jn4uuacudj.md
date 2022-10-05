## Amazon WorkMail now supports Impersonation Roles

Amazon WorkMail now offers Impersonation Roles, a secure way to more easily grant programmatic access to mailboxes. Customers can use Impersonation Roles with Exchange Web Services (EWS) to perform impersonated actions in other users’ mailboxes. 

Administrators have the ability to limit the scope of Impersonation Roles to specific users, including choosing whether actions have full or read-only access.
The Impersonation Roles feature provides administrators an alternative to having to share and securely store user credentials, since authentication is done by using the short lived bearer tokens from each role. In addition, Impersonation Roles help administrators provide an extra layer of security by allowing them to restrict the actions that can be performed by impersonated calls. Administrators can choose to create impersonation roles with type “Read only”, which will only allow read actions in the impersonated user’s mailbox.

The WorkMail administrator can create an impersonation role for the service or programmatic user that will be making impersonated calls. This service will then call AssumeImpersonationRole via the WorkMail API to get a bearer token. This token can then be passed as an Authorization header in subsequent EWS impersonation calls along with the primary email address of the user being impersonated.

To learn more, see [Programmatic Access to Mailboxes](https://docs.aws.amazon.com/workmail/latest/adminguide/mail_perms_programmatic.html) on Amazon WorkMail. To learn more about Amazon WorkMail, or to create a no-cost 30-day test organization, see [Amazon WorkMail](https://aws.amazon.com/workmail/).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/amazon-workmail-supports-impersonation-roles/