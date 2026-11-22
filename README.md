# ASFIX SMP — pack de ressources Java

## Version 106.16 · Minecraft Java 26.2

Pack unifié pour ASFIX SMP, avec ItemsAdder et les ressources BetterHud du thème violet, cyan et or.

- Format de pack 88.0 (Java 26.2).
- **31 modèles d’objets en vraie géométrie 3D cuboïde** : 5 caisses, 6 armes, 4 outils de métier et 16 pièces d’armure d’inventaire.
- **498 cuboïdes** dans ces modèles; chaque modèle a sa silhouette et ses textures propres. Les cuboïdes ne sont pas des sprites aplatis.
- **63 icônes ItemsAdder** et **7 icônes BetterHud** distinctes.
- HUD ASFIX avec ressources pixel art, portrait de skin dynamique, monnaie, métier, rang et progression; police Oxanium.
- Aperçu isométrique généré depuis les géométries JSON : [31 modèles](preview/asfix-v106.16-geometry-preview.png).

Les 16 modèles d’armure custom sont les objets d’inventaire; l’équipement porté garde le maillage vanilla de Minecraft. L’aperçu de géométrie montre les couleurs moyennes des textures; l’aperçu interactif local charge les textures complètes. Le rendu final dans un client Minecraft réel n’a pas été confirmé.

Le pack BetterHud nécessite BetterHud 2.2.0-SNAPSHOT-449 et AsfixHudBridge 1.0.1. La configuration BetterHud du serveur est gérée séparément du ZIP de ressources.

### Archive

- Fichier : `AsfixSMP-Java-ResourcePack-26.2-v106.16-3D-REALISTIC-HUD-UNIQUE-ICONS.zip`
- SHA-1 : `3186928BD71CBD5EF821662E4742A450D2EFA794`
- SHA-256 : `6E9C3E14D484E892F4774978D46EE27863B88E943E51515C59A16C9830EDEB6D`
- Téléchargement : <https://raw.githubusercontent.com/wizedddhub-blip/asfixsmp-java-resourcepack/main/AsfixSMP-Java-ResourcePack-26.2-v106.16-3D-REALISTIC-HUD-UNIQUE-ICONS.zip>

Smoke local isolé : Paper 26.2 / Java 25 a chargé BetterHud et AsfixHudBridge, puis a généré le pack BetterHud sans erreur de configuration. BetterHud annonce cette version comme une build de développement.

Installation manuelle : placez le ZIP dans le dossier `resourcepacks`, puis sélectionnez-le dans Minecraft. Le serveur ASFIX peut le distribuer avec le SHA-1 ci-dessus.