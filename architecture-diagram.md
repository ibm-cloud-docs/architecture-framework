---

copyright:
  years: 2023, 2024
lastupdated: "2024-12-03"
keywords: 
subcollection: architecture-framework

---

{{site.data.keyword.attribute-definition-list}}


# Creating an architecture diagram
{: #architecture-diagram}

Every architecture solution should have an architecture diagram that shows the components of the solution, relationships between components, boundaries between elements, data flow, and so on.
{: shortdesc}

![Creating Architecture Diagrams Tutorial](https://www.kaltura.com/p/1773841/sp/177384100/embedIframeJs/uiconf_id/27941801/partner_id/1773841?iframeembed=true&entry_id=1_7wjh4y2c){: video output="iframe" data-script="#video-transcript-ui" id="mediacenterplayer" frameborder="0" width="560" height="315" allowfullscreen webkitallowfullscreen mozAllowFullScreen}

#### Video transcript
{: #video-transcript-ui}
{: notoc}

0:00 Hello and welcome to the draw.io native icon tutorial today, we're gonna show you how to get the IBM icons into your draw.io.

0:08 So if you come over here to the left side and the very bottom, it says more shapes, click on that and come down to networking.

0:15 You'll see there's two IBMs.

0:16 The IBM by itself is depreciated as it's version ones.

0:20 So we want to click on the IBM Cloud.

0:22 Once you highlight that you'll then notice when you come back to your main page that all of the icons are now on the left hand navigation bar by section.

0:33 So we'll have IBM compute, AI, actors.

0:36 We've got some data icons, we got some devops, networking.

0:40 And as you go down, open each one of these groups, you'll see more and more icons available.

0:45 So if you come up to the top to the groups, you can just grab an IBM Cloud group. Come over here, give it a little back fill. Let's put another group in there.

0:55 So let's maybe just grab a region.

0:58 There we go.

0:58 Grab the region, pull it over, put it in.

1:02 Now, typically you'd wanna highlight that in the gray.

1:04 So we'll show you how to do that in a little while.

1:06 Then you grab a user icon and let's grab a classic bare metal server and now we can connect them with the connector.

1:14 However, on the very bottom of the left hand side, we've also given you the IBM connectors that follow our standard nomenclature.

1:22 So we'll talk about that in another tutorial.

1:24 But this is where the icons and the connectors both come together.

1:29 As you can see, we grabbed a connector with dots on both ends and connect them both to the icons.

1:36 OK.

1:37 Let's talk about the complimentary icon repo these icons are not currently published in draw.io, will be published at a later time.

1:44 Their complementary icons will depreciate once those are published and they're used in conjunction with the published icon.

1:50 So we go over to the icon repo, the IBM Cloud Stencil repo.

1:54 You can see there's a lot of information on this page.

1:57 And as you scroll down, you see, there's tutorials, there's tools and conventions.

2:01 So this is where you'll find the colors, you'll find connectors, the metadata, any information that you need and some quick start tutorials also.

2:10 So if you click, come back to the top, click on the draw.io and then click on the stencils you'll see on the very bottom here.

2:16 There's a file called not released in draw.io.

2:19 So this is the complementary file of icons that we've created that have not been published by draw.io yet.

2:26 So click on the raw and come over here and then file save page as it'll be saved as a library not released in drew.io so add that to your folder, then it'll come back to draw.io file, come down to open the library from device, find that library, we just saved XML library and now you can see we have 3.0 the IBM icons that have not been released yet.

2:54 So these are complementary to the ones that there.

2:57 So for example, let's pull testing out of here, this testing icon in devops.

3:01 And if you go to devops, you'll see that that testing icon has not yet been published natively to draw.io.

3:07 So hence, we're providing you guys some additional icons that have not been published yet.

3:13 So you can see these are all alphabetical, starting with the groups and then moving through the different types of icons all grouped by color and alphabetical.

3:25 So let's talk about the search feature, top left corner of the nav bar, you'll see the search shapes and this will now work.

3:31 The search will work on both the complementary and the native icons.

3:38 Thanks to a lot of work done by my coworker Jose Monge.

3:42 So if you come here, let's search on the complimentary icons we'll put in wifi router.

3:48 And as you see, there's the wifi router showing up.

3:51 And then if we come down to the native icons, let's search for the Container Registry and as you can see type in Container Registry and it shows up.

4:01 So you need to look for the square mono colored boxes.

4:04 Those are the IBM icons.

4:06 Thanks again for your time and I hope this native draw.io IBM icons is very helpful to you.

4:13 It's taken a lot of time and a lot of our work by a lot of people to make this happen.

4:17 I will keep you posted on when the second set of complementary icons will be published.

4:21 So keep an eye out for that.

4:23 And thanks again.


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
