# ASFIX SMP Java Resource Pack — v106.76

Minecraft Java 26.2 pack, including the ASFIX natural-material HUD and tools plus nine realistic, volumetric crate models for AsyCrates.

[Download the resource pack](AsfixSMP-Java-ResourcePack-26.2-v106.76-AsyCrates-Realistic3D.zip)

## Crates

The pack maps nine unique crate models to note-block states for use with AsyCrates 1.1.4 and the ASFIX crate bridge:

- `cosmic_common`, `cosmic_rare`, `cosmic_epic`
- `cosmic_legendary`, `cosmic_mythic`
- `astral_royal`, `grim_reaper`, `nightshade`, `christmas_dreams`

The models use Minecraft cuboid geometry with visible depth, natural wood and metal colors, and distinct trims and gems. Each crate uses 44–54 cuboids (443 total). All 18 powered/unpowered note-block state mappings are present. The pack archive contains 2,728 files and its model texture references resolve.

The local Paper 26.2 build 135 smoke check loaded AsyCrates 1.1.4 and AsfixCrateBridge, listed all nine crate IDs, and confirmed their locations were unset. No crate locations or structures are included in this release; place each crate in game yourself. The two existing `cosmic_common` virtual keys were preserved during migration.

## Tools and HUD

The existing 13 volumetric tool models and ASFIX BetterHud assets are retained from v106.75. The tool models use vanilla handheld item definitions and natural-material textures. The HUD includes the ASFIX theme and custom font assets.

## Verification limits

The plugin startup/configuration and pack structure were checked locally. A Minecraft client render and live-server deployment were not performed, so in-game visual rendering still needs confirmation after the pack and plugins are installed on the server.

## Release data

- SHA-1: `4C9867702BF6DCE06C60B2497C2E2F7B00E96480`
- Archive size: 19,738,909 bytes
- Release metadata: [`release-v106.76.json`](release-v106.76.json)
