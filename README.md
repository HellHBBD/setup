# Quick start for Linux

## Add user to sudoers

```
sudo vi /etc/sudoers
```

## Install apt

```
sudo apt update ; sudo apt upgrade -y
sudo apt install neovim -y
sudo apt install curl -y
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
sudo apt install git -y
sudo apt install gcc -y
sudo apt install g++ -y
sudo apt install gdb -y
sudo apt install clang-format -y
sudo apt install make -y
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

## Uninstall

```
rm -rf ~/.local/share/nvim
rm -rf ~/.config/nvim
rm -rf ~/coding
```
