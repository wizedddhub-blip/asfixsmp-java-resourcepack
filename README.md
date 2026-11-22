# ASFIX SMP — pack de ressources Java

## Version 106.19 · Minecraft Java 26.2

Pack ASFIX pour ItemsAdder et BetterHud. La direction visuelle garde des matières naturelles — bois, pierre, métal, bronze, jade et gemmes — pour les blocs personnalisés, les caisses et le HUD. L’audit trouve zéro pixel violet dans les 34 textures de blocs personnalisés et les cinq icônes de caisse. Les icônes de rang et certains objets cosmiques gardent leurs couleurs d’identité.

- Format Minecraft 26.2 : `pack.mcmeta` 88.0.
- **34 modèles 3D volumétriques** : 5 caisses, 6 armes, 3 pioches évolutives, 4 outils de métier et 16 pièces d’armure d’inventaire.
- **1 380 cuboïdes**, dont 118 éléments orientés, sur 34 géométries source. Aucun élément du modèle suivi n’est un plan plat.
- Contrôle des modèles : 8 280 faces avec textures résolues; zéro texture ou alias manquant.
- 20 matériaux de caisse, 9 textures de minerais, 49 textures d’armes/outils et 56 textures d’armure.
- Les cinq icônes d’inventaire des caisses sont distinctes. Les textures des blocs personnalisés et des caisses utilisent une palette naturelle.
- **HUD BetterHud ASFIX** : tête dynamique, grade, nom, métier, coordonnées, niveau, barre d’XP du métier, santé, armure, faim et solde. Cadres en bois et bronze, accents jade et icônes dédiées, avec une mise en page lisible inspirée des HUD de serveur.

### Aperçus

- [Galerie interactive des modèles (115 cartes)](preview/apercu-tous-modeles-asfix-v106.19.html)
- [Planche des 34 géométries 3D — PNG](preview/asfix-v106.19-geometry-preview.png)
- [Planche des 34 géométries 3D — SVG](preview/asfix-v106.19-geometry-preview.svg)
- [HUD naturel ASFIX — maquette](preview/asfix-hud-natural-v106.19.png)
- [Icônes de caisses — maquette](preview/asfix-natural-crate-icons-v106.19.png)

Les planches 3D et le HUD sont des aperçus construits depuis les sources, pas des captures du client Minecraft. Les 16 modèles d’armure sont des objets d’inventaire; l’armure portée utilise les couches de personnage Minecraft.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.19-NATURAL-3D-MODELS-CUSTOM-HUD.zip`
- Taille : 14 292 107 octets.
- SHA-1 : `9C0755A4DDBAE7D408178FF9C0FBE054E268CC0B`
- SHA-256 : `6D710B52AFC9CE3357328509CD27454120E9BDDE66978B004D69DBA5ACAD67C7`
- 2 486 chemins d’archive uniques; aucun chemin ZIP en double.
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.19-NATURAL-3D-MODELS-CUSTOM-HUD.zip>

### Vérifications

La vérification d’archive confirme la version de pack, les modèles 3D, les textures résolues, l’unicité des cinq icônes de caisse et l’absence de violet dans les textures de blocs personnalisés et de caisses. Un smoke test isolé Paper 26.2 / Java 25 a chargé BetterHud 2.2.0-SNAPSHOT-449 et AsfixHudBridge 1.0.2, puis généré `build.zip` avec 615 ressources BetterHud intégrées au pack.

Le chargement côté serveur/plugin est vérifié. L’apparence finale des modèles et du HUD n’a pas été confirmée par une capture d’un client Minecraft.