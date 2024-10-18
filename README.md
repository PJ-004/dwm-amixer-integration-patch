# dwm-amixer-integration-patch
Storing the amixer integration patch I wrote for dwm. This patch allows the use of volume buttons, provided that amixer and xorg's xf68keysym are installed.

## Install
1. Clone the repository using https://github.com/PJ-004/dwm-amixer-integration-patch/ or just download the diff file
2. Put the diff file into the directory that dwm is installed
3. Use the command `patch -p1 < dwm-amixer-integration-6.5.diff` in the same directory
4. If the patch is applied successfully, use `sudo make clean install` to reinstall dwm
5. Log out of DWM and then log back in
