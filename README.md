# ASFIX SMP — pack de ressources Java

## Version 106.18 · Minecraft Java 26.2

Pack ASFIX unifié pour ItemsAdder et BetterHud. Les blocs, minerais, caisses et équipements utilisent des couleurs naturelles de pierre, bois, métal, végétation et gemmes. Le violet reste un accent d’interface, sans teinte violette généralisée sur les matériaux du monde.

- Format de pack 88.0, ciblé Minecraft Java 26.2.
- **34 modèles d’objets en géométrie 3D volumétrique** : 5 caisses, 6 armes, 3 pioches évolutives, 4 outils de métier et 16 pièces d’armure d’inventaire.
- **1 384 volumes 3D** répartis sur 34 géométries distinctes. Les éléments passent le seuil de 0,2 unité d’épaisseur sur chaque axe; aucun modèle suivi n’est une simple plaque 2D.
- Textures 64×64 détaillées pour les outils, armes et armures; 20 matériaux de caisses uniques; 9 textures de minerais sur roche naturelle.
- **63 icônes ItemsAdder**, **7 icônes HUD**, **20 matériaux de caisses** et **4 sigils d’armure** tous uniques.
- HUD ASFIX avec portrait de skin dynamique, solde NetherCore, métier, niveau, progression d’XP, santé, armure, coordonnées et noms de mondes lisibles. Le bridge BetterHud 1.0.2 fournit les variables ASFIX.
- Aperçus : [planche des 34 modèles](preview/asfix-v106.18-geometry-preview.png), [SVG](preview/asfix-v106.18-geometry-preview.svg) et [galerie interactive](preview/apercu-tous-modeles-asfix-v106.18.html).

Les 16 modèles d’armure sont les objets affichés en inventaire; l’armure portée utilise les couches de personnage Minecraft. Les aperçus PNG/SVG montrent la géométrie source en projection isométrique, pas le moteur Minecraft. Le rendu en jeu doit être confirmé dans un client Java.

Le HUD généré nécessite BetterHud 2.2.0-SNAPSHOT-449 et AsfixHudBridge 1.0.2. Le ZIP contient les assets BetterHud, mais pas les JAR ni leur configuration de serveur.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.18-NATURAL-REALISTIC-MODELS-CUSTOM-HUD.zip`
- SHA-1 : `EE07F7CCCFB75F45988616CCF7156B1F0035B19B`
- SHA-256 : `EA0BCEF63F0A410BACEBFD6C22886D07E00F7F55A56F44C9C68F085F594B3B4E`
- Taille : 13 080 967 octets.
- Vérifications : 2 483 chemins uniques, 248 JSON analysés, 34 modèles uniques, 8 304 faces texturées sans alias manquant, zéro erreur d’UV de caisse, neuf minerais 64×64 et icônes/matériaux uniques.
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.18-NATURAL-REALISTIC-MODELS-CUSTOM-HUD.zip>

Smoke local isolé réussi sous Paper 26.2 / Java 25 : BetterHud a chargé AsfixHudBridge 1.0.2 et généré son `build.zip`. Cette vérification ne confirme pas le rendu en jeu côté client.

Installation manuelle : placez le ZIP dans le dossier `resourcepacks`, puis sélectionnez-le dans Minecraft. Le serveur ASFIX peut le distribuer avec le SHA-1 indiqué ci-dessus.
