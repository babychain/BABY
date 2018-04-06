
Debian
====================
This directory contains files used to package babyd/baby-qt
for Debian-based Linux systems. If you compile babyd/baby-qt yourself, there are some useful files here.

## baby: URI support ##


baby-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install baby-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your babyqt binary to `/usr/bin`
and the `../../share/pixmaps/baby128.png` to `/usr/share/pixmaps`

baby-qt.protocol (KDE)

