# Quick start for Linux

```
vi /etc/sudoers
sudo apt install neovim
sudo apt install curl
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
sudo apt install git
mkdir -p ~/.config/nvim
cd ~/.config/nvim
git clone https://github.com/HellHBBD/nvim-config.git .
cd ~
sudo apt install gdb
```

# Quick remove for Linux

# Neovim

[Neovim Download Page](https://github.com/neovim/neovim/wiki/Installing-Neovim#install-from-download)

# vim-plug

## Install

[vim-plug Installation Page](https://github.com/junegunn/vim-plug#neovim)

## Uninstall

### Windows

```
rd /s /q %LOCALAPPDATA%\nvim-data
```

### Linux

```
rm -rf ~/.local/share/nvim
```

# nvim-config

[nvim-config github](https://github.com/HellHBBD/nvim-config)
