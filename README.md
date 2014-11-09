unzip-sfark
===========

Intended to be launched from a Nautilus script or KDE service menu, this script will invoke sfarkxtc on each selected sfArk file in turn. It assumes that sfarkxtc is installed in a directory included in the PATH environment variable (e.g. /usr/bin, /usr/local/bin).
___

Unzip sfArk
===========

Nautilus script to invoke sfarkxtc via the unzip-sfark script. It assumes that unzip-sfark is installed in a directory included in the PATH environment variable (e.g. /usr/bin, /usr/local/bin) and that xterm is available.

Near the top of the script are variables that may be modified if you need to specify the path of unzip-sfark or if you wish to use a different terminal emulator:

    UNZIP_SFARK_PATH="unzip-sfark"
    TERMINAL_COMMAND="xterm -hold -title UnzipSfArk -font 9x15 -e"

Place the script in the Nautilus scripts directory, e.g. '~/.gnome2/nautilus-scripts'. If Nautilus Scripts Manager is installed, place the script in '/usr/share/nautilus-scripts'.
___

unzip-sfark.desktop
===================

KDE service menu .desktop file to invoke sfarkxtc via the unzip-sfark script. It assumes that unzip-sfark is installed in a directory included in the PATH environment variable (e.g. /usr/bin, /usr/local/bin).

Place the .desktop file in one of the service menu directories, e.g. '/usr/share/services/ServiceMenus'.

You can find the location of all service directories like so:

    kde4-config --path services


