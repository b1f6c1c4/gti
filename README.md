ivm
===

Just a silly `vim` launcher, basically. Inspired by `sl`.

Build and Install
-----------------

From a package system:
* [Fedora](https://src.fedoraproject.org/rpms/ivm)
* it's in ArchLinux' AUR as [ivm-vim](https://aur.archlinux.org/packages/ivm-vim/) and as [ivm](https://aur.archlinux.org/packages/ivm/)
* [Gentoo](https://packages.gentoo.org/packages/dev-vcs/ivm)
* [Nix/NixOS](https://search.nixos.org/packages?show=ivm&query=ivm)
* [FreeBSD ports](http://svnweb.freebsd.org/ports/head/games/ivm/)
* [OpenBSD ports](http://openports.se/games/ivm)
* [Homebrew/MacOS X](https://formulae.brew.sh/formula/ivm#default)
* [Cygwin](https://cygwin.com/packages/summary/ivm.html)

From source:

    $ make
    $ make install # as root, probably

The default install PREFIX is `/usr/bin`.

You can change the speed of the car at runtime via `IVM_SPEED`.
For example:

    $ IVM_SPEED=2000 ivm push # default is 1000

Usage
-----

Try typing `vim` really fast, on an unfamiliar keyboard.

Author and License
------------------

Copyright 2012 by Richard Wossal <richard@r-wos.org>

Permission to use, copy, modify, distribute, and sell this software
and its documentation for any purpose is hereby granted without fee,
provided that the above copyright notice appear in all copies and
that both that copyright notice and this permission notice appear in
supporting documentation.  No representations are made about the
suitability of this software for any purpose.  It is provided "as
is" without express or implied warranty.

