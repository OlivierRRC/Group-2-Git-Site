---
title: The Git Life Cycle
layout: default
nav_order: 2
---

# The Git Life Cycle  

This section explains the fundamental concepts of the Git life cycle. It covers the states of files in the working directory, distinguishing between tracked and untracked files, and the process of staging and committing changes.  

## Table of Contents  
- [Tracked vs Untracked Files](#tracked-vs-untracked-files)  
- [Modifying Tracked Files](#modifying-tracked-files)  
- [Staging Changes](#staging-changes) 
- [Committing Changes](#committing-changes)  
- [Life Cycle](#life-cycle)  
- [Resources](#resources)  

## Tracked vs Untracked Files  
In Git, files in your working directory can be either **tracked** or **untracked**. Tracked files are those that Git knows about, including files from the last snapshot and newly staged files. Untracked files, on the other hand, are any files in your working directory that were not in the last snapshot and are not in the staging area.

## Modifying Tracked Files  
When you edit files, Git recognizes them as **modified**. This means you've made changes since your last commit.

## Staging Changes  
To prepare modified files for a commit, you **stage** them. Staging files allows you to selectively include changes in the next commit.

## Committing Changes  
Once you've staged your changes, you **commit** them. Commits create a snapshot of your repository at a specific point in time.

## Life Cycle
Remember that each file in your working directory can be in one of two states: tracked or untracked. Tracked files are files that were in the last snapshot, as well as any newly staged files; they can be unmodified, modified, or staged. In short, tracked files are files that Git knows about.  
Untracked files are everything else — any files in your working directory that were not in your last snapshot and are not in your staging area. When you first clone a repository, all of your files will be tracked and unmodified because Git just checked them out and you haven’t edited anything.  
As you edit files, Git sees them as modified, because you’ve changed them since your last commit. As you work, you selectively stage these modified files and then commit all those staged changes, and the cycle repeats.  

![GitLifeCycle](https://git-scm.com/book/en/v2/images/lifecycle.png)  

Image Source:  
[https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)  

## Resources  
- [Git Basics: Recording Changes to the Repository](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository)  

## Additional Resources  
- [Git Documentation](https://git-scm.com/doc)  
- [GitHub Guides](https://guides.github.com/)  
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)  