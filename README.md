# Cope

Cope is a desktop app for Windows, built with C# and Avalonia. It has chat, friends, groups and profiles, plus a built-in launcher for **Minecraft: Java Edition**.

## Minecraft launcher

- **Microsoft sign-in.** Players sign in with their own Microsoft account using the device code flow (XboxLive.signin offline_access). Cope then signs in to Xbox Live and Minecraft to get the player's profile. Only accounts that own Java Edition can play. There is no offline or cracked mode.
- **Instances.** Each instance has its own version, mod loader, mods and worlds.
- **Mod loaders.** Vanilla, Fabric, Quilt, Forge and NeoForge.
- **Mods.** Search and install mods from Modrinth, including the mods they need.
- **Official files only.** The game, libraries, assets and Java come from Mojang's own servers.

## Privacy

Sign-in tokens are stored only on the user's own computer, in `%APPDATA%\Cope`. Cope doesn't send them anywhere except Microsoft, Xbox and Minecraft's own sign-in servers.

## Status

Personal project, in active development.
