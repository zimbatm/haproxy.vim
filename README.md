# VIM syntax for Haproxy

## Install

haproxy.vim follows the standard runtime path structure, so I highly recommend
to use a common and well known plugin manager to install it.

*  [Pathogen](https://github.com/tpope/vim-pathogen)
  * `git clone https://github.com/zimbatm/haproxy.vim.git ~/.vim/bundle/haproxy.vim`
*  [vim-plug](https://github.com/junegunn/vim-plug)
  * `Plug 'zimbatm/haproxy.vim'`
*  [NeoBundle](https://github.com/Shougo/neobundle.vim)
  * `NeoBundle 'zimbatm/haproxy.vim'`
*  [Vundle](https://github.com/gmarik/vundle)
  * `Plugin 'zimbatm/haproxy.vim'`

Because haproxy uses a generic ".cfg" file extension the syntax is not
automatically detected. You've got to add a pragma header like that to the
first line of the file:

```
# vim: set ft=haproxy :
```

## License

Copyright ??? Bruno Michel <brmichel@free.fr>, 2015 zimbatm

Cribbed from the original file over here:
http://www.haproxy.org/download/contrib/haproxy.vim
