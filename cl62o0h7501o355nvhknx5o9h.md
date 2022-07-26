## Malware protection now a feature of Amazon GuardDuty

[Amazon GuardDuty Malware Protection](https://docs.aws.amazon.com/guardduty/latest/ug/malware-protection.html) is now available, in [Amazon GuardDuty](https://aws.amazon.com/guardduty/), to help detect malicious files residing on an instance or container workload running on Amazon Elastic Compute Cloud (Amazon EC2) without deploying security software or agents. Amazon GuardDuty Malware Protection adds file scanning for workloads utilizing Amazon Elastic Block Store (EBS) volumes to detect malware that can be used to compromise resources, modify access permissions, and exfiltrate data. Malicious files that contain trojans, worms, crypto miners, rootkits, bots, and the like can be used to compromise workloads, repurpose resources for malicious use, and gain unauthorized access to data. Existing customers can enable the GuardDuty Malware Protection feature with a single click in the GuardDuty console or through the GuardDuty API. When threats are detected, GuardDuty Malware Protection automatically sends security findings to [AWS Security Hub](https://aws.amazon.com/security-hub/), [Amazon EventBridge](https://aws.amazon.com/eventbridge/), and [Amazon Detective](https://aws.amazon.com/detective/). These integrations help centralize monitoring for AWS and partner services, automate responses to malware findings, and perform security investigations from the GuardDuty console. With the launch of Amazon GuardDuty Malware Protection there are eight new [threat detections](https://docs.aws.amazon.com/guardduty/latest/ug/findings-malware-protection.html):

Execution:EC2/MaliciousFile
Execution:ECS/MaliciousFile
Execution:Kubernetes/MaliciousFile
Execution:Container/MaliciousFile
Execution:EC2/SuspiciousFile
Execution:ECS/SuspiciousFile
Execution:Kubernetes/SuspiciousFile
Execution:Container/SuspiciousFile

The first 30 days of GuardDuty Malware Protection are available at no additional charge for existing GuardDuty accounts. For new accounts, GuardDuty Malware Protection is part of the 30-day [Amazon GuardDuty free trial](https://aws.amazon.com/guardduty/pricing/). During the trial period you can see the estimated cost of running the service after the trial period ends in the GuardDuty Management Console. GuardDuty optimizes your costs by only scanning for malware after GuardDuty detects suspicious behavior associated with malware. GuardDuty Malware Protection is available in all [AWS regions](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/) where GuardDuty is available, excluding the AWS GovCloud (US), AWS China (Beijing) region, operated by Sinnet, and AWS China (Ningxia) region, operated by NWCD. To receive programmatic updates on new Amazon GuardDuty features and threat detections, subscribe to the [Amazon GuardDuty SNS topic](https://docs.aws.amazon.com/guardduty/latest/ug/guardduty_sns.html).

To get started:

Visit [Amazon GuardDuty](https://aws.amazon.com/guardduty/) product page

Read the [AWS News Blog on Amazon GuardDuty Malware Protection](https://aws.amazon.com/blogs/aws/new-for-amazon-guardduty-malware-detection-for-amazon-ebs-volumes/)

Learn more at the [GuardDuty Malware Protection FAQ](https://aws.amazon.com/guardduty/faqs/#GuardDuty_Malware_Protection)

Existing customers, enable Amazon GuardDuty Malware Protection from your Amazon 

GuardDuty console or API and receive this feature at no additional charge for 30 days

New customers, start your 30-day [Amazon GuardDuty free trial](https://aws.amazon.com/guardduty/pricing/), which includes GuardDuty Malware Protection

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/malware-protection-feature-amazon-guardduty/ 