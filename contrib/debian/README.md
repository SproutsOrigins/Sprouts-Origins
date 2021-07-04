
Debian
====================
This directory contains files used to package Sprouts-Originsd/Sprouts-Origins-qt
for Debian-based Linux systems. If you compile Sprouts-Originsd/Sprouts-Origins-qt yourself, there are some useful files here.

## Sprouts-Origins: URI support ##


Sprouts-Origins-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Sprouts-Origins-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Sprouts-Origins-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

pivx-qt.protocol (KDE)

