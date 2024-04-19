---

copyright:
  years: 2023
lastupdated: "2023-05-02"

keywords:

subcollection: architecture-framework

---

{{site.data.keyword.attribute-definition-list}}


# Documenting your architecture decisions
{: #document-decisions}

After you evaluate the component options, you can use architecture decision template to document the components evaluated, the decision criteria, and the component chosen for your solution based on the assessment performed when selecting the components.
{: shortdesc}

You should have one or more architecture decisions for each of the applicable domains that are highlighted in the solution architecture heat map mapped to your solution requirements.

Documenting the architecture decisions is important for several reasons:

- To provide traceability across the solution or application lifecycle and a historical record of why a particular decision was made.
- To capture interdependencies across solution components.
- To create the Bill of Materials (BoM) for your solution and build your cost case.
- To estimate delivery timelines and perform risk assessments.
- To transition to your application or build teams for delivery, detailed design, or scrum activities.

## Architecture decisions template
{: #decision-template}

The following template is in markdown markup.

Listing of components and their purpose in the architecture should include what requirement the component meets, what component was chosen for this architecture, the reasons for the choice, and any alternative choices considered. These alternative choices _should_ be components or modules that have been tested to swap out.

If the architecture is large and includes several rows of the heat map, consider grouping each row in the design requirements heat map as an H3 section. Include a table for just that row where the caption represents that title. For example, `### Security decisions`. Otherwise, use a single table and row subsections.

```markdown
# Components
{: #components}

| Requirement | Component | Reasons for choice | Alternative choice |
|-------------|-----------|--------------------|--------------------|
|             |           |                    |                    |
{: caption="Table 1. Architectural decisions" caption-side="bottom"}
```
