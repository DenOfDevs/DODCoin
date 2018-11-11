
Debian
====================
This directory contains files used to package dodcoind/dodcoin-qt
for Debian-based Linux systems. If you compile dodcoind/dodcoin-qt yourself, there are some useful files here.

## dodcoin: URI support ##


dodcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dodcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dodcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/dodcoin128.png` to `/usr/share/pixmaps`

dodcoin-qt.protocol (KDE)

