## Amazon SageMaker adds ml.g5, ml.p4d, and ml.c6i instances for model deployment

Amazon SageMaker expands access to new ML instances so customers can deploy models on the best instance for their workloads. Now, customers can use ml.g5, ml.p4d, and ml.c6i instances for Asynchronous and Real-time model deployment options.

AWS's vision is to put ML into the hands of everyday developers and to democratize access to cutting edge infrastructure made available in a low-cost, pay as-you-go usage model. To deliver on this vision, we are innovating at a fast pace to continuously deliver better performing and lower cost infrastructure for ML workloads.

ml.g5 instances deliver up to 3x higher performance and up to 40% better performance per unit cost for machine learning inference compared to G4dn instances. They are a highly performant and cost-efficient solution for customers who want to use NVIDIA libraries such as TensorRT, CUDA, and cuDNN to run their ML applications. These instances are ideal for usecases such as recommendations, chatbots, smart assistants, and image recognition. ml.g5 instances are available in US East (N. Virginia), US West (Oregon), and Europe (Ireland).

ml.p4d instances provide an average of 2.5x better performance for deep learning models compared to previous generation P3 instances. 24 GB of memory per GPU along with support for up to 7.6 TB of local NVMe SSD storage enable local storage of large models and datasets for high performance machine learning inference such as large language models, and computer vision models. ml.p4d instances are available in US East (N. Virginia), and US West (Oregon).

ml.c6i instances are powered by 3rd generation Intel Xeon Scalable processors and deliver up to 15% better performance per unit cost compared to C5 instances for a wide variety of workloads. C6i instances also offer new larger sizes with up to 128 vCPUs and 256 GiB of memory, enabling customers to consolidate workloads on less instances. C6i instances support new Intel Advanced Vector Extensions (AVX 512) instructions, Intel Turbo Boost, and Intel Deep Learning Boost for further performance improvements specifically for machine learning workloads. ml.c6i are available in all commercial regions.

For pricing information on these instances, please visit [pricing page](https://aws.amazon.com/sagemaker/pricing/).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/07/amazon-sagemaker-adds-ml-g5-ml-p4d-ml-c6i-instances-model-deployment/