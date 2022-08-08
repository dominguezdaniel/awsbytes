## AWS IoT Greengrass v2 updates Stream Manager to report new telemetry metrics and more

[AWS IoT Greengrass](https://aws.amazon.com/greengrass/) is an Internet of Things (IoT) edge runtime and cloud service that helps customers build, deploy, and manage device software. We are excited to announce our version 2.7 release with the following features:

System Telemetry Enhancements - The Stream Manager agent component now has the ability (enabled by default) to send system telemetry metrics to Amazon EventBridge. 

System telemetry data is diagnostic data that can help you monitor the performance of critical operations on your AWS IoT Greengrass core devices. You can create projects and applications to retrieve, analyze, transform, and report telemetry data from your edge devices. Domain experts, such as process engineers, can use these applications to gain insights into their fleet health based on device data uploaded through Stream Manager to AWS Services such as Amazon Kinesis, Amazon Simple Storage Service (Amazon S3), AWS IoT Analytics, AWS IoT SiteWise, and more. For more information, see Gathering System Telemetry section in the developer guide.

Local Deployment Improvements - The new improvements now enable AWS IoT Greengrass nucleus to send near real time deployment status updates to AWS IoT Greengrass cloud service. For instance, using the ListInstalledComponents API, customers can now observe the status of locally deployed components for a connected device.

Additional Support for Client Certificates - Certificate signed by a custom certificate authority (CA), where the CA isn't registered with AWS IoT, is now supported. This allows customer the flexibility to use a custom certificate authority that is not registered with AWS IoT. To use this feature, you can set the new greengrassDataPlaneEndpoint configuration option to iotdata. For more information, see Use a device certificate signed by a private CA.
To learn more, visit the AWS IoT Greengrass product page and view the updated developer guide. Please see the AWS Region table for all the regions where AWS IoT Greengrass is available.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/aws-iot-greengrass-v2-updates-stream-manager-report-telemetry-metrics/