# ASFIX SMP Java Resource Pack — v106.51

[Download the Minecraft Java 26.2 pack](AsfixSMP-Java-ResourcePack-26.2-v106.51-realistic-tools.zip)

## Tool models

This release refreshes all 13 custom tools with distinct, high-detail material artwork:

- 3 evolving miner pickaxes
- 4 profession tools
- 3 swords
- 3 axes

Each tool has its own 768×768 transparent texture. The item models use Minecraft's native minecraft:item/handheld parent, so their hand pose and standard generated-item extrusion match vanilla tools such as the diamond pickaxe. Item IDs and abilities are unchanged. The same 13 model definitions and versioned textures are also synchronized into the local ItemsAdder source tree.

## Custom HUD

The pack retains the natural-material ASFIX BetterHud design: framed HUD and hotbar panels, player head, rank/job/coordinates, health/armor/food, currency, job XP, unique icons, and Oxanium/Silkscreen fonts. The matching BetterHud settings and source assets are in the central server folder under plugins/BetterHud.

## Verification

- Target: Minecraft Java 26.2; resource format 88.0.
- All 13 model files use minecraft:item/handheld and reference a unique v106.51 texture.
- All 13 textures are present in the pack and in the ItemsAdder source.
- Archive: 2,689 entries, 0 duplicate paths, 21,248,782 bytes.
- SHA-1: 8B8A946DF8D615E179A217365F6BB20194735503.
- SHA-256: F473BEAF893163E6917C9781AAE0DB0F0D526D6648CC997409352B42838FA1CB.

Structural checks are complete. The exact in-game appearance still needs to be confirmed in a Minecraft 26.2 client after that client loads this v106.51 archive.
