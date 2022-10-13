# AWS Gateway Load Balancer launches new option to rebalance flows when target fails or deregisters

AWS is launching a new feature that provides an option to define flow handling behavior for AWS Gateway Load Balancer. Using this option, customers can now rebalance existing flows to a healthy target, when the target fails or deregisters. This helps reduce failover time when a target becomes unhealthy, and also allows customers to gracefully patch or upgrade the appliances during maintenance windows.

This feature uses the existing ELB API/Console and provides new attributes to specify the flow handling behavior. See the documentation on how to use this capability. Since this feature changes flow behavior, customers should evaluate the effect of enabling this feature on availability and check with their third-party appliance provider documentation.

AWS appliance partners should consider taking following actions - (a) Partners should validate whether rebalancing existing flows to healthy target has implications on their appliance as it will start receiving the flow midway, i.e. without getting the TCP SYN. (b) Update public documentation on how this feature will affect their appliance. (c) Partner may use this capability to improve stateful flow handling on their appliances.

To get started with AWS Gateway Load Balancer, please see the [product page](https://aws.amazon.com/elasticloadbalancing/gateway-load-balancer/) and service [documentation](https://docs.aws.amazon.com/elasticloadbalancing/latest/gateway/introduction.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/10/aws-gateway-load-balancer-launches-new-option-rebalance-flows-target-fails-deregisters/