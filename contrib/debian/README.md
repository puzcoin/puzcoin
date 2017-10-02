
Debian
====================
This directory contains files used to package puzcoind/puzcoin-qt
for Debian-based Linux systems. If you compile puzcoind/puzcoin-qt yourself, there are some useful files here.

## puzcoin: URI support ##


puzcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install puzcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your puzcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/puzcoin128.png` to `/usr/share/pixmaps`

puzcoin-qt.protocol (KDE)

