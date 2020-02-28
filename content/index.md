---
layout: default
title: "Selecting Web Accessibility Evaluation Tools"
permalink: /test-evaluate/tools/selecting/
github:
  repository: w3c/wai-selecting-eval-tools
footer: >
  <p><strong>Date:</strong> Updated 23 December 2017.</p>
  <p><strong>Editors:</strong> <a href="http://www.w3.org/People/shadi">Shadi Abou-Zahra</a>, Nicolas Steenhout, and Laura Keen.</p>
  <p>Developed by the Education and Outreach Working Group (<a href="http://www.w3.org/WAI/EO/">EOWG</a>).</p>

---


{::nomarkdown}
{% include box.html type="start" h="2" title="Introduction" class="full" %}
{:/}

Web accessibility evaluation tools are software programs or online services that help determine if web content meets accessibility guidelines. This document highlights features of evaluation tools, and discusses different aspects to consider when selecting these tools. Links to different tools are provided in the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/).

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" class="full" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## What Evaluation Tools Can Do and Can *Not* Do
{:#cannot}

Web accessibility evaluation tools can help you quickly identify potential accessibility issues. You can use them through all phases of the web design and development process. Tools can provide fully-automated checks, and help you with manual review.

We cannot check all accessibility aspects automatically. Human judgement is required. Sometimes evaluation tools can produce false or misleading results. Web accessibility evaluation tools can not *determine* accessibility, they can only *assist* in doing so.

## Features of Evaluation Tools
{:#features}

Web accessibility evaluation tools target different audiences. This includes designers, developers, non-technical content authors, quality assurance testers, and sometimes also end-users. Tools offer different features and functionality which may help users to compare and assess web accessibility evaluation tools for their specific needs.

### Main Features

The following features describe tools found on the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/). These can be used as filters to reduce the number of tools shown.

* **Guidelines**<br>
Different organizations and governments may require conformance with different accessibility standards, thus different tools support these standards. The W3C Web Content Accessibility Guidelines (WCAG) is internationally recognized as the standard for web accessibility, and supported by most tools.

* **Language**<br>
Evaluation tools support different languages. This includes the user interface of the tools, as well as the language of the content they support (for example, for detecting language-related barriers).

* **Type of Tool**<br>
Evaluation tools can be plugins (extensions) for authoring tools and web browsers, command line tools, desktop or mobile applications, and online services. Different tools may be combined, depending on your design and development process.

* **Supported Formats**<br>
Most evaluation tools check the accessibility of HTML content. Some check other web technologies, such as WAI-ARIA, CSS, SVG, and PDF.

* **Assists by**<br>
Some web accessibility evaluation tools can be used in more than one way. The following are some common characteristics used to support the evaluation process:

  * *Reports* are useful to determine the conformance of the checkpoints that can be automatically checked.

  * *Step-by-step evaluations*: Wizard-based evaluation tools guide users through sequences of checks. They conduct automated checks and prompt the user to manually assess the rest. For example, a wizard-based tool may check images for alternate text. The user then evaluates how appropriate the alternate text is.

  * *In-page feedback*: This feature inserts temporary icons and markup to display results of accessibility checks. They are useful to view issues in context. They are also useful to understand the relative importance of each issue.

  * *Page transformation*: Transformation tools change the appearance of a site to help identify design issues. For example, the tool may show the site in text only or without color. These tools are useful to compensate for the limitations of automated testing.

* **Automatically Checks**<br>
The scope of what the evaluation tool can automatically test varies depending on the tool. Some tools check a single page, while others check entire groups of related pages. Some can also access password-restricted content.

* **License**<br>
Evaluation tools are available under a variety of license types, such as Open Source, Commercial, Enterprise, etc.

* **Accessibility Information**<br>
It is important that evaluation tools are accessible so that people with disabilities can use them. Some tools provide information on how well they support accessibility.

### More Detailed Features

The following features are other options available in evaluation tools. Some features listed are available in the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/) under Type of Tool.

* **Authoring Tool Plugins**<br>
Such plugin tools often assist non-technical content authors to check the content they are creating directly within their authoring tools. These include MS Word, Adobe Acrobat, content management systems, as well as other tools.

* **API**<br>
Some authoring and quality assurance tools can access some evaluation tools directly. The evaluation tools offer different types of APIs to allow this interaction.

* **Browser Plugin**<br>
Such plugins may assist web designers, quality assurance testers, and evaluation experts to check content directly within the browser.

* **Online Service**<br>
Evaluation tools provide different types of online services:

  * *Online checkers* often are websites where you can enter your own website's address to get it checked. Sometimes this may also be a web service accessed through an API by authoring or quality assurance tools.

  * *Hosted services* can regularly check your entire website and provide reports on improvements over time. They may also offer other solutions for enterprises. Usually these require subscription with the tool vendor.

  * *Server installation* of some evaluation tools provides an integrated way to check your entire website on your internal network. They can sometimes check password-restricted or draft content.

* **Report Format**<br>
Many tools generate report formats such as HTML, CSV, PDF, XML, etc.

## Further Considerations
{:#further}

There are many considerations to take into account when selecting an evaluation tool.

Each organization, project, and team has differing needs for different features.

Web designers could be looking for tools to analyze their design's accessibility performance. Web developers will prefer tools that help them assess their code. Web content authors have different requirements to help them complete their tasks. An organization may need a fully automated evaluation tool to track their whole website. Another organization may only need occasional spot checks.

You may want to consider the following items when selecting an evaluation tool:

### Organizational Structure and Development Process

Development teams may gain from using a combination of evaluation tools. Using a combination of tools could meet the various team members' needs during all stages of the project.

### Complexity and Size of the Web Content

Some complex sites could have a lot of multimedia content. Other complex sites could use advanced technologies such as SMIL or MathML. Specialized evaluation tools may be critical for these websites.

### Skills and Knowledge of the Web Developers

Select the tool commensurate to team's skills. Some evaluation tools require users to have more knowledge of accessibility or code. Some tools also help to increase accessibility or code knowledge.
