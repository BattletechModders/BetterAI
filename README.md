# BetterAI - AI Behavior Variable Tweaks for HBS BATTLETECH
This is a ModTek mod to improve the tactical AI in combat.  The biggest improvement allows the AI to reserve 'Mechs.  I've also removed the lowered critical hit chance for the AI team and put it on par with the player's default values.  It also considers protecting their weakened side and exploiting the damaged sides of the enemy to a greater degree.  While there are still some poor tactical choices baked in to the AI, this should be much harder to fight than stock.  

Better AI shouldn't cause any errors with save files, even saves in combat, or with version updates.  I've done extensive testing back and forth between stock and modded play without any errors.  It does not add any new items to the VersionManifest.csv.

### Full change log can be found here:

https://forum.paradoxplaza.com/forum/index.php?threads/mod-release-better-ai-tweaks-for-deadlier-ai.1075322/

### Googledoc sheets with all stock + modded variables, unit_role and unit_lance tags:

https://docs.google.com/spreadsheets/d/1Q-Z0jSjb1rRd5-r0zYHwH_yES8cgVdmv-kE2WS_7lHE/edit#gid=0&range=A1

### Recommended Companion Mods

https://github.com/BattletechModders/cFixes - Commuinity bug fixes, Better AI integrates some of the 'Mech tag fixes found in cFixes, but not all.  These may help the game better categorize units for Lance selection.

### ModTek/BTML
This mod needs ModTek and BTML to work, links below:

https://github.com/BattletechModders/ModTek/releases

https://github.com/BattletechModders/BattleTechModLoader/releases


## Stock Files edited by this mod:
#### StreamingAssets\data\behaviorVariables - AI variable edits
global.json

global_def.json

global_sensorlock.json

role_lastmanstanding.json

role_meleeonly.json

role_scout.json

role_sniper.json

role_vehicle.json

role_vehicle_def.json


#### StreamingAssets\data\constants - AI Crit Chance and Dynamic Role Maximums
CombatGameConstants.json


#### StreamingAssets\data\mech - Adjusting 'Mech roles to match stock load-outs to appropriate role
mechdef_awesome_AWS-8Q.json

mechdef_enforcer_ENF-4R.json

mechdef_locust_LCT-1M.json

mechdef_quickdraw_QKD-4G.json

mechdef_quickdraw_QKD-5A.json

mechdef_shadowhawk_SHD-2D.json

mechdef_urbanmech_UM-R60.json

mechdef_zeus_ZEU-6S.json
