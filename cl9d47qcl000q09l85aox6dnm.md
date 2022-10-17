# New FreeRTOS Long Term Support version released

AWS announced the second release of FreeRTOS Long Term Support (LTS) - FreeRTOS 202210.00 LTS. This release includes new libraries such as AWS IoT Fleet Provisioning and Cellular LTE-M Interface for easier device provisioning and cellular connectivity. It also includes coreMQTT and FreeRTOS-Plus-TCP libraries with improved modularity and robustness. All libraries included in this FreeRTOS LTS version, summarized in [this post](https://freertos.org/2022/10/new-freertos-long-term-support-version-released.html), will receive security and critical bug fixes until October 2024. With an LTS release, you can continue to maintain your existing FreeRTOS code base and avoid any potential disruptions resulting from FreeRTOS version upgrades.

Similar to the previous FreeRTOS LTS release, FreeRTOS 202210.00 LTS includes libraries that have been validated for memory safety with the C Bounded Model Checker (CBMC) automated reasoning tool to help mitigate code security issues such as buffer overflow. In addition, all LTS libraries have undergone certain code quality checks including MISRA-C compliance and Coverity static analysis to help improve code safety, portability, and reliability in embedded systems (see LTS Code Quality Checklist).

The support period for the previous LTS release will end on March-2023, providing you a six-month overlap between the LTS releases for easy migration of your project. See the migration guide and corresponding validation tests to upgrade your project to FreeRTOS 202210.00 LTS. If you prefer not to upgrade and want to continue receiving critical fixes on the previous LTS version beyond its expiry, you can consider the FreeRTOS Extended Maintenance Plan.

To qualify your development board (or update a qualified board) using the latest LTS version and list (or update) it in the AWS Partner Device Catalog, you can use AWS IoT Device Tester for FreeRTOS 202210.00 LTS.

To learn more and get started, refer to the [FreeRTOS LTS page](https://freertos.org/lts-libraries.html) and [FreeRTOS LTS GitHub repository](https://github.com/FreeRTOS/FreeRTOS-LTS).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/new-freertos-long-term-support-version-released/