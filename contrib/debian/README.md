
Debian
====================
This directory contains files used to package esterrad/esterra-qt
for Debian-based Linux systems. If you compile esterrad/esterra-qt yourself, there are some useful files here.

## esterra: URI support ##


esterra-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install esterra-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your esterraqt binary to `/usr/bin`
and the `../../share/pixmaps/esterra128.png` to `/usr/share/pixmaps`

esterra-qt.protocol (KDE)

