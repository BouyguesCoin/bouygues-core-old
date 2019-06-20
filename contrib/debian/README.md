
Debian
====================
This directory contains files used to package bygd/byg-qt
for Debian-based Linux systems. If you compile bygd/byg-qt yourself, there are some useful files here.

## byg: URI support ##


byg-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install byg-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your byg-qt binary to `/usr/bin`
and the `../../share/pixmaps/byg128.png` to `/usr/share/pixmaps`

byg-qt.protocol (KDE)

