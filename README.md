# What is this mod?
A mod for PC version of Gorilla Tag that shows an info about your current gamestate in Discord.

## What is this fork about
This fork of MonkeRPC is a fork that update's the mod more including adding support for newer maps

## Manual Installation
Be sure that you are already installed BepInEx (using MonkeModManager for example). You need x64 version. [Take it there.](https://github.com/BepInEx/BepInEx/releases)

If your BepInEx copy installed then copy-paste MonkeRPC.dll to your Gorilla Tag/BepInEx/plugins folder somewhere (Gorilla Tag/BepInEx/MonkeRPC/MonkeRPC.dll for example).

Download Discord Game SDK: https://discord.com/developers/docs/game-sdk/sdk-starter-guide

Open discord_game_sdk.zip and follow that path: discord_game_sdk.zip\lib\x86_64. You need to copy discord_game_sdk.dll near the "Gorilla Tag.exe".

## Requirements
Fork of BananaHook: https://github.com/Replay-Tag/BananaHook

## Config

You can found a config at this path: `Gorilla Tag/BepInEx/config/MonkeRPC.cfg`

Just open it and you'll see everything you need.

### Available codenames
```sh
 {nickname} = Your monke name!
 {mapname} = Lobby/Forest/Cave/Canyon/Name of a custom map
 {mode} = Current gamemode in a lobby: Default/Casual/Competitive
 {code} = Room code
 {players} = Players count in a room
 {maxplayers} = Max players possible in a current room (should be 10 but who knows?)
 {roomprivacy} = Public/Private
 {tagged} = Is your gorilla infected/not infected?
 {taggedme} = A person tagged you
 {taggedbyme} = A count of players you're tagged!
```
