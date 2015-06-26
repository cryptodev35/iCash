
Debian
====================
This directory contains files used to package icashd/icash-qt
for Debian-based Linux systems. If you compile icashd/icash-qt yourself, there are some useful files here.

## icash: URI support ##


icash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install icash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your icash-qt binary to `/usr/bin`
and the `../../share/pixmaps/icash128.png` to `/usr/share/pixmaps`

icash-qt.protocol (KDE)

