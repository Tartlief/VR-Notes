# Cloud Notes

## Week #8: Cloud Computing Fundamentals

### Why Cloud Computing?
- Millions of services
- Billions of users
- Hundreds of billion dollars global annual revenue
- >15% Annual growth rate

### What is Cloud Computing?
- "Cloud computing is a style of computing in which scalable and elastic IT-enabled capabilities are delivered as a servcie using internet technologies." - Gartner

#### IT-related Capabilities
- Virtual machines
- Databases
- Data Analytics
- Storage
- Network
- AI/ML
- Software Tools
- OS
- Clusters
- Security
- Platforms
- APIs
- Customer Relationships
- Email Services

### Why called "Cloud"?
- Cloud computing metaphor:
    - The group of networked elements providing services need not be individually addressed or managed by users; instead, the entire provider-managed suite of hardware and software can be thoight of as an amorphous cloud.

#### Pay-as-you-go
- Pay-per-use is a payment model that allows users to be charged accoridng to the usage of cloud resources.

### Benefits of Cloud Computing
- Cost efficiency
- Easy data recovery / back-up
- Easy deployment
- Flexibility

#### Major Market Players
- Amazon Web services
- Google Cloud
- Microsoft Azure
- Alibaba Cloud

### IMPORTANT AREAS TO UNDERSTAND
- Cloud computing delivers on-demand IT-related capabilities including servers, data storage, networking, software through the internet.
#### Cloud Computing Fundamentals
##### Virtualisation
- Technologies to create virtualised resources on top of computer resources.
- Originated in the 60's
    - By IBM to divide mainframe computers logically to run different applications.
- Virtualisation divides a single-computer's processor, memory, storage, network ... into multiple smaller virtual units.
    - (Remember VirtualBox and Linux?)
    - (Remember Bluestacks that emulates Android devices)

###### Important Terminologies
- Virtualization: Technology which enables abstraction level of resources, including virtual computers, storage devices, computer network resource, etc.
- Hypervisor: Software that creates and runs virtual machines (VMs). A hypervisor allows one host computer to support multiple guest VMs by virtually sharing its resources, such as memory and processors.
- Virtual Machine: Software emulation of a physical computer.

###### Benefits of Virtualisation:
- Encapsulation and Isolation
- Hardware Utilisation
- Flexibility
- Cost Reduction
- Energy Saving
- No Hardware / Software Lock-in
- Replication for Recovery
- Quick Server Provisioning

###### Two types of Hypervisor
- Type 1: Highly efficient as there is no OS between it and the host hardware.
    - Pros
        - Highly efficient due to direct access to physical hardware.
        - Increases their security, as there is no OS to compromise.
    - Cons
        - Often requires a separate management machine to administer different VMs and control the host hardware.
- Type 2: Hypervisor has a OS between it and the host hardware.
    Pros:
        - Enables quick and easy access to an alternative guest OS alongside the primary one running on the host-system. Great for end-user productivity
    Cons:
        - (SLOW) Must access computing, memory, and network resources via host OS, which has access to the physical hardware. This introduces latency issues.
        - Potential security risks if OS is compromised.

- Virtual Machines like Virtual Box is a Type 2 Hypervisor that manages VMs locally.

##### Containers
- While hypervisors allow multiple VMs to run on a single machine.
- Multiple containers can run on the same machine and share the OS with other containers.

- Containerisation is a form of operating system virtualization. Multiple applications and services can run in their isolated partitions called Containers.
    - Containers are lightweight with much less overhead than traditional virtual machines, enabling them to launch applications much more quickly.

##### Containers VS VMs
- Containers are virtualized in OS, while virtual machines are server virtualizations.
- Containers share the same OS as host, while VM can run its own OS.
- Containers are smaller in MB, while VMs are larger in GB
- Containers boot up in seconds compared to VMs.
- Multiple containers can be run on the same laptop, while multiple VMs cannot run simultaneously on a common laptop.


#### Key Takeaways
- Virtualisation technology has evolved from virtualising basic computer resources in a machine to virtualising other resources at different abstract levels which leads to various types of cloud services
- Over the time, deployment of the cloud services are also evolving into various forms such as public clouds, private clouds, hybrid clouds and multi-clouds to cope with evolving user demand.
- Microservices are an architectural and organization approach to software development where software is composed of small independant services which enables fast application development and innovation.

#### Cloud Computing Service Models

#### Cloud Deployment Models

#### Cloud Data Analytics

#### Cloud Security