---

copyright:
  years: 2022, 2023
lastupdated: "2023-01-06"

keywords: enterprise, enterprise account, create enterprise, set up enterprise, enterprise users, enterprise access, enterprise tutorial

subcollection: architecture-framework

content-type: tutorial
completion-time: 1h

---

{{site.data.keyword.attribute-definition-list}}


# Designing a cloud solution by using the architecture framework
{: #create-solution}
{: toc-content-type="tutorial"}
{: toc-completion-time="1h"}

This tutorial walks you through how to create a solution by using the assets from the architecture framework.
{: shortdesc}

There are several business and technical assets available to help you through the solutioning process:
* Checklist of Questions to Ask at the Start of an Engagement
* Conversations on Framework Assets for an Engagement

The questions match aspects on the framework, so solution traceability can be established. And, the list can be used as a consultative resource to guide discussions about the solution.

## Create the heat map for the solution architecture
{: #create-heatmap}
{: step}

The solution architecture heat map is based on the architecture framework and is used to identify the requirements and drive the architecture decisions for the solution. Use the [heat map template](/docs/architecture-framework?topic=architecture-framework-heat-map) to identify the aspects and domains that will be part of your solution.

After it is completed, the solution architecture heat map provides an at-a-glance view of the domains mapped to your solution requirements. For each of the domains highlighted in the solution architecture heat map, an architecture decision needs to be documented in [step 4](#decision-template).

## Decide on solution components
{: #decide-components}
{: step}

After you have created the solution architecture heat map, the next step is to identify the available components (technology or product choices) for each domain on a specific target cloud deployment or cloud service provider.

The components are identified for the applicable domains highlighted in the solution architecture heat map, which are based on your solution requirements from step 1.

## Use decision tools
{: #decision-tools}
{: step}

The third step is to use decision tools to evaluate the component options for the applicable domains against solution requirements and known constraints. Common constraints that impact the cloud architecture design include, but are not limited to: Regulatory Compliance, Service Level Agreements (SLAs), Performance, Cost, Timeliness of Product Availability, Compatibility and Portability, Geographic Availability, and Delivery Support.

Decision tools are used to select the best component to satisfy the requirements mapped to each domain. You should evaluate available components for a specific target deployment and one or more cloud service providers to determine the best-fit-for-purpose component for your solution.

You can use your cloud service providers documentation, available comparison matricies, and decision trees to evaluate the component options.

## Document architecture decisions
{: #decision-template}
{: step}

After you have evaluated the component options, you can use [architecture decision templates](https://github.ibm.com/cloud-docs-internal/writing/blob/draft/content-kit/solutions/architectural-decisions-template.md) to document the components evaluated, the decision criteria, and the component chosen for your solution based on the assessment performed in step 3. 

You should have one or more architecture decisions for each of the applicable domains highlighted in the solution architecture heat map mapped to your solution requirements.

Documenting the architecture decisions is important for several reasons:

- To provide traceability across the solution or application lifecycle and a historical record of why a particular decision was made.
- To capture interdependencies across solution components.
- To create the Bill of Materials (BoM) for your solution and build your cost case.
- To estimate delivery timelines and perform risk assessments.
- To transition to your application or build teams for delivery, detailed design, or scrum activities.

## Create architecture diagram
{: #architecture diagram}
{: step}

The last step is to create an architecture diagram that illustrates the connections among the chosen components for the applicable domains identified in step 1, on the target cloud deployment model.

Use draw.io to create an architecture diagram that represents your solution. For more details, see [Creating an architecture diagram](/docs/architecture-framework?topic=architecture-framework-architecture-diagram)
