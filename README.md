## DigitalOcean: Setting Up and Configuring Droplets with `doctl` and Cloud-Init
### Introduction:
Welcome to **DigitalOcean: Setting Up and Configuring Droplets with `doctl` and Cloud-Init**. DigitalOcean is a cloud infrastructure provider that offers virtual private servers called Droplets. These Droplets can be used for many tasks, such as web hosting, development, and managing databases.

---
### Intended Use
This manual aims to guide users through the process of creating and managing DigitalOcean Droplets using the `doctl` command-line tool and configuring them with cloud-init. By following this guide, users will learn how to deploy and automate the setup of remote servers.

---
### Assumption Regarding Knowledge Level 
This tutorial assumes the following:
- **Arch Linux Droplet**: The reader already has an Arch Linux Droplet set up on DigitalOcean and can SSH into it.
- **Terminal Access**: All code and commands in this tutorial will be executed through the terminal, so the reader should have a working knowledge of terminal commands.
- **Command Explanations**: Every command and its options will be explained at least once in the tutorial to ensure clarity, even if the reader is not fully familiar with each tool or option.
- **Neovim Installed**: You will need Neovim to edit configuration files. If Neovim is not installed, you can add it using `sudo pacman -S neovim`.
- **A Computer Running Arch Linux**: The steps and commands provided assume the reader is working on a system running Arch Linux.
---
### Installing and Configuring `doctl`
This section will be covering the process of installing and configuring `doctl`, which is the official command-line for interacting with the DigitalOcean API. `doctl` provides an interface for managing your DigitalOcean resources directly from your terminal, allowing you to do tasks such as creating and managing Droplets, managing DNS records, and viewing usage statistics.

---
#### Installing `doctl`
You may need to download `wget` beforehand. Please use the following command:
```bash
sudo pacman -S wget
```
1. Visit the [Releases page](https://github.com/digitalocean/doctl/releases) for `doctl` and find the archive for your operating system and architecture. In this example, we will be using "doctl-1.114.0-linux-amd64.tar.gz"
![release]("C:\Users\lilli\Documents\CIT\term-2\2420-linux\assignment1\gallery\20240925154156.png")
