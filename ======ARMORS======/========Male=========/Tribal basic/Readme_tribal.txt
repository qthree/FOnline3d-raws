Files for test version of "Tribal", using part of White Tiger's shaman base texture.

######################

This all assumes that you've already :
1) Downloaded the SDK, and the files from the 3D development SDK
2) Added your own admin password to :
"Access_admin=YOUR PASSWORD" in \Server\FOnlineServer.cfg

######################

Files included :

Armor_male_tribal.x (rigged model of tribal straps)
Armor_male_tribal.png (Texture for body and straps)
alterations_to_fo3d_tribal.txt (lines to paste into "_FOHuman.fo3d")
Readme.txt_tribal (This document)

######################

To implement :

1) Copy 
Armor_male_tribal.x

to \Client\data\art\critters

2) Copy
Armor_male_tribal.png

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
7) ~param 0 155 28 (this recolours the trousers)
8) ~param 0 153 28 (this adds the straps on the arm and torso)

Hope that all makes sense.

Regards,
Luther Blissett