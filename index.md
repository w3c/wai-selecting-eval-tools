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

Web accessibility evaluation tools can help you quickly identify potential accessibility issues. You can use them through all phases of the web design and development process. Tools provide fully-automated checks, as well as help you with manual review.

But we cannot check all accessibility aspects automatically. Human judgement is often required. Sometimes evaluation tools can produce false or misleading results. Web accessibility evaluation tools can not *determine* accessibility, they can only *assist* in doing so.

## Features of Evaluation Tools
{:#Features}

Web accessibility evaluation tools target different audiences. This includes designers, developers, non-technical content authors, quality assurance testers, and sometimes also end-users. Tools tend to offer different features and functionality which may help users to compare and assess web accessibility evaluation tools for their specific needs.

The following describes tool features found on the [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/). 

* **Guidelines**  
Different organizations and governments may require conformance with different accessibility standards, thus different tools support these standards. The W3C Web Content Accessibility Guidelines (WCAG) is internationally recognized as the standard for web accessibility, and supported by most tools.

* **Language**  
The support for different languages provided by evaluation tools. This includes the user interface of the tools, as well as the language of the content they support (for example for detecting language-related barriers).

* **Type of Tool**  
Evaluation tools can be plugins (extensions) for authoring tools and web browsers, command line tools, desktop or mobile applications, and online services. Diffent tools may be combined, depending on your design and development process.

* **Supported Formats**
Most evaluation tools check the accessibility of HTML content. Some also support other web technologies, such as WAI-ARIA, CSS, SVG, and PDF.

* **Assists by**  
Some web accessibility evaluation tools can be used in more than one way. The following are some common tool characteristics used to support the evaluation process:

** *Reports*. Reports generally list issues identified on many pages or whole sites. They are useful to help developers focus their attention on potential conformance issues can be automatically checked.

** *Step-by-step evaluations*. Wizard-based evaluation tools guide users through sequences of checks, step by step. They are able to conduct automated checks and prompt the user to manually assess the rest. For example a wizard-based tool may check images for alternative text. The user then evaluates how appropriate the alternative text is.

** *In-page feedback*. These tools, usually online services, insert temporary icons and markup to display results of accessibility checks within the actual pages. They are useful to view issues in context. They are also useful to understand the relative importance of each issue.

** *Page transformation*. Transformation tools change the appearance of the content to help identify design issues. For example, the tool may show the site in text only or without color. These tools are useful to compensate for the limitations of automated testing.

* **Automatically Checks**  
The scope of automatic crawling that evaluation tools support. Sometimes single pages, and other times entire groups of pages. Some tools can crawl groups of entire websites. Some can also access password-restricted content.

* **License**  
Which licenses the evaluation tool offers, such as Open Source, Commercial, Enterprise, and other options

* **Accessibility Information**
People with disabilities can and do contribute to the Web. Evaluation tools should therefore also be accessible for people with disabilities. Some tools provide information on how well they support accessibility.

### Detailed Tool Features

The [Web Accessibility Evaluation Tools List](https://www.w3.org/WAI/ER/tools/) provides more specifics for some of the tool features listed above. These can be viewed after expanding the "Detailed Information" tab of the listed tools. These detailed tool features include:

* **Authoring Tools**
Lists the authoring tools that an evaluation tool can be integrated with. Such plugin tools often assist non-technical content authors to check the content they are creating directly within their authoring tools, including content management systems.

* **Browser Plugin**
Lists the web browsers that an evaluation tool can be integrated with. Such plugin tools often assist web designers, quality assurance testers, and evaluation experts to check the content as it is presented, directly within different web browsers.

* **Online Service**
Evaluation tools provide different types of online services:

** *Online checker* Often this is a website where you can enter the address of your own website, to get it checked. Sometimes this may also be a web service that is accessed through an API by authoring and quality assurance tools.

** *Hosted service* Some evaluation tools can regularly check your entire website and provide you with reports on improvements over time, and other solutions for enterprises. Usually these require subscription with the tool vendor.

** *Server installation* Some evaluation tools can be installed within your own network, to provide features of hosted services. These can sometimes also check password-restricted content and draft content before it is published.

* **API**
Some evaluation tools, in particular online checkers, can be accessed directly as a service by other software, such as authoring and quality assurance tools. They support different types of APIs, to allow this interaction between tools.

* **Report Format**
Many tools provide reports. However, these reports vary significantly. Usually they are intended to be read by human evaluators and developers, and are in HTML or PDF format. Other times they are intended to be machine-readable, and are in [EARL](https://www.w3.org/WAI/intro/earl), XML, CSV, and other formats.

## Further Considerations
{:#Further}

There are many considerations to take into account when selecting evaluation tools. Each organization, project, and team will have differing needs for different features. Web designers could be looking for tools to analyse the accessibility of their designs. Web developers will prefer tools that help them assess their code. Web content authors have different requirements to help them publish accessible content. An organization may need a fully automated evaluation tool to track their whole website. Another organization may only need occasional spot checks.

You may wish to consider the following items when selecting an evaluation tool:

* **Organizational Structure and Development Process**
Development teams may gain from using a combination of evaluation tools. Using a combination of tools could meet the various teams members' needs during all stages of the project.

* **Complexity and Size of the Web Content**
Some websites could have a lot of multimedia content. Other websites could use advanced technologies such as SMIL or MathML. Specialized evaluation tools may be critical for these sites. 

* **Skills and Knowledge of the Project Team**
Select the tool commensurate to the skills of your team. Some evaluation tools require users to have more knowledge of accessibility or code. Some tools also help to increase accessibility or code knowledge.
