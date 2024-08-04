# 06 - Operating data products in production 

## Description
We'll dive into navigating the different stages of a data product's life cycle, from its first release to
potential decommissioning. To kick things off, we will delve into release methodologies by
introducing the principles of continuous integration and continuous delivery (CI/CD). Moving
forward, we'll explore the intricacies of managing a data product in a production environment. This
will encompass operational considerations like governance and observability, alongside consumer focused aspects such as discoverability and access control. Finally, we'll present diverse techniques
for steering the evolution and reuse of data products within a distributed setting

## Chapter Headings  
* **Deploying data products**
  * Understanding continuous integration
  * Understanding continuous delivery
  * Defining the deployment pipeline 
* **Governing data products**
  * Collecting and sharing metadata
  * Implementing computational policy
  * Observing data products
  * Controlling data products
  * Composing data products 
* **Consuming data products**
  * Discovering data products
  * Accessing data products
* **Evolving data products**
  * Versioning Data Products
  * Deprecating Data Products 

## Skills learned
* **SKILL 1**: Skill in managing the CI/CD process of a data product, incorporating DevOps best
practices within the data context
* **SKILL 2**: Skill in designing and implementing features essential for enhancing governance and
observability of a data product in a production environment
* **SKILL 3**: Ability to design and implement the necessary features to facilitate secure and
profiled consumption of data exposed by a data product
* **SKILL 4**: Understand how to design and manage the evolution of a data product to minimize
unintended impacts on its consumers

## Image list
* [Figure 6.1 - Continuous Integration](./images/chapter-06-Fig-01-Continuous-Integration.png)
* [Figure 6.2 - Integration test](./images/chapter-06-Fig-02-Integration-Tests.png)
* [Figure 6.3 - Exposing the descriptor file through a discoverbility port](./images/chapter-06-Fig-03-Observability-Ports.png)
* [Figure 6.4 - Observability ports](./images/chapter-06-Fig-04-Observability-Port.png)
* [Figure 6.5 - Data Product Registry](./images/chapter-06-Fig-05-Data-Product-Registry.png)

## Further reading 
For more information on the topics covered in this chapter, please see the following resources: 

* [Software Delivery Guide](https://www.martinfowler.com/delivery.html) - Martin Fowler (2019)  
* [Continuous Integration: Improving Software Quality and Reducing Risk](https://www.amazon.com/Continuous-Integration-Improving-Software-Reducing/dp/0321336380) - P.M. Duvall, S. Matyas, A.Glover (2007)  
* [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](https://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912/) – J. Humble, D. Farley (2010)  
* [Accelerate: The Science of Lean Software and DevOps: Building and Scaling High Performing Technology Organizations](https://www.amazon.com/Accelerate-Software-Performing-Technology-Organizations/dp/1942788339) - N. Forsgren, J. Humble, G. Kim (2018)  
* [Infrastructure as Code: Dynamic Systems for the Cloud Age](https://www.amazon.com/Infrastructure-Code-Dynamic-Systems-Cloud/dp/1098114671/) – K. Morris (2021)  
* [Policy As Code: Improving Cloud-native Security](https://www.amazon.com/Policy-As-Code-Improving-Cloud-native/dp/1098139186) – J. Ray (2024)  
* [Data Observability for Data Engineering: Proactive strategies for ensuring data accuracy and addressing broken data pipelines](https://www.amazon.com/Data-Observability-Engineering-pipelines-actionable/dp/1804616028/) - M. Pinto, Sammy E. Khammal (2023) 
* [Learning Open Telemetry: Setting Up and Operating a Modern Observability System](https://www.amazon.com/Learning-OpenTelemetry-Setting-Operating-Observability/dp/1098147189) – T. Young, A. Parker (2004)  
