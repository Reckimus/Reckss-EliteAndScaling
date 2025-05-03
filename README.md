# Reckss-EliteAndScaling
Elites and Mob Scaling
Elite Enemy Mod

Version: 1.1.3

A BepInEx plugin for Erenshor that dynamically promotes nearby enemies to "Elite" status, making them tougher and more interesting.

Features

Automatic Elite Promotion: Periodically selects up to N enemies within a configurable range of the player and promotes them to elites.

Configurable Stats & Scaling: Adjust level offsets, HP, AC, damage, movement speed, and all RPG attributes via a standalone config file.

Consider Mechanic Integration: Press C to query any enemy’s level in front of you.

Exclusions: Easily exclude entire factions (e.g., Player, Villager) or specific scenes (e.g., Main, LoadScene) from mod effects.

Installation

Ensure you have BepInEx installed for your game.

Download Reckss.ErenshorMods.EliteEnemy.dll and place it in BepInEx/plugins/.

Launch the game; the plugin will generate EliteEnemyMod.cfg in BepInEx/config/.

Configuration

All settings live in BepInEx/config/EliteEnemyMod.cfg. You can also use BepInEx Config Manager to edit on-the-fly.

General

Key

Default

Description

SpawnRange

100.0

Maximum distance (meters) to search for and scale enemies.

SpawnInterval

15.0

Time (seconds) between checking and spawning elites.

MaxElites

2

Maximum number of simultaneous elites allowed.

EliteScaleMultiplier

2.0

Model scale multiplier applied to elites.

ExcludeFactions

Player, Villager

Comma-separated list of factions to ignore when spawning/scaling.

ExcludeScenes

Main, LoadScene

Scenes where the mod remains inactive.

EliteStats

Key

Default

Description

Level_Offset

5

Additional levels added to the player level for elites.

HP_Multiplier

2.5

Multiplier for elite HP.

AC_Multiplier

2.5

Multiplier for elite Armor Class.

Damage_Multiplier

2.5

Multiplier for elite damage values.

MoveSpeed_Multiplier

1.2

Movement speed multiplier for elites.

Str_Multiplier

2.5

Strength attribute multiplier for elites.

Dex_Multiplier

2.5

Dexterity attribute multiplier for elites.

Endurance_Multiplier

2.5

Endurance attribute multiplier for elites.

Int_Multiplier

2.5

Intelligence attribute multiplier for elites.

Wis_Multiplier

2.5

Wisdom attribute multiplier for elites.

Cha_Multiplier

2.5

Charisma attribute multiplier for elites.

