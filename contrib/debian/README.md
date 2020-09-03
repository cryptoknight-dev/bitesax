
Debian
====================
This directory contains files used to package bitesaxd/bitesax-qt
for Debian-based Linux systems. If you compile bitesaxd/bitesax-qt yourself, there are some useful files here.

## bitesax: URI support ##


bitesax-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitesax-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitesaxqt binary to `/usr/bin`
and the `../../share/pixmaps/bitesax128.png` to `/usr/share/pixmaps`

bitesax-qt.protocol (KDE)

