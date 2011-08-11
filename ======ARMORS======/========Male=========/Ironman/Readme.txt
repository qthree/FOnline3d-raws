Files for test version of "ironman", made by White Tiger.

Note that these files will quickly become obsolete, as I attempt to improve the rigging so that the "robe" moves properly around the legs. You can play with the existing files though, of course.

Any further info to be found here :
http://fonline2238.net/forum/index.php?board=31.0

######################

This all assumes that you've already :
1) Downloaded the SDK, and the files from the 3D development SDK
2) Added your own admin password to :
"Access_admin=YOUR PASSWORD" in \Server\FOnlineServer.cfg

######################

Files included :

Armor_male_ironman.x (Rigged model of coat / armour)
Armor_male_ironmask.x (Rigged model of gas mask)
Armor_male_ironman_coat.png (Texture for coat / armour)
Armor_male_ironman_body.png (Texture for base body)
Armor_male_ironman_mask.png (Texture for gas mask)
alterations_to_fo3d.txt (lines to paste into "_FOHuman.fo3d")
Readme.txt (This document)

######################

To implement :

1) Copy 
Armor_male_ironman.x
Armor_male_ironmask.x

to \Client\data\art\critters

2) Copy
Armor_male_ironman_coat.png
Armor_male_ironman_body.png
Armor_male_ironman_mask.png

to \Client\data\textures

3) Copy and paste the relevant lines from
alterations_to_fo3d.txt

into 
\Client\data\art\critters\_FOHuman.fo3d

Note that .fo3d files can open in notepad / wordpad / gedit / equivalent

######################

4) In game, you'll need to add the models by command, like so :
5) Press enter to bring up the chat / command line
6) ~getaccess admin YOUR PASSWORD
7) ~param 0 155 26 (this recolours the base skin)
8) ~param 0 154 26 (this adds the mask, and currently overwrites the hair)
9) ~param 0 153 26 (this adds the armour)

Hope that all makes sense.

Regards,
Luther Blissett