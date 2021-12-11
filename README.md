Personal dmenu build with the following patches:
1. allow color font
2. border
3. case insensitive
4. center
5. fuzzymatch
6. fuzzyhighlight
7. line height
8. numbers
9. xresources alt

dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
