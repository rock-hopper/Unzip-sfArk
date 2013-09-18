Unzip-sfArk
===========

Nautilus script to invoke 'sfArkXTm'

This script allows you to invoke sfArkXTm on any number of selected .sfArk files. It assumes that sfArkXTm is installed in /usr/bin and that xterm is available.

Near the top of the script are variables that may be modified if sfArkXTm is installed somewhere else or if you wish to use a terminal emulator other than xterm:

    SFARKXTM_DIR="/usr/bin"
    SFARKXTM_EXEC="sfArkXTm"
    TERMINAL_COMMAND="xterm -hold -title UnzipSfArk -font 9x15 -e"

Once downloaded, make the script executable then move it to /usr/share/nautilus-scripts if Nautilus Scripts Manager is installed or to ~/.gnome2/nautilus-scripts to make the script always available.
