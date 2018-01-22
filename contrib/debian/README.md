
Debian
====================
This directory contains files used to package argod/argo-qt
for Debian-based Linux systems. If you compile argod/argo-qt yourself, there are some useful files here.

## argo: URI support ##


argo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install argo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your argo-qt binary to `/usr/bin`
and the `../../share/pixmaps/argo128.png` to `/usr/share/pixmaps`

argo-qt.protocol (KDE)

