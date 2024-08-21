VehicleAlarms Looting and Damaging
A22/Stable1.0 - Version 1.00
Description and Updates


⚡______________________________________________________________________________________________________________________⚡
README TABLE OF CONTENTS
1. About Author
2. Mod Philosophy
3. Features
4. Updates
 - Bugs
5. Wish List

⚡_____________________________________________________________________________________________________________________⚡
1.  ABOUT AUTHOR
	-Name - DarkAoRaidenX
	-Started playing 7d2d during Alpha 18
	-Started attempting to mod in Alpha 19
	-First published a mod during Alpha 19
	-Where to find:
		Discord Name - DarkAoRaidenX
		Discord (Streaming) - https://discord.gg/UccyzVm5Xq.
		https://github.com/DarkAoRaidenX/7-days-to-die-mods
		https://darkaoraidenx.github.io/
		https://7daystodiemods.com/
		https://www.nexusmods.com/users/96342523?tab=user+files
		https://www.twitch.tv/DarkAoRaidenX

		
⚡______________________________________________________________________________________________________________________⚡
2.  MOD PHILOSOPHY (Taken from AuroraGiggleFairy - My Favorite HUD mod maker.)
	-Singleplayer AND/OR Server-Side! (If I can help it!)
	-Goal: Enhance Vanilla Gameplay!
	-Feedback and Testing is Beneficial!
	-Detailed Notes for Individual Preference and Mod Learning!
	
	"The best mods rely on community involvement."
	
	
⚡______________________________________________________________________________________________________________________⚡
3.  Features
	*If you run into any conflicts or need help, you may contact Me via Discord: DarkAoRaidenX or https://discord.gg/UccyzVm5Xq 


This mod adds alarms to vehicles. There is 2 versions One with just the alarm going off if you loot and another which adds an alarm when you damage a vehicle.
Be warn Wrenching a vehicle can set it off and depending how often spawns are it can be frequently. 

It has a random chance to go off every time you try to Loot/Open an vehicle. The sound can heat up the map which then will spawn a Screamer.

Alarm Chances
Config>buffs.xml the Value Number/Number is in Percentage
<requirement name="RandomRoll" seed_type="Random" min_max="0,100" operation="LTE" value="25"/>

Alarm Duration
Config>gameevents.xml the Value Number/Number is in Seconds
<action_sequence name="alarm_sound">
<property name="loop_duration" value="6" />

Spawn Chances
Config>gameevents.xml the Value Number/Number is in Percentage
<requirement class="RandomRoll">
<property name="value" value="30" />

Spawn Numbers
Config>gameevents.xml the Value Number
<action class="SpawnEntity">
<property name="spawn_count" value="4" />


⚡______________________________________________________________________________________________________________________⚡
4. Updates
Stable 1.0
- Fixed alarm sound. 


⚡______________________________________________________________________________________________________________________⚡
5.  Wish List
Make the alarm attract zombies!
