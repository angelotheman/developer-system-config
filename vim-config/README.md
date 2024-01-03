# Vim Configurations

This directory contains my vimrc configurations I use

## Installation

1. Install vim
```
sudo apt update
sudo apt install vim
```

2. Create a vim config file if it doesn't exist
```
touch ~/.vimrc
```

3. Clone this repo to your home directory
```
git clone https://github.com/angelotheman/developer-system-config.git ~/.vim
```

4. Create a symbolic link for the `vimrc` file
```
ln -s ~/.vim/vim_file ~/.vimrc
```

5. Launch Vim 
```vim```

and run the following command to install plugins:
`:PlugInstall`

**NOTE**: Make sure to have the linters ie. Betty and Pycodestyle installed to enable this procedure work without errors

### Happy Coding 🚀
