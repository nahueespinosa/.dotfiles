# Dotfiles

[![CI](https://github.com/nahueespinosa/.dotfiles/actions/workflows/build.yml/badge.svg)](https://github.com/nahueespinosa/.dotfiles/actions/workflows/build.yml)

These are the configuration files that I ([@nahueespinosa](https://github.com/nahueespinosa)) use for command-line programs.

Provisioned by [Ansible](https://www.ansible.com/) for idempotent, declarative system setup.

> [!CAUTION]
> I **do not recommend** installing them unless you're willing to overwrite the dotfiles on your machine. However, feel free to copy whatever you want.

![Screenshot](misc/screenshot.png)

## Requirements

These configuration files have been tested in `Ubuntu 24.04` with:

- `ansible 2.9+`
- `cmake 3.28.3`
- `git 2.43.0`
- `python 3.12.3`
- `tmux 3.4`
- `vim 9.1`

## Installation

### Quick Start

Install `ansible` and `git` in a fresh system:

```bash
sudo apt update
sudo apt install -y ansible git
```

Clone this repository and run the installation script:

```bash
cd $HOME && git clone git@github.com:nahueespinosa/.dotfiles.git
ansible-playbook ~/.dotfiles/ansible/playbooks/main.yml
```
