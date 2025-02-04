# Dotfiles
This contains dotfiles for my personal develop environment config for nixOS. Meant to be utilized with GNU stow to allow easy referencing of dotfiles.

# Installation
```
stow . --adopt --dotfiles --target=$HOME
```
this will sym link all of the dot-files to your home user directory, replacing dot- with . for files and folders.
