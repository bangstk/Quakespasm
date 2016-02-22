# Quakespasm
My branch of Quakespasm with a few quality-of-life features and changes.

+ QuakeWorld hud option (controlled though "cl_sbar" cvar) including expansion support
+ Re-enable weapon viewmodel vertical offset with status bar enabled 
    - also adjusts with status bar scale
+ Scoot centerprint messages up off the crosshair
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
