# ASFIX SMP Java Resource Pack — v106.63

[Download the Minecraft Java 26.2 pack](AsfixSMP-Java-ResourcePack-26.2-v106.63-true-3d-tools.zip)

![Volumetric preview of the 13 ASFIX tools](preview/v106.63-3d-tool-gallery.png)

![ASFIX wood, bronze and jade HUD frame](preview/v106.60-hud-bois-bronze-jade.png)

The tool gallery is projected from the actual Minecraft model cuboids and their material textures. The geometry uses the native Minecraft handheld item-model format: the tools have depth and separate 3D parts, while retaining the block-built style of vanilla items.

## Tools

The pack contains 13 models: three Miner pickaxes, four job tools, three axes and three swords. The tool models use 684 cuboids total, with 13 different geometry shapes and 13 natural material textures. The pick heads use thinner forged profiles, angled wings, sharpened rails and distinct central fittings. Shafts, grip wraps, collars, guards, blade/head parts and gems are modeled as separate cuboids.

Materials use natural oak and walnut, leather, forged iron, cold steel, dark iron, brass, aged bronze, amber, azurite, emerald, ruby and amethyst. Custom model rotations use Minecraft-supported 22.5 degree steps. No flat sprite is being treated as a 3D tool.

## HUD

The combined pack includes five BetterHud configuration files and the ASFIX theme assets. The theme uses dark wood, bronze fittings and jade accents, with player head, role, job, coordinates, health, armor, food, balance and job XP panels. It includes Oxanium SemiBold and Silkscreen fonts. BetterHud disables the custom HUD for Bedrock clients.

The pack contents and configuration files are present in the release archive. Live BetterHud rendering with the server plugin was not verified in this build.

## Release checks

- Target: Minecraft Java 26.2, resource format 88.0.
- Archive contains 2,712 ZIP entries, with no duplicate paths.
- 13 models and 684 cuboids; 13 distinct shapes.
- 13 new 64×64 tool textures, all referenced by the models; no v106.61 tool textures remain.
- Five BetterHud configuration files are present.
- Archive size: 17,961,612 bytes.
- SHA-1: `33F0B7D9D7E854EC68809E0E9D718FA7D35E8732`.
- SHA-256: `C7F05CE2D88203A9BBE2553F5081DDA6F8AD9548141DCFE460DA1EF915676C79`.

Automated validation checked each model's geometry bounds, face UVs, texture bindings, custom rotations and rotated bounds. The v106.62 pickaxe was loaded in a local Minecraft 26.2 client and showed visible 3D depth. The updated v106.63 models passed pack validation; an in-client render check of this exact v106.63 archive is still pending.