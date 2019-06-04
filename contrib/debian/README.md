
Debian
====================
This directory contains files used to package excld/excl-qt
for Debian-based Linux systems. If you compile excld/excl-qt yourself, there are some useful files here.

## excl: URI support ##


excl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install excl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your excl-qt binary to `/usr/bin`
and the `../../share/pixmaps/excl128.png` to `/usr/share/pixmaps`

excl-qt.protocol (KDE)

