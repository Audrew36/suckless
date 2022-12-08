## Getting started

In order to install dwm together with ubuntu you going to need to move dwm.desktop to /usr/share/xsessions directory
For debian based systems, please watch tutorials on how to setup .xinitrc with "exec dwm"
### Installation

Most usually dwm directory is in ~/.config/suckless/ directory

cd into all suckless folders individually and do "sudo make" and "sudo make install"

and thats all. enjoy

### Use

Windows key is a super key

to enter search press "super key + p"
to enter new window press "super key + enter"
to move between windows use "super key + k or j"
to switch between work spaces press "super key + tab"
to escape dwm press "super + shift + q"
to set backround run "sudo apt-get install fehbg" and set ~/.fehb in your .xinitrc or .bashrc and make "feh --bg-fill ~/Picures/myWallpaper.png"
to set transparent windows run "sudo apt-get install compton" and set create comton.conf in ~/.config/comtpon/ directory with necessary settings ( you can find compton.conf example in root directory). Then write "compton" in terminal in order to launch it 
