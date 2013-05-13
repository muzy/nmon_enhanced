nmon_enhanced
=============

An enhanced version of nmon (Version 14g) by Nigel Griffiths
The original nmon was released under GPL Version 3 on 27th July 2009.

Build nmon_enhanced (NMON version 15a)
======================================
cc -o nmon lmon15a.c -g -O2 -D JFS -D GETUSER -Wall -D LARGEMEM -lncurses -g
