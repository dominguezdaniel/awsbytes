## Scaling From Half a Million to a Million Users

At this stage, we need to know our requirements in terms of defining min/max pool sizes, the CloudWatch metrics to drive scaling, and using on demand and Spot instances in our auto scaling groups. 

Over provisioning resources for peak periods will get expensive at these volumes. You can create an auto scaling group for web servers in the web tier across the AZs.

At the most basic level, we need to be clear on three parameters for auto scaling: the minimum, maximum, and the desired number of instances. We should always keep the minimum number of instances running, and launch or terminate new instances to meet desired capacity. As a practice, we never start more than a maximum number of instances, and as much as possible we keep the instances balanced across the AZs. 

We will need to define launch configurations to determine what is going to be launched (EC2 instance type and size) and the AMI to be used along with the security groups, SSH keys, IAM instance profile, and users' data (essentially any arbitrary data). 

Bootstrapping the infrastructure requires the installation and setup to be fully automated. We use an AMI with all the required software and configurations specified. These configurations can be specified via user data, or using tools like Chef/Puppet/Ansible and AWS CodeDeploy.

If we are terminating an instance due to reduced traffic then we also need to de-register the instance from the ELB, select a target instance, and then terminate it. 

Which instance is terminated can be configured using termination policies, and the service will try to terminate the instance in a manner that balances the capacities across the AZs. Termination policies determine which instances are terminated first. 

There are several options such as the longest running, the one having the oldest launch configuration, and the closest to the full billing hour (for better cost control, as it gets the most value out of the terminating instance). Scaling plans determine when an Auto Scaling group scales in or scales out. If the desired capacity is greater than the current capacity then we launch new instances, and if the desired capacity is less than the current capacity then we terminate instances.

There are different types of scaling plans. The default plan ensures that the current capacity of healthy instances remains within boundaries (never less than the minimum). We can also modify the desired capacity (via the API, console, or CLI) to trigger a scaling event. This type of manual scaling is helpful for testing, and can be set and changed through scripts based on requirements at any given point. 

A scheduled scale in/scale out plan is based on timed events, for example, in order to align with extended business hours, we can have a plan that scales up at 8 A.M. and scales down at 8 P.M. We can also do dynamic scaling that scales based on Amazon CloudWatch metrics and thresholds.

You should also configure the Auto Scaling groups to work with one or more ELB. This integration will enable the registering of new instances and deregistering instances on termination automatically. Furthermore, we can use ELB metrics when defining our auto scaling policies.

Scaling policies determine when to change capacity. The capacity can be changed in different ways. For example, setting a fixed capacity as the desired capacity and adding/removing a fixed number of instances or adding/removing a percentage of existing capacity. Similarly, dynamic scaling policies trigger scaling events based on demand. The demand is measured based on metrics and the changes in metrics can be mapped to scaling policies.

><div class="csl-entry">Sarkar, A. and Shah, A. (2018) <i>Learning AWS.</i> 2nd edn. Packt Publishing. Available at: https://www.perlego.com/book/578848/learning-aws-pdf (Accessed: 25 September 2021).</div>