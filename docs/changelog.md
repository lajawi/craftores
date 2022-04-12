# Changelog
Welcome to the changelog. Here you will find all versions of CraftOres documented, together with all the changes made in each version. Even if newer versions of CraftOres are released, the changelog of older versions may get updated if any changes were forgotten, spelling mistakes were made etc.

- [Changelog](#changelog)
  - [CraftOres V1.0.0 - Release](#craftores-v100---release)
  - [CraftOres V1.0.1 - More Folders](#craftores-v101---more-folders)
  - [CraftOres V1.0.2 - Documentation](#craftores-v102---documentation)
  - [CraftOres V1.0.3 - Documentation Raw Metals](#craftores-v103---documentation-raw-metals)
  - [CraftOres V1.1.0 - Coral Update](#craftores-v110---coral-update)
  - [CraftOres V1.1.1 - Spelling Correction](#craftores-v111---spelling-correction)

---
## CraftOres V1.0.0 - Release

---
### Additions<!-- omit in toc -->
- Crafting recipes for all ore blocks including
    - Coal ore
    - Deepslate coal ore
    - Diamond ore
    - Deepslate diamond ore
    - Emerald ore
    - Deepslate emerald ore
    - Iron ore
    - Deepslate iron ore
    - Copper ore
    - Deepslate copper ore
    - Gold ore
    - Deepslate gold ore
    - Nether gold ore
    - Lapis lazuli ore
    - Deepslate lapis lazuli ore
    - Redstone ore
    - Deepslate redstone ore
- Crafting recipes for raw metals including
    - Raw copper
    - Raw gold
    - Raw iron
- [`pack.mcmeta`](../pack.mcmeta), stating datapack version and description
- [`README.md`](./README.md)

---
## CraftOres V1.0.1 - More Folders

---
### Additions<!-- omit in toc -->
- [`LICENSE.md`](./LICENSE.md). Check out the license.
### Changes<!-- omit in toc -->
- Changed folderstructure
    - Now all docs not related to Minecraft will be stored in [documents](../docs/), currently including:
        - [`README.md`](./README.md)
        - [`LICENSE.md`](./LICENSE.md)
        - [`changelog.md`](./changelog.md)
### Updated<!-- omit in toc -->
- [`changelog.md`](./changelog.md)

---
## CraftOres V1.0.2 - Documentation

---
### Additions<!-- omit in toc -->
- [Documentation images](images/)
- [Data pack image](../pack.png)
### Changes<!-- omit in toc -->
- [`README.md`](README.md) now has a more detailed documentation about the software
  - [How to craft](README.md#how-to-craft)
  - [Install](README.md#install)
  - [Issues and ideas](README.md#issues-and-ideas)
- [`LICENSE.md`](LICENSE.md).
  - Simplefied: Reussing parts of the software in your own is granted, *as long as you give proper credit where credit is due.* For further information read [`LICENSE.md`](LICENSE.md)
### Updated<!-- omit in toc -->
- [`changelog.md`](changelog.md)

---
## CraftOres V1.0.3 - Documentation Raw Metals

---
### Additions<!-- omit in toc -->
- More [documentation images](images/) for the raw metals
### Changes<!-- omit in toc -->
- [`README.md`](README.md) now has documentation for the recipes for the [raw](README.md#raw-ingots) metals
### Updated<!-- omit in toc -->
- [`changelog.md`](changelog.md)

---
## CraftOres V1.1.0 - Coral Update

---
### Additions<!-- omit in toc -->
- [`credits.txt`](CREDITS.txt) stating all third parties involved. Can be found in [`README.md#Credits`](README.md#Credits) as well
- [`howtocraft.md`](howtocraft.md) now has all the crafting recipes, instead of [`README.md`](README.md) to prevent cluttering
- Added [advancements](../data/craftores/advancements/), you unlock recipes by getting required items
- Recipes to craft coral blocks, dead and alive, using their respective corals and coral fans, including [advancements](../data/craftcorals/advancements/), in a separate namespace called [`craftcorals`](../data/craftcorals/). Heavily inspired by [VanillaTweaks](https://vanillatweaks.net/ "Vanilla Tweaks")
  - Coral block recipes are documented in [`howtocraft.md`](howtocraft.md)
- Added a recipe to *uncraft* amethyst blocks into shards again
  - Recipe documented in [`howtocraft.md`](howtocraft.md)
### Changes<!-- omit in toc -->
- Removed crafting recipes from [`README.md`](README.md) to prevent cluttering. Visit [`howtocraft.md`](howtocraft.md) to get a full documentation of all recipes
- Changed the hierarchy of the [`README.md`](README.md) file
- Namespace renamed from `minecraft` to `craftores` to represent the pack better, and to prevent conflicts between CraftOres and other packs
- Changed coal ore recipes to use [tags](../data/craftores/tags/)
- Removed the `"count"` in most recipes, as it defaults to one without
- Changed folder structure in [`images`](images/)
### Updated<!-- omit in toc -->
- [`changelog.md`](changelog.md)
  - Added new version
  - Added titles to older versions briefly describing what the updates were
- Updated [`howtocraft.md`](howtocraft.md) and [`README.md`](README.md) to account for the new folder structure in [`images`](images/)

---
## CraftOres V1.1.1 - Spelling Correction

---
### Changes<!-- omit in toc -->
- Changed the name from `/images\amythyst_shard.png` to [`/images\crafting_amethyst_shard.png`](images/crafting_amethyst_shard.png)
  - Changed the links to above file in [`howtocraft.md#amethyst-shards`](howtocraft.md#amethyst-shardshttpsminecraftfandomcomwikiamethystshard-"amethyst-shard") accordingly
- Excluded the title from [`howtocraft.md`](howtocraft.md) from the table of contents
### Updated<!-- omit in toc -->
- [`changelog.md`](changelog.md)
  - Excluded all heading level 3 from the table of contents