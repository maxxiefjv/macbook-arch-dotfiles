# My dotfiles

This directory contains the dotfiles for my hyprland system

## Requirements
Install the following packages to get started

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow

```

## Installation
Checkout the dotfiles repository in your $HOME directory using git
```
git clone git@github.com:maxxiefjv/macbook-arch-dotfiles.git dotfiles
cd dotfiles
```

Then use GNU stow to create all the symlinks
```
stow .
```

