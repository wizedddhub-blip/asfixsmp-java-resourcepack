# ASFIX SMP — Resource pack Java 26.2, v106.35

Cette version conserve le thème ASFIX en acier, fer sombre, bois, cuir, bronze et jade. Elle ajoute un reflet animé aux neuf gemmes d’icônes de caisses.

## Changements

- Neuf icônes de gemme animées avec quatre images chacune. Le reflet se déplace sur la gemme et sa silhouette reste stable.
- Les caisses en monde restent des modèles fixes dans cette version; seule l’icône de gemme scintille.
- Les modèles ItemsAdder v106.34, les 20 glyphes de grade et le HUD BetterHud v106.34 sont conservés.
- Le HUD comprend un cadre illustré bois et bronze, des touches jade, la police Oxanium, un portrait joueur, le profil, le métier, les coordonnées, les statistiques, le solde et la progression.
- Le pack cible Minecraft Java 26.2, avec les définitions de modèles au format 88.0.

## Aperçus

- [Galerie des armes, outils, caisses, clés, badges et HUD](apercu-v106.35.html)
- [Galerie des 128 modèles](../apercu-tous-modeles-asfix-v106.35.html)
- [Aperçu des quatre images par gemme](previews/crate-gem-animation-preview-v10635.png)
- [HUD BetterHud](previews/asfix-v106.35-hud-preview.png)
- [Pioches, outils et armes 3D](previews/asfix-v106.35-weapons-gui.png)
- [Neuf caisses 3D, vue GUI](previews/asfix-v106.35-crates-gui.png)
- [Neuf caisses, transformation monde FIXED](previews/asfix-v106.35-crates-world-fixed.png)
- [Neuf clés 3D](previews/asfix-v106.35-keys-gui.png)

Ces vues de modèles sont des projections hors du moteur Minecraft; elles ne remplacent pas le rendu client. Le HUD correspond aux fichiers et textures BetterHud inclus, mais son affichage en jeu dépend du chargement du pack et du plugin.

## Validation locale

- 2 639 entrées ZIP uniques.
- 132 fichiers JSON de modèle, dont 128 modèles avec volumes.
- 31 modèles de gameplay vérifiés : armes, outils, caisses et clés.
- Les neuf caisses monde sont associées à ItemsAdder et à la transformation FIXED.
- 20 glyphes de grade uniques; 349 références de textures présentes.
- 18 atlas et métadonnées d’animation contrôlés (neuf variantes pour les chemins item et block).
- HUD BetterHud vérifié dans le pack : cadres naturels, police Oxanium, portrait fancy.
- Les JAR NetherRanks 1.0.15 et NetherCrates 1.0.8 restent uniques dans le dossier plugins.

Scripts de vérification : [validate-v10635.ps1](validate-v10635.ps1) et [verify-v10635-archive.ps1](verify-v10635-archive.ps1). La génération et la stabilisation des reflets sont documentées dans [build-crate-gem-animations.ps1](../asfix-resourcepack-v106.34/build-crate-gem-animations.ps1) et [stabilize-crate-gem-animations.ps1](../asfix-resourcepack-v106.34/stabilize-crate-gem-animations.ps1).

## Archive

- Fichier : AsfixSMP-Java-ResourcePack-26.2-v106.35.zip
- Taille : 14 922 741 octets
- SHA-1 : 78B53AB7285BBD504BF81A2E69B4B21433BC1CFD
- SHA-256 : 85EF97B9D10E8829C1BFD4429F706B08C73FFEC63422B1B00EFE70D820AB5B3F
- [Télécharger v106.35](AsfixSMP-Java-ResourcePack-26.2-v106.35.zip)
- Dépôt public : [wizedddhub-blip/asfixsmp-java-resourcepack](https://github.com/wizedddhub-blip/asfixsmp-java-resourcepack)

Le server.properties du dossier central pointe vers cette archive. Le serveur WinHeberg n’a pas été redémarré ni vérifié avec ce nouveau pack.

## Limites du format

Les modèles d’objets Minecraft utilisent des cuboïdes texturés et des faces orientées. Ils ont une géométrie 3D réelle et ne sont pas des sprites épaissis, mais ce ne sont pas des meshes lissés avec matériaux PBR. Le rendu dans un client Minecraft après chargement du pack reste à confirmer.