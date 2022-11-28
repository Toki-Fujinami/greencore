
Debian
====================
This directory contains files used to package cryptogreend/cryptogreen-qt
for Debian-based Linux systems. If you compile cryptogreend/cryptogreen-qt yourself, there are some useful files here.

## cryptogreen: URI support ##


cryptogreen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptogreen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptogreenqt binary to `/usr/bin`
and the `../../share/pixmaps/cryptogreen128.png` to `/usr/share/pixmaps`

cryptogreen-qt.protocol (KDE)

