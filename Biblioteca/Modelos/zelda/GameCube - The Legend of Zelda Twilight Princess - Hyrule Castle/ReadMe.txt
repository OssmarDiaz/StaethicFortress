Models do NOT have broken texture/UV mapping. Many of the models use mirrored repeat or seamless tiling. This allowed game developers to for example only draw half or quarter of a circle and mirror tiling will turn it into a full circle. Also material blending is lost as that was done in-game.

I split the models into 3 folders. Inside, Outside and Props and Objects. Should be easy to find what your looking for this way.

All models are vary large so you need to zoom out and/or scale the models down. IIRC scaling down to 0.01 is what I see people say most. I have NOT changed the geolocation for any of the models and this mean most of the models are quite far away from the center of the world. If you load R00 to R08 into one large scene they look like they are geolocated so you can move room to room like in game.


Other info:
Dolphin used to pull the D_MN09 and D_MN09A directories out of the ISO than Switch ToolBox by KillzXGaming used open the .arc files inside of the extracted directories and save the models as .dae and save textures as .png.

All of the Outside areas when extracted (the .bmd files) will dump what looks like many corrupted textures. I'm not sure why the .bmd files have these corrupted textures but it looks like the game is programed to skip these corrupted textures load .bti textures from the D_MN09's STG_00.arc

So to do my best and make sure no corrupted get upload I extracted every room model into its own folder 1st than replaced any texture that looked from textures extracted from the Hyrule Castle STG_00.arc. I'm quite confident that no corrupted textures got uploaded as corrupted textures look corrupted and have black bars with green dots at the top of the texture. See the Corrupted_Textures.png for what they look like. 

Props and Objects:
I keep all of TPs objects extracted out as .bmd files This was done with yaz0dec and rarcdump before Switch Toolbox was a thing. Most of the .bmd files where loaded into Switch Toolbox and saved as .dae with .png. The Suit of Armor (lv9_md.dae) had to be loaded into Blender with Blemd by niacdoial and saved as .dae.

AJD-262
3/7/24