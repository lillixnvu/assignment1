## DigitalOcean: Setting Up and Configuring Droplets with `doctl` and Cloud-Init
### Introduction:
---
Welcome to **DigitalOcean: Setting Up and Configuring Droplets with `doctl` and Cloud-Init**. DigitalOcean is a cloud infrastructure provider that offers virtual private servers called Droplets. These Droplets can be used for many tasks, such as web hosting, development, and managing databases.

### Intended Use
---
This manual aims to guide users through the process of creating and managing DigitalOcean Droplets using the `doctl` command-line tool and configuring them with cloud-init. By following this guide, users will learn how to deploy and automate the setup of remote servers.

### Assumption Regarding Knowledge Level 
---
This tutorial assumes the following:
- **Arch Linux Droplet**: The reader already has an Arch Linux Droplet set up on DigitalOcean and can SSH into it.
- **Terminal Access**: All code and commands in this tutorial will be executed through the terminal, so the reader should have a working knowledge of terminal commands.
- **Command Explanations**: Every command and its options will be explained at least once in the tutorial to ensure clarity, even if the reader is not fully familiar with each tool or option.
- **Neovim Installed**: You will need Neovim to edit configuration files. If Neovim is not installed, you can add it using `sudo pacman -S neovim`.
- **A Computer Running Arch Linux**: The steps and commands provided assume the reader is working on a system running Arch Linux.

