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


Add configs/files
-----------------

just add all wanted files to the `root-image` directory. All files will be copied as-is into the final image.


Todos
-----

- remove unneeded packages

More info
---------

For more information, check out the [Archiso](https://wiki.archlinux.org/index.php/Archiso) wiki page.
