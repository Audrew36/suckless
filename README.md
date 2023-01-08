## Getting started

In order to install dwm together with ubuntu you going to need to move dwm.desktop to /usr/share/xsessions directory
For debian based systems, please watch tutorials on how to setup .xinitrc with "exec dwm"
### Installation

Most usually dwm directory is in ~/.config/suckless/ directory

cd into all suckless folders individually and do "sudo make" and "sudo make install"

to set backround run "sudo apt-get install feh" and set ~/.fehbg in your .xinitrc or .bashrc and make "feh --bg-fill ~/Pictures/myWallpaper.png"
to set transparent windows run "sudo apt-get install compton" and set create comton.conf in ~/.config/compton/ directory with necessary settings ( you can find compton.conf example in root directory). Then add "compton -b" command to .bashrc or .xinitrc to launch it on startup
to set slstatus, you need to configure correct path for every script in config.def.h and set sudo priviliges for sh scripts. To execute them on autostart write "exec slstatus" in your .bashrc or .xinitrc

NOTE: in order for suckless patch to apply you may need to delete config.h and edit config.def.h before compiling and config.h will be generated automatically 

and thats all. enjoy

### Use

Windows key is a super key

# to enter search in dmenu press "super key + i"
# to enter new window press "super key + enter"
# to move between windows use "super key + k or j"
# to switch between work spaces press "super key + tab"
# to escape dwm press "super + shift + q"
# to switch main window press "super key + shift + enter"
# to change language to lithuanian or united states press "super key + space or super key + shift + space"
# to volume up or down press "alt + o or alt + p"
# to open firefox press "super key + w"
# to set window for other work space press "super key + ctrl + shift + workspace number"
# to volume up or down use "alt + n or alt + m"
# to do screenshots install gnome-screenshots and then press "alt + s"
