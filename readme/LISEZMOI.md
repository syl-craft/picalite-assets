# Assets du README GitHub — PicaLite

Destination prévue : `docs/assets/`. Images fabriquées (aucune photo personnelle), PNG/WebP, toutes < 60 Ko.

| Fichier | Taille | Usage |
|---|---|---|
| `picalite-banniere-clair.png` / `-sombre.png` | 1280×400 | En-tête du README (bascule selon le thème GitHub) |
| `picalite-logo-clair.png` / `-sombre.png` | 840×192 | Logo horizontal seul |
| `picalite-logo-vertical-clair.png` / `-sombre.png` | 400×400 | Logo empilé (sections, docs) |
| `picalite-logo-anime.webp` | 320×320 | Symbole animé, fond transparent, joué une fois |
| `picalite-apercu-social.png` | 1280×640 | *Settings → Social preview* du dépôt (pas dans le README) |

« clair » = texte foncé, pour le thème clair de GitHub ; « sombre » = texte clair.

## Extrait à coller en tête du README

```html
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/assets/picalite-banniere-sombre.png">
    <img alt="PicaLite — Vos photos, imprimées à la maison" src="docs/assets/picalite-banniere-clair.png" width="640">
  </picture>
</p>
```

Variante animée (le symbole se forme, fond transparent, valable sur les deux thèmes) :

```html
<p align="center"><img alt="PicaLite" src="docs/assets/picalite-logo-anime.webp" width="160"></p>
```

## À savoir

- Le nom et le slogan sont vectorisés depuis **Poppins** (SemiBold / Regular, SIL Open Font License 1.1) :
  aucune police n'est requise pour les afficher. Le slogan « Vos photos, imprimées à la maison » est une proposition.
- Les SVG sources (lockups vectorisés) sont dans `..\logo\svg\`.
