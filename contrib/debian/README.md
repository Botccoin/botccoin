
Debian
====================
This directory contains files used to package Botccoind/Botccoin-qt
for Debian-based Linux systems. If you compile Botccoind/Botccoin-qt yourself, there are some useful files here.

## Botccoin: URI support ##


Botccoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Botccoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Botccoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/Botccoin128.png` to `/usr/share/pixmaps`

Botccoin-qt.protocol (KDE)

