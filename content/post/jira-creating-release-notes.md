+++
author = "Vladimir Likhanov"
title = "Creating Release Notes in Jira"
date = "2021-09-26"
description = "Jira Software"
featured = true
tags = [
    "Hugo"
]
categories = [
    "Jira Software",
    "Release Notes",
]
thumbnail = "images/blog/hugo-bg.png"
+++

> In this post, we'll describe how to automatically create the release notes using standard Jira functionality.
If you are interested on how to automate this process with the **Release Management** application, click here.

The release notes are an accompanying document that is sent to the customers along with a new release.
They usually contain the information on the new features implemented in the release, improvements, fixed bugs,
and known issues, if any.

Depending on the company, this important document is prepared and published by different departments:

* Product managers
* Marketing managers
* Technical writers
* Developers
* etc.

When creating the release notes, you collect the information about all new features, improvements, fixed and
known issues in the upcoming release. After that, you need to discuss the collected issues with the
stakeholders (SMEs, product managers, etc.) and decide what information should be included in the document.
Finally, you have to transfer (copy and reword) the relevant content from the respective project tracking programs
to the program you use for creating the release notes (e.g., text editor or content managment system).

This process is rather time-consuming and usually happens shortly before the release when you and your
colleagues may have many other things to do: finish tests, fix last bugs, etc. This is where the automatic
release notes come in.

If you are using the Jira tracking software for managing your projects, you can use one of the following ways
to automate much of this process:

* Use Jira standard functionality
* Use functionality available in the **Release Management** application

## Creating release notes - Jira standard functionality

You can use standard functionality in Jira to create release notes for a specific version of a project. In this case,
the release notes will contain all features and issues within the project you specify as the value in the
**Fix versions** field, for example:

![Jira - filling out the "Fix versions" field](/images/blog/jira-fix-versions-field.png)

The release notes can also be generated in a number of formats (e.g. HTML, plain text, etc.) so as they can be included in various documents.
This process includes the following tasks:

* Creating a version for your release.
* Assigning the stories and tasks to the created release. (Mapping Jira issues to releases.)
* Generating the release notes ouf of the assigned stories and tasks.

## Creating a new release version

You normally create a new release version when ... But generally you can create a new version at any time and
add the necessary issues to it.

Using the Jira standard functionality, you can create release notes containing all issues for a specific
project that have a **Fix For** version value. These release notes can be in HTML or Markdown, using the
example templates included.

All you have to do is run a release report in Jira to see the progress of your release. This report shows
you how many total issues are in the current release broken down by the number in a completed status, in
progress or yet to do.

