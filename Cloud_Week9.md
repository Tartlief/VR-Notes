# Cloud Notes

## Week #9: Cloud Service Models

### 1. Cloud Software Stack
- Traditional IT vs IaaS (Infrastructure-as-a-Service)
    - Inclusion of a Hypervisor in the middle of OS and Server Hardware
### 2. Cloud Service Models:
#### IaaS: Infrastructure-as-a-Service
- This provides on-demand services of computing infrastructure such as servers, storage, and networking resources that users can configure and use via the Internet.
    - User Request IaaS
    - Service virtualises Computer Resources / Infrastructure
    - Provide cloud servers, storage and networks on demand back to user.
- IaaS Providers handles:
    - Hypervisor
    - Server Hardware
    - Storage
    - Networking

##### Examples of IaaS
- Compute
    - AWS EC2
    - Google Cloud Compute Engine
- Storage
    - AWS S3
    - Google Cloud Storage
- Networks
    - AWS VPC
    - Google Cloud VPC

##### Launch a Cloud Instance
- It is a virtualized computer server that includes CPU, RAM, and storage, offered by a cloud computing platform.

##### Pro and Cons
- Pros
    - Scalable and Elastic: Resources can be scaled according to demand
    - Redundancy and Reliability: Important data can be replicated and stored in the cloud
    - Pay-per-Use: Charged according to usage instead of having to buy it outright.
- Cons:
    - Relies on Internet Connection
    - Security Issues
    - Learning Curve

##### Use Cases:
- Dynamic or unpredictable demand: IaaS services are more suitable to cope with fluctuation of computing resource usage.
    - E-Commerce sites have the ability to scale-up during periods of high demand.
- Limited Capital Investment and Fast Innovation: It is cost-effective choice for start-ups.
- Large volume of Data and on-line access
- Disaster Recovery: Data can be recovered easily due to cloud provider's existing geographically-dispersed infrastructure.

#### PaaS: Platform-as-a-Service
- Development tools such as databases, middleware, runtime frameworks available to developers.
- PaaS services handle:
    - Runtime
    - Middleware
    - OS
    - Hypervisor
    - Server Hardware
    - Storage
    - Networking

##### Pros and Cons
- Pros
    - Collaborative Development
    - Additional Development Capabilities
    - Automated Testing and Deployment

- Cons
    - Security and Data Privacy
    - Platform / Vendor Lock-in
    - Complexity

#### SaaS
- Provides on-demand software services by hosting applications and making them available to end users over the internet
- SaaS provides:
    - Application
    - Data
    - Runtime
    - Middleware
    - OS
    - Hypervisor
    - Server Hardware
    - Storage
    - Networking

##### Pros and Cons
- Pros
    - On-demand, variable workload, one-to-many
    - Compatible to various devices
    - Ease of Maintenance

- Cons
    - Security and data privacy
    - Internet Connection
    - Limited Customization options

### 3. New Cloud Service Models
#### CaaS

#### FaaS