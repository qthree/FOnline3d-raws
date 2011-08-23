Files for test version of "Duster Hat", made by Luther Blissett.

Note that as part of a little experiment, the skeleton attached to this hat only goes from spine to head (i.e. the arms and legs are cut off). Remaining bones are named the same as before.

Any further info to be found here :
http://fonline2238.net/forum/index.php?board=31.0

######################

This all assumes that you've already :
1) Downloaded the SDK, and the files from the 3D development SDK
2) Added your own admin password to :
"Access_admin=YOUR PASSWORD" in \Server\FOnlineServer.cfg

######################

Files included :

armor_male_dusterhat.X (rigged model of hat)
Armor_male_cowboyhat_brown.png (Texture brown)
Armor_male_cowboyhat_black.png (Texture black)
alterations_to_fo3d.txt (lines to paste into "_FOHuman.fo3d")
Readme.txt (This document)

######################

To implement :

1) Copy 
armor_male_dusterhat.X

to \Client\data\art\critters

2) Copy
Armor_male_cowboyhat_brown.png
Armor_male_cowboyhat_black.png

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
7) ~param 0 154 27 (this adds the brown hat)
8) ~param 0 154 28 (this adds the black hat)

Hope that all makes sense.

Regards,
Luther Blissett