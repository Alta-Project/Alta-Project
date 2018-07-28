
Debian
====================
This directory contains files used to package altad/alta-qt
for Debian-based Linux systems. If you compile altad/alta-qt yourself, there are some useful files here.

## alta: URI support ##


alta-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alta-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your altaqt binary to `/usr/bin`
and the `../../share/pixmaps/alta128.png` to `/usr/share/pixmaps`

alta-qt.protocol (KDE)

