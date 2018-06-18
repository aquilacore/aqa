
Debian
====================
This directory contains files used to package aqad/aqa-qt
for Debian-based Linux systems. If you compile aqad/aqa-qt yourself, there are some useful files here.

## aqa: URI support ##


aqa-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aqa-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aqaqt binary to `/usr/bin`
and the `../../share/pixmaps/aqa128.png` to `/usr/share/pixmaps`

aqa-qt.protocol (KDE)

