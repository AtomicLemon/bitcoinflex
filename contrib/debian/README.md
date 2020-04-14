
Debian
====================
This directory contains files used to package bitcoinflexd/bitcoinflex-qt
for Debian-based Linux systems. If you compile bitcoinflexd/bitcoinflex-qt yourself, there are some useful files here.

## bitcoinflex: URI support ##


bitcoinflex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinflex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinflex-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoinflex128.png` to `/usr/share/pixmaps`

bitcoinflex-qt.protocol (KDE)

