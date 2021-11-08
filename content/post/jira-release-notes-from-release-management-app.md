+++
author = "Vladimir Likhanov"
title = "Jira - release notes from the Release Management app"
date = "2021-11-08"
description = "Jira"
featured = true
draft = true
tags = [
    "Jira"
]
categories = [
    "Jira",
    "Release Notes",
]
thumbnail = "images/blog/jira-bg.png"
+++

> In this post, we'll take a look at how to create release notes from Jira using the **Release Management**
app. You are interested in creating the release notes using standard Jira functionality, click
[here](/post/jira-creating-release-notes/).

If your company is using the [Release Management](https://marketplace.atlassian.com/apps/1221946/release-management-roadmap-jira-cloud?tab=overview&hosting=cloud)
app to manage, plan, and control your software releases, you can use its functionality and generate the release notes out of this app.

The release notes generator included in this app provides you with the possibility to create your own templates or customize existing ones. You can ...

## Default templates

The following example describes how to generate the release notes in the **Release Management** app using one of the default templates. To follow along with the
example below, you first need to complete the following steps:

* Install and activated the **Release Management** app in your Jira installation.
* Create at least one project in your system.

Once you are done with steps above, perform the following operations:

> If you aleady have one or more release boards, you can skip the first three steps.

1. Click on the **Release Management** menu in the left Jira navigation.

2. Create a release board using the **Create board** button. For the board, you just need to provide a name and choose the desired project.

![Jira - creating a new release board](/images/blog/jira/jira-creating-release-board.png)

* After the new board has been created, it is displayed at the top of the **Release Boards** page.

![Jira - displaying the created board](/images/blog/jira/jira-displaying-created-board.png)

3. Click on the board name.

* The **Release Management** app opens and you are redirected to the **Versions** tab.

4. Click on the **Release notes** tab.

* The list of default templates provided with the app is displayed.

![Jira - list of default templates in the Release Management app](/images/blog/jira/jira-default-templates.png)

5. Click on the **Generate Notes** button opposite the **Default Version Release Notes Template**.

* The **Generate Notes** window opens.

6. Make sure that the name of the release for which you want to generate the release notes is selected in the
**Version** field and click on the **Generate Notes** button.

![Jira - generating the release notes for the selected release version](/images/blog/jira/jira-generating-release-notes.png)

* After a while, the generated release notes are shown in the **Generates Notes** window.

![Jira - viewing the generated release notes](/images/blog/jira/jira-viewing-generated-release-notes.png)

In the next step, we'll customize the default template to make the generated release notes meet our needs.