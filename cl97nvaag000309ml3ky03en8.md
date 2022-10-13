# AWS Glue introduces Git integration

[AWS Glue](https://aws.amazon.com/glue/) now offers integration with Git, the widely-used open source version control system. AWS Glue is a serverless data integration service that uses reusable jobs to perform extract, transform, and load (ETL) tasks on data sets of nearly any scale. With this feature, customers can use GitHub and [AWS CodeCommit](https://aws.amazon.com/codecommit/) to maintain a history of changes to their AWS Glue jobs and apply their existing DevOps practices to deploy them. Before now, customers needed to set up their own integrations with their code versioning systems and build tooling to move jobs from development environments to production environments.

Git integration in AWS Glue works for all AWS Glue job types, whether visual or code-based. It includes built-in integration with both GitHub and AWS CodeCommit and also makes it simpler to use automation tools like Jenkins and [AWS CodeDeploy](https://aws.amazon.com/codedeploy/) to deploy AWS Glue jobs. This feature also adds the option to download and upload jobs manually. Finally, AWS Glue Studio’s visual editor now supports parameterizing data sources and targets so you can update them when deploying the job to a new account.

To learn more, visit our [documentation](https://docs.aws.amazon.com/glue/latest/ug/edit-job-add-source-control-integration.html), [blog post](https://aws.amazon.com/blogs/big-data/code-versioning-using-aws-glue-studio-and-github/), and [demo video](https://www.youtube.com/watch?v=XRlZq2kvE4U).

This feature is available in all commercial AWS Regions where AWS Glue is available.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-glue-git-integration/