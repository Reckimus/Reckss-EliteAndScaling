# Reckss-EliteAndScaling
Elites and Mob Scaling
Elite Enemy Mod

Version: 1.3.0

A BepInEx plugin for Erenshor that dynamically promotes nearby enemies to "Elite" status, making them tougher and more interesting.

Features

Automatic Elite Promotion: Periodically selects up to N enemies within a configurable range of the player and promotes them to elites.

Configurable Stats & Scaling: Adjust level offsets, HP, AC, damage, movement speed, and all RPG attributes via a standalone config file.

Consider Mechanic Integration: Press C to query any enemy’s level in front of you.

Exclusions: Easily exclude entire factions (e.g., Player, Villager) or specific scenes (e.g., Main, LoadScene) from mod effects.

Installation

Ensure you have BepInEx installed for your game.

Download Reckss_EliteAndScaling.dll and place it in BepInEx/plugins/.

Launch the game; the plugin will generate EliteEnemyMod.cfg in BepInEx/config/.

Users with Bepinex config manager can edit values directly in game!

Still a few bugs but quite a few fixes 
Update: Added dynamic and Lerp scaling to smooth lower lvl gameplay while still offering a challenge for max levels.
Grouping is highly recommended unless youre fully purple geared. Some elites will remain easy (aka grass spiders) while others will be near god like and are tiered/prepared for upcoming Raid geared players or full purple groups.
Also hooked into the Consider Opponent mechanic so pressing C now also gives you npcs true LVL and HP.
if you use Drizzlx's enemy lvl mod disable the overhead option and you shouldnt get any conflicting lvl information any more.
