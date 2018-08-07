
Debian
====================
This directory contains files used to package fchaind/fchain-qt
for Debian-based Linux systems. If you compile fchaind/fchain-qt yourself, there are some useful files here.

## fchain: URI support ##


fchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fchainqt binary to `/usr/bin`
and the `../../share/pixmaps/fchain128.png` to `/usr/share/pixmaps`

fchain-qt.protocol (KDE)

