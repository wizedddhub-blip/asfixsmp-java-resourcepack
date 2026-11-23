# ASFIX SMP — pack de ressources Java

## Version 106.25 · Minecraft Java 26.2

Pack ASFIX pour ItemsAdder et BetterHud. La direction artistique garde des matériaux naturels — acier, bois, cuir, bronze, pierre et jade — et réserve les couleurs cosmiques aux gemmes et aux effets qui en ont besoin.

### Modifications v106.25

- 42 textures dédiées haute définition (256×256) pour les armes et pioches évolutives : métal brossé et usé, tranchants, cuir gainé, bois veiné, gemmes facettées et accents métalliques.
- 55 modèles JSON tridimensionnels avec 1 666 cuboïdes volumétriques, dont 235 orientés. Les pioches, épées, haches, armures, crates, outils de métier et clés ont une géométrie en volume.
- 110 définitions ItemsAdder vérifiées : chaque référence personnalisée utilisée par le pack résout son modèle.
- HUD BetterHud ASFIX au thème bois, bronze et jade : portrait, grade, métier, coordonnées, niveau et progression, santé, armure, faim et solde. Police Oxanium; 603 ressources BetterHud incluses et vérifiées.
- Format Minecraft Java 26.2 (88.0); aucune entrée ZIP dupliquée, référence de texture manquante ni texture violette dans les 34 textures de blocs personnalisés.

### Géométrie et rendu

Les modèles sont réellement en volume dans le format JSON d’ItemsAdder/Minecraft; ils ne sont pas des sprites 2D auxquels on a simplement donné de l’épaisseur. Ils sont assemblés avec des cuboïdes, car c’est la géométrie permise par ce format. Les cartes détaillées apportent les stries, les gravures, le grain, les tranchants et les facettes. Ce n’est pas un maillage polygonal PBR.

Les aperçus sont des projections des modèles et textures sources, pas des captures moteur. Le rendu sur le client doit encore être observé avec la bonne version du serveur et ItemsAdder actifs.

### HUD

Le HUD s’inspire des panneaux lisibles et des informations de progression montrés dans les références Tavern HUD et des autres interfaces envoyées. Il utilise une charte propre à ASFIX, des cadres et textures naturels, des icônes cohérentes et la police Oxanium; les visuels des ressources commerciales n’ont pas été copiés.

### Aperçus

- [Planche des 35 géométries principales v106.25](preview/asfix-v106.25-geometry-preview.png)
- [Projection vectorielle v106.25](preview/asfix-v106.25-geometry-preview.svg)
- [Ancienne maquette du HUD naturel ASFIX](preview/apercu-hud-naturel-asfix-v10621.png) — maquette illustrative, pas une capture de jeu.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.25.zip`
- Taille : 17 601 107 octets.
- SHA-1 : `B3E45FE104751AC01C92D215480D9DF0874E4BE6`
- SHA-256 : `1B45CBB7152980AF5A47185C16F35C052C8298DE82B441B158E7C710A230D61D`
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.25.zip>
