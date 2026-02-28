# Ergglace

Une disposition pour le français, l’anglais et la programmation. Ce projet est basé sur [Erglace](https://github.com/cmoinard/Erglace), lui-même dérivé d’ErgEAU, et reprend de nombreuses conventions de [Ergo-L][ergol].

[ergol]: https://ergol.org

## Cette version

Ergglace est ma version personnelle de la disposition de cmoinard.

Le principe reste le même : la disposition de base n’est pas modifiée. Cette variante ajoute surtout quelques symboles accessibles via la touche morte (1DK), pour une meilleure qualité de vie à l’usage quotidien.

## Caractéristiques

- disposition optimisée pour le français et l’anglais
- utilisation d’une touche morte pour les caractères accentués les plus fréquents
- couche AltGr dédiée aux symboles de programmation
- compatible avec les claviers compacts (30 touches)
- optimisation globale privilégiée par rapport à l’accès direct à certains raccourcis
- SFB plus bas que la plupart des dispositions françaises précédentes
- peu de redirections, au prix de moins de roulements

## Liens

- [Discord (Ergo-L)][discord]


[discord]: https://discord.gg/RH34GjQEgC


## Disposition
![couche de base](img/erglace.svg)

La touche morte ★ donne accès à toutes les lettres accentuées nécessaires pour écrire un français correct :

Version originale (Erglace de cmoinard) :
![couche touche morte originale](img/erglace_1dk.svg)

Version personnelle (Ergglace) :

La disposition reste la même, avec quelques ajustements de qualité de vie dans les symboles accessibles via la touche morte (1DK).
![couche touche morte Ergglace](img/ergglace_1dk.svg)

Caractères déplacés (entre `erglace.toml` et `ergglace.toml`) :

- `@` (COMMERCIAL AT) : ajouté sur `Z` en couche 1DK (était absent), plus facile d’accès en main gauche direct depuis 1DK, mais serait plus logique (et sans doute moins pratique !) sur `Q` puisque `AltGr+Q` produit `@`
- `ß` (LATIN SMALL LETTER SHARP S) : retiré de `X` en couche 1DK car je ne l’utilise pas et ne l’utiliserai jamais
- `€` (EURO SIGN) : ajouté sur `I` en couche 1DK
- `æ` (LATIN SMALL LETTER AE) : déplacé de la couche 1DK principale vers l’autre niveau 1DK sur `I`, inutile pour mon usage ; je n’écris pas en latin, mais il reste accessible pour les rares mots qui l’utilisent
- `•` (BULLET) : déplacé de `P` vers `Y` en accès 1DK ; je ne m’en suis jamais servi mais ça peut être utile pour faire des listes au lieu du tiret
- `·` (MIDDLE DOT) : déplacé de `P` vers `Y` en accès 1DK ; je ne m’en suis jamais servi et n’en vois pas l’utilité, mais il reste accessible
- `µ` (MICRO SIGN) : déplacé de `M` vers l’autre niveau 1DK sur `M` ; je ne m’en suis jamais servi et n’en vois pas l’utilité, mais il reste accessible
- `ñ` (LATIN SMALL LETTER N WITH TILDE) : déplacé de `V` vers l’autre niveau 1DK sur `V` ; je ne m’en suis jamais servi et n’en vois pas l’utilité en français, mais il reste accessible au cas où il faudrait taper un mot espagnol
- `(` (LEFT PARENTHESIS) : ajouté sur `P` en couche 1DK ; l’accès 1DK des parenthèses de Ergol-L me manquait
- `)` (RIGHT PARENTHESIS) : ajouté sur `M` en couche 1DK
- `«` (LEFT-POINTING DOUBLE ANGLE QUOTATION MARK) : ajouté sur `V` en couche 1DK ; accès 1DK plus pratique qu’avec la ligne des chiffres
- `»` (RIGHT-POINTING DOUBLE ANGLE QUOTATION MARK) : ajouté sur `W` en couche 1DK
- `/` (SOLIDUS) : ajouté sur `B` en couche 1DK ; accès 1DK plus pratique qu’avec la couche AltGr
- `\` (REVERSE SOLIDUS) : ajouté sur `G` en couche 1DK ; accès 1DK plus pratique qu’avec la couche AltGr

La couche AltGr, issue de [Ergo-L][ergol], est entièrement dédiée aux symboles de programmation :
![couche AltGr](img/erglace_altgr.svg)


## Comparaison avec Ergo-L

> Erglace abandonne l’accès facile aux raccourcis usuels (Ctrl+C, Ctrl+V, etc.) pour obtenir de meilleures statistiques, en particulier un SFB plus bas (sous 1%). Le SFB correspond aux enchaînements de deux caractères utilisant le même doigt, ce qui ralentit la frappe.
>
> L’autre différence est la volonté de minimiser les redirections, c’est-à-dire les enchaînements de trois caractères d’une même main avec changement de direction, mouvement considéré comme inconfortable. Pour cela, les voyelles sont regroupées d’un côté, comme en Bépo, ce qui favorise l’alternance des mains. Le désavantage est un nombre de roulements plus faible.

## Installation

Sous Linux, vous pouvez utiliser `xkalamine` pour l’installation. Suivez les étapes du dépôt [Ergo-L][ergol-install] en utilisant `erglace.toml` ou `ergglace.toml` selon la variante souhaitée.

[releases]: https://github.com/Lysquid/Erglace/releases
[kalamine-layout]: https://github.com/OneDeadKey/kalamine#using-distributable-layouts
[ergol-install]: https://github.com/Nuclear-Squid/ergol#install-linux-only

## Personnaliser la disposition

Vous pouvez modifier facilement [la disposition](erglace.toml) (ou sa variante `ergglace.toml`), décrite en ASCII art lisible. Ensuite, utilisez [Kalamine][kalamine] pour générer les pilotes.

[kalamine]: https://github.com/OneDeadKey/kalamine
