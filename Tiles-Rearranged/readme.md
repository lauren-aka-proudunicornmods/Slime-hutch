# [CP] Tilesheets Rearranged Readme

This is the [v2.0-alpha](https://github.com/lauren-aka-proudunicornmods/Tilesheets-Rearranged/blob/main/Changelogs.md#v20-alpha) update which I have not published yet. I have not finished adding the recolours.

## Installation

Drag `[CP] Tilesheets Rearranged` into your mods folder.

The mod will automatically determine which recolours you have (if any) and apply those tilesheets.

## What it does

This mod takes the two Vanilla tilesheets and loads them into the game as **four new tilesheets** that **can be used in any custom map**. It also ***checks if there are recolours*** installed, and then loads the matching files.

The **forever spring** tilesheets are loaded so that you will *always* get the tilesheet for spring, regardless of the in-game season.

The **seasons indoors** tilesheets are the same, but seasonal. So, if it's fall outdoors, the fall tilesheet will be loaded.

The two vanilla tilesheets that are used are:

- *Spring_outdoorstilesheet*
- *Spring_outdoorstilesheet2*

You can see how these tilesheets correspond to each other in the table below.

| Vanilla  | Tilesheets Rearranged | |
|---|---|---|
|   | **Fixed as Spring** | **Seasonal** |
|Spring_outdoorstilesheet.png | z_foreverspring.png | z_seasonsindoors.png |
|Spring_outdoorstilesheet2.png | z_foreverspring2.png | z_seasonsindoors2.png |
||||

## How you can use it in your mod

You have my permission to target the tilesheets above in your mods, whether or not they are published.

### Example

Let's say you want to use `spring_outdoorstilesheet.png` in your custom `farmhouse.tbin/tmx` to make a seasonal backdrop. 

1. Rename `spring_outdoorstilesheet.png` to **the tilesheet you want**

        e.g. `z_seasonsindoors.png`

2. Put the renamed tilesheet into your **editing folder** and load it into your map as you would a vanilla tilesheet.

3. Make your map

4. Compile your mod but **don't** put the tilesheet in your assets folder. It should load in the same way as a vanilla tilesheet.

5. Put this mod as a dependency in your manifest, making sure to set the requirement as *true*:

```

  "Dependencies": [
    {
      "UniqueID": "proudunicorn.tilesheetsrearranged",
      "IsRequired": true
    },
  ],
```
That's it!

## Note

I have included the renamed vanilla tilesheets [here](https://github.com/lauren-aka-proudunicornmods/Tilesheets-Rearranged/tree/main/reference-tilesheets) for reference and ease of use.

## Permissions

You can target this freely as explained above without permission. Feel free to download and experiment!

If you want to work on it and expand it you can also do that without asking, but please update the manifest to reflect your contributions/authorship.

You **don't** have permission to **upload** this mod on any other sites without asking me first. If you want to upload it on another site and manage that upload, please ask. I will probably say yes if you ask!
