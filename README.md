# Dotfiles

[![CI](https://github.com/nahueespinosa/.dotfiles/actions/workflows/build.yml/badge.svg)](https://github.com/nahueespinosa/.dotfiles/actions/workflows/build.yml)

These are the configuration files and plugins that I ([@nahueespinosa](https://github.com/nahueespinosa)) use for command-line programs.

Powered by [dotbot](https://github.com/anishathalye/dotbot/).

> [!CAUTION]
> I **do not recommend** installing them unless you're willing to overwrite the dotfiles on your machine. However, feel free to copy whatever you want.

![Screenshot](misc/screenshot.png)

## Requirements

These configuration files have been tested in `Ubuntu 24.04` with:

- `cmake 3.28.3`
- `git 2.43.0`
- `python 3.12.3`
- `tmux 3.4`
- `vim 9.1`

## Installation

Change directory to `$HOME` and clone this repository:

```bash
cd $HOME && git clone git@github.com:nahueespinosa/.dotfiles.git
```

Install dotfiles:

```bash
~/.dotfiles/install
```
