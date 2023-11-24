# Quick start for Linux

## Add user to sudoers

```
sudo vi /etc/sudoers
```

## Install apt

```
sudo apt install neovim
sudo apt install curl
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
sudo apt install git
sudo apt install gcc
sudo apt install g++
sudo apt install gdb
sudo apt install clang-format
sudo apt install make
```

## Git clone with ssh

```
ssh-keygen
```

give me your public ssh key

```
mkdir -p ~/.config/nvim
cd ~/.config/nvim
git clone git@github.com:HellHBBD/nvim-config.git .
cd ~
git clone git@github.com:HellHBBD/coding.git
```

change git config

```
git config --global user.email "paulyu602@gmail.com"
git config --global user.name "Hell HBBD"
git config --global core.editor "nvim"
```

## Git clone with https

```
mkdir -p ~/.config/nvim
cd ~/.config/nvim
git clone https://github.com/HellHBBD/nvim-config.git .
cd ~
git clone https://github.com/HellHBBD/coding
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
