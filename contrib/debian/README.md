
Debian
====================
This directory contains files used to package polariscoinnetworkd/polariscoinnetwork-qt
for Debian-based Linux systems. If you compile polariscoinnetworkd/polariscoinnetwork-qt yourself, there are some useful files here.

## polariscoinnetwork: URI support ##


polariscoinnetwork-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install polariscoinnetwork-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your polariscoinnetworkqt binary to `/usr/bin`
and the `../../share/pixmaps/polariscoinnetwork128.png` to `/usr/share/pixmaps`

polariscoinnetwork-qt.protocol (KDE)

