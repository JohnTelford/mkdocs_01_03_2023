---
title: Develpopment Tools
---

## VScode 

<!--
![vscodelogo](/img/vscodelogo.png)
-->

<img src="/img/vscodelogo.png" width="100"/>


[Visual Studio Code](https://code.visualstudio.com) (VScode) is a Microsoft product.

It has become the goto editor for many. It is free, built on open source, and runs everywhere.

[VScode](#vscode) is the command and control center for the website development stack.

The development command and control tasks are:

- Editing Markdown and Markdown web programming materials
- Use [git](#git) and [GitHub](#github) to manage project files. [Git](#git) is built-in and optimized to work with Microsoft [GitHub](#github)
- Editor tool extensions continually check for syntax and other errors
- Live edit browser previews show how edits will look when deployed
- Deploy secure website previews to the Internet for stakeholders
- Deploy production website to the Internet
- Built-in command shell
- And **much** more

### Extensions

Useful extensions are:

- Dark+ Material.  
The default Dark+ theme, using Material's color palette

- ESlint.  
Integrates ESLint JavaScript into VS Code

- [GitHub](#github) Repositories.  
Remotely browse and edit any [GitHub](#github) repository

- Lorem Text Generator  
Lorem text generator extension for [VScode](#vscode)

-  Markdown All in One  
All you need for Markdown (keyboard shortcuts, table of contents, auto preview and more)

- Rainbow Brackets  
Provide rainbow colors for the round brackets, the square brackets and the squiggly brackets

- Todo Tree  
This extension quickly searches the local repository workspace for comment tags like TODO and FIXME, and displays them in a tree view in the activity bar

- [VScode](#vscode)-icons  
Icons for Visual Studio Code

#### Git Client

[VScode](#vscode) built-in git commands :

 - Review diffs, 
 - Stage files
 - Make commits
 - Push 
 - pull
 - and more

## Git Desktop

![Git Desk Top](/img/gitdesktop.png)

An alternative to using these built-in [VScode](#vscode) commands is to use [GitHub Desktop](https://docs.github.com/en/desktop). It abstract [Github](#github) and more [Git](#git) commands. It interacts with GitHub using a GUI instead of the command line or a web browser. 

[GitHub Desktop and VSCode](http://www.rodanthi-alexiou.com/github-101-github-desktop-and-vscode/) documents how to use GitHub Desktop with [VScode](#vscode). 

---

## Git and GitHub References

:::tip

These [Git](#git) and [Github](#github) references contain concepts and commands:

- [Version Control System](https://www.w3docs.com/learn-git/introduction4.html)
- [VScode](#vscode) built-in gitg commands
- [Git version-control tools in Visual Studio Code](https://docs.microsoft.com/en-us/learn/modules/use-git-from-vs-code/)
- [Git and GitHub Introduction](https://www.w3schools.com/git/git_intro.asp?remote=github)
- [Git](https://git-scm.com/book/en/v2)
- [GitHub](https://docs.microsoft.com/en-us/learn/modules/introduction-to-github/)
- [GitHub Desktop](https://docs.github.com/en/desktop)

:::

## GitHub

<img src="/img/gitHublogo.png" width="100"/>


The core technologies of Iterative Development are, [Git](#git) and GitHub. The central project repository is controlled by the project gatekeeper, and a content delivery network, like [Cloudflare](#deploy/cloudflare), where Internet production websites and individual team private [Preview](deploy#preview) Internet websites, are deployed.

GitHub is a Distributed Version Control Systems enabling multiple teams to work separately on the same project without having an impact on the work of others. GitHub manages an online web hosted central project repository containing all project files. It is a unified source of truth. It helps teams collaborate and maintain the entire history of project file changes.

> It helps answer the questions for the lifetime of the project *who changed what, where, when, and why?* 

Team members use the [Website Development Stack](website-development-stack) to develop and deploy websites to the Internet.

### The GitHub Workflow

GitHub workflow is centered on Pull Request The GitHub workflow works with collaborating team members contributing to the central project repository using the Forks. It is centered on the topic Branches workflow.

A summary of GitHub workflow for each team member is:

1. Fork the central project repository creating a local project repository in individual team members GitHub account
2. Clone the forked local project repository in team member GitHub account to workstation
1. Creates a topic Branch off the cloned local project repository *main* branch
1. Make topic edits and commits 
2. Push after each commit to the cloned local project repository in GitHub account
3. Periodically Pull from the central project repository. The *develop* branch will have merged accepted Pull Requests
4. Periodically deploy local project repository to a private [Preview ](deploy#preview) website without disturbing other developers work or the production version, for stake holders viewing and feedback. This reduces the Pull Request evaluation time because stake holders interested in topics can see how they are progressing and working with the website.
4. Open a Pull Request on the GitHub local project repository to begin the  process of integrating the local project repository with the central project repository  
1. Team members discuss, and optionally continue committing on Pull Requests.

The project gatekeeper merges or closes Pull Requests to the central project repository, and deploys the central project repository to a private [Preview ](deploy#preview) website for stack holders viewing. The teams and gatekeeper continues the GitHub workflow process until stack holders agree the central project repository is ready for release to the public internet 

Teams may Pull the central project repository at anytime to view and test other topic branches.

---

## Git

<img src="/img/gitlogo.png" width="100"/>

[Git Tutorial](https://www.w3schools.com/git/default.asp?remote=github)

### Fork

[Git GitHub Fork](https://www.w3schools.com/git/git_remote_fork.asp?remote=github)

A *fork* is a copy of the project repository in a team member's GitHub account. Forks let team members make changes to a project without affecting the original repository or other team members. Team members can fetch updates from the project repository with a [pull](#pull) command

 Forks are used to either propose changes to someone else's project to which you do not have write access, or to use someone else's project as a starting point for your own idea. You can fork a repository to create a copy of the repository and make changes without affecting the upstream repository

Forking a repository is similar to copying a repository, with two major differences:

- You can use a pull request to suggest changes from your user-owned fork to the original repository in its GitHub instance, also known as the upstream repository.

- You can bring changes from the upstream repository to your local fork by synchronizing your fork with the upstream repository.

[Fork a Repo](https://docs.github.com/en/enterprise-server@3.4/get-started/quickstart/fork-a-repo)

### Clone

[Git Clone from GitHub](https://www.w3schools.com/git/git_clone.asp?remote=github)

A clone is a full copy of a repository, including all logging and versions of files, copied from the team member GitHub account to team member workstation.

[Commits](#commits) keep the team member local project repository up to date on the workstation and on GitHub. If the workstation copy is damaged, the latest commit can be cloned from GitHubto the workstation.

### Branch

[Git Branch](https://www.w3schools.com/git/git_branch.asp?remote=github)

Creating a branch is to safely diverge from a line of development and continuing on another. An example is creating a branch create a feature or to test a radical idea

Branching enables working on different parts of a project without impacting other branches. Work on a branch can be merged with other project branches. 

Switching between branches and work on different projects without them interfering with each other. Branching in Git is lightweight and fast!

### Checkout

### Switch 

Switches to a new branch

A quick way of switching branch on Git is to use the `git switch` command and specify the name of the branch you want to switch.

If the destination branch does not exist, you have to specify the “-c” option (for “create branch“), otherwise you will get an error message when switching to that branch.

$ git switch <existing_branch>

$ git switch -c <non_existing_branch>
Again, as an example, let’s say that you want to switch to the “feature” branch from the “master” branch.

In order to switch from the “master” branch to the “feature” branch, use the “git switch” command and specify the destination branch (which is “feature” in this case)

$ git switch feature
switch branch using git switch
On the other hand, if you try to switch to a non existing branch, you will get the following error message

$ git switch non-existing-branch

fatal: invalid reference: non-existing-branch
To solve this error, make sure to append the “-c” option to the “git switch” command to specify that you want to switch to a new branch.

$ git switch -c non-existing-branch

Switched to a new branch 'non-existing-branch'
Congratulations, you have now successfully switched to another branch and you can start working on it.


---
 
### Git Desktop

<img src="/img/gitdesktop.png" width="100"/>

 Git Desktop is an alternative to using [VScode](#vscode) built-in Git commands. It abstract [Github](#github) and more [Git](#git) commands. It interacts with GitHub using a GUI instead of the command line or a web browser. It is a Microsoft product available on Mac and Windows.

[GitHub Desktop and VSCode](http://www.rodanthi-alexiou.com/github-101-github-desktop-and-vscode/) documents explain how to use GitHub Desktop with [VScode](#vscode). 

---

## iA Writer

Editing Markdown / MDX website pages and blog posts using iA Writer is faster because of focus and grammar features with live preview.

<!--
![ialogo](/img/ialogo.png)
-->

<img src="/img/ialogo.png" width="100"/>

- [iA Writer](https://apps.apple.com/us/app/ia-writer/id775737590?mt=12) is a Markdown Writing app:
    - Faster way to write MDX website material 
    - Extensive Style Check
    - Focus
        - Sentence
        - Paragraph
    - Available for Mac, iOS, Windows, and Android

 The Mac iA Writer stores files in iCloud. They are available for editing using supported devices when there is an internet connection.

---

## Chronosync

<!--
![ChronoSync](/img/CSLogo300.png)
-->


<img src="/img/CSLogo300.png" width="100"/>

When one or more pages have been edited using [iA Writer](#ia-writer), the  [ChronoSync](https://www.econtechnologies.com/chronosync/overview.html) Mac app is used to synchronize files between iA Writer and the local repository. Since the  iA Writer files are store in iCloud, they are available for editing using supported devices when there is an internet connection.

If edits have been made to files the local repository, use ChronoSync to synchronize them to iA Writer.

---

!!! Danger "Defects"
	The slightest configuration, programming or security defect issues during the project will require Remediating and increasing overall lifetime costs 
