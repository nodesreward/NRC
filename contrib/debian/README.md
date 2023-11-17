
Debian
====================
This directory contains files used to package nrcd/nrc-qt
for Debian-based Linux systems. If you compile nrcd/nrc-qt yourself, there are some useful files here.

## pivx: URI support ##


nrc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nrc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nrc-qt binary to `/usr/bin`
and the `../../share/pixmaps/nrc128.png` to `/usr/share/pixmaps`

nrc-qt.protocol (KDE)

