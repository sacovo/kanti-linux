kanti-linux
===========

Archiso, with persistence and other stuff...

Persistence is working

TODO
=====
* Configure locale stuff
* Fine tune applications
* ...

HOWTO
=====
Build with ./build.sh, copy to usb-stick with dd. Then create an additional partition on that usb stick, format with ext{2,3,4}, and give it the label 'persistent'. All changes that are made during usage are stored as cow on that partition.

Alternativly this should also work with a cd/dvd and additional usb-stick.
