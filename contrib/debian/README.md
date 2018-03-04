
Debian
====================
This directory contains files used to package gcxd/gcx-qt
for Debian-based Linux systems. If you compile gcxd/gcx-qt yourself, there are some useful files here.

## gcx: URI support ##


gcx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gcx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gcxqt binary to `/usr/bin`
and the `../../share/pixmaps/gcx128.png` to `/usr/share/pixmaps`

gcx-qt.protocol (KDE)

