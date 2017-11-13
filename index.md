---
layout: default
title: "Selecting Web Accessibility Evaluation Tools"
order: 1
---

## Page Contents

-   [Introduction](#introduction)
-   [What to expect from evaluation tools](#expect)
-   [Features of evaluation tools](#features)
-  [Further considerations](#further)
-   [Related pages](#related)


## Introduction
{:#introduction}

Web accessibility evaluation tools are software programs or online services that help determine if a website is accessible. This document highlights features of evaluation tools, and discusses different aspects to consider when selecting these tools. Links to different tools are provided in the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/).

## What to Expect from Evaluations Tools
{:#Expect}

Web accessibility evaluation tools can help you quickly identify potential accessibility issues. You can use them through all phases of the web design and development process. Tools can provide fully-automated checks, as well as help you with manual review.

But we cannot check all accessibility aspects automatically. Human judgement is often required. Sometimes evaluation tools can produce false or misleading results. Web accessibility evaluation tools can not *determine* accessibility, they can only *assist* in doing so.

## Features of Evaluation Tools
{:#Features}

Web accessibility evaluation tools target different audiences. This includes designers, developers, non-technical content authors, quality assurance testers, and sometimes also end-users. Tools tend to offer different features and functionality which may help users to compare and assess web accessibility evaluation tools for their specific needs.

The following features describe tools found on the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/). 

### Features You Can Use as a Filter

You may use the following features to reduce the number of evaluation tools listed.

* **Guidelines**  
Different organizations and governments may require conformance with different accessibility standards, thus different tools support these standards. The W3C Web Content Accessibility Guidelines (WCAG) is internationally recognized as the standard for web accessibility, and supported by most tools.

* **Language**  
Evaluation tools support different languages. This includes the user interface of the tools, as well as the language of the content they support (for example for detecting language-related barriers).

* **Type of Tool**  
Lists the platform and type of tools that are available, e.g. authoring tool or browser plugin, command line, desktop or mobile application.

* **Supported Formats** 
Lists the format the tool can test, e.g. HTML, CSS, PDF, etc.

* **Assists by**  
Some web accessibility evaluation tools can be used in more than one way. The following are some common characteristics used to support the evaluation process:

  * *Reports* are useful to determine the conformance of the checkpoints that can be automatically checked.
  
  * *Step-by-step evaluations*. Wizard-based evaluation tools guide users through sequences of checks. They conduct automated checks and prompt the user to manually assess the rest. For example a wizard-based tool may check images for alternate text. The user then evaluates how appropriate the alternate text is.

  * *In-page feedback*. This feature inserts temporary icons and markup to display results of accessibility checks. They are useful to view issues in context. They are also useful to understand the relative importance of each issue.

  * *Page transformation* Transformation tools change the appearance of a site to help identify design issues. For example, the tool may show the site in text only or without color. These tools are useful to compensate for the limitations of automated testing.

* **Automatically Checks**  
The scope of what the evaluation tool can automatically test. Sometimes a single page. Other times entire groups of related pages. Some can also access password-restricted content.

* **License**  
Which licenses the evaluation tool offers, such as Open Source, Commercial, Enterprise, etc.

### More Detailed Features

* **Authoring Tools**  
Lists which authoring tool the evaluation tool integrates with. Such plugin tools often assist non-technical content authors to check the content they are creating directly within their authoring tools. These include MS Word, Adobe Acrobat, content management systems, as well as other tools.

* **API**  
Some authoring and quality assurance tools can access some evaluation tools directly. The evaluation tools offer different types of APIs to allow this interaction. 

* **Browser Plugin**  
Lists the browsers for which a plugin exists, if any. Such plugins may assist web designers, quality assurance testers, and evaluation experts to check content directly within the browser.

* **Online Service**  
Evaluation tools provide different types of online services:

  * *Online checkers* often are websites where you can enter your own website's address to get it checked. Sometimes this may also be a web service accessed through an API by authoring or quality assurance tools.
  
  * *Hosted services* can regularly check your entire website and provide reports on improvements over time. They may also offer other solutions for enterprises. Usualy these require subscription with the tool vendor.
  
  * *Server installation* of some evaluation tools provides an integrated way to check the entirety of your website on your internal network. They can sometimes check password-restricted or draft content. 

* **Report Format**  
Lists the report format(s) the tool generates, e.g. HTML, CSV, Jira, PDF, XML, etc. 

* **Accessibility Information**  
People with disabilities can and do contribute to the Web. It is important for evaluation tools to be accessible for people with disabilities. Some tools provide information on how well they support accessibility.


## Further Considerations
{:#Further}

There are many considerations to take into account when selecting an evaluation tool.

Each organization, project and team will have differing needs for different features.

Web designers could be looking for tools to analyse their design's accessibility performance. Web developers will prefer tools that help them assess their code. Web content authors have different requirements to help them complete their tasks. An organization may need a fully automated evaluation tool to track their whole Web site. Another organization may only need occasional spot checks.

You may wish to consider the following items when selecting an evaluation tool:

### Organizational Structure and Development Process

Development teams may gain from using a combination of evaluation tools. Using a combination of tools could meet the various teams members' needs during all stages of the project.

### Complexity and Size of the Web Content

Some complex sites could have a lot of multimedia content. Other complex sites could use advanced technologies such as SMIL or MathML. Specialized evaluation tools may be critical for these websites. 

### Skills and Knowledge of the Web Developers

Select the tool commensurate to team's skills. Some evaluation tools require users to have more knowledge of accessibility or code. Some tools also help to increase accessibility or code knowledge.
