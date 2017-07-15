# Points of Interest

A Mod for Minetest.

![Screenshot 1](textures/minetest_poi_screenshot.jpg)

This Mod adds PoI's, Point's of Interest to your World.
If you have set a PoI, you can everytime jump back to the PoI with a simple Chatcommand.

### /poi_list [-a]  [-f]  [-c]
Lists Points of Interest.
Option -a: List all Points of Interest with Coordinates
Option -f: Lists forbidden Chars or Names
Option -c: Lists the Categories of PoI's

### /poi_jump [Name]
Jumps to a Point of Interest.

### /poi_gui
Opens a simple GUI, where you can Double-Click the Points to Jump.

### This commands demands the Priv "poi":
### /poi_set [Name]
Set's a new Point of Interest. You can't overwrite an existing POI.
This Action will be logged.

### /poi_delete [Name]
Deletes a Point of Interest. You can't delete an unknown POI.
This Action will be logged.

### /poi_move [Name]
This command overwrites the Coordinates of the given POI with your current Coordinates.
This Action will be logged.

### /poi_rename [Name1],[Name2]
This command renames an existing Point [Name1] of Interest to Point of Interest [Name2]. [Name2] can't have the name of an already existing Point. 
This Action will be logged.

### /poi_reload
If the List of POI's are in any kind corrupted, you can reload the List without a new Serverstart.

As Admin, you can grant Privs for the Player.
All the Points will be stored at a File in your World-Directory with the name: poi.txt

### /poi_validate
Checks the List of Entrys for invalid Names or Positions. If found an Entry, the command deletes it.<br>
This Action will be logged.

## Privileges

interact:<br>
/poi_jump [name]<br>
/poi_list [-a]  [-f]  [-c]<br>
/poi_gui<br>

poi:<br>
/poi_set [name]<br>
/poi_delete [name]<br>
/poi_reload<br>
/poi_move [name]<br>
/poi_rename [name1], [name2]<br>
/poi_validate

## Install

Move your Download to the Mods-Folder.

## Depends

none

## License

License: WTFPL
