Unzip-sfArk
===========

Nautilus script to invoke 'sfArkXTm'

This script allows you to invoke sfArkXTm on any number of selected .sfArk files. It was primarily written for use in AVLinux 6.0.1 and therefore assumes that sfArkXTm is installed in ~/Extra Goodies/SfArkXTm and that xterm is available.

Near the top of the script are variables that may be modified if sfArkXTm is installed somewhere else or if you wish to use a terminal emulator other than xterm:

    SFARKXTM_DIR="$HOME/Extra Goodies/SfArkXTm"
    SFARKXTM_EXEC="sfArkXTm"
    TERMINAL_COMMAND="xterm -hold -title UnzipSfArk -font 9x15 -e"

Once downloaded, make the script executable then move it to /usr/share/nautilus-scripts if Nautilus Scripts Manager is installed or to ~/.gnome2/nautilus-scripts to make the script always available.
