---
title: Status, Log, and Diff
parent: Git Fundamentals
layout: default
nav_order: 4
---

It can be useful to know whats going on in your git repo, here's a few helpful commands to figure that out.

## Table of Contents
{: .no_toc}

1. TOC
{:toc}

# Checking Tracked Files with Status

You can see the status of files as compared to what's already been commited using:

`git status`

This will tell you if you:

 - If you have new files
 - If you have changed files
 - If your changes are staged or not

# Git Commits and the Git Log

Commits can be reviewed by using:

`git log`

Each entry in the log shows:

- The commit hash.
- Who made the commit.
- When it was made.
- The commit message.

## Two Git Log Examples Entries

![](https://stungeye.github.io/Software-Development-And-Documentation-1/01-version-control-tools/commit.png)

The 40 character hex numbers shown at the start of each entry are the SHA1 hashes that uniquely identify each commit.

# What's the Difference

To compare the **diff**erences between the current files and the last commit:

`git diff`

We can diff specific files:

`git diff secret_plans.txt`

Or specific folders (and their sub-folders):

`git diff ./textfiles/plans`