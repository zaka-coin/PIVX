
Debian
====================
This directory contains files used to package zakad/zaka-qt
for Debian-based Linux systems. If you compile zakad/zaka-qt yourself, there are some useful files here.

## zaka: URI support ##


zaka-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zaka-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zakaqt binary to `/usr/bin`
and the `../../share/pixmaps/zaka128.png` to `/usr/share/pixmaps`

zaka-qt.protocol (KDE)

