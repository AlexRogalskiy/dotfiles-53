# dotfiles

Most files should be copied into `$HOME`. This could be scripted in the future.

Some of this has been inspired by other dotfiles repositories scattered around the Internet.

## Initial Setup

Things should run without extra dependencies added but there are some things to do for the _full experience_.

1. Install [Starship](https://starship.rs)
2. Initialize git submodules for zsh plugins (`git submodule init`)
3. Setup GPG for git commit signing (or disable by editing .gitconfig)

I like to link my zsh, vim, and git configs to make it easier to keep up to
date with this repo.

```sh
ln -s "${HOME}/.dotfiles/.config" "${HOME}/.config
ln -s "${HOME}/.dotfiles/.zsh" "${HOME}/.zsh"
ln -s "${HOME}/.dotfiles/.zshrc" "${HOME}/.zshrc"
ln -s "${HOME}/.dotfiles/.vimrc" "${HOME}/.vimrc"
ln -s "${HOME}/.dotfiles/.gitconfig" "${HOME}/.gitconfig"
ln -s "${HOME}/.dotfiles/.gitignore_global" "${HOME}/.gitignore_global"
```

## Themes

Included in this repo is my custom [Brian Theme.terminal](Brian%20Theme.terminal). It uses a dark gray background with an opacity of 90% and blur of 40% and the DejaVu Sans Mono Nerd Font at 12pt (checkout [Nerd Fonts](https://www.nerdfonts.com/)). I use the [Starship](https://starship.rs) prompt.
![Screenshot of Terminal and zsh themes](brian-theme.png?raw=true)

