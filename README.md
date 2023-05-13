Fallout 4 VR Modern Tactical Overhaul

Nexus Download: https://www.nexusmods.com/fallout4/mods/71281

Best way to show your appreciation is to endorse on Nexus and post images/videos of this mod list on Reddit/Youtube.  

This modlist is designed for 3070 and up.  I was playing on 11700 + 3070 until I upgraded to 3090, Virtual Desktop High (1.35x native Quest 2 resolution which shines with FSR upscaling), 45 FPS reprojected to 90.  For all crash issues, drop crash<dateTime stamp>.log from My Documents\Fallout4VR\F4SE in chat.  All other issues, please specify GPU and headset.
  
DLC from regular Fallout 4 is required.  There are just too many mods that require it.

- [Installation](#installation)
- [Starting The Game](#starting-the-game)
- [Visuals and Performance](#visuals-and-performance)
- [Gameplay Notes](#gameplay-notes)
- [Updating to New Version](#updating-to-new-version)
- [Add New Mods](#add-new-mods)
- [Changing Weather](#changing-weather)
- [Known Issues](#known-issues)
  
## **Installation**

- (Mandatory!) Copy DLC from Fallout 4 To Fallout 4VR.  In /data/ folder copy all 32 files that start with DLC
- (Optional) Clean install of Fallout 4: https://www.youtube.com/watch?v=zwTJ3jImCiQ
- Download the zip file from Nexus, extract into .wabbajack file
- Download and run Wabbajack program itself from https://www.wabbajack.org/ and choose the install from disk option, install to a root folder not shared by Fallout 4 VR, as MO2 needs full lock to the entire directory
- Antivirus will occasionally flag Wabbajack files or even textures from Nexus, it is safe to ignore, please see Wabbajack Discord for this well known issue.  You may need to whitelist the directory it installs to as well as the downloads
- You do not EVER need to delete and install a Wabbajack list from scratch, it is a 100% file sync
- Typical download errors are caused by Nexus server issues.  Quit Wabbajack, restart, overwrite to resume and you won't lose any progress
- If the error is about a file that should be part of standard Fallout 4 VR installation, set the game to English, do a Steam file validation

## **Starting The Game**

- Once installation is complete, open MO2 from the installed folder and run "Play Game (F4SEVR)" from upper right corner, everything is already included and ready to go out of box
- When starting new game, stand still wait for all the workshop framework to run and finish after you create character, you will be teleported into the game automatically once it is done
- FRIK crashes the game when you create new characters (unless you already loaded a save in the current session which initiates its skeleton), so it is disabled on start up.  Once you create a character you can enable the mod and plugin sections, it is the last mod and plugin on each side of MO2.  Use FRIK holo tape in inventory to calibrate your height and you can move your view forward if you have hair/armor in your view, or enable headless mode although it will lower your difficulties as it reduces your hit box   
- Other mods/plugins are disabled for a reason, do not mass enable all, if you did, restore mod order with back arrow on mod tab.  Do not sort plugins with LOOT, restore plugin order with back arrow on plugin tab if you messed it up  
- Always start the game with Play Game (F4SEVR) in MO2, do not open Steam VR ahead of the time.  If MO2 gets stuck before opening Steam VR, close MO2 and end all VR Server related processes in task manager
- Set Steam resolution based on your headset resolution and GPU.  On Quest 2 and 3070 for example, I use Virtual Desktop high (equivalent of 135% Steam resolution) and leave Steam itself to 100%, using FSR balanced  
- Oculus/Pico users, I strongly recommend Virtual Desktop

## **Visuals and Performance**

- If you have a much better card than 3070, consider disable FSR with the" FSR Disabled Sharpening Only" profile in MO2 mods section
- If you need more FPS, enable FSR performance instead of quality in MO2 mods
- Running out of VRAM is the easiest way to make the game unplayable.  On 8GB cards, consider download and replace the textures with Luxor 2K if you experience stuttering in cities: https://www.nexusmods.com/fallout4/mods/65720 

## **Gameplay Notes**

- This is the modern tactical edition, standing in the open for a few seconds means you are dead against a couple of raider's with AK's on higher difficulties.  Time to kill is fast on both sides.  Every single weapon you can use, the enemy has them too  
- You can lower the difficulty any time, cheat terminal is also included to quickly try out new guns, SKK respec is included to try new builds
- Weapons are randomly distributed on both sides for the element of surprise.  Higher character levels will provide more variety, more modern weapons, think from MP5 to MP9, or AK47 to AN94
- Character builds, especially with legendary crafting thanks to ECO, is deep and satisfying.  You can still build a very powerful character, but the enemy will always be able to kill you quickly on higher difficulties.  Being able to take 4 bullets instead of 2, is not the same as being able to take 4 fireballs instead of 2 in Skyrim
- Highly recommend you enable SKK Stalker halo tape!  It is the best random enemy spawner and really keeps you on your toes
  
## **Updating to New Version**

- With the exception of major version upgrades like 2.0, I will never break a save intentionally
- It is however not possible to predict save stability if you added/removed mods, or test every iteration of every save game.  Review change log and make changes manually is always the safest way to update the list and keep the changes you made
- You can use [NoDelete] in front of installed mods like "[NoDelete] Better Settlers" to keep them from being removed, however you will still need to manually put them back into load order
- You will still lose sort order and personal FOMOD choices when you update, so consider making updates manually based on change logs

## **Add New Mods**

- Always have a separate save game before adding new mods, in case you need to remove and revert
- In general any mod without specific requirement is safe to add, place them in the right category on left side and right side.  For example new gunss should go after weapon mods, new companion should go after NPC mods.  Do not sort with LOOT
- Any mods that need to be in root folder will need to be put into the root folder of Essential Boot Files (back up existing files first).  This modlist uses Root Builder so your actual root folder is 100% clean

## **Changing Weather**
- Go indoor and make a save, exit game
- Turn off current weather (NAC X) in MO2 mods, enable new weather (Vivid and True Storms)
- Click back arrow from plugins tab to sort the plugins correctly
  
## **Known Issues**
- Weapon and armor balance will need more work, your feedback is welcome!  Any number can be edited easily
- DLC weapon and armor replacer need more work, for the first release I focused on vanilla contents  
- Given the huge change to the entire leveled list, if you notice bugs or crashes, please let me know on Discord and I will patch it
