![Hack2023](https://github.com/Fork-N-Forge/HacktoberFest-2023/assets/92796050/f96a74f7-f772-4844-97e0-59cf22e18899)


<h4>Hacktoberfest is digitalocean's annual event that encourages people to contribute to open source throughout october. Much of modern tech infrstructure including some of digitalocean's own products-relies on open-source projects built and maintained by passionate people who often don't have the staff or budgets to do much more than keep the project alive. Hacktoberfest is all about giving back to those projects, sharpening skills, and celebrating all the things open source, especially the people that make open source so special.<h4>

<!-- TABLE OF CONTENTS -->

Fork-N-Forge's hacktober repository , you're welcome to get started in the world of open sourcing , contributing and writing good code.
## Table of Contents

* [Getting Started](#getting-started)
* [Installation](#installation)
* [List of projects](#table)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.
# 📌 Videos 📽️:

- [Hacktoberfest Intro](https://www.youtube.com/watch?v=mq_FIHdxmIk)
- [How to pull request [Overview]](https://youtu.be/DIj2q02gvKs)
- [Merge Conflict / comment](https://youtu.be/zOx5PJTY8CI)


# Contribution Rules📚:

- You are allowed to make pull requests that break the rules. We just merge it ;)
- Do NOT add any build steps e.g npm install (we want to keep this a simple static site)
- Do NOT remove other content.
- Styling/code can be pretty, ugly or stupid, big or small as long as it works
<!-- - Add your name to the contributorsList file. -->
- Try to keep pull requests small to minimize merge conflicts


### Installation

1. Clone the repo
```sh
git clone https://github.com/Fork-N-Forge/HacktoberFest-2023
```
2. Start a new branch.
```sh
Check Contributing topic to find out about branching
```

3. And start your contributions.

----------

## Steps to follow :scroll:

### 0. Star The Repository :star2:

Star the repository by pressing the topmost-right button to start your wonderful journey.

### 1. Fork it :fork_and_knife:

You can get your own fork/copy of [HacktoberFest-2023](https://github.com/Fork-N-Forge/HacktoberFest-2023) by using the <a href="https://github.com/Fork-N-Forge/HacktoberFest-2023/fork"><kbd><b>Fork</b></kbd></a> button.


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be executed on Linux, Mac, and Windows(using Powershell)`

You need to clone or (download) it to local machine using

```sh
$ git clone https://github.com/Fork-N-Forge/HacktoberFest-2023.git
```

> This makes a local copy of the repository in your machine.
Once you have cloned the `HacktoberFest-2023` repository in Github, move to that folder first using change directory command on Linux, Mac, and Windows(PowerShell to be used).

```sh
# This will change directory to a folder HacktoberFest-2023
$ cd HacktoberFest-2023
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/HacktoberFest-2023.git (fetch)
origin  https://github.com/Your_Username/HacktoberFest-2023.git (push)
```

Now, let's add a reference to the original [Hacktoberfest-2023](https://github.com/Fork-N-Forge/HacktoberFest-2023) repository using


### 4. Sync it :recycle:

Always keep your local copy of the repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune
# Switch to `main` branch
$ git checkout main
# Reset local `main` branch to match the `upstream` repository's `main` branch
$ git reset --hard upstream/main
# Push changes to your forked `HacktoberFest-2023` repo
$ git push origin main
```


### 5. Create a new branch :bangbang:

Whenever you are going to contribute. Please create a separate branch using command and keep your `main` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```

Create a separate branch for contribution and try to use the same name of the branch as of folder.

To switch to the desired branch

```sh
# To switch from one folder to other
$ git checkout BranchName
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reviewer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```

## List of Repositories to contribute 

### Sample Topic

Sr. no | Topic | Repo Link |  
|---|---|---|
| 1 | Sample Topic | [Sample Link](https://www.adoptapet.com/public/apis/pet_list.html) |


# FAQs (Frequently Asked Questions) ❓

- Who all can contribute?
  - Anyone with a github account and who is signed up for
[hacktoberfest](https://hacktoberfest.com/register/) :)
- Are you getting paid for this?
  - Sadly no. But we think we should. This is 100% unofficial and we do it for fun, fame and glory.
- Who are you and why are you doing this?
  - We are the programmers from India.We are doing this because we love Open Source and Hacktoberfest. We want to make it easier for people to get started with Hacktoberfest and Open Source.
- Should I come closer to the text saying 'Don't come closer' on the left side of the home tab ?
  - Nope.
- How many pull request (PR) must be made, if I want to get an awesome tshirt from Hacktoberfest 2022?
  - 4
- How do I track my progress to get an awesome shirt from Hacktoberfest 2023?
  - [go to ->](https://hacktoberfest.digitalocean.com/profile/). (Check Out Your Own Stats at Right Top)
- What is the duration of Hacktoberfest 2023?
  - It is from 1st october to 31st october 2023...
- What is the event for?
  - For the open source community engagement and learn how to contribute to open source.




###### *We will do our best to merge as much as possible from everyone. However, time is limited and the merge conflicts are horrible :astonished: <3*
<br>
