# gzdoom-snap

Version 3.5.1 of the Doom engine source-port in a snap, along with a graphical launcher for launching wads and pk3s.

All game files should go into the ~/snap/gzdoom/current/.config/gzdoom. You may have to create a folder or run the game first in order for the folder to show up.

This is my first attempt at making a snap. I might return to this in the future and see what changes I can make to it.

## Installation
cd to the gzdoom-snap directory and run:
 
`snapcraft`
 
In the same directory, run:
 
`sudo snap install --force-dangerous gzdoom_3.5.1_amd64.snap`
 
The launcher should appear in your app menu. First run will take a while, but subsiquent loads be normal.
