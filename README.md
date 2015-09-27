# Dotfiles

These are the dotfiles I use to configure VIM.

1. Clone repo
2. Move `.vim` and `.vimrc` to home directory
3. Install NERDTree using command below
4. If YouCompleteMe is desired, follow instructions below to install MacVim 7.4+ with Python and do some config magic to figure it out. 

Color configurations/plugins may not be available immediately.
Comment lines for color scheme and plugins if only VIM settings are desired.

Installing NERDTree should be easy as:

`cd ~/.vim/bundle`

`git clone https://github.com/scrooloose/nerdtree.git`

Notes:

YouCompleteMe requires MacVim with Python.

`http://stackoverflow.com/questions/7211820/update-built-in-vim-on-mac-os-x` is useful for installing the latest version of VIM. This just tells you to install it in a different directory instead of overwriting the built-in VIM in your `/usr/bin`.

Comment out the line that aliases `vim` in `.zshrc` and enable it again after following instructions to install MacVim in their official docs. 
