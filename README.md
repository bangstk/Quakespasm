# Quakespasm
My branch of Quakespasm with some minor features and changes.

+ QuakeWorld hud option (controlled though "cl_sbar" cvar) including expansion support
+ Automatic UI/HUD scaling 
    - (set scr_sbarscale/menuscale/conscale to 0 to use, or Scale slider to far left)
    - Handy as a default setting
    - Scales for even pixel size
    - Recalculate refdef on sbar scale change
+ Re-enable weapon viewmodel vertical offset with status bar enabled 
    - also adjusts with status bar scale
+ Scoot centerprint messages up off the crosshair
+ Widescreen status bar 
    - (hacky, this will probably be redone)

Upcoming:
+ Make the font textures use a texture atlas to prevent bleeding on seams
