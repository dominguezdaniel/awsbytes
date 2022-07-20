## Introducing Amazon EC2 R6a instances

AWS announces the general availability of [Amazon EC2 R6a instances](https://aws.amazon.com/ec2/instance-types/r6a/). Designed for memory-intensive workloads, R6a instances are built on the [AWS Nitro System](https://aws.amazon.com/ec2/nitro/), which delivers almost all the compute and memory resources of the host hardware to your instances. R6a instances are powered by third-generation AMD EPYC processors with an all-core turbo frequency of up to 3.6 GHz. These memory-optimized instances, which are SAP certified, deliver up to 35% better compute price performance compared to R5a instances for a wide variety of workloads and offer 10% lower cost than comparable x86-based EC2 instances.

To meet customer demands for increased scalability, R6a instances provide two new sizes, the largest with 192 vCPUs and 1,536 GiB of memory, which is twice the size of the largest R5a instances. Each instance vCPU has 20% higher memory bandwidth compared to R5 instances. R6a instances also provide up to 50 Gbps of networking speed and 40 Gbps of bandwidth to the Amazon Elastic Block Store (Amazon EBS). You can use the Elastic Fabric Adapter (EFA) on the 48xlarge and bare metal sizes, which enables low latency and highly scalable internode communication.

You can use R6a instances in the following [AWS Regions](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/): US East (Ohio), US East (N. Virginia), US West (Oregon), Asia Pacific (Mumbai), Europe (Frankfurt), and Europe (Ireland).

To learn more, see the [R6a instances page](https://aws.amazon.com/ec2/instance-types/r6a/). To get started, see the [AWS Management Console](https://console.aws.amazon.com/), [AWS Command Line Interface (AWS CLI)](https://aws.amazon.com/cli/), and [AWS SDKs](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/EC2.html).

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/07/introducing-amazon-ec2-r6a-instances/