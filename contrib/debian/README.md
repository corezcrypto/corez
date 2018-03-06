
Debian
====================
This directory contains files used to package corezd/corez-qt
for Debian-based Linux systems. If you compile corezd/corez-qt yourself, there are some useful files here.

## corez: URI support ##


corez-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install corez-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your corez-qt binary to `/usr/bin`
and the `../../share/pixmaps/corez128.png` to `/usr/share/pixmaps`

corez-qt.protocol (KDE)

