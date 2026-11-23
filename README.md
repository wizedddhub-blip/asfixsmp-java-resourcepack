# ASFIX SMP — pack de ressources Java

## Version 106.23 · Minecraft Java 26.2

Pack ASFIX pour ItemsAdder et BetterHud. La direction des blocs personnalisés reste naturelle : pierre sombre, cuivre, or, azur, glace et jade. Les tons violets restent réservés aux noms ou objets cosmiques hors blocs.

### Modifications v106.23

- Reprise volumétrique des six armes (trois épées, trois haches), des trois pioches évolutives et de la clé de galaxie, avec matériaux texturés et pièces sculptées.
- Ajout de quatre textures de matériaux à la clé de galaxie; corrections des rotations hors limites sur les pioches et deux crates.
- Le pack conserve les 603 ressources BetterHud 26.2 vérifiées dans l’archive : cadre bois et bronze, accents jade, icônes, barres et police Oxanium.
- L’audit v106.23 trouve 55 modèles, 1 666 volumes, 235 pièces orientées, 9 996 faces mappées et zéro référence de texture manquante.

### Base naturelle v106.20

- Neuf textures de minerais retravaillées en 64×64 : pierre texturée et veines minérales irrégulières, avec des teintes naturelles.
- Les 34 textures de blocs personnalisés ont été contrôlées : aucun pixel violet détecté.
- Correction de 12 fichiers .mcmeta qui demandaient des images inexistantes. Les textures concernées n’avaient qu’une seule image; elles chargent maintenant une frame valide sans animations fantômes.
- Les mêmes textures et métadonnées corrigées sont synchronisées dans la source ItemsAdder 4.0.16 du dossier central.
- Les cadres des menus NetherCore, NetherJobs, NetherRanks, AsfixModeration et AsfixCharacter suivent une palette bois, cuivre et vert.

### Modèles et HUD

- 55 modèles Minecraft à volumes : les 35 modèles détaillés de caisses, clé, armes, outils et pièces d’armure d’inventaire, plus les modèles de grades.
- Les éléments 3D restent soumis à la géométrie cuboïde du format Minecraft; les interfaces utilisent des icônes 2D. Les pièces d’armure sont des modèles d’objet d’inventaire, pas un maillage porté sur le personnage.
- HUD BetterHud ASFIX : tête du joueur, grade, nom, métier, coordonnées, niveau, expérience métier, santé, armure, faim et solde. Cadres en bois et bronze, accents jade, icônes dédiées et police Oxanium.
- Les aperçus sont des projections des JSON source, pas des captures du moteur Minecraft. Le rendu final des objets avec les transforms ItemsAdder reste à confirmer côté client.

### Aperçus

- [Nouvelles textures de minerais naturels](preview/asfix-natural-ore-blocks-v106.20.png)
- [Planche des 35 géométries principales](preview/asfix-v106.23-geometry-preview.png)
- [Projection vectorielle des géométries](preview/asfix-v106.23-geometry-preview.svg)

Les aperçus de géométrie sont des projections depuis les JSON source, pas des captures Minecraft. Le chargement en jeu des modèles et des textures n’est pas encore validé par capture client.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.23.zip`
- Taille : 14 537 951 octets.
- SHA-1 : `46E7DDBF7BAAF6A8C738299D2142C5D9A0EA2B9A`
- SHA-256 : `FD6BED652E7574FBBFD3F84078327CAF44142B2717E12FA9D0D4328685FBE003`
- Audit local : 2 528 entrées uniques, format 88.0, 55 modèles à volumes, aucune rotation invalide, texture ou alias manquant, et aucune teinte violette détectée dans les blocs.
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.23.zip>
