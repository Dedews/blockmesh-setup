# BlockMesh CLI Setup Script

This script automates the installation of the BlockMesh CLI on Ubuntu servers.

## Features

- Installs Docker and Docker Compose
- Downloads the latest BlockMesh CLI
- Sets up a Docker container for the BlockMesh CLI

## Prerequisites

Before running the script, ensure that you have the following:

- A VPS running Ubuntu
- Access to the terminal
- `curl` installed (usually pre-installed on most systems)

## Installation Instructions

To install the BlockMesh CLI, you can run the following command directly in your terminal:

```bash
bash <(curl -s https://raw.githubusercontent.com/Dedews/blockmesh-setup/refs/heads/main/setup_blockmesh.sh)
