---
title: Initializing a Repo
parent: Git Fundamentals
layout: default
nav_order: 2
---

# Initializing a **Repo**sitory

Let's start by making a folder to play in:
`mkdir my-first-git`
`cd my-first-git`

To bring a new project **under control** we must first initialize the repository (the repo) from within the project's root folder:
To **init**ialize a new git repo from the command prompt:
`git init .`

Git defaults to using the word "master" (as in "master copy" or "master recording") for
the main branch, but we can change this:
`git branch -m main`

## Checking Your Repo's Status
To check the **status** of the repo for changes or additions:
`git status`

### Create a file

Open the Windows File Explorer:
`explorer.exe .`
And then create a `readme.md` file.

Add some text to the file and stylize it using [Markdown Synthax](https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md).

If you check your repo's status again, you should have some untracked changes listed.