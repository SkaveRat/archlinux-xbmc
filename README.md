Archlinux XBMC
==============

This image automaticly boots an archlinux and starts xbmc on startup.

Usable as a livesystem for CD, USB or network boot.

This configuration is tailored for a system of the [chaosdorf](http://chaosdorf.de) hackspace.

If you want to use this for your own system, please note the specific settings (hostname, ssh private keys)


Dependencies
------------

This needs to be build on an x86\_64 archlinux system

Needed packages:

- archiso

Building
--------

    cd releng
    sudo ./build.sh -v

Output is located in `out/`

Add package
-----------

Just add wanted package to `packages.*`

Todos
-----

- remove unneeded packages
