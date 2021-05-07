
Debian
====================
This directory contains files used to package felixcoind/felixcoin-qt
for Debian-based Linux systems. If you compile felixcoind/felixcoin-qt yourself, there are some useful files here.

## felixcoin: URI support ##


felixcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install felixcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your felixcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

felixcoin-qt.protocol (KDE)

