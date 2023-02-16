# ![Project-tech - Getting Started][banner-guide]

## Table of Contents

*   [Description](#description)
*   [Prerequisite](#Prerequisite)
*   [Installation](#installation)
*   [Communication](#communication)

## Description

👋 **Welcome to project-tech!** 

This getting started guide will get you up and running with all the software and tools you need for this course. Throughout this guide there are additional video's that further explain important topics from lectures but also show you how to install certain technology. Look for a 🎦 emoji!

## Prerequisite

### Text Editor

If you don’t have one yet, install a text editor. It doesn't really matter which one you pick, as long as you feel comfortable using it. However, we do recommend moving away from [Brackets](http://brackets.io/), other editors offer better customizability. [VSCode](https://code.visualstudio.com/) is our recommended choice but there are others.  [Atom](https://atom.io) and [Sublime](https://www.sublimetext.com) are both also good choices. 

> Take some time to [learn the interface and features of VSCode][learnvs]. If you know your way around the interface, coding will be easier. Feeling comfortable with your tools is very important when writing code.

[🎦 _Watch a video_ on how to install Text Editors.][videotext]

### GitHub

If you haven’t already, [sign up for
GitHub](https://help.github.com/articles/signing-up-for-a-new-github-account/). Take some time to set up your [GitHub profile](https://github.com/settings/profile).
Include your name, a profile picture, and a URL to your homepage. Teachers will appreciate it if you upload a representing profile and pick a username that closely resembles your real name. Silly pictures are allowed 🤪

> You’re allowed to stay anonymous online for this course by omitting sensitive information, but a good looking GitHub profile can help you get an internship or job later. 

[🎦 _Watch a video_ on how this GitHub organisation works.][videoorg]

## Installation

### CLI

*Windows:*  
Modern Windows versions provide Windows PowerShell as a command line interface. Just type 'PowerShell' in the searchbar in your start-menu or taskbar. By default you will start the Powershell as a normal user, but you can also choose to run it as an adminstrator. For everyday use, we recommend to run it as a normal user. You will have less rights to change things, which also means less risk of accidentally breaking things. For the few times you do need more permissions, you can run Powershell as an administrator. On older Windows machines you can also use the Command Prompt, which is less sophisticated. Many people also like to use the [Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal) directly in your code editor like in VSCode.

The default security settings for PowerShell prevent you from running any scripts without permission. You may run into this problem later on, for example when you try to start nodemon and it doesn't work. You can check your current settings in PowerShell with the command:
```sh
Get-ExecutionPolicy -List
```
and if needed, relax the security settings a bit using the command:
```sh
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

> 💡 Be aware that lecturers may not be able to help you with very specific Windows problems. Additionally some resources used in this course show the MacOS interface. If you're on Windows many tools offer equivalent experiences and most steps and commands you enter will be the same. If something is different on Windows, please let your instructor and other students know in the `#windows` channel so we can troubleshoot and look at alternatives!

*MacOS:*  
Apple already has a terminal emulator by default to provide a command line interface. Just search for `terminal` in **spotlight** or find it in your applications folder. There are other command-line interfaces out there you can download that add more features. [Hyper](https://hyper.is/) and [iTerm](https://iterm2.com/) are very popular choices. Many people also like to use the [Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal) directly in your code editor like in VSCode.

> 💡 If you have a Mac running MacOS Catalina (or above) the current default shell is `zsh`, previously this was `bash`. If `bash` is still the default on your machine we highly suggest you switch your default shell to `zsh` [using this Apple support article](https://support.apple.com/en-us/HT208050).

### Git

*Windows:*  
Download and install [Git for Windows](https://gitforwindows.org/). Most default options are fine, but there are a few settings to consider during installation:
* You can select your own preferred editor (Visual Studio Code or other).
* We recommend to override the default branch name for new repositories. If you choose 'main' as default branch name, this will align with the default used on GitHub.
* Finally select 'Git from the command line', so you can use Git commands in PowerShell.

*MacOS:*  
Install Git using [Homebrew](https://brew.sh/)

```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

then install Git

```sh
brew install git
```

*Configure Git:*
Both for *Windows* and for *MacOS*, connect Git and GitHub together inside of your **command line interface** like so:

[Connect your GitHub to Git locally][ssh-github]

Use the same email for Git as you used to sign up for GitHub.

[🎦 _Watch a video_ on how to set-up gia via the terminal.][videogit]


## Communication

### Brightspace

We use our DLO Brightspace for schedulers and rubric feedback. Make sure you enroll to the **Project-tech** course, you can do so by using the [HvA courseselector][course]. It's important to **select the right class** for teachers to give you feedback and grades. Go to Administration > Groups and pick the right class. If you're not sure, ask your teacher to see if you are on the correct _classlist_.

### Microsoft Teams

Sign up for our _Blok-Tech_ MS Team. **You can find the sign-up code in the announcement on Brightspace.** Join the `#project-tech` channel in our team. Get your account set up properly, add your  **real name**, **a profile picture**, and you can even set your **GitHub username** as a status message. We’ll use this info to link your GitHub and MS Teams account to our administration files.

### GitHub

GitHub is a social platform so give this repository `pt-course-22-23` [a ⭐ star][star] and start [following][follow] your teachers and fellow students!


## Introduction

**Wow, you did it! Virtual high five! 🖐** During this course we'll use GitHub issues and templates. Each assignment has a different template in which you can hand in your assignments for that week. This is also the place where teachers and student-assistants will give you feedback. You can use [GitHub notifications][notifications] (bell on the top right of the GitHub website) to keep track of those changes.

> 🚨 Make sure you never publicly share you name and student number in combination! If you fill in your class you can **use your tech group** `tech-x` not your 'regular' `20x` group.

/Happy Coding!

[banner-guide]: https://cmda-bt.github.io/pt-course-21-22/assets/banner-guide.svg
[examples]: examples
[stackoverflow]: https://stackoverflow.com
[duckduckgo]: https://duckduckgo.com
[synopsis]: #synopsis
[terminal]: https://github.com/microsoft/terminal

[notifications]: https://help.github.com/en/github/managing-subscriptions-and-notifications-on-github/configuring-notifications
[course]: https://courseselector.mijnhva.nl/nl#/CourseSelector/78076118-8f51-e911-a82e-000d3a29a761/2019-2020
[star]: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/saving-repositories-with-stars
[follow]: https://docs.github.com/en/free-pro-team@latest/github/getting-started-with-github/following-people
[videoask]: https://www.youtube.com/watch?v=0CARthL2RPo
[videotext]: https://www.youtube.com/watch?v=a2A_AGAnNjQ
[videoorg]: https://www.youtube.com/watch?v=8w69jLPpPXM
[videogit]: https://www.youtube.com/watch?v=Qq39mizx5kE
[issues]: https://github.com/cmda-bt/pt-course-22-23/issues/new/choose
[learnvs]: https://code.visualstudio.com/learntocode
[ssh-github]: https://docs.github.com/en/authentication/connecting-to-github-with-ssh
