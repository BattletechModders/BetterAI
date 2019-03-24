# BetterAI - AI Behavior Variable Tweaks for HBS BATTLETECH
This is a ModTek mod to improve the tactical AI in combat.  The biggest improvement allows the AI to reserve 'Mechs.  The AI's critical hit chance is also raised to the same level as the player.  It also considers protecting their weakened side and exploiting the damaged sides of the enemy to a greater degree.  There are some poor tactical choices baked in to the AI, this should still be much harder to fight than stock.  

Better AI shouldn't cause any errors with save files, even saves in combat, or with version updates.  I've done extensive testing back and forth between stock and modded play without any errors.  It does not add any new items to the VersionManifest.csv.

### Instructions:

    Copy Better AI folder in to Mods folder created for ModTek.  Remove older Better AI folder if present.

### Full change log can be found here:

https://forum.paradoxplaza.com/forum/index.php?threads/mod-release-better-ai-tweaks-for-deadlier-ai.1075322/

### Googledoc sheets with all stock + modded variables, unit_role and unit_lance tags:

https://docs.google.com/spreadsheets/d/1Q-Z0jSjb1rRd5-r0zYHwH_yES8cgVdmv-kE2WS_7lHE/edit#gid=0&range=A1

### Recommended Companion Mods

https://github.com/BattletechModders/cFixes/releases - Commuinity bug fixes, Better AI integrates some of the 'Mech tag fixes found in cFixes, but not all.  These may help the game better categorize units for Lance selection.

#####  NOTE - Better AI has cFixes set as an Optional Dependency.  It will automatically load after cFixes changes.  Better AI does not need cFixes to work.

### ModTek
This mod needs ModTek to work:

https://github.com/BattletechModders/ModTek/releases

## Stock Files Edited:
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

#### StreamingAssets\data\constants - AI Crit Chance
    CombatGameConstants.json

#### StreamingAssets\data\lance - LanceDef Pilot Optimizations (WIP)
    All Dynamic Lances difficulty 3 - 10

#### StreamingAssets\data\mech - Role Tag Replacement
    mechdef_awesome_AWS-8Q.json
    mechdef_enforcer_ENF-4R.json
    mechdef_locust_LCT-1M.json
    mechdef_quickdraw_QKD-4G.json
    mechdef_quickdraw_QKD-5A.json
    mechdef_shadowhawk_SHD-2D.json
    mechdef_urbanmech_UM-R60.json
    mechdef_zeus_ZEU-6S.json
