# These notes come from the official lesson on the Microsoft Website Prepping students for the AZ-900 Exam: Microsoft Azure Fundamentals
I. Describe Cloud Concepts (25-30% of exam weight)
Covers: Cloud Concepts, Deployment models, & shared Responsibility in the cloud

Learning Objectives:
- Define Cloud Computing
- Describe the shared responsibility model
- Define cloud models inclduing public, private, and hybrid
- Identify the appropriate use case for each cloud model
- Describe the consumption-based model
- compare cloud pricing models

# Notes

What is Microsoft Azure?: 
A cloud computing platform with services to help the user meet business goals, including web hosting in the cloud, the ability to run VC's (Virtual Computers), cloud-based services like remote storage, database hosting, centralized account management; and AI and Internet of Things (IoT) - focused services

What is Cloud Computing?:
The delivery of computing services over the internet
  Common Computing services: 
  - IT Infrastructure (VM's, Storage, databases, networking)
  - Traditional IT Offerings (Internet of Things, Machine Learning, Artificial Intelligence)

Why is the cloud better compared to traditional Infrastructure?:
Since cloud computing uses the internet to deliver their services, you (the user) can use the cloud to rapidly increase your IT Infrastructure, instead of having to wait for another physical datacenter to be built. Additionally, you only pay for what you use (what you need).

What is the Shared Responsibilty model?:
Through cloud computing, the traditional IT responsibilities (Such as maintaining infrastructure, software, physical space, servers, etc.) get shared between the cloud provider and the consumer.

_You_, (The consumer), Will _ALWAYS_ be responsible for:
- The Information and data stored in the cloud
- Devices that are allowed to connect to your cloud
- The Accounts
  
The _Cloud_ provider is _ALWAYS_ responsible for:
- The Physical Datacenter
- The Physical network
- The Physical hosts
  
Your _service model_ will determine responsibility for:
- Identity and Infrastructure
- Applications
- Network Controls
- Operating Systems  
  
***
What are Cloud Models?:
Cloud models define the _deployment type_ of cloud resources.
There are three main cloud models:

➤ **Private Cloud**: A Cloud (Delivering IT services over the internet) used by a _single_ entity. It provides much greater control, but comes with much greater cost & fewer benefits of a public cloud development. A private cloud can be hosted from your on-site data center, as well as in an off-site datacenter, potentially even by a 3rd party that has dedicated that datacenter to your company.
<br>
  Features: 
<br>
▶️ Hardware must be purchased for startup and maintainance
<br>
▶️ Organizations are responsible for hardware maintenance and updates
<br>
_-Data is not collocated with other organization's data_
<br>
_-Organizations have complete control over resources and security_

➤ **Public Cloud**: Build, controlled, & maintained by a 3rd-party cloud provider. _Anyone_ that wants to purchase cloud services can access and use resources. Benefits: No capital expenditures required to scale up).
<br>
  Features:
<br>
_- No capital Expenditures required to scale up_
<br>
_- Applications can be quicky provisioned and De-provisioned_
<br>
_- Organizations pay only for what they use_
<br>
▶️ Organizations don't have complete control over resources and security

➤ **Hybrid Cloud**: Uses both public & private clouds in an inter-connected environment. Can be used to allow a private cloud to surge for increased, temporary demand _by deploying public cloud resources._ It can be used to provide an extra layer of security, for example, allowing users to choose which services to keep in public cloud and which to deploy in the private cloud infrastructure.
<br>
  Features:
<br>
_- Provides the most flexibility_
<br>
_- Organizations determine where to run their applications_
<br>
_- Organizations control security, compliance, or legal requirements_
<br>
