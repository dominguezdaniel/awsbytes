## AWS Batch extends the job report retention period from 24 hours to 7 days

AWS Batch has increased the job report retention period from 24 hours to 7 days. This means that you can now query the details for AWS Batch jobs that were completed up to 7 days ago. With this longer retention period, you no longer need to worry about jobs disappearing after a day. You can query jobs a few days after submitting them, and have greater visibility over the jobs that you submitted throughout the week.

As before, you can call the ListJobs and DescribeJobs API operations to query job reports. When you call either one of these operations, you can get a response that shows the details for jobs that were completed within the past week. You can filter the results by using parameters such as job definition and job status.

Now you can query job reports in a way that fits your schedule. You no longer need to worry about job reports disappearing within a day. The extended retention period is now available in all AWS Regions where AWS Batch is currently available. To learn more about AWS Batch, see the AWS Batch User Guide. To learn more about the AWS Batch API, see the [AWS Batch API Reference](https://docs.aws.amazon.com/batch/latest/APIReference/Welcome.html).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/aws-batch-extends-job-report-retention-period-24-hours-7-days/