# .Vim configuration

README file for this repository
This repository contains the code that I use for my vim configuration

The code is organized in the following way:

- `.vimrc`: the main configuration file for vim

- `plugged/`: directory containing the plugins that I use

- `colors/`: directory containing the color schemes that I use

- `autoload/`: directory containing the scripts that I use

## Installation

To install this configuration, you need to follow these steps:
```bash
git clone git@github.com:CSantos01/vim_config.git
cd vim_config
cp .vimrc ~/.vimrc
```

Then install [vim-plug](https://github.com/junegunn/vim-plug)
```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

Finally, inside vim, install all the plugins and source:
```vim
:PlugInstall
:source ~/.vimrc
```
(You may encounter an error when installing the live markdown plugin, but just press "R" to retry and it should work) 

