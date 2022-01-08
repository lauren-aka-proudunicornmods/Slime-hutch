# Readme

## Contents

1. [Installation](#Installation)
2. [Using Recolour Mods](#Using Recolour Mods)
3. [For Mod Authors: Making Automatic Recolor Possible](#For Mod Authors)
4. [For Mod Authors: What it Does](#what it does)
5. [Permissions](#permissions)

## Installation

Drag `[CP] Proudunicorns Tiles Rearranged` into your mods folder.

## Using Recolor Mods

Tiles rearranged can't target files in a recolor mod, so to use recolors with this mod, we have to use a [manual workaround](#manual workaround) or the recolor mod author can [patch their mod.](#For Mod Authors)

### Manual Workaround
You will need to add in the files manually to the manual-recolour folder.

You can find this here:
```
[CP] ProudUnicorns Tiles Rearranged\assets\manual-recolour
```

The files you will need to copy in are:
```
Spring_outdoorstilesheet.png
Spring_outdoorstilesheet2.png
Summer_outdoorstilesheet.png
Summer_outdoorstilesheet2.png
Fall_outdoorstilesheet.png
Fall_outdoorstilesheet2.png
Winter_outdoorstilesheet.png
Winter_outdoorstilesheet2.png
```

You should be able to find these in the assets folder of the mod you are using.

### Notes

I'm sorry that I can't patch in all the recolours myself. I figured out that the patches need to be in the recolour mods themselves, and not in this mod. You could also request that the recolor author adds in patches to recolor my mod, or if you are a content patcher pro DIY it!

In previous versions I manually added in some recolour files that I had permission for, however I don't feel totally comfortable doing that as they are not my assets and I can't anticipate all recolours that may come out!

## What it does

This mod takes the two Vanilla tilesheets and loads them into the game as **four new tilesheets** that **can be used in any custom map**.
The **forever spring** tilesheets are loaded so that you will *always* get the tilesheet for spring, regardless of the in-game season.

The **seasons indoors** tilesheets are the same, but seasonal. So, if it's fall outdoors, the fall tilesheet will be loaded.

The two vanilla tilesheets that are used are:

- *Spring_outdoorstilesheet*
- *Spring_outdoorstilesheet2*

You can see how these tilesheets correspond to each other in the table below.

| Vanilla  | Tiles Rearranged | |
|---|---|---|
|   | **Fixed as Spring** | **Seasonal** |
|Spring_outdoorstilesheet.png | z_foreverspring.png | z_seasonsindoors.png |
|Spring_outdoorstilesheet2.png | z_foreverspring2.png | z_seasonsindoors2.png |
||||

## For Mod Authors

How to enable your mod to automatically recolor my tilesheets if a user has this mod installed:

1. Add the patches [here](https://github.com/lauren-mods/StardewMods/blob/main/Tiles-Rearranged/patches.json) to your content.json.
2. Add the (optional) dependency string to ensure your mod is loaded after tiles rearranged.
```
"UniqueID": "proudunicorn.tilesrearranged",
"IsRequired": false
```
You have my full permission to target the tilesheets above in your mods, whether or not they are published :)

## Permissions

You can target this freely as explained above without permission. Feel free to download and experiment!

If you want to work on it and expand it you can also do that without asking, but please update the manifest to reflect your contributions/authorship.

You **don't** have permission to **upload** this mod on any other sites without asking me first. If you want to upload it on another site and manage that upload, please ask. I will probably say yes if you ask!
