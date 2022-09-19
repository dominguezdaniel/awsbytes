## Amazon SageMaker Automatic Model Tuning now provides up to 3x faster hyperparameter tuning with Hyperband as a new search strategy

Amazon SageMaker Automatic Model Tuning allows you to find the most accurate version of your machine learning model by searching for the optimal set of hyperparameter configurations. SageMaker Automatic Model Tuning now supports Hyperband, a new search strategy that can find the optimal set of hyperparameters up to 3x faster than Bayesian search for large-scale models such as deep neural networks that address computer vision problems.

Before this launch, you had the option to tune your models through either Random or Bayesian search, which runs each training job launched as part of the tuning to full completion. Hyperband is a new multi-fidelity tuning strategy that uses both intermediate and final results of training jobs to dynamically re-allocate resources to promising hyperparameter configurations and automatically stops the underperforming training jobs. When tuning iterative algorithms that publish results at different resource levels, such as neural networks trained for multiple epochs or gradient-boosted decision trees trained for multiple rounds, Hyperband can find the optimal hyperparameter configurations up to 3x faster than Random and Bayesian search.

The Hyperband search strategy is now available for Amazon SageMaker Automatic Model Tuning in all commercial AWS Regions. To learn more, review the [blog post](https://aws.amazon.com/blogs/machine-learning/amazon-sagemaker-automatic-model-tuning-now-provides-up-to-three-times-faster-hyperparameter-tuning-with-hyperband/) or visit Amazon SageMaker Automatic Model Tuning technical documentation.

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/09/amazon-sagemaker-automatic-model-tuning-provides-faster-hyperparameter-tuning-hyperband-search-strategy/