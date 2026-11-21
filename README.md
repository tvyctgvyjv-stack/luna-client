# Luna Client

**Luna Client** is a client-side [Fabric](https://fabricmc.net/) mod for **Minecraft: Java Edition** that adds cosmetics and emotes,
made to stay light on FPS. Everything in it (models, textures, sounds, music) is original work made for the project.

> Luna Client is an independent fan project. It is not an official Minecraft product and is not approved by or associated with
> Mojang or Microsoft.

![Phoenix set: crown, wings and aura](images/phoenix-set.png)

## Features

- **Cosmetics**: capes, wings, crowns, halos and auras, in themed sets (Phoenix, Forest, Storm, Moon…), all rendered in real 3D.
- **Emotes**: a radial emote wheel with animated emotes, some with their own props and music (for example a pickup truck you sit on).
- **Locker**: a wardrobe screen to try on outfits with a live 3D preview before equipping them.
- **Performance first**: cosmetics are drawn with no per-frame allocations and are measured for their FPS cost before release.
- **Client-side only**: no server plugin needed, works in singleplayer and multiplayer.

![Storm set](images/storm-set.png)

![Pickup truck emote model](images/big-truck-emote.png)

## Versions

| Minecraft | Status |
|---|---|
| 26.3 | Main version |
| 1.21.11 | Beta |

Requires the Fabric Loader and Fabric API.

## Luna Launcher (in development)

**Luna Launcher** is a desktop launcher for Luna Client (Windows). It lets players manage instances (Fabric 26.3 or 1.21.11), browse
Fabric mods, resource packs and shaders from Modrinth, and manage their skins.

- Players sign in with **their own Microsoft account**. The launcher checks that the account owns Minecraft: Java Edition before
  starting the game.
- **There is no offline or cracked mode.** The game is never launched without a valid sign-in and ownership check.
- Sign-in tokens stay on the player's computer (Windows Credential Manager) and are never sent to any Luna server.
- No password is ever seen or stored by the launcher: sign-in happens on Microsoft's own page.

## Status

Both the mod and the launcher are in active development. Releases will be linked here when they are available.
