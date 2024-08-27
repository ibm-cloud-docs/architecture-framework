---

copyright:
  years: 2023, 2024
lastupdated: "2024-08-22"
keywords: 
subcollection: architecture-framework

---

{{site.data.keyword.attribute-definition-list}}


# Creating an architecture diagram
{: #architecture-diagram}

Every architecture solution should have an architecture diagram that shows the components of the solution, relationships between components, boundaries between elements, data flow, and so on.
{: shortdesc}


## Library of stencils and shapes
{: #library}

{{site.data.keyword.cloud_notm}} provides a library of stencils and shapes to use in draw.io. This makes it so that all diagrams are using a standard set of shapes, colors, and flows.

However, {{site.data.keyword.cloud_notm}}'s approved design tool is Draw.io we have also provided PowerPoint (.ppt) and SVG (.svg) files for your convenience. You can access the [{{site.data.keyword.cloud_notm}} Architecture Stencils](https://github.com/IBM-Cloud/architecture-icons){: external} in GitHub.

IBM stencils and shapes can be of any of the following formats:

- Boxes that represent a deployedOn relationship for locations (logical, virtual, physical) of platforms, infrastructure, network, and so on, on which services and applications are deployed.
- Groups that represent a deployedTo relationship for grouping services and applications that are deployed on boxes.
- Nodes that are meant to represent stand-alone components or devices.

For example, a virtual server instance is deployed on a subnet and deployed to a security group.

The stencils are also organized by type, function, or purpose by using the following categories:

- IBM (Core): Components that are typically technology and brand independent or not associated with a specific {{site.data.keyword.cloud_notm}} offering or service. Examples: Server, Router, Database, Application
- {{site.data.keyword.cloud_notm}}: {{site.data.keyword.cloud_notm}} specific offerings and services. Examples: IBM VPC, Classic VSI, Serverless, Internet Services, Security-Group.
- IBM Domains or Industries: Extensions that are focused on IBM specific non-Cloud domains and industries. Examples: Automotive, Retail, Blockchain, Watson.
- 3rd Party: Third-party products or services. Examples: VMware, BigFix, Akamai.


## Installing the stencils and shapes
{: #ibm-cloud-stencils}

The latest library was built in collaboration with IBM Design Language. You can install the `{{site.data.keyword.cloud_notm}} Architecture Stencils` for draw.io from [architecture-icons](https://github.com/IBM-Cloud/architecture-icons/tree/main/drawio){: external}.



## Creating your diagram
{: #drawio-diagram}

Before you create your diagram, follow the instructions to download the {{site.data.keyword.cloud_notm}} stencils in [Getting stencil libraries compatible with draw.io application](https://github.com/IBM-Cloud/architecture-icons?tab=readme-ov-file#getting-stencil-libraries-compatible-with-drawio-application){: external}.

To start creating diagrams, open the draw.io application.

1. Select **Create New Diagram**, then click **Create**.
1. Go to **File** > **Open Library** and browse to your where you downloaded the {{site.data.keyword.cloud_notm}} stencils, select the XML file, and click **Open**.
1. Optionally, [add the {{site.data.keyword.cloud_notm}} service icons](#service-icons).
1. Create the layout of the diagram from left to right (west to east) to represent the public traffic flow orientation.

### Adding {{site.data.keyword.cloud_notm}} service icons
{: #service-icons}

The icons that are included in the {{site.data.keyword.cloud_notm}} catalog for each service are not part of the IBM2 library. However, if you want to represent an {{site.data.keyword.cloud_notm}} service with the catalog icon for that service in your architecture diagram @fredl has created a draw.io [{{site.data.keyword.cloud_notm}} catalog](https://l2fprod.github.io/myarchitecture/){: external} library of these icons.

1. Add the icon of choice to your palette. 

The icons size, color, background, and outline are reflecting the approved Design Language guidance. The icons are 20 x 20 px in a 48 x 48 px square container with white fill and a 1 px outline.

## Exporting your diagram to SVG output
{: #drawio-export}

1. Go to **File** >> **Export as** >> **SVG...**
2. Keep the defaults and also select **Transparent background**, **Embed images**, **Embed fonts**, and **Open in a New Window**.

Make sure that the **Include a copy of my diagram** is selected so that when you share the output with others they can open the diagram and edit it again when the SVG file is imported into diagrams.net.
{: important}
