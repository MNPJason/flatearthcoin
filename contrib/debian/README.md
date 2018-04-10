
Debian
====================
This directory contains files used to package flatearthd/flatearth-qt
for Debian-based Linux systems. If you compile flatearthd/flatearth-qt yourself, there are some useful files here.

## flatearth: URI support ##


flatearth-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install flatearth-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your flatearth-qt binary to `/usr/bin`
and the `../../share/pixmaps/flatearth128.png` to `/usr/share/pixmaps`

flatearth-qt.protocol (KDE)

