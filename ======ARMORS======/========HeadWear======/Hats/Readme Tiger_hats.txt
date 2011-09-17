Files for test version of various hats, made by White Tiger.

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

armor_male_hockeymask.x (rigged model of mask)
armor_male_tophat.x (rigged model of hat)
armor_male_spikedhelmet.x (rigged model of helmet)
armor_all_hockeymask.png  (texture)
armor_all_tophat_skull.png (texture black with skull)
armor_all_tophat_american.png (texture, stars and stripes)
armor_all_spikedhelmet.png (texture)
alterations_to_fo3d Tiger_hats.txt (lines to paste into "_FOHuman.fo3d")
Readme Tiger_hats.txt (This document)

######################

To implement :

1) Copy 
armor_male_hockeymask.x
armor_male_tophat.x
armor_male_spikedhelmet.x

to \Client\data\art\critters

2) Copy
armor_all_hockeymask.png
armor_all_tophat_skull.png
armor_all_tophat_american.png
armor_all_spikedhelmet.png

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
7) ~param 0 154 30 (this adds the hockey mask)
8) ~param 0 154 31 (this adds the tophat / skull)
9) ~param 0 154 32 (this adds the tophat / american)
10) ~param 0 154 33 (this adds the spiked helmet)

Hope that all makes sense.

Regards,
Luther Blissett