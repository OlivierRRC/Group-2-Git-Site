---
title: Feature Branch Workflow
layout: default
parent: Overview of Git Workflow
nav_ order: 2
---

# Feature Branch Workflow

All feature development or bug fixes are done in dedicated branches.
- Isolates new development from the main branch.
- Makes it easy to discard experimental changes.
- Facilitates code review via pull requests.

🎵***Note:*** *This workflow is sometimes called [Github Flow].

Works like the Centralized Workflow, except:
- **Branching:** New features or fixes are developed locally in a short-lived branch.
- **Resolving Conflicts:** Remote commits by other developers can be pulled into the
local feature branch, with merge conflicts resolved as required.
- **Pushing to Remote:** Completed and resolved branches are then pushed.
- **Requesting a Remote Merge:** A pull request is next initiated on the git hosting
service (example: GitHub).
- **Reviewing:** One or more team members review the pull request before merging it
into the main remote branch.

🎵***Note:*** *Pull requests can be sent back unmerged if rework is deemed necessary.*

[Github Flow]: https://docs.github.com/en/get-started/quickstart/github-flow