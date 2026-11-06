# PicaLite

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="readme/picalite-banniere-sombre.png">
  <img src="readme/picalite-banniere-clair.png" alt="PicaLite">
</picture>

PicaLite est une visionneuse et un organiseur de photos et vidéos pour Windows, inspiré de Picasa.
Vos fichiers restent dans leurs dossiers. Parcourez votre collection par dossiers ou chronologie,
préparez une sélection et imprimez plusieurs photos sur une feuille, avec cadrage et repères de coupe.

**[Télécharger PicaLite pour Windows x64](https://github.com/syl-craft/picalite-assets/releases/latest/download/PicaLiteApp-win-Setup.exe)**

Le programme d'installation installe le runtime .NET 10 Desktop si nécessaire. Il s'installe pour
votre compte, sans remplacer le dossier du profil. L'application recherche les mises à jour ; vous
décidez de leur téléchargement et du redémarrage. Cette recherche peut être désactivée dans les Paramètres.
Le programme n'est pas signé : Windows SmartScreen peut afficher un avertissement.

## Photos, vidéos et impression

- Navigation par dossiers et chronologie, visionneuse avec zoom et lecture vidéo.
- Sélection commune aux sources, export et rotation JPEG sans réencodage.
- Impression photo : formats personnalisés, cadrage, plusieurs photos par feuille, repères de coupe.
- Interface en français et en anglais, thèmes clair, sombre et système.

## Modules optionnels

Les moteurs natifs lourds sont téléchargés à la demande depuis **Paramètres → Modules** :
Magick pour les formats avancés, FFmpeg pour les vignettes vidéo et libVLC pour la lecture vidéo.

Le [manifeste des modules](https://github.com/syl-craft/picalite-assets/releases/download/modules/manifest.json)
est conservé dans la release permanente `modules`. Les archives, sources et licences sont disponibles
dans les releases `modules-AAAA-MM-JJ`. Ces releases ne remplacent pas la dernière version de l'application.

Les modules conservent les licences de leurs composants, distinctes de celle de PicaLite.
Consultez les textes inclus dans chaque archive et les sources publiées dans la même release :
ImageMagick/Magick.NET et leurs dépendances, FFmpeg en variante LGPL, libVLC et les greffons LGPL retenus.
Les licences et avis des dépendances restent applicables. Leur téléchargement n'accorde aucun droit
supplémentaire sur le code de PicaLite.

Ce dépôt héberge uniquement les visuels de présentation, les distributions et les modules.
Le code source de PicaLite est conservé dans un dépôt privé. Aucune photo personnelle n'est distribuée ici.
