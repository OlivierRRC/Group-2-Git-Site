---
title: Configuring Git
parent: Git Fundamentals
layout: default
nav_order: 1
---

In order to use git, you first have to have git.

## Table of Contents
{: .no_toc}

1. TOC
{:toc}

# Start bu Installing the Windows Terminal and Git

- [Install the Windows Termnial](https://aka.ms/terminal/)
- [Install git and Git GUI for Windows](https://gitforwindows.org/)

## Test Git Install

Open the Windows Terminal.
Try running: 

`git --version`

you should see an output that looks something like this: 

`git version 2.42.0.windows.2`

### Configuring Git

Next, let's tell Git who you are. Git needs to know your name and email.

```
git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"
```

We can also turn on some context-aware colourization.

*Colourization only works if you're using poweshell in windows and not with the regualr command prompt.*

`git config --global color.ui auto`

You only need to set these once!