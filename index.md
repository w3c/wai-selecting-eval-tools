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

Web accessibility evaluation tools are software programs or online services. They help determine if a Web site is accessible. This document highlights features of evaluation tools. It discusses different aspects of evaluation tools to consider when selecting these tools. 

Automated web accessibility evaluation tools are unable to test all accessibility criteria. Many aspects of accessibility need human verification. 

The [Web Accessibility Tool List](https://www.w3.org/WAI/ER/tools/) provides several features of evaluation tools. Some of these features include: 

- Guidelines
- Specific uses of the tool
- What authoring tools integrate with the evaluation tool
- API
- Browser plugin
- etc.

This document also discusses some specific usage of evaluation tools, such as:
- Reports
- Step-by-step evaluation
- In-page feedback
- Page transformation

Finally, this document offers further aspects to consider, such as:
- Organizational structure and development process
- Complexity and size of Web site
- Skills and knowledge of Web developers

*Disclaimer*: WAI encourages the development and evolution of Web accessibility evaluation tools. WAI maintains an extensive [list of evaluation, repair and transformation tools](https://www.w3.org/WAI/ER/tools/). WAI does not endorse or promote any single tool or vendor.

## What to expect from evaluations tools
{:#Expect}

Web accessibility evaluation tools can be a powerful part of a developer's arsenal. You can use evaluation tools through all phases of Web site development. They assist with determining the level of accessibility of Web sites. Evaluation tools can verify the conformance of Web sites for items that can be reviewed automatically. They can also help with manual reviews.

But we cannot check all aspects of a site's accessibility automatically. Human judgement is often required. Sometimes evaluation tools can produce false or misleading results. Web accessibility evaluation tools can not *determine* the accessibility of Web sites. They can only *assist* in doing so.

## Features of evaluation tools
{:#Features}

Web accessibility evaluation tools often have many features. The features are sometimes similar from one tool to another. Sometimes they are very different. 

The following features describe tools found on the [Web Accessibility Tool List](https://www.w3.org/WAI/ER/tools/). Analyse each tool carefully because not all tools implement all features adequately.

### Guidelines

Tools are developed to test a set of guideline checkpoints which verify conformance of a Web site. In the United States, the guidelines are WCAG 2.0 or Section 508. Guidelines that are available for other countries include France, Germany, Italy, Ireland, Japan, and others.

### Assists by

Lists what the specific uses of the tool, e.g. generating reports, providing step-by-step guidance, or displaying information within a web page

### Authoring tools

Lists which authoring tool the evaluation tool integrates with, e.g. MS Word, Adobe Acrobat, etc.

### Automatically checks

The scope of what the evaluation tool can test. Sometimes a single page. Other times entire groups of related pages.

### Language

The languages the evaluation tool supports.

### API

Describes which API are available, if any, e.g. Java, Rest, etc

### Browser Plugin

Lists the browsers for which a plugin exist, if any. Plugins can be important for workflow integration. But their parent application may constrain their usefulness.


### Supported formats

Lists the format the tool can test, e.g. HTML, CSS, PDF, etc.

### Online service

Which services are offered online, e.g. Online checker, Hosted services, or Server installation

### Report format

Lists the report format(s) the tool generates, e.g. HTML, CSV, Jira, PDF, XML, etc. 

### License

Which licenses the evaluation tool offers, e.g. Open Source, Commercial, Enterprise, etc.

### Accessibility information

People with disabilities can and do contribute to the Web. It is important that evaluation tools work for people with disabilities.

### Specific operation usages

Some web accessibility evaluation tools can be used in more than one way. The following are some common tool characteristics used to support the evaluation process:

- *Reports*. Reports generally provide information about many pages or whole sites. They are useful to determine the conformance of the checkpoints that can be automatically checked.

- *Step-by-step evaluations*. Wizard-based evaluation tools guide users through sequences of checks, step by step. They are able to conduct automated checks and prompt the user to manually assess the rest. For example a wizard-based tool may check images for alternate text. The user then evaluates how appropriate the alternate text is.

- *In-page feedback*. This feature inserts temporary icons and markup to display results of accessibility checks. They are useful to view issues in context. They are also useful to understand the relative importance of each issue.

- *Page transformation*. Transformation tools change the appearance of a site to help identify design issues. For example, the tool may show the site in text only or without color. These tools are useful to compensate for the limitations of automated testing.

## Further considerations
{:#Further}

There are many considerations to take into account when selecting an evaluation tool.

Each organization, project and team will have differing needs for different features.

Web designers could be looking for tools to analyse their design's accessibility performance. Web developers will prefer tools that help them assess their code. Web content authors have different requirements to help them complete their tasks. An organization may need a fully automated evaluation tool to track their whole Web site. Another organization may only need occasional spot checks.

You may wish to consider the following items when selecting an evaluation tool:

### Organizational structure and development process

Larger organizations may gain from using a combination of evaluation tools. Using a combination of tools could meet the various teams' needs during all stages of the project.

### Complexity and size of the Web site

Some complex sites could have a lot of multimedia content. Other complex sites could use advanced technologies such as SMIL or MathML. Specialized evaluation tools may be more useful for these sites, even if they may be more limited. 

### Skills and knowledge of the Web developers

Select the tool commensurate to the developer's skills. Some evaluation tools require users to have more knowledge of accessibility or code. Developers may also use some tools to increase their accessibility or code knowledge.

## Related pages
{:#related}









This document is part of a multi-page [Evaluating Web Accessibility
resource suite](#) that outlines different approaches for
evaluating Web accessibility.
