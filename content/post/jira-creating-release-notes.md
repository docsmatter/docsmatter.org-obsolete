+++
author = "Vladimir Likhanov"
title = "Creating Release Notes in Jira"
date = "2021-10-01"
description = "Jira"
featured = true
draft = true
tags = [
    "Hugo"
]
categories = [
    "Jira",
    "Release Notes",
]
thumbnail = "images/blog/hugo-bg.png"
+++

> In this post, we'll describe how to automatically create the release notes using standard Jira functionality.


The release notes are an accompanying document that is sent to the customers along with a new release.
They usually contain the information on new features, improvements, fixed bugs, and known issues, if any.

Depending on the company, this important document is prepared and published by different departments:

* Product managers
* Marketing managers
* Technical writers
* Developers
* etc.

When creating the release notes, you collect the information about all implemented features and improvements in the
upcoming release as well as fixed bugs and known issues. After that, you discuss the collected topics with the
respective stakeholders (SMEs, product managers, etc.) and decide what information to include in the document.
Finally, you transfer (copy and sometimes reword) the relevant content from the respective project tracking systems
to the application you use for creating the release notes (e.g., text editor or content management system).

This whole process is rather time-consuming and usually happens shortly before the release when you and your
colleagues may have many other things to do: finish tests, fix last bugs, etc. This is where the automatic
release notes come in.

If you are using the Jira tracking software for managing your projects, you can use one of the following ways
to automate the process of creating release notes:

* Use Jira standard functionality
* Use functionality available in the **Release Management** application

## Creating release notes - Jira standard functionality

You can use standard functionality in Jira to create release notes for a specific version of a project. In this case,
the release notes will contain all features and issues within the project you specify as the value in the
**Fix versions** field, for example:

![Jira - filling out the "Fix versions" field](/images/blog/jira-fix-versions-field.png)

You can generate the release notes in the HTML or Markdown format and integrate them in various documents (e.g., create
a Word document on their basis or publish them on your website).

Using Jira standard functionality to create release notes usually includes the following tasks:

* Creating a new version for your release.
* Assigning the stories and tasks to the created release. (Mapping Jira issues to releases.)
* Generating the release notes out of the assigned stories and tasks.

## Creating release notes - example

The following example demonstrates how to create the Markdown version of release notes:

1. Open the desired project in Jira and go to the **Releases** menu.

    * The **Releases** page opens displaying all available release versions.

2. If you do not have a release version for generating the release notes, create it by using on the **Create version** button.

3. Click on the name of your release version.

    * The **Version-Name-of-Your-Project** page opens containing all the issues currently included in your release. All you have to do is run a release report in Jira to see the progress of your release. This report shows you how many total issues are in the current release broken down by the number in a completed status, in progress or yet to do. These issues will be included in the release notes?
    
4. Click on the **Release notes** button at the top of the page.

    * The **Release notes** page opens. The central part lists all issues included in the release notes.

5. In the **Format** section, click on the down arrow and select the **Markdown** entry.

6. In the **Layout** section, activate the **No issue key** radio button as the issue keys are not relevant for our customers.

7. Click the **Regenerate notes** button.

8. If the **Reset release notes** window is displayed, click **Regenerate** to confirm your action.

    * The release notes are regenerated in the Markdown format and do not contain issues key now.