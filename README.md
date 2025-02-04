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

Add a background image at the location of `dotfiles/.config/background.png`

Then use GNU stow to create all the symlinks
```
stow .
```

## Packages

This is an attempt to list essential packages required for using these dotfiles:
```bash
hyprland
hyprlock
hyprcursor
hyprland-qtutils
hyprland-qr-support
xdg-desktop-portal-hyprland
greetd
greetd-regreet
ttf-font-awesome
ttf-jetbrains-mono-nerd
ttf-nerd-fonts-symbols
ttf-nerd-fonts-symbols-common
tmux
neovim

```

## Important:
In order to get networkign to work I had to use a specific version of wpa_supplicant: `wpa_supplicant:2:2.10-8.1`.

