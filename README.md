Fallout 4 VR Modern Tactical Overhaul

Nexus Download: https://www.nexusmods.com/fallout4/mods/71281

Best way to show your appreciation is to endorse on Nexus and post images/videos of this mod list on Reddit/Youtube.  

This modlist is designed for 3070 and up.  I was playing on 11700 + 3070 until I upgraded to 3090, Virtual Desktop High (1.35x native Quest 2 resolution which shines with FSR upscaling), 45 FPS reprojected to 90.  For all crash issues, drop crash<dateTime stamp>.log from My Documents\Fallout4VR\F4SE in chat.  All other issues, please specify GPU and headset.
  
DLC from regular Fallout 4 is required.  There are just too many mods that require it.

- [Installation](#installation)
- [Starting The Game](#starting-the-game)
- [Visuals and Performance](#visuals-and-performance)
- [Mod Settings](#mod-settings)  
- [Gameplay Notes](#gameplay-notes)
- [Updating to New Version](#updating-to-new-version)
- [Add New Mods](#add-new-mods)
- [Changing Weather](#changing-weather)
- [Known Issues](#known-issues)
  
## **Installation**

- Installation Video: https://youtu.be/sREEaEwBQck
- (Mandatory!) Copy DLC from Fallout 4 To Fallout 4 VR.  Copy all 32 files that start with DLC from Fallout 4 /data to Fallout 4 VR /data 
- Download the zip file from Nexus, extract into .wabbajack file
- Download and run Wabbajack program itself from https://www.wabbajack.org/ and choose the "Install From Disk" option, install to a root folder not shared by Fallout 4 VR like D:\FO4VR_Overhaul, as MO2 needs full lock to the entire directory
- Antivirus will occasionally flag Wabbajack files or even textures from Nexus, it is safe to ignore, please see Wabbajack Discord for this well known issue.  You may need to whitelist the directory it installs to as well as the downloads folder
- You do not EVER need to delete and install a Wabbajack list from scratch, it is a 100% file sync
- Typical download errors are caused by Nexus server issues.  Quit Wabbajack, restart, overwrite to resume and you won't lose any progress
- If the error is about a file that should be part of standard Fallout 4 VR installation, set the game to English, do a Steam file validation

## **Starting The Game**

- Once installation is complete, open MO2 from the installed folder and run "Play Game (F4SEVR)" from upper right corner, everything is already included and ready to go out of box
- Depend on your headset you may need to launch Steam VR ahead of the time before opening the game in MO2, if your game crashes before Bethesda logo and you see "Unable to Initialize VR" in crash log, uninstall and reinstall Steam VR
- Set resolution multiplier in only ONE of the three places: Virtual Desktop, Oculus App or Steam VR, the others should be left at 100%. The sweet spot is VD ultra, Oculus 1.5x or Steam VR 150% resolution to cover barrel distortion. This is not always playable depend on your headset resolution and GPU, on a 3070 and Quest 2 for example, I could only do 130% of device resolution, change the headset to Pico 4 I will need to go 110% device resoluton, with Index I can do 150% device resolution. G2 100% Steam VR resolution is already 150% of device resolution, so reduce it to 90% or 80% if needed
- When starting new game, stand still wait for all the workshop framework to run and finish after you create character, you will be teleported into the game automatically once it is done, so chill in your house for a while.  This will skip the buggy intro sequence, feel free to play the game unmodded to watch the opening scene if you want to experience the intro, then run MO2 to resume on the save after you leave vault
- FRIK crashes the game when you create new characters so it is disabled on start up.  Once you create a character and get to the surface, you can save the game, exit, enable FRIK in MO2 to resume, it is the last mod and plugin on each side of MO2  
- Pip Boy should be set to Projected with in-game setting, otherwise you may get a blank screen in FRIK  
- Other mods/plugins are disabled for a reason, do not mass enable all, if you did, restore mod order with back arrow on mod tab.  Do not sort plugins with LOOT, restore plugin order with back arrow on plugin tab if you messed it up  
- Oculus/Pico users, I strongly recommend Virtual Desktop

## **Visuals and Performance**  

- Right click the FSR mods you selected, open in explorer, edit the YML file and increase sharpness
- Use FSR quality in MO2 mods or in the case of 4080/4090, try the FSR Disabled Sharpening Only profile
- Increase resolution multiplier in Virtual Desktop, Oculus App or Steam VR, the sweet spot is 150% of device resolution in one of these three places 
- Running out of VRAM is the easiest way to make the game unplayable.  On 8GB cards like 3070 and 3060TI, consider download and replace the textures with Luxor 2K if you experience stuttering in cities: https://www.nexusmods.com/fallout4/mods/65720 
  
## **Gameplay Notes**

- I play on survival difficulty, with no follower.  Thanks to the "Unlimited Survival" mod, many tedious aspects of survival are disabled.  You can save game any time and fast travel, and the extra survival elements really makes it fun
- This is the modern tactical edition, standing in the open for a few seconds against a raider with AK47, and you are dead.  Time to kill is fast on both sides.  Every single weapon you can use, the enemy has them too!
- Bullet time VATS is a great way to even the odds, although I personally only use it if I die many times in a row for the challenge.  Relying on positioning and tactics instead of super power
- Weapons are randomly distributed on both sides for rogue-like element of surprise.  This provides an element of surprise as you never know whether the next Raider is packing a simple pistol or an AK.  Higher character levels will provide more variety, more modern weapons, as you level you will see loot pool grow from MP5 to MP9, AK47 to AN94 and so on  
- Character builds, especially with legendary crafting thanks to ECO, is deep and satisfying.  You can still build a very powerful character, but the enemy will always be able to kill you quickly on higher difficulties.  Being able to take 4 bullets instead of 2 through build/equipment upgrades, is not the same as being able to take 4 fireballs instead of 2 in Skyrim
- You can lower the difficulty any time, cheat terminal is also included to quickly try out new guns, SKK respec is included to try new builds

## **Mod Settings**  

MO2 Mods Section
  
FSR
- Choose different quality settings depend on your hardware and device resolution

Reshade
- Applies color correction and sharpening, the full version applies a faux HDR on lighting, see which one you like better  

V.A.T.S. Tweaks
- Reinstall this mod to make bullet time faster/slower

HUIDE - Hide HUD Elements in VR
- Reinstall this mod to choose more/less UI elements

Enable Nudity
- Run included BodySlide from MO2 drop down menu
- Click Batch Build (lower left corner)
- Right click the list of outfits and Select All
- Choose CBBE Body Physics 

In Game MCM
  
FRIK
- Use FRIK holo tape in inventory to calibrate your height
- You can move your view forward if you have hair/armor in your view, or enable headless mode although it will lower your difficulties as it reduces your hit box and makes you immune to head shots
- The weapon positions are adjusted for static gripping which should always be on, there are a lot of custom edits to the weapon custom patches and I will not support anything other than static gripping

NAC X
- Disable chem FX, hit FX and specific weather effects if you don't like it
- I already edited ESP to disable sunglass, vignette and noise by default  

SKK Combat Stalker 
- It is the best random enemy spawner, and really keeps you on your toes with search and destroy death squads, recommended although it can make your game a tad less stable if spawned in specific situations  

Virtual Chems - This mod is quite janky at times and I will probably leave it disabled by default next release
- With your left hand pick up stimpaks from your left ear and stab em in your right hand! Inhale all accidentally picked up jets!
  
Virtual Holsters - This mod is quite janky at times and I will probably leave it disabled by default next release
- Have a weapon in your hand. Move it over a holster sphere, feel light buzz on the controller.
- Hold Favorites button until bigger buzz, now the weapon is assigned to that holster.
- Now you can pick up the weapon from holster with Grip Or A button.aka "Use" button, same that opens doors. Same button to put the weapon pack to holster
- To remove/empty weapon from holster, hold Favorites button with empty hands over the holster sphere until a big buzz informs that holster is empty and ready for a different weapon
  
## **Updating to New Version**

- With the exception of major version upgrades like 2.0, I will never break a save intentionally
- It is however not possible to predict save stability if you added/removed mods, or test every iteration of every save game.  Review change log and make changes manually is always the safest way to update the list and keep the changes you made
- You can use [NoDelete] in front of installed mods like "[NoDelete] Better Settlers" to keep them from being removed, however you will still need to manually put them back into load order
- You will still lose sort order and personal FOMOD choices when you update, so consider making updates manually based on change logs

## **Add New Mods**

- Always have a separate save game before adding new mods, in case you need to remove and revert
- In general any mod without specific requirement is safe to add, place them in the right category on left side and right side.  For example new guns should go after weapon mods, new companion should go after NPC mods.  Do not sort with LOOT
- Any mods that need to be in root folder will need to be put into the root folder of Essential Boot Files (back up existing files first).  This modlist uses Root Builder so your actual root folder is 100% clean

## **Changing Weather**

- Go indoor and make a save, exit game
- Turn off current weather (NAC X) in MO2 mods, enable new weather (Vivid and True Storms)
- Click back arrow from plugins tab to sort the plugins correctly
  
## **Known Issues**

- Virtual Chem and Holster are quite unreliable, will disable/remove from next release
- VR Weapon Overhaul has done a ton of calibration on weapons, scopes and sights but not every single combination is going to be perfect for every user.  Use the Westtek Scope created by the author for most accurate scopes, or use a weapon that works better for you    
- Balance of weapon and armor distribution will likely need more work, your feedback is welcome!
- DLC weapon and armor replacer need more work, for the first release I focused on vanilla contents  
- Given the huge change to the entire leveled list, if you notice bugs or crashes like fighting a specific enemy with a specific weapon, or weapon/armor bench crashes due to specific keywords, please let me know on the Discord and I will patch it
- Do not save in power armor, can cause corrupted saves, same as vanilla Fallout 4 VR
- Turning on flashlight while opening inventory has a chance of crashing your game, same as vanilla Fallout 4 VR
