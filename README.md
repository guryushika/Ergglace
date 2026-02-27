# Ergglace

Une disposition pour le français, l’anglais et la programmation. Ce projet est basé sur [Erglace](https://github.com/cmoinard/Erglace), lui-même dérivé de [ErgEAU][ergeau], et reprend de nombreuses conventions de [Ergo-L][ergol].

[ergeau]: https://github.com/IgrecL/ErgEAU
[ergol]: https://ergol.org

## Cette version

Ergglace est ma version personnelle de la disposition de cmoinard.

Le principe reste le même : la disposition de base n’est pas modifiée. Cette variante ajoute surtout quelques symboles accessibles via la touche morte (1DK), pour une meilleure quality of life à l’usage quotidien.

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

La touche morte ★ donne accès aux caractères accentués nécessaires pour écrire correctement en français, ainsi qu’aux ajouts de cette variante Ergglace :

![couche touche morte](img/ergglace_1dk.svg)

La couche AltGr, issue de [Ergo-L][ergol], est entièrement dédiée aux symboles de programmation :

![couche AltGr](img/erglace_altgr.svg)

Images supplémentaires : [toutes les couches](img/erglace_all.svg) et variante [ISO](img/erglace_iso.svg) ([1DK](img/erglace_iso_1dk.svg), [AltGr](img/erglace_iso_altgr.svg), [Toutes](img/erglace_iso_all.svg)).

## Comparaison avec Ergo-L

> Erglace abandonne l’accès facile aux raccourcis usuels (Ctrl+C, Ctrl+V, etc.) pour obtenir de meilleures statistiques, en particulier un SFB plus bas (sous 1%). Le SFB correspond aux enchaînements de deux caractères utilisant le même doigt, ce qui ralentit la frappe.
>
> L’autre différence est la volonté de minimiser les redirections, c’est-à-dire les enchaînements de trois caractères d’une même main avec changement de direction, mouvement considéré comme inconfortable. Pour cela, les voyelles sont regroupées d’un côté, comme en Bépo, ce qui favorise l’alternance des mains. Le désavantage est un nombre de roulements plus faible.

## Installation

Récupérez le pilote correspondant à votre système depuis la [section Releases][releases]. Consultez aussi la documentation de [Kalamine][kalamine-layout] pour les détails d’utilisation.

Sous Linux, vous pouvez utiliser `xkalamine` pour l’installation. Suivez les étapes du dépôt [Ergo-L][ergol-install] en utilisant `erglace.toml` ou `ergglace.toml` selon la variante souhaitée.

[releases]: https://github.com/Lysquid/Erglace/releases
[kalamine-layout]: https://github.com/OneDeadKey/kalamine#using-distributable-layouts
[ergol-install]: https://github.com/Nuclear-Squid/ergol#install-linux-only

## Personnaliser la disposition

Vous pouvez modifier facilement [la disposition](erglace.toml) (ou sa variante `ergglace.toml`), décrite en ASCII art lisible. Ensuite, utilisez [Kalamine][kalamine] pour générer les pilotes.

[kalamine]: https://github.com/OneDeadKey/kalamine
