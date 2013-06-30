# Mike's dotfiles

dotfiles are settings to personalize your system. This repository contains mine.

Mostly taken from [Paul Irish's dotfiles](https://github.com/paulirish/dotfiles/blob/master/README.md).

## Installation

Clone the repository into ~/.dotfiles. Back up your bash files in your home folder, remove them and create symlinks to the .dotfiles version.

```bash
git clone git@github.com:3px/dotfiles.git ~/.dotfiles
ln -s ~/.dotfiles/.bash_rc ~/.bash_rc
ln -s ~/.dotfiles/.bash_profile ~/.bash_profile
ln -s ~/.dotfiles/.bash_prompt ~/.bash_prompt
ln -s ~/.dotfiles/.aliases ~/.aliases
ln -s ~/.dotfiles/.functions ~/.functions
```