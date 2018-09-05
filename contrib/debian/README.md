
Debian
====================
This directory contains files used to package BitFd/BitF-qt
for Debian-based Linux systems. If you compile BitFd/BitF-qt yourself, there are some useful files here.

## BitF: URI support ##


BitF-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BitF-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BitFqt binary to `/usr/bin`
and the `../../share/pixmaps/BitF128.png` to `/usr/share/pixmaps`

BitF-qt.protocol (KDE)

