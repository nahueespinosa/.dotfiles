# Dotfiles [![CI](https://github.com/nahueespinosa/.dotfiles/actions/workflows/build.yml/badge.svg)](https://github.com/nahueespinosa/.dotfiles/actions/workflows/build.yml)

These are the configuration files and plugins that I use for command-line programs.
I **do not recommend** installing them unless you're willing to overwrite the dotfiles on your machine. However, feel free to copy whatever you want.

Powered by [dotbot](https://github.com/anishathalye/dotbot/).

## Requirements

This configuration files have been tested with:

- `zsh 5.8`
- `git 2.25.1`
- `vim 8.1.2269`
- `tmux 3.0a`

Plugin requirements:

- [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe/tree/master#requirements)

## Installation

Change directory to `$HOME` and clone this repository:

```bash
cd $HOME && git clone git@github.com:nahueespinosa/.dotfiles.git
```

Install dotfiles:

```bash
~/.dotfiles/install
```

Make `zsh` you default shell if you haven't already:

```bash
chsh -s $(which zsh)
```
