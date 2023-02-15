# Amazon SageMaker Autopilot now provides feature selection and the ability to change data types while creating an AutoML experiment

Amazon SageMaker Autopilot now provides the ability to perform feature selection and change auto inferred data types while creating an AutoML experiment, enabling you with the flexibility to choose which features to include while training your machine learning (ML) models. SageMaker Autopilot automatically builds, trains and tunes the best ML models based on your data, while allowing you to maintain full control and visibility. 
The features you choose to include in your data have a significant effect on the model’s results and predictions. As a part of its automated evaluation criteria, SageMaker Autopilot includes all features in the uploaded dataset. It now offers controls to the end user who understands their data to make their feature selections. Starting today, when creating an Amazon SageMaker Autopilot experiment, you can not only select or deselect the features from the training dataset but also change the data types that were automatically inferred by SageMaker Autopilot. This release also includes the ability to preview the uploaded input training dataset.

To get started, update Amazon SageMaker Studio to the latest release and launch SageMaker Autopilot either from [SageMaker Studio Launcher](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-launcher.html) or APIs. To learn more on how to update studio please see [documentation](https://docs.aws.amazon.com/sagemaker/latest/dg/studio-tasks-update.html).

These new features are now available in all regions where SageMaker Autopilot is available. To get started, see [Creating an Experiment with Autopilot](https://docs.aws.amazon.com/sagemaker/latest/dg/autopilot-automate-model-development-create-experiment.html) and [SageMaker Autopilot API reference](https://docs.aws.amazon.com/sagemaker/latest/dg/autopilot-reference.html#autopilot-api-reference). To learn more, visit the [SageMaker Autopilot product page](https://aws.amazon.com/sagemaker/autopilot/).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/11/amazon-sagemaker-autopilot-feature-selection-ability-change-data-types-creating-automl-experiment/