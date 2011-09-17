Files for test version of "Archlight helmet", made by Haraldx.

As with previous hat experiments, the skeleton attached to this hat only goes from spine to head (i.e. the arms and legs are cut off). Remaining bones are named the same as before.

Any further info to be found here :
http://fonline2238.net/forum/index.php?board=31.0

######################

This all assumes that you've already :
1) Downloaded the SDK, and the files from the 3D development SDK
2) Added your own admin password to :
"Access_admin=YOUR PASSWORD" in \Server\FOnlineServer.cfg

######################

Files included :

armor_male_weldingmask.x (rigged model of helmet)
Armor_male_weldingmask.png (texture)
alterations_to_fo3d Archlight_helmet.txt (lines to paste into "_FOHuman.fo3d")
Readme Archlight_helmet.txt (This document)

######################

To implement :

1) Copy 
armor_male_weldingmask.x

to \Client\data\art\critters

2) Copy
Armor_male_weldingmask.png

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
7) ~param 0 154 29

Hope that all makes sense.

Regards,
Luther Blissett