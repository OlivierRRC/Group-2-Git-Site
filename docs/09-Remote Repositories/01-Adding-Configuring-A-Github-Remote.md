---
title: Adding/Configuring a Github Remote
layout: default
parent: Remote Repositories
nav_ order: 1
---

# Introduction to GitHub

**GitHub is a hosting platform for Git repositories owned by Microsoft.**

It provides a web-based interface to interact with your repositories and adds social and collaboration features.


## Some Remote Repo / GitHub Terminology 

- **Push:** Send your changes to a remote repository.
- **Pull:** Fetch and merge changes from a remote repository into your current branch.
- **Clone:** Make a full copy of a repository at its current state.
- **Fork:** Create a copy of someone else's repository in your own GitHub account.

## Add a Repo to GitHub 

To save a local git repository to your GitHub account, create a new repository by way of the "+" button in the top right corner of the GitHub website.

**IMPORTANT:** Be sure not to initialize with a README or with any other files.

## Linking Your Local Repo to GitHub

Let's say you've created a new repo on Github called My-Lovely-Repo and you've already initialized this project's local git repository.

From the command line (within your project folder) add Github as a remote:

`git remote add origin git@github.com:<username>/My-Lovely-Repo.git`

_This should be all one line with `<username>` replaced by your actual username._

You can check if a remote has been added to a repo:

`git remote -v`

