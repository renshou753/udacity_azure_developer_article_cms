# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

The cost of deploying this CMS application to VM is higher than app service.

In terms of the scalability and availability, app service is capable for vertical or horizontal scaling, but app service does have a hardware upside limit, a maximum of 14GB of memory and 4 vCPU cores per instance; VM, however, allows be grouped to provide high availability, scalability, and redundancy.

With VM, I would have complete control over the operating system and applications, this level of control allows for more flexibility but also requires more management and maintenance of the VM which is something I don't want for this project.

App service on the other hand, is fully managed platform as a service product, it allows me to quickly deploy my application without worry about the underlying infrastructure and operating system. It has built in feature of continious deployment which is helpful for me to quickly deploy and test my application.

Overall, based on the requirement of this project, I would choose app service to deploy this cms application, it's such a light weight app and it does not require high bandwidth to handle the web request. App service is more affordable, also easier for me to deploy than VM.

### Assess app changes that would change your decision.

If this cms application suddently attracts significant amount of users I would consider to use dedicated virtual machines to handle the traffic.
