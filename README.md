rcm
===

This is a management suite for dotfiles.

It assumes that you have a separate dotfiles directory, or are
interested in creating one.

The programs provided are `rcup`, `mkrc`, `rcdn`, and `lsrc`.

Installation
------------

Arch Linux:

  https://aur.archlinux.org/packages/rcm-git/

Debian-based (including Ubuntu):

    wget http://thoughtbot.github.io/rcm/debs/rcm_1.1.0_all.deb
    sudo dpkg -i rcm_1.1.0_all.deb

OS X:

    brew tap thoughtbot/formulae
    brew install rcm

Elsewhere:

This uses the standard GNU autotools, so it's the normal dance:

    ./configure && \
    make && \
    make install

For more, see `INSTALL`.

Programs
--------

* `rcup` is the main program. It is used to install and update dotfiles,
  with support for tags, host-specific files, and multiple source
  directories.
* `rcdn` is the opposite of `rcup`.
* `mkrc` is for introducing a dotfile into your dotfiles directory, with
  support for tags and multiple source directories.
* `lsrc` shows you all your dotfiles and where they would be symlinked
  to. It is used by `rcup` but is provided for your own use, too.

Support
-------

Pull requests welcome; see `DEVELOPERS.MD`.

License
-------

Copyright 2013 Mike Burns. BSD license.
