# Minecraft Bedrock Economy and Community Add-on

Bedrock Realm Essentials is a Minecraft Bedrock add-on that provides a community menu, set spawn system, spawn teleportation, economy, money sidebar, jobs, rare-item shop, selling system, ranks, kits, kill and death tracking, and an action bar showing player information.

## Install

1. Copy the project folder into your Minecraft Bedrock development behavior packs directory, or package the behavior-pack files as a `.mcpack` file.
2. Import the behavior pack into Minecraft Bedrock.
3. Activate the behavior pack in your world.
4. Enable the Script API or Beta APIs required by your Bedrock version if Minecraft requests them.
5. Optionally import and activate `resources/manifest.json` as a separate resource pack.
6. Give an operator the required admin tag:

```text
/tag <player> add community_admin
```

7. Stand at the desired spawn location and run:

```text
!setspawn
```

Only players with the `community_admin` tag can set the spawn.

## Use

Players can use these chat commands:

```text
!menu
!help
!spawn
```

`!menu` and `!help` open the main community menu. The menu provides access to:

- Teleporting to the saved spawn
- Buying rare items
- Selecting a job
- Selling supported valuables
- Purchasing ranks
- Claiming kits

The economy starts players with $1,000.

The shop sells:

- Diamonds
- Emerald blocks
- Golden apples
- Netherite ingots

The sell system accepts:

- Diamonds
- Emeralds
- Gold ingots

Available jobs:

- Miner: earns money when breaking blocks
- Farmer: can be selected, but has no activity reward implemented
- Hunter: can be selected, but has no activity reward implemented
- Builder: earns money when placing blocks

Available ranks:

- Member
- Hero
- Legend

Available kits:

- Starter Kit
- Miner Kit
- Warrior Kit

Players earn money for player kills, and the add-on tracks kills and deaths. The native scoreboard sidebar displays numeric money. The action bar displays money, username, kills, and deaths.

The add-on uses Minecraft scoreboards for player money and statistics. The saved spawn location is stored as a world dynamic property.

---

More Minecraft mod projects by EnderDevelopment: https://github.com/EnderDevelopment

Project page: https://dash.enderdevelopment.com/community/1d2b7f12-ee6a-40ce-8e92-32527b8e31c7?utm_source=github&utm_medium=readme&utm_campaign=auto_publish&utm_content=1d2b7f12-ee6a-40ce-8e92-32527b8e31c7
