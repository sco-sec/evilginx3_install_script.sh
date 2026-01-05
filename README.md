# Evilginx3 Installer (Ubuntu)

## Overview

This repository contains an automated **Bash script** for installing **Evilginx3** on an **Ubuntu Linux** host. The script simplifies the setup process by handling system updates, required dependencies, and the installation workflow, allowing users to deploy Evilginx3 quickly and consistently.

The goal of this project is to reduce manual configuration errors and save time when setting up Evilginx3 in a controlled testing environment.

## Features

- Automated installation using a single Bash script  
- Handles system updates and dependency installation  
- Designed specifically for Ubuntu-based systems  
- Lightweight and easy to customize  
- Suitable for repeatable and consistent deployments  

## Intended Audience

This script is intended for:

- Security researchers  
- Penetration testers  
- Red team professionals  
- Students learning about web security and authentication testing  

## Requirements

- Ubuntu Linux (tested on modern LTS versions)  
- Root or sudo privileges  
- Internet connection  

## Usage

Clone the repository and run the installer script:

```bash
git clone <repository-url>
cd <repository-name>
chmod +x install.sh
sudo ./install.sh
