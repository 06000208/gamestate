# gamestate

Game server monitoring & management from node, available as an NPM package

Planned features:

- Monitoring for any game supported by [gamedig](https://www.npmjs.com/package/gamedig)
- Allows for communication between existing game server architecture with node.js
- Direct shell output & process wrapping

## Bridge Support

| Game | Architecture | Gamestate<br> Implementation | Notes |
| --- | --- | --- | --- |
| Unturned | [OpenMod](https://github.com/openmod/openmod) | [gamestate-openmod](https://github.com/06000208/gamestate-openmod) | [Docs](https://openmod.github.io/openmod-docs/) |
| Unturned | [LDM / Rocketmod](https://github.com/SmartlyDressedGames/Legally-Distinct-Missile) | [gamestate-ldm](https://github.com/06000208/gamestate-ldm) | [Docs](https://ldm-community.github.io/docs/) |
| Garry's Mod | [Lua API](https://wiki.facepunch.com/gmod) | [gamestate-gmod](https://github.com/06000208/gamestate-gmod) |  |
| [Team Fortress 2,<br> CSS, CSGO, L4D2,<br> etc.](<https://wiki.alliedmods.net/Required_Versions_(SourceMod)>) | [Sourcemod](https://www.sourcemod.net/) | Not Done |  |
| Minecraft | [Spigot](https://www.spigotmc.org/), [Paper](https://papermc.io/), etc. | Not done |  |
| Minecraft | [Fabric](https://fabricmc.net/), [Quilt](https://quiltmc.org) | Not done |  |
| Minecraft | [Forge](https://files.minecraftforge.net) | Not done |  |
| Terraria | [tModLoader](https://www.tmodloader.net/) | Not done |  |
| Terraria | [TShock](https://github.com/Pryaxis/TShock) | Not done |  |

<!-- | Starbound? |  |  |  | -->
<!-- | Rust? |  |  |  | -->
<!-- | Don't Starve Together? |  |  |  | -->

## Wrapper Support

Not implemented
