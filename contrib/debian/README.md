
Debian
====================
This directory contains files used to package rivad/riva-qt
for Debian-based Linux systems. If you compile rivad/riva-qt yourself, there are some useful files here.

## riva: URI support ##


riva-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install riva-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rivaqt binary to `/usr/bin`
and the `../../share/pixmaps/riva128.png` to `/usr/share/pixmaps`

riva-qt.protocol (KDE)

