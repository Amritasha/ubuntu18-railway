![Ubuntu](https://img.shields.io/badge/Ubuntu-18.04-E95420?logo=ubuntu)
![Docker](https://img.shields.io/badge/Docker-Supported-blue?logo=docker)

# Ubuntu 18.04 Railway

A browser-accessible Ubuntu 18.04 terminal deployed on Railway using [ttyd](https://github.com/tsl0922/ttyd).

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.com/new/template)

## Description

Deploys an Ubuntu 18.04 LTS container accessible from any browser. Useful for testing legacy software or older package versions.

## Environment Variables

| Variable | Description |
|----------|-------------|
| `PORT` | Port for ttyd to listen on |
| `USERNAME` | Login username for the web terminal |
| `PASSWORD` | Login password for the web terminal |

> **Note:** Always set USERNAME and PASSWORD before deploying.

## Features

- 🐧 Ubuntu 18.04 LTS (Bionic Beaver)
- 🔒 Password-protected web terminal
- 💻 Neofetch on login
- 🛠️ Pre-installed: wget, curl, git, python3, pip

## Use Cases

- Test software on older Ubuntu LTS
- Reproduce legacy environment issues
- Learn/compare older Linux tooling
- CI debugging for older distro targets
