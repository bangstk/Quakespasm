# Quakespasm
My branch of Quakespasm with a few quality-of-life features and changes.

+ [QuakeWorld hud option](http://i.imgur.com/IucSPLL.png) (controlled though "cl_sbar" cvar) [including expansion support](http://i.imgur.com/l7wGfZV.png)
+ [Re-enable weapon viewmodel vertical offset with status bar enabled](http://i.imgur.com/kJpRDqb.png)
    - [also adjusts with status bar scale](http://i.imgur.com/GBEYIaG.jpg)
+ [Scoot centerprint messages up off the crosshair](http://i.imgur.com/PofcgdD.png)
+ Recalculate refdef on sbar scale change


Upcoming:
+ Automatic UI/HUD scaling 
    - (set scr_sbarscale/menuscale/conscale to 0 to use, or Scale slider to far left)
    - Handy as a default setting
    - Scales for even pixel size
+ "vid_width 0" or "vid_height 0" to use desktop resolution
    - Handy as a default setting
+ Widescreen status bar 
    - (hacky, this will probably be redone)
+ Try to make the font textures use an array to prevent bleeding on seams, allowing linear filtering
