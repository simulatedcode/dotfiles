# My Dotfiles

This repository contains my personal dotfiles for setting up a customized development environment. Most of the configurations are inspired by [craftzdog's dotfiles](https://https://github.com/craftzdog/dotfiles-public), with some tweaks to fit my workflow.

## 📂 Folder Structure

All configurations are stored inside the `.config/` directory, with the following subfolders:

- **fish/**: Configuration for [Fish shell](https://fishshell.com/)
- **bat/**: Settings for [bat](https://github.com/sharkdp/bat), a cat replacement
- **nvim/**: My [Neovim](https://neovim.io/) setup using [LazyVim](https://www.lazyvim.org/)
- **tmux/**: Custom [tmux](https://github.com/tmux/tmux) configuration

## 🚀 Installation

To set up these dotfiles on a new system, follow these steps:

```sh
# Clone the repository
git clone --recursive https://github.com/simulatedcode/dotfiles.git ~/.dotfiles

# Create symlinks (example using GNU stow)
cd ~/.dotfiles
stow fish bat nvim tmux
```

If you don’t use `stow`, you can manually create symlinks:

```sh
ln -s ~/.dotfiles/fish ~/.config/fish
ln -s ~/.dotfiles/bat ~/.config/bat
ln -s ~/.dotfiles/nvim ~/.config/nvim
ln -s ~/.dotfiles/tmux ~/.config/tmux
```

## 🛠 Dependencies

Ensure you have the following installed:

- [Fish shell](https://fishshell.com/)
- [Neovim](https://neovim.io/)
- [tmux](https://github.com/tmux/tmux)
- [bat](https://github.com/sharkdp/bat)
- [stow](https://www.gnu.org/software/stow/) (optional, for managing symlinks)

Feel free to use and modify these dotfiles. If you find them useful, a star on GitHub would be appreciated! ⭐


