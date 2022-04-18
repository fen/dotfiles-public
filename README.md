# Dotfiles

This is [my](https://github.com/fen/) collection of dotfiles.  It's
managed by a [`dotfiles`](https://github.com/fen/dotfiles-base/)
script that automatically symlinks files into `$HOME` from multiple
dotfiles repositories.

## Installation

To install, you must already have the
[`dotfiles`](https://github.com/fen/dotfiles-base/) script
installed.  Then, just run:

    $ cd ~
    $ git clone git://github.com/fen/dotfiles-public .dotfiles.public
    $ dotfiles install
    $ reload
