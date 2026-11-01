# Assets vidéo et motion design — PicaLite

À garder hors du dépôt (vidéos publiées via un lien externe).

## Vidéos prêtes

| Fichier | Format | Usage |
|---|---|---|
| `picalite-intro-clair-1080p.mp4` / `-sombre-1080p.mp4` | H.264, 1920×1080, 30 i/s, 3,5 s | Intro de vidéo de présentation : le cadre se pose, les coins d'album viennent le tenir, puis le nom et le slogan |
| `picalite-symbole-anime-alpha.mov` | ProRes 4444 avec alpha, 1080×1080, 2,5 s | Symbole animé sur fond transparent, à poser sur n'importe quel plan (Premiere, DaVinci, After Effects, Final Cut) |
| `picalite-symbole-anime-alpha.webm` | VP9 avec alpha | Même chose, léger, pour le web, OBS ou CapCut |

## Images fixes

| Fichier | Usage |
|---|---|
| `picalite-carte-titre-clair-1080p.png`, `-4k.png` (et `sombre`) | Carte titre / carte de fin |
| `calques/picalite-calque-<pièce>.png` | 4096×4096, une pièce par fichier, **même cadrage** : empilez-les pour animer chaque pièce séparément |
| `picalite-calques.svg` | Le logo vectoriel avec un calque nommé par pièce (`cadre-haut`, `cadre-bas`, `coin-haut`, `coin-bas`, `nom`), à importer dans Illustrator, Figma ou After Effects |

## Palette

`palette/` : la même palette en JSON, CSS et GIMP/Inkscape (`.gpl`).

| Nom | HEX |
|---|---|
| violet (équerre haute) | `#7B5CFF` |
| turquoise (équerre basse) | `#00C2A8` |
| framboise (coin haut) | `#FF3B6B` |
| ambre (coin bas) | `#FFB000` |
| encre sur fond clair | `#1B1B1B` |
| encre sur fond sombre / fond sombre | `#F2F2F2` / `#161616` |

## Animer le logo soi-même

- Ordre d'entrée : les deux équerres glissent depuis des coins opposés (0 à 0,7 s, décélération),
  puis les coins d'album se posent avec un léger rebond (0,55 à 1,25 s), puis le nom et le slogan (à partir de 1,05 s).
- Typographie : Poppins SemiBold (nom) et Regular (slogan), licence SIL OFL 1.1, libre pour la vidéo.
