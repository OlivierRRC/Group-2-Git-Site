---
title: Pushing and Pulling
layout: default
parent: Remote Repositories
nav_ order: 2
---

# Pushing and Pulling 

- Use `git push -u origin main` to push your local commits to the remote
repository.
- The `-u` option sets the remote repository as the upstream repository for the
current branch. Subsequent pushes can now be done with `git push` .
- Use `git pull origin main` to fetch the commit you
made on GitHub and merge it into your local branch.

## Simplest GitHub Workflow
If you don't have a local copy of a Github repo, you can clone it:

`git clone git@github.com:<username>/<repo-name>.git`

When you want to push the latest state of your repo to Github:

`git push origin <branch-name>`

When you want to grab the latest commits from Github:

`git pull origin <branch-name>`
