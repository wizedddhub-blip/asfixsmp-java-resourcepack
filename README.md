# ASFIX SMP — Resource pack Java 26.2

Pack ItemsAdder et BetterHud pour Minecraft Java 26.2. La direction visuelle ASFIX utilise des matériaux naturels — acier, fer sombre, bois, cuir, bronze et jade — avec des accents propres à chaque série.

## Publication v106.35

- 31 modèles de gameplay reliés aux contenus actifs : armes, outils, caisses et clés.
- 128 géométries de modèles volumétriques dans l’archive; 9 caisses de monde avec silhouettes et ornements distincts.
- HUD BetterHud ASFIX : cadre bois sombre, ferrures acier et bronze, touches jade, police Oxanium, profil, métier, coordonnées, statistiques, progression et barre personnalisée.
- Icônes de grades uniques et éléments d’interface assortis au thème ASFIX.
- Ressource préparée pour Minecraft Java 26.2, ItemsAdder et BetterHud.

### Aperçus

Les images ci-dessous sont des aperçus générés hors moteur Minecraft. Elles servent à examiner les modèles et la composition visuelle; elles ne prouvent pas le rendu dans un client connecté au serveur.

![HUD ASFIX v106.35](preview/asfix-v106.34-hud-preview.png)

![Pioches, outils et armes 3D](preview/asfix-v106.34-weapons-gui.png)

![Caisses ASFIX 3D](preview/asfix-v106.34-crates-gui.png)

![Caisses dans le monde — aperçu](preview/asfix-v106.34-crates-world-fixed.png)

![Clés ASFIX](preview/asfix-v106.34-keys-gui.png)

### Gemmes animees

Neuf icones de gemme de caisse ont quatre images avec un reflet mobile et une silhouette stable. Cette animation concerne les icones; les caisses en monde restent des modeles fixes.

![Apercu des gemmes de caisses animees](preview/crate-gem-animation-v10635.png)

## Limites de rendu

Les modèles d’objets Minecraft sont construits avec des cuboïdes texturés et des faces orientées; ils ne sont pas des maillages PBR libres. Les modèles d’armes et de caisses ont du volume réel dans leurs définitions JSON, plutôt qu’une simple image plane ou un sprite épaissi. Les armures portées utilisent les couches de texture du joueur. Le rendu final dépend des versions installées d’ItemsAdder et BetterHud et doit encore être confirmé dans le client Minecraft du serveur.

## Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.35.zip`
- Taille : 14 922 741 octets
- SHA-1 : `78B53AB7285BBD504BF81A2E69B4B21433BC1CFD`
- SHA-256 : `85EF97B9D10E8829C1BFD4429F706B08C73FFEC63422B1B00EFE70D820AB5B3F`
- [Télécharger le pack v106.35](AsfixSMP-Java-ResourcePack-26.2-v106.35.zip)

## Installation ItemsAdder et BetterHud

Sur le serveur, BetterHud doit générer ses ressources avec `/betterhud reload`, puis ItemsAdder reconstruire le resource pack avec `/iazip`. Cette reconstruction en direct et l’apparence finale dans Minecraft Java 26.2 ne sont pas revendiquées comme vérifiées par cette publication.
