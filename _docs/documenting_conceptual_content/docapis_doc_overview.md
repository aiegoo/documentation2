---
title: API overview
permalink: /docapis_doc_overview.html
keywords:
course: "Documenting REST APIs"
weight: 6.1
sidebar: docapis
section: docconceptual
path1: /docconceptual.html
---

The API overview explains what you can do with the API, including the high-level business goals, the market needs or pain points it solves, who the API is for, and other introductory information.

{% if site.format == "web" %}
* TOC
{:toc}
{% endif %}

## Purpose of the API overview

Too often with API documentation (perhaps because the content is often written by developers), the documentation gets quickly mired in technical details without ever explaining clearly what the API is used for. Don't lose sight of the overall purpose and business goals of your API by getting lost in the endpoints.

{: .note2}

The API overview grounds users with a high-level understanding of the system. This high-level understanding is critical in order to grasp the system as a whole. It allows the details to fit into a broader conceptual framework.

To get an idea of what the API is about, users start at a high-level, getting a gist of what something is about from the title and description, and then work their way into more details. This overview provides this initial orientation for the user.

{% include course_image.html size="medium" border="true" filename="nonref_overview" ext_print="png" ext_web="svg" alt="API overview" caption="The API overview provides high-level detail about the purpose, audience, and market need for your API." %}

{: .tip}
For more details on the importance of high-level overviews, see [Reduction, layering, and distillation as a strategy for simplicity](https://idratherbewriting.com/simplifying-complexity/reduction-layering-distillation.html).

In the overview, list some common business scenarios in which the API might be useful. These scenarios will give users the context they need to evaluate whether the API is relevant to their needs.

{: .note2}

Keep in mind that there are thousands of APIs. If people are browsing your API, their first and most pressing question is, what information does it return? Is this information relevant and useful to my needs?

## Explain the market problems your API solves

In [The Top 20 Reasons Startups Fail](https://www.cbinsights.com/research/startup-failure-reasons-top/), one of the main reasons startups fail is their inability to solve a market problem. The authors explain:

> Startups fail when they are not solving a market problem. We were not solving a large enough problem that we could universally serve with a scalable solution. We had great technology, great data on shopping behavior, great reputation as a thought leader, great expertise, great advisors, etc, but what we didn’t have was technology or business model that solved a pain point in a scalable way. (*CB Insights*)

This overview focuses in on the market problem that the API solves. If your API fails, it's likely because it's not solving a market problem.

The API overview usually appears on the homepage of the API. The homepage (the start of your docs) is a good place to put this overview because in this overview you also define your audience. Understanding your audience helps you orient the content in your API documentation appropriately.

## Sample API overviews

Here are a few sample API overviews.

### SendGrid

{% include course_image.html url="https://sendgrid.com/docs/User_Guide/index.html" filename="sendgridoverview" ext_web="png" ext_print="png" alt="SendGrid API overview" caption="SendGrid API overview" %}

The Sendgrid overview starts with two key sections: "What is SendGrid?" and "Who is SendGrid for?" I like the straightforward approach. Even in the description of what SendGrid is, the authors don't assume everyone knows what an SMTP provider is, so they link out to more information. Overall, in about 10 seconds you can get an idea of what the SendGrid API is all about.

### Lyft

{% include course_image.html url="https://developer.lyft.com/docs/overview" filename="lyftapioverview" ext_web="png" ext_print="png" alt="Lyft API overview" caption="Lyft API overview" %}

Lyft's API overview starts in a similar way, with sections titled "What is Lyft?" and "Why Use Lyft as a Developer." Their homepage also provides information on access, rate limits and throttling, and testing. The Lyft authors also recognize that each tech domain has its own lingo, so they provide a [glossary](docapis_glossary_section.html) up front.

### IBM Watson Assistant

{% include course_image.html url="https://cloud.ibm.com/docs/services/assistant?topic=assistant-index#index" filename="ibmcloudoverview" ext_web="png" ext_print="png" alt="IBM Watson Assistant overview" caption="IBM Watson Assistant overview" %}

IBM Watson Assistant starts off with a brief summary of the service, followed by a high-level diagram of the system and a summary about how to implement it. Including a diagram of your API gives users a good grounding about what to expect, such as the level of complexity and time it will take to incorporate the API.

## <i class="fa fa-user-circle"></i> Activity with API overviews

{: .note3}

With the [open-source project you identified](docapis_find_open_source_project.html), identify the API overview. Then answer the following questions:

1. Does the documentation have an API overview?
2. Does the overview clarify who the API is for?
3. Does the overview indicate the market need or business problem the API solves?
4. What questions do you still have about the API after reading the overview?
5. How does the overview transition into a getting started tutorial or other first steps with the API?

{: .note2}
