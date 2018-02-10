
Debian
====================
This directory contains files used to package instacashd/instacash-qt
for Debian-based Linux systems. If you compile instacashd/instacash-qt yourself, there are some useful files here.

## instacash: URI support ##


instacash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install instacash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your instacashqt binary to `/usr/bin`
and the `../../share/pixmaps/instacash128.png` to `/usr/share/pixmaps`

instacash-qt.protocol (KDE)

