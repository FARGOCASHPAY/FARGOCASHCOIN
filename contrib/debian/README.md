
Debian
====================
This directory contains files used to package fargocashd/fargocash-qt
for Debian-based Linux systems. If you compile fargocashd/fargocash-qt yourself, there are some useful files here.

## fargocash: URI support ##


fargocash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fargocash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fargocashqt binary to `/usr/bin`
and the `../../share/pixmaps/fargocash128.png` to `/usr/share/pixmaps`

fargocash-qt.protocol (KDE)

