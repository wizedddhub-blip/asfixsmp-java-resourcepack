# ASFIX SMP — Resource pack Java 26.2, v106.37

## Version courante

Le pack v106.37 reprend la base locale v106.36 et ajoute les outils/armes voxel style vanilla ainsi que les ressources BetterHud générées pour Minecraft 26.2.

- 3 pioches évolutives, 4 outils de métier, 3 épées et 3 haches en modèles 3D faits de petits cuboïdes.
- Textures d’outil 16×16 avec bois, acier, jade, cyan et ambre.
- HUD BetterHud ASFIX : cadre naturel bois/bronze/jade, icônes distinctes, Silkscreen pour le titre et Oxanium pour les valeurs.
- Modèles précédents conservés, dont les modèles d’armure volumétriques et les assets de caisses/GUI présents dans la base.
- Format pack Minecraft 26.2 : `88.0`.

## Contrôles effectués

- 2 716 chemins ZIP, aucun doublon.
- 132 modèles JSON, 2 085 cuboïdes, aucune profondeur nulle, aucune coordonnée hors plage 0–16.
- 332 références de textures résolues, aucune manquante.
- 65 textures de face des outils, toutes en 16×16.
- Chargement isolé Paper 26.2 / Java 25 avec BetterHud, PlaceholderAPI et AsfixHudBridge : 11 variables ASFIX enregistrées et aucune erreur de layout/image.

Le test serveur vérifie le chargement BetterHud et la construction du pack. Il n’a pas été rejoint par un client Minecraft ; le rendu exact dans le client reste à confirmer. Le pack cible Java 26.2. Le HUD Bedrock est désactivé dans la configuration BetterHud actuelle.

## Aperçus

- Galerie des modèles : [aperçu 3D des outils](preview/v106.37-all-tools-voxel.png)
- Aperçu HUD : [HUD ASFIX](preview/v106.37-hud.png)

## Archive v106.37

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.37.zip`
- Taille : 15 905 670 octets
- SHA-1 : `7EDD583595BD3956E5B33008B7741B329609DF14`
- SHA-256 : `4E1C6D2E1435566A740B35AA019B51E0E2DAE515648765AE00DE41D6AB1EF885`
- Construction : générée localement à partir des contenus ItemsAdder et de BetterHud pour 26.2.
