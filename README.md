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
