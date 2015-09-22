# rolo

vCard viewer and editor.  Fork of the [Rolo](http://rolo.sourceforge.net/) project by Andrew Hsu, which seems abandoned.

Original read me file provided in README.

## Compilation

    autoreconf -f -i
    ./configure
    make
    make install

Note: if making changes, use

    git update-index --assume-unchanged INSTALL

to avoid automatic changes to INSTALL making it into the git history.

## Changes to Original

Debian patches applied from  https://anonscm.debian.org/cgit/users/rafael/deb-pkg/rolo.git

*  Rafael Laboissiere's manpage-close-list patch.
