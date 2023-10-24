---
title: Forking Workflow
layout: default
parent: Overview of Git Workflow
nav_order: 3
---

# Forking Workflow

Often used for open source projects, in this workflow each developer gets not only their
own local repository, but also a server-side copy of the project.
- Developers push to their own server-side repositories.
- Changes are shared via pull requests from their personal public repository.
- The project maintainer has the final say on what is merged into the official
repository.

Works like the Feature Branch workflow, except:
- **Forking:** Each team member creates a fork of the project on the git hosting
service.
- **Cloning:** Team members clone their remote fork to a local repo.
- **Adding an Upstream:** Team members configure a secondary remote called
`upstream` that points to the official repo.
- **Resolving Conflicts:** Remote commits from `upstream` can be pulled into the
local feature branch, with merge conflicts resolved as required.
- **Pushing to Remote:** Local feature branches are pushed to the forked remote.
- **Requesting a Remote Merge:** Pull request are initiated to request merges from
the remote fork to the official upstream repo.