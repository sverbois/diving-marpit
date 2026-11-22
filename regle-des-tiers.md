# Règle des tiers et turn pressure

## Règle des tiers

- 1/3 : pour l'aller
- 1/3 : pour le retour
- 1/3 : pour les autres = le plus grand tiers de la palanquée

## Turn pressure

La *turn pressure* est la pression à laquelle on fait demi-tour.

Pour chaque plongeur i (i = 1..n) :

- VBi = volume de la bouteille du plongeur i (L)
- PBi = pression de la bouteille du plongeur i (bar)
- Vi = volume de gaz du plongeur i (L) = VBi × PBi
- Vsec = volume de sécurité (L)
- TPi = *turn pressure* du plongeur i (bar)

```
Vsec = max(V1 / 3, V2 / 3, …, Vn / 3)
```

```
TPi = (Vsec + (Vi − Vsec) / 2) / VBi
    = (Vi + Vsec) / (2 × VBi)
```

## Règle

La palanquée fait demi-tour dès que le **premier** plongeur atteint sa propre TPi.

## Remarques

- La plongée n'est faisable que si Vi > Vsec pour tout i : sinon, la bouteille du plongeur est trop petite pour ce groupe.
- La formule considère que les plongeurs consomment la même chose au retour qu'à l'aller.
- TPi = 2/3 de PBi pour le plus gros volume de gaz, plus de 2/3 pour les autres.

## Exemple à 3 plongeurs

- Kathy     : 10 L à 210 bar → Vkat = 2100 L
- Sébastien : 14 L à 200 bar → Vseb = 2800 L
- Jonas     : 15 L à 190 bar → Vjon = 2850 L

Vsec = max(2100 / 3, 2800 / 3, 2850 / 3) = max(700 ; 933,3 ; 950) = 950 L

- TPkat = (2100 + 950) / (2 × 10) = 152,5 bar
- TPseb = (2800 + 950) / (2 × 14) = 133,9 bar
- TPjon = (2850 + 950) / (2 × 15) = 126,7 bar
