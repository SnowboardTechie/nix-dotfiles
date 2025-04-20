# Dotfiles
This contains dotfiles for my personal develop environment config for nixOS. Meant to be utilized with GNU stow to allow easy referencing of dotfiles.

# Installation
```
stow . --adopt --dotfiles --target=$HOME
```
For nixOS config, go into the preferred nixos-config folder and run
```
stow . --adopt --dotfiles --target=/etc/nixos
```
this will sym link all of the dot-files to your home user directory, replacing dot- with . for files and folders.

# Alt Repos
This repo is located in 3 locations that sync commits from the primary to backups

### Primary
  - [git.snowboardtechie.com](https://git.snowboardtechie.com/bryan/nix-dotfiles)

### Backups
  - [github.com](https://github.com/snowboardtechie/nix-dotfiles)
  - [gitlab.com](https://gitlab.com/snowboardtechie/nix-dotfiles)
