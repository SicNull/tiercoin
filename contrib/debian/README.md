
Debian
====================
This directory contains files used to package tiercoind/tiercoin-qt
for Debian-based Linux systems. If you compile tiercoind/tiercoin-qt yourself, there are some useful files here.

## tiercoin: URI support ##


tiercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tiercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tiercoinqt binary to `/usr/bin`
and the `../../share/pixmaps/tiercoin128.png` to `/usr/share/pixmaps`

tiercoin-qt.protocol (KDE)

