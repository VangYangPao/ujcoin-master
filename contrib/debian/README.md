
Debian
====================
This directory contains files used to package zulad/zula-qt
for Debian-based Linux systems. If you compile zulad/zula-qt yourself, there are some useful files here.

## zula: URI support ##


zula-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zula-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zula-qt binary to `/usr/bin`
and the `../../share/pixmaps/zula128.png` to `/usr/share/pixmaps`

zula-qt.protocol (KDE)

