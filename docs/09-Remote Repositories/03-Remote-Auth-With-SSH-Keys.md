---
title: Remote Authentication with SSH Keys
layout: default
parent: Remote Repositories
nav_ order: 3
---

# SSH Keys for Authentication

With SSH keys, you can connect to GitHub without supplying your username and personal access token at each visit. You can also use an SSH key to sign commits. 

## Creating an SSH Key

- Generate a public/private key pair, from the Git Bash terminal:
`ssh-keygen -t ed25519 -C "your_email@example.com"`

- Press Enter to accept the default save path, and make note of this path.

- It's good practice to secure your keys with a passphrase. Just don't forget it.

- Navigate to the save path, open the `id_ed2551.pub` file and [copy-paste it's contents here](https://github.com/settings/ssh/new)

- Test your from the terminal: `ssh -T git@github.com` (Type `yes` when prompted.)