# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git

```
sudo dnf install git
```

### Stow

```
sudo dnf -y install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ mkdir .dotfiles
$ cd .dotfiles
$ git clone git@github.com:dineshwar/.dotfiles.git .
```

then use GNU stow to create symlinks

```
$ stow .
```
