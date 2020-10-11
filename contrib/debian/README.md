
Debian
====================
This directory contains files used to package sproutsoriginsd/sproutsorigins-qt
for Debian-based Linux systems. If you compile sproutsoriginsd/sproutsorigins-qt yourself, there are some useful files here.

## sproutsorigins: URI support ##


sproutsorigins-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sproutsorigins-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sproutsoriginsqt binary to `/usr/bin`
and the `../../share/pixmaps/sproutsorigins128.png` to `/usr/share/pixmaps`

sproutsorigins-qt.protocol (KDE)

