
Debian
====================
This directory contains files used to package agenad/agena-qt
for Debian-based Linux systems. If you compile agenad/agena-qt yourself, there are some useful files here.

## agena: URI support ##


agena-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install agena-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your agena-qt binary to `/usr/bin`
and the `../../share/pixmaps/agena128.png` to `/usr/share/pixmaps`

agena-qt.protocol (KDE)

