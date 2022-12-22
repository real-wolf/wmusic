# wmusic
WMusic windowmaker dockapp forked from https://repo.or.cz/dockapps.git/tree/HEAD:/wmusic to build on modern systems, mainly removing hard version requirements from libs/includes

Requirements:
	- libdockapp (https://www.dockapps.net/libdockapp)
	- playerctl (https://github.com/acrisci/playerctl)
	- an MPRIS-compatible media player (most of them)

Building:

    ./configure
    make
    sudo make install
    
Running:

    $ wmusic
    
should build and run on any modern system (tested on fedora 37)
