<h1 align="center">Git Cheat Sheet by Md Faijul Islam</h1>

## Table of Contents

1. **[Installing Git](#installing-git-based-on-your-operating-system)**
   - [Windows](#windows)
   - [Linux & Unix](#linux--unix)
   - [MacOS](#mac)
2. **[Git Profile Setup On Local Machine](#setting-up-git-user-profile)**

---

## Installing git based on your operating system

**The best place to get git based on your distribution is [git-scm.com](https://git-scm.com/downloads)**

### Windows

- On window we can install by downloading the git.exe file form the official webpage [Install Git For Windows](https://git-scm.com/downloads/win)

  ![](./screenshots/windows-download.png)

- You can also use _winget_ to install by command line in powershell.

  > winget install --id Git.Git -e --source winget

  ![](./screenshots/windows-download-powershell.png)

### Linux & Unix

- You can follow the instructions and command line code depending on your linux & unix distribution form the official webpage [Install Git For Linux and Unix](https://git-scm.com/downloads/linux)

### Mac

- Mac is also a UNIX based platform. There are several options for installing Git on macOS. You can choose the right option for you form the official webpage [Install Git For MacOS](https://git-scm.com/downloads/mac)

After installation to lookup of your `git` is set up correctly you an use the command `git --version` and verify it.

![](./screenshots/check-git-version.png)

---

## Setting up git user profile on your local machine

You can setup you profile from the command line in order to associate your commits with your corresponding identity. The following identity setup is build upon assuming you have a `Github` account. The command that you will use are:

> git config --global user.name "your Github User Name"
> git config --global user.email "your Github Email"

After witch you can verify or check the list of users in your machine using the command

> git config --global --list

You can edit them by using the following command

> git config --global --edit
