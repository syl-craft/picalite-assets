# Logo PicaLite

**Idée :** une photo glissée dans deux coins d'album. Le cadre est coupé en deux équerres,
chaque pièce a sa couleur : un clin d'œil à l'énergie multicolore de Picasa, sans en reprendre
la forme ni les couleurs de Google.

## Fichiers

| Fichier | Usage |
|---|---|
| `ico/picalite.ico` | `ApplicationIcon` du .csproj, icône de fenêtre, « Ouvrir avec ». Tailles 16, 24, 32, 48, 64, 128, 256 |
| `svg/picalite-symbol.svg` | Master couleur, à partir de 48 px |
| `svg/picalite-symbol-small.svg` | Version simplifiée pour 16 à 32 px (cadre plus épais, espaces plus larges) |
| `svg/*-black.svg`, `svg/*-white.svg` | Versions une couleur (noir sur clair, blanc sur sombre) |
| `png/picalite-<taille>.png` | PNG transparents. 16, 24 et 32 viennent de la version simplifiée |
| `png/picalite-lockup-clair.png`, `-sombre.png` | Symbole + nom, pour l'écran « À propos » |
| `svg/picalite-logo-clair.svg`, `-sombre.svg` | Symbole + nom horizontal, nom vectorisé (aucune police requise) |
| `svg/picalite-logo-vertical-clair.svg`, `-sombre.svg` | Symbole au-dessus du nom |
| `xaml/PicaLiteLogo.xaml` | `ResourceDictionary` WPF : `PicaLiteLogo` et `PicaLiteLogoPetit` (`DrawingImage`) |
| `police/Poppins-OFL.txt` | Licence de la police du nom (SIL OFL 1.1) |

« clair » = texte foncé, pour un fond clair ; « sombre » = texte clair, pour un fond sombre.
Les assets du README GitHub et des vidéos sont dans `..\readme\` et `..\video\`.

Dans le `.ico`, les tailles 16, 24 et 32 sont tirées de la version simplifiée, et les tailles
de 48 à 256 du master.

## Couleurs

| Pièce | HEX | RGB |
|---|---|---|
| Équerre haute (violet) | `#7B5CFF` | 123, 92, 255 |
| Équerre basse (turquoise) | `#00C2A8` | 0, 194, 168 |
| Coin haut (framboise) | `#FF3B6B` | 255, 59, 107 |
| Coin bas (ambre) | `#FFB000` | 255, 176, 0 |

Le symbole fonctionne tel quel sur les thèmes clair et sombre : aucune version spécifique n'est
nécessaire. L'accent bleu de l'interface (`#0078D4`) reste celui de l'UI : il ne fait pas partie
du logo.

## Règles

- **Zone de protection :** autour du symbole, laisser au moins la largeur d'un coin d'album
  (un tiers de la largeur du symbole).
- **Tailles :** version simplifiée de 16 à 32 px, master au-delà.
- **À ne pas faire :** changer l'ordre ou les couleurs des pièces, refermer les espaces entre
  les pièces, faire tourner le symbole, ajouter ombre, dégradé ou contour, ou le poser sur une
  photo chargée sans fond uni.

## À savoir

- Le nom est en **Poppins SemiBold** (licence SIL OFL 1.1, libre pour un logo), converti en
  tracés : les SVG et PNG s'affichent pareil partout. Dans l'app WPF, on peut aussi afficher le
  symbole et écrire « PicaLite » dans la police de l'interface.
- « PicaLite » est un nom de travail. Le symbole ne contient pas de texte : il survit à un
  changement de nom.
- Aucune recherche d'antériorité de marque n'a été faite. À prévoir avant une diffusion publique.
- Conçu avec le skill `logo-design` (kaankiziltug/logo-design-skill) : brief, 3 concepts,
  tests à 16 px, en une couleur et sur fond clair et sombre.
