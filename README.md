# ASFIX SMP — pack de ressources Java

## Version 106.17 · Minecraft Java 26.2

Pack ASFIX unifié pour ItemsAdder et BetterHud, avec le thème violet, cyan et or.

- Format de pack 88.0, ciblé Minecraft Java 26.2.
- **34 modèles d’objets en vraie géométrie 3D**, faits de volumes Minecraft : 5 caisses, 6 armes, 3 pioches évolutives, 4 outils de métier et 16 pièces d’armure d’inventaire.
- **844 volumes 3D** et 5 silhouettes de caisses différenciées. Les éléments décoratifs ont une épaisseur réelle; les modèles ne sont pas des sprites plats auxquels on a ajouté une plaque.
- Textures dédiées : 20 matériaux de caisses, 39 d’armes et d’outils, et 56 textures d’armurerie.
- **63 icônes ItemsAdder**, **7 icônes HUD**, **20 matériaux de caisses** et **4 sigils d’armure** tous uniques.
- HUD ASFIX avec portrait de skin dynamique, solde NetherCore, métier, niveau, progression d’XP, santé, armure, coordonnées et noms de mondes lisibles. Le bridge BetterHud 1.0.2 fournit les variables ASFIX.
- Aperçus : [planche des 34 modèles](preview/asfix-v106.17-geometry-preview.png), [SVG](preview/asfix-v106.17-geometry-preview.svg) et [galerie interactive des modèles](preview/apercu-tous-modeles-asfix-v106.17.html).

Les 16 modèles d’armure sont les objets affichés en inventaire; l’armure portée utilise toujours les couches de personnage Minecraft. Le PNG/SVG est une projection des modèles JSON et non une capture du moteur de jeu. La galerie charge les textures et permet d’inspecter les modèles, mais le rendu final n’a pas encore été confirmé dans un client Minecraft.

Le HUD généré nécessite BetterHud 2.2.0-SNAPSHOT-449 et AsfixHudBridge 1.0.2. Le ZIP de ressources contient les assets BetterHud, mais pas les JAR ni leur configuration de serveur.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.17-REALISTIC-3D-MODELS-CUSTOM-HUD.zip`
- SHA-1 : `05775B52264D88117674AE80E0248E7376130FAA`
- SHA-256 : `34150D26DABE9A3290B97829CA1E601227AC61F5E6C77BD249EA87810CD1FF41`
- Validation : 2 482 chemins internes uniques, 248 fichiers JSON analysés, 34 modèles et textures résolus, aucune erreur d’UV de caisse.
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.17-REALISTIC-3D-MODELS-CUSTOM-HUD.zip>

Smoke local isolé réussi sous Paper 26.2 / Java 25 : BetterHud a chargé AsfixHudBridge 1.0.2 et généré son `build.zip`. Cette vérification ne confirme pas le rendu en jeu côté client.

Installation manuelle : placez le ZIP dans le dossier `resourcepacks`, puis sélectionnez-le dans Minecraft. Le serveur ASFIX peut le distribuer avec le SHA-1 ci-dessus.
