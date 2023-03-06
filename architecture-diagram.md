---

copyright:
  years: 2023
lastupdated: "2023-03-06"
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

IBM Cloud provides a library of stencils and shapes through draw.io. This makes it so that all diagrams are using a standard set of shapes, colors, and flows.

IBM stencils/shapes can be of any of the following formats:

- Boxes (under / as groups too) which represent a deployedOn relationship for locations (logical, virtual, physical) of platforms, infrastructure, network, etc, on which services and applications are deployed.
- Groups which represent a deployedTo relationship for grouping services and applications deployed on boxes.
- Nodes which are meant to represent standalone components or devices.

For example, a virtual server instance is deployed on a subnet and deployed to a security group.

The stencils are also organized by type, function, or purpose by using the following categories:

- IBM (Core): Components that are typically technology and brand independent and/or not associated with an specific IBM Cloud offering/service. Examples: Server, Router, Database, Application
- IBM Cloud: IBM Cloud specific offerings and services. Examples: IBM VPC, Classic VSI, Serverless, Internet Services, Security-Group.
- IBM Domains/Industries: Extensions focused on IBM specific non-Cloud domains and industries. Examples: Automotive, Retail, Blockchain, Watson.
- 3rd Party: Third party products/services. Examples: VMware, BigFix, Akamai.

## Watch the Draw.io Tool Tutorial
{: #video-tutorial}

![Draw.io Tool Tutorial](https://video.ibm.com/embed/recorded/132605612){: video output="iframe" data-script="none" id="ibmmediaplayer1" width="560" height="315" scrolling="no" allowfullscreen webkitallowfullscreen mozAllowFullScreen frameborder="0" style="border: 0 none transparent;"}

## Installing ibm2beta2.draw.io
{: #ibm2beta2}

The new IBM2 library was built in collaboration with IBM Design Language. While this library is in progress of getting added to the public diagrams.net code, it is recommended that you install the `ibm2beta2.draw.io` from [it-architecture-diagrams](https://github.com/IBM/it-architecture-diagrams) >> **Releases** so that you can start creating diagrams with IBM2 and any future updates. Updates that have been released, but not yet incorporated into the public diagrams.net code will continue to release here first.

Although there is an online version of draw.io available, this version is currently **not** approved for use within IBM. 
{: important} 

For an intro tutorial for using Draw.io, see [Draw.io diagrams, IBM Cloud icons and style with templates](https://secure.video.ibm.com/channel/23586917/video/131812498). 

## Creating your diagram
{: #drawio-diagram}

To start creating diagrams, open the `ibm2beta2.draw.io` application.

1. When creating a new diagram select the **IBM** template.
1. If it is your first time creating a diagram, add the IBM library by clicking **+ More Shapes** and select **IBM**.
1. Optionally, [add the {{site.data.keyword.cloud_notm}} service icons](#service-icons).
1. Create the layout of the diagram from left to right (west to east) to represent the public traffic flow orientation.

### Adding {{site.data.keyword.cloud_notm}} service icons
{: #service-icons}

The icons that are included in the {{site.data.keyword.cloud_notm}} catalog for each service are not part of the IBM2 library. However, if you want to represent an {{site.data.keyword.cloud_notm}} service with the catalog icon for that service in your architecture diagram @fredl has created a draw.io [IBM Cloud Catalog](https://l2fprod.github.io/myarchitecture/) library of these icons.

1. Add the icon of choice to your palette. 

The icons size, color, background, and outline are reflecting the approved Design Language guidance. The icons are 20 x 20 px in a 48 x 48 px square container with white fill and a 1 px outline.

## Exporting your diagram to SVG output
{: #drawio-export}

1. Go to **File** >> **Export as** >> **SVG...**
2. Keep the defaults and also select **Transparent background**, **Embed images**, **Embed fonts**, and **Open in a New Window**.

Make sure that the **Include a copy of my diagram** is selected so that when users download the image they can open the diagram and edit it again when the SVG file is imported into diagrams.net.
{: important}
