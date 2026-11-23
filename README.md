# ASFIX SMP — pack Java 26.2, v106.40

[Télécharger le pack](AsfixSMP-Java-ResourcePack-26.2-v106.40.zip)

## Outils

Le pack contient 13 modèles ItemsAdder : trois pioches évolutives, quatre outils de métier, trois épées et trois haches. Ils totalisent 1 309 volumes cubiques avec profondeur non nulle. Les textures gardent des matériaux naturels (bois, métal forgé, cuir) et des accents de gemmes adaptés à chaque set.

Chaque outil hérite des transformations `minecraft:item/handheld` de Minecraft. Les rotations et échelles personnalisées ont été retirées pour retrouver la pose des outils vanilla en main. Les 13 définitions d’objets pointent vers leurs modèles, et les textures référencées sont présentes dans le pack.

## HUD

L’archive contient les ressources BetterHud ASFIX compilées pour Minecraft 26.2 : 48 tuiles d’image pour le HUD et la hotbar, ainsi que l’overlay shader texte de la version 26.2. Aucun JAR de plugin n’est inclus dans le resource pack.

## Vérification

- Format Minecraft : `88.0` (26.2).
- 2 645 entrées ZIP, sans chemin en double.
- 273 fichiers JSON analysés sans erreur.
- 13 modèles et 1 309 volumes 3D, aucun élément à profondeur nulle.
- Aucune texture manquante parmi les modèles d’outils et aucune liaison ItemsAdder manquante.
- 48 tuiles BetterHud compilées et shader 26.2 présents.
- Taille : 15 462 566 octets.
- SHA-1 : `6AE2A5CBFEDC888CFB7C80479E4BE4BD233FEC26`.
- SHA-256 : `4B6268866065E5468F13C2059D386955027355418CF0CFCAEAA505040F878EDF`.

La galerie ci-dessous est une projection hors moteur Minecraft des cuboïdes du pack. La structure a été vérifiée, mais cette archive v106.40 n’a pas encore été affichée dans un client Minecraft ; son apparence exacte en jeu reste donc à confirmer.

[Ouvrir l’aperçu hors jeu des 13 outils](preview/v106.40-tools-offline-projection.png)

## Reconstruction

Lancer `build-release-v106.40.ps1` dans PowerShell. Le script part du ZIP v106.39, remplace les 13 modèles d’outils, intègre les ressources BetterHud compilées pour 26.2, puis vérifie l’archive et écrit `release-v106.40-manifest.txt`.
