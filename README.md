# ASFIX SMP Java Resource Pack — v106.52

[Download the Minecraft Java 26.2 pack](AsfixSMP-Java-ResourcePack-26.2-v106.52-realistic-voxel-tools.zip)

## Tool models

This release replaces the previous angled painted tool cutouts with 13 upright, voxel-faceted sprites designed around vanilla Minecraft handheld silhouettes and natural materials:

- 3 evolving miner pickaxes
- 4 profession tools
- 3 swords
- 3 axes

The heads and hilts are aligned for a vanilla-like in-hand pose. Iron, steel, bronze, wood grain, leather wraps, rivets and restrained gems give each item its own readable silhouette. Every 256×256 RGBA texture is unique and transparent. The item models use Minecraft's native minecraft:item/handheld parent, which produces the same generated-item depth behavior as the vanilla diamond pickaxe. Item IDs, abilities and item-definition links are unchanged.

The matching versioned textures and model definitions are synchronized into the ItemsAdder source tree at plugins/ItemsAdder/contents/asfix_base/resourcepack/assets/asfix/.

## Custom HUD

The pack retains the ASFIX BetterHud assets and configuration: natural dark wood and iron frames, framed hotbar panels, player head, rank/job/coordinates, health/armor/food, currency, job XP, unique icons, and Oxanium/Silkscreen fonts. The matching settings and source assets are in plugins/BetterHud.

## Verification

- Target: Minecraft Java 26.2; resource format 88.0.
- All 13 model files use minecraft:item/handheld and resolve to 13 distinct v106.52 textures.
- All 13 PNGs are 256×256 RGBA with transparent corners.
- ZIP contains 2,702 entries and no duplicate paths.
- Archive size: 21987163 bytes.
- SHA-1: $sha1.
- SHA-256: $sha256.

These checks confirm archive structure and references. Rendering in an actual Minecraft 26.2 client still requires loading this exact v106.52 archive; the previously observed live server was still serving v106.48.