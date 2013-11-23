# Fist of all

Specially thanks to Lokaltog who created great [vim-easymotion](https://github.com/Lokaltog/vim-easymotion).
Without his former work, I don't think I could create smalls from scratch.

# What is this?
Yet another cursor movement plugin.
Search and jump with easymotion style.

## Features
* jump directly with easymotion style.
* support all, forward, backward direction. but 'all' is always best I believe.
* skip fold.
* work for normal, operator, visual mode.
* highlight selected area in operator and visual mode, it helps you know area to be deleted or yanked.
* move around candidate with hkjl(excursion-mode)
* full customizable keybinding in excursion-mode and cli-mode
* auto-show-up easymotion style jump key at specified timeout.
* auto-show-up timeout would't be triggerd until it exceed specified type length.
* color customizable.
* always ignore case for jump key(easy to type).

# Movie
![Movie](http://gifzo.net/NBDnZVtDNJ.gif)

# Configuration example

    " map normal-mode 's' for simple search
    nmap s <Plug>(smalls)
    " if you want to use smalls in visual/operator or both mode.
    omap s <Plug>(smalls)
    xmap s <Plug>(smalls)


# Related work
If you don't like this plugin? It's ok, there are a lot of plugins like bellow.  

* [easymotion](https://github.com/Lokaltog/vim-easymotion)
* [clever-f](https://github.com/rhysd/clever-f.vim)
* [sneak](https://github.com/justinmk/vim-sneak)
