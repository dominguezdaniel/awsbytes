## Cloud Service Models – IaaS, PaaS, and SaaS

There are three cloud-based service models. The main features of each are: 

- IaaS provides a capability for users to provision processing, storage, and network resources on demand. The customers deploy and run their own applications on these resources. Using this service model is closest to the traditional in-premise models but without the lengthy procurement processes. The onus of administering these resources rests, largely, with the customer.

- In PaaS, the service provider makes certain core components such as databases, queues, workflow engines, email, and so on, available as services to the customer. The customer then leverages these components for building their own applications. The service provider ensures high service levels, and is responsible for scalability, high availability, and so on, for these components. This allows customers to focus a lot more on their application functionality. However, this model also leads to application-level dependency on the providers' services.

- In the SaaS model, typically, third-party providers using a subscription model provide end user applications to their customers. The customers may have some administrative capability at the application level, for example, to create and manage their users. Such applications also provide some degree of customizability, for example, the customers can use their own corporate logos, colors, and so on. Applications that have a very wide user base most often operate in a self-service mode. In contrast, the provider provisions the infrastructure and the application for the customer for more specialized applications. The provider also hands over the management of the application to the customer's application administrator (in most cases this is limited to user management tasks). 

From an infrastructure perspective, the customer does not manage or control the underlying cloud infrastructure in all three service models.

The following figure illustrates who is responsible for managing the various components of a typical user application across IaaS, PaaS, and SaaS cloud service models. The shaded boxes represent the service-providers' responsibilities, while the other boxes represent the users' or end customers' responsibilities.

![model.JPG](https://cdn.hashnode.com/res/hashnode/image/upload/v1644592842426/pKgYWoI09.jpeg)

The level of control the user has over operating systems, storage, applications, and certain network components (for example, load balancers) is the highest in the IaaS model while the least (or none) in the SaaS model.

><div class="csl-entry">Sarkar, A. and Shah, A. (2018) <i>Learning AWS.</i> 2nd edn. Packt Publishing. Available at: https://www.perlego.com/book/578848/learning-aws-pdf (Accessed: 25 September 2021).</div>