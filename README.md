# vim-racket

Installation
------------

This module works with many Vim plugin managers. To use with pathogen, type the following into a terminal:

    cd ~/.vim/bundle
    git clone https://github.com/wlangstroth/vim-racket.git

Re-open your file(s) and benefit from the features of _vim-racket_.

## Available commands

`RktTest` - Runs the tests in the current buffer

`RktRun` - Runs the current buffer

## Thanks

Most of the real work on this module was done by [Paul Cannon](https://github.com/thepaul) and [Asumu Takikawa](https://github.com/takikawa).

To see all the contributors,

    git log | grep ^Author: | sed 's/ <.*//; s/^Author: //' | sort | uniq -c | sort -nr
