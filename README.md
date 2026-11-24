# ASFIX SMP Java Resource Pack — v106.50

[Download the Minecraft 26.2 pack](AsfixSMP-Java-ResourcePack-26.2-v106.50.zip)

## Tools

The pack contains 13 custom ItemsAdder tools: three evolving miner pickaxes, four profession tools, three swords, and three axes. The models now use Minecraft's native minecraft:item/handheld and generated-layer pipeline, with the same orientation and held pose as a vanilla diamond pickaxe. This removes the previous noisy micro-cube meshes and uses the transparent, detailed tool artwork already included in the pack. The generated item layer supplies Minecraft's standard pixel-edge extrusion.

| Set | Count |
| --- | ---: |
| Miner pickaxes | 3 |
| Profession tools | 4 |
| Swords | 3 |
| Axes | 3 |
| **Total** | **13** |

The ItemsAdder item definitions still reference the same model IDs. This release does not change item IDs, names, abilities, progression, or HUD layout.

## HUD

The natural ASFIX BetterHud design from v106.49 remains included in this pack: wood, iron, bronze and turquoise-gem panels, custom Oxanium and Silkscreen fonts, unique icons, and player-head display. The matching BetterHud configuration patch is [BetterHud v106.49](BetterHud-v106.49-release.zip).

## Verification

- Resource-pack format 88.0 for Minecraft 26.2.
- 13 tool models use minecraft:item/handheld and the vanilla generated-layer pipeline.
- Every model's texture reference resolves; all 13 item definitions still point to the intended model.
- The archive has 2,676 entries and no duplicate paths.
- Archive size: 16,274,542 bytes.
- SHA-1: 947239F85C1334613BF09C55AE7A03A00CAF06FB.
- SHA-256: F679A6F7AE381B06004834E57350639FFC9B043839B9FB732E8DB48DC5CCA78F.

Archive validation is structural. The actual Minecraft 26.2 client render is being checked with this exact release.
