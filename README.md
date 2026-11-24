# ASFIX SMP Java Resource Pack — v106.49

[Download the Minecraft 26.2 pack](AsfixSMP-Java-ResourcePack-26.2-v106.49.zip) · [View all 13 tools in 3D](preview/v106.49-tools-gui.png) · [View the pickaxes in the vanilla hand pose](preview/v106.49-pickaxes-held.png)

## Tools

The pack includes 13 ItemsAdder handheld models: three evolving miner pickaxes, four job tools, three swords, and three axes. Their item transforms use Minecraft's vanilla `item/handheld` pose. Each model has a 192×192 volumetric silhouette mesh, individual front and darkened reverse textures at 768×768, and forged depth tiers from 1.0 to 2.2 model units. Steel, wood, leather, bronze, and gem details use distinct textures and side palettes.

| Tool | Cuboids |
| --- | ---: |
| Miner pickaxe I | 1,666 |
| Miner pickaxe II | 1,403 |
| Miner pickaxe III | 1,704 |
| Miner job tool | 1,512 |
| Farmer job tool | 1,307 |
| Woodcutter job tool | 1,850 |
| Hunter job tool | 1,720 |
| Astral sword | 1,605 |
| Infernal sword | 1,691 |
| Nebula sword | 1,811 |
| Astral axe | 1,645 |
| Infernal axe | 1,835 |
| Nebula axe | 1,900 |
| **Total** | **21,649** |

The artwork is mapped to the front and rear surfaces, while the mesh adds the actual silhouette depth and separately shaded side faces. This keeps each object in the familiar Minecraft held-item shape while giving the head, grip, fittings, wraps, and gemstones physical thickness.

## HUD

The archive includes the ASFIX BetterHud resources for Minecraft 26.2: 48 natural wood, iron, bronze, and turquoise-gem tiles, seven unique HUD icons, custom Oxanium and Silkscreen fonts, and the player-head element. The HUD layout keeps its existing image names and coordinates, so the new art fits the configured panels. No plugin JAR is included in this resource pack.

For servers that already have BetterHud installed, [download the v106.49 BetterHud config and asset patch](BetterHud-v106.49-release.zip). It contains the matching HUD configs, image definitions, fonts, heads, layouts, and 75 files from the central BetterHud directory; it does not include the plugin JAR or server-specific runtime data.

## Verification

- Resource-pack format `88.0` for Minecraft 26.2.
- All 13 ItemsAdder definitions resolve to their models; every model uses `minecraft:item/handheld`.
- All 129,894 model faces have six valid sides, known textures, and valid UVs.
- All 13 front textures are unique; front and rear tool textures are 768×768.
- 48 BetterHud tiles are present at 256×228 each.
- 2,676 ZIP entries; no duplicate paths.
- Archive size: 17,572,962 bytes.
- SHA-1: `697BD00989369EA711F5FB3909186B23822C826F`.
- SHA-256: `A5835097C389E85723FDF35BA43BF791EDCF401BBFF1D8CACC02117B4DE2C0D5`.

The included gallery is an offline projection of the actual model JSON and textures, not an in-client screenshot. Model references, geometry bounds, UVs, and archive contents pass validation; the final Minecraft-client rendering still requires an in-game check with this exact pack loaded.
