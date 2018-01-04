
Debian
====================
This directory contains files used to package nefd/nef-qt
for Debian-based Linux systems. If you compile nefd/nef-qt yourself, there are some useful files here.

## nef: URI support ##


nef-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nef-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nefqt binary to `/usr/bin`
and the `../../share/pixmaps/nef128.png` to `/usr/share/pixmaps`

nef-qt.protocol (KDE)

