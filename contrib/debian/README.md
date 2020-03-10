
Debian
====================
This directory contains files used to package pictureexd/pictureex-qt
for Debian-based Linux systems. If you compile pictureexd/pictureex-qt yourself, there are some useful files here.

## pictureex: URI support ##


pictureex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pictureex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pictureexqt binary to `/usr/bin`
and the `../../share/pixmaps/pictureex128.png` to `/usr/share/pixmaps`

pictureex-qt.protocol (KDE)

