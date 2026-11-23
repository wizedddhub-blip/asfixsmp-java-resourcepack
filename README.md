# ASFIX SMP — pack de ressources Java

## Version 106.24 · Minecraft Java 26.2

Pack ASFIX pour ItemsAdder et BetterHud. La direction artistique garde des matériaux naturels — bois, bronze, acier, pierre et jade — avec les couleurs cosmiques réservées aux objets qui les utilisent.

### Modifications v106.24

- Textures de matériaux détaillées en 128×128 pour les six armes et les trois pioches évolutives : acier forgé, tranchants, cuir, bois, gemmes et accents gravés.
- Synchronisation de 110 définitions ItemsAdder, de 55 modèles 3D et de leurs références. Toutes les définitions d’objets personnalisés du pack pointent vers un modèle présent.
- HUD BetterHud ASFIX au thème bois, bronze et jade : tête, grade, nom, métier, coordonnées, niveau, barre d’expérience du métier, santé, armure, faim et solde. Police Oxanium et 603 ressources BetterHud vérifiées.
- Format Minecraft Java 26.2 (88.0). Aucun doublon de chemin dans l’archive.

### Modèles et rendu

- L’audit trouve 55 modèles cuboïdes, 1 666 volumes, 235 éléments orientés et 9 996 faces texturées. Aucune face aplatie, texture manquante ou référence d’item sans modèle n’a été détectée.
- Les objets sont réellement en volume dans le format modèle Java. La géométrie reste composée de cuboïdes Minecraft; les détails supplémentaires viennent des volumes, des textures haute résolution, des arêtes et des matériaux. Cela ne produit pas un maillage polygonal PBR.
- Les pioches et armes utilisent des textures dédiées, pas une épaisseur appliquée à un sprite 2D.
- Les aperçus sont des projections des JSON et textures sources, pas des captures de rendu en jeu. Le rendu final doit encore être observé avec le client Minecraft et ItemsAdder actifs.

### Direction du HUD

Le HUD reprend les panneaux lisibles et les informations de progression mis en avant par les références Tavern HUD, avec des cadres texturés naturels, une tête de joueur, une typographie dédiée, des icônes ASFIX cohérentes et des couleurs de grade distinctes. Les icônes et préfixes sont recréés pour ASFIX plutôt que copiés d’assets commerciaux.

### Aperçus

- [Planche des 35 géométries principales v106.24](preview/asfix-v106.24-geometry-preview.png)
- [Projection vectorielle v106.24](preview/asfix-v106.24-geometry-preview.svg)
- [HUD naturel ASFIX v106.21](preview/apercu-hud-naturel-asfix-v10621.png) — la composition et les textures BetterHud sont reprises dans v106.24; maquette illustrative, pas une capture du jeu.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.24.zip`
- Taille : 15 201 036 octets.
- SHA-1 : `4F34111FB33AAC84EB19A8CFB58FB3C77B5FDC68`
- SHA-256 : `6CAEBD8957EDABE2BE0599AE61520A663B68EE667E320AAED4E78715B30B5ABD`
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.24.zip>
