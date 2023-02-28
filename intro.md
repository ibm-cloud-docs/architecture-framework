---

copyright:
  years: 2023
lastupdated: "2023-02-27"
keywords: 
subcollection: architecture-framework

---

{{site.data.keyword.attribute-definition-list}}


# Introduction to the architecture framework
{: #intro}

Cloud architecture can be thought of as a multi-dimensional matrix that considers application workloads, cloud deployment models, service management, and design aspects to provide a basis for cloud computing architectural designs that align with business drivers and requirements.
{: shortdesc}

In addition, when architecting cloud solutions, consideration needs to be given to items such as:
* Resiliency and service availability
* Data privacy
* Performance and scale
* Distributed storage
* Management
* Interoperability and integration

![matrix diagram](images/matrix.svg){: caption="Figure 1. Matrix view" caption-side="bottom"}

Evaluating options and designing a suitable architecture for comprehensive enterprise cloud solutions can be a daunting task. The use of an architecture framework can assist in enhancing the ability to design optimum cloud computing solutions.

## What is the architecture framework?
{: #what-is}

The architecture framework is a structured, technology agnostic, enterprise architecture approach, inspired by the technology layer of the [TOGAF](https://www.opengroup.org/togaf) model. It can be used as a guide to provide a consistent approach to architect hybrid, multi-cloud end-to-end solutions based on your requirements.

The architecture framework defines a technology- and cloud-provider-agnostic taxonomy of "aspects" and "domains" that can be used to develop reference solutions or patterns for specific platforms or applications on any target cloud deployment, be it private cloud, public cloud, hybrid cloud, or multi-cloud.

Aspect
    : Aspects are architectural areas that need to be considered for any enterprise solution. Some aspects are associated with nonfunctional requirements like security and resiliency. Each aspect can have one or more domains.

Domain
    : Domains are common capabilities or similar technology functions within an aspect. For example, Enterprise Connectivity and Load Balancers are considered networking technologies.

Component
    : Components are product offerings that can be used to satisfy the solution requirements. The component options depend on the target cloud deployment and cloud provider. For example, Direct Link 2.0 and VPC VPN Gateways are Enterprise Connectivity components on the IBM Cloud.
