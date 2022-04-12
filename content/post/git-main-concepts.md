+++
author = "Vladimir Likhanov"
title = "Working with Git - basics"
date = "2022-03-31"
description = "Git"
featured = true
draft = true
tags = [
    "Git"
]
categories = [
    "Git"
]
thumbnail = "images/blog/git/git-logo.png"
+++

> This post introduces the basic operations you perform when working with Git: initializing a Git repository,
adding a new file to it, staging and committing your changes to the repository.

The diagram below demonstrates the basic Git workflow.

The main steps you usually perform when working with Git are listed below. To learn more about a particular step, click on the corresponding link:

1. You [create a new file](#creating-file) or modify an existing one in the Git working directory.

2. You add the new / modified file to the Git staging area. The staging area is where you prepare your files for committing to the repository.

3. You commit the new / modified file to the Git local repository. By performing a commit to the local repository, you save the current state of your files.

4. You push your local changes to a remote repository. It can be GitHub, GitLab, BitBucket, or another Git-specific repository.

## Checking prerequisites

Before we get started, let's quickly discuss what you'll need to follow along with the steps described in this article. We
assume the following:

* You've just started working on your new website.

* You've decided to use Git when developing the website.

* You've created a new folder - **my-website** - for storing all website-related files.

* You've installed and configured Git on your local computer. If you have not, refer to [Setting up Git](/post/git-introduction)
to learn how you can install Git before continuing with the steps in this article.

* If you are on a Windows computer, you use Git Bash to work with Git and perfom Git-related commands.

## <a name="creating-file"></a> Creating a Git repository and adding files

We'll start with creating (initializing) a new Git repository on our computer. This local repository will store all files for our website.

1. Change to the **my-website** folder. This folder is known as a working directory. That means that this folder contains all files you are currently working on.

        ~> cd 'C:\my-website'

2. Initialize the repository:

        ~> git init
        Initialized empty Git repository in C:/my-website/.git/

Now you can create the **index.html** file and add it to your local repository.

1. 

![Downloading Git for Windows](/images/blog/git/git-downloading-windows-version.png)

2. Click the **Windows** link in the **Download** section.

* The **Download for Windows** page opens.

![Choosing the right Git version for Windows](/images/blog/git/git-choosing-installation-file.png)

3. Click one of the links to download the right version for your system.

4. Once the download is complete, double-click the installation file.

* The installer window opens.

5. Follow the on-screen instructions to install Git. You can stick to the default settings
offered by the installer.

## <a name="verifying-installation"></a>Verifying the Git installation

Your Git installation on Windows comes with a tool called Git Bash. You can use this tool
to work with Git in the command prompt.

> If you are using a Linux distribution or a MacOS, your system should already come with a
built-in terminal where you can run Git commands. On Mac, you can click the magnifying glass
at the top right of your desktop, type **Terminal**, select the terminal from the list of
applications, and press Enter. On Linux, press Ctrl-Alt-T to open the terminal window.

Let's use Git Bash to verify your Git installation:

1. Click **All apps** - **Git** - **Git Bash** on the Windows **Start** menu.

* The Git Bash application opens.
* You see the command prompt.

![Opening the Git Bash application](/images/blog/git/git-bash-windows.png)

2. Type the following command and press Enter:

        ~> git --version
        git version 2.33.0.windows.2

If your output looks similar to the one above - that is, you see the version of Git, you've successfully
installed Git on your computer and can proceed with the next step.

## <a name="configuring-credentials"></a>Preparing to work with Git

Before you can start working with Git, you need to configure some of its settings. Git
requires at least your name and email address to be specified. To configure these settings,
launch Git Basch and execute these commands:

* Setting your name:

        ~> git config user.name "John Doe"

* Setting your email address:

        ~> git config user.email "john.doe@email.com"

You can check that the settings have been successfully set with this command:

        ~> git config --list
        ...
        user.email=john.doe@email.com
        user.name=John Doe

Now that you have configured your user credentials, you are ready to start using Git for
tracking your content.