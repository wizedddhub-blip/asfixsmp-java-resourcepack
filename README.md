# ASFIX SMP Java Resource Pack — v106.61

[Download the Minecraft Java 26.2 pack](AsfixSMP-Java-ResourcePack-26.2-v106.61-realistic-tools-64-grid.zip)

![Thirteen high-detail volumetric 3D tools](preview/v106.61-realistic-3d-tools.png)

![ASFIX wood, bronze and jade HUD frame](preview/v106.60-hud-bois-bronze-jade.png)

The model sheet is an offline projection of the Minecraft item-model geometry. The HUD image shows the themed frame artwork; BetterHud composes the live text and icons from its configuration.

## Tools

The pack contains 13 volumetric models: three miner pickaxes, four job tools, three axes and three swords. They use 8,215 beveled 3D cuboids across seven depth bands, with a 64-step silhouette grid and a maximum of 967 cuboids in one tool. Each model uses Minecraft's `minecraft:item/handheld` parent and a tuned held pose. The natural wood, leather, steel, copper, jade, ember and gemstone surfaces use 26 separate face and edge textures.

The v106.61 rebuild also fixes the numeric UV values that caused Minecraft 26.2 to reject the previous model files. The release archive drops 135 superseded tool textures; the active ItemsAdder content drops its 26 unreferenced v106.60 tool textures after the model references are updated.

## HUD

The combined pack retains the ASFIX BetterHud theme: dark wood, bronze fittings and jade accents, with the custom panel and hotbar frame, player head, role, job, coordinates, health, armor, food, money and job XP. It uses Oxanium SemiBold and Silkscreen. BetterHud disables this custom HUD for Bedrock clients.

## Release checks

- Minecraft Java 26.2 resource format: 88.0
- ZIP entries: 2,699, with no duplicate paths
- Volumetric tool models: 13, with 8,215 cuboids total and 967 maximum per model
- Unique v106.61 tool face and edge textures: 26
- Total archive images/data: 2,262 PNG and 273 JSON files
- Archive size: 18,153,300 bytes
- SHA-1: `AF53A935D4C436FF74A2461B9E1C9364C9A59149`
- SHA-256: `ADA3DEE820386BBC75B3BE5DFF796567A05EE1121DCA38A5D7D7299F3C74CF4B`

The pack was reloaded in a local Minecraft 26.2 singleplayer world. A custom `diamond_pickaxe` with `minecraft:item_model="asfix:pickaxes/miner_1"` rendered in the native handheld pose with visible depth. The client log contained no model/UV load errors after reload. The BetterHud plugin overlay was not part of that singleplayer render check.
