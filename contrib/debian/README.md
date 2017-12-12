
Debian
====================
This directory contains files used to package vritzcoind/vritzcoin-qt
for Debian-based Linux systems. If you compile vritzcoind/vritzcoin-qt yourself, there are some useful files here.

## vritzcoin: URI support ##


vritzcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vritzcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vritzcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/vritzcoin128.png` to `/usr/share/pixmaps`

vritzcoin-qt.protocol (KDE)

