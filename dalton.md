---
marp: true
theme: gaia-orange
size: 16:9
paginate: true
footer: Sébastien VERBOIS - Novembre 2026
---

<!--
_paginate: skip
_class: lead cover
-->

![w:180](images/diving-mask.png)

# Loi de Dalton et toxicité des gaz

### Sébastien VERBOIS · Novembre 2026

---

# Pression dans une bouteille

- La pression d’un gaz dans une bouteille est due aux chocs des molécules du gaz contre les parois de la bouteille.
- Ces molécules sont en mouvement permanent et désordonné.
- Plus il y a de chocs (ou plus ils sont violents), plus la pression augmente.

---

# Fraction

> La **fraction** (F) d'un gaz dans un mélange est le nombre de ses molécules divisé par le nombre total de molécules du mélange.

<br />

### F gaz = N gaz ÷ N total

<br />

### % gaz = F gaz × 100

---

# Air

| Gaz | Fraction | % |
|:---|:---:|:---:|
| Azote (N₂) | 0,7808 | 78,08 % |
| Oxygène (O₂) | 0,2095 | 20,95 % |
| Argon (Ar) | 0,0093 | 0,93 % |
| Gaz carbonique (CO₂) | 0,0004 | 0,04 % |
| Autres gaz | traces | traces |

## Simplification pour la plongée

### FN₂ = 0,79 (79 %) et FO₂ = 0,21 (21 %)

---

# Pression partielle

- Dans un mélange, chaque gaz participe aux chocs contre les parois.
- Chaque gaz « fait sa part » de la pression.
- Cette part de pression s'appelle la **pression partielle** (Pp) du gaz.

> La **pression partielle** d’un gaz composant un mélange est la pression qu’exercerait ce gaz s’il occupait seul le volume total.

---

# Loi de Dalton

> La **pression absolue** d’un mélange gazeux est égale à la **somme des pressions partielles** de chacun des gaz qui le composent.

### Pabs = Pp gaz 1 + Pp gaz 2 + … + Pp gaz n

**Exemple** : pour l'air, Pabs = PpN₂ + PpO₂ + PpAr + PpCO₂

---

# Calcul de la pression partielle

Conséquence de la loi de Dalton : la pression partielle d'un gaz est égale à sa **fraction** dans le mélange multipliée par la **pression absolue**.

### Pp gaz = F gaz × Pabs

**Exemple** : l'oxygène représente 21 % des molécules de l'air → il fait 21 % de la pression → FO₂ = 0,21 → PpO₂ = 0,21 × Pabs

---

# Et en profondeur ?

| Profondeur | Pabs | PpO₂ | PpN₂ |
|:---:|:---:|:---:|:---:|
| 0 m | 1 bar | 0,21 bar | 0,79 bar |
| 10 m | 2 bar | 0,42 bar | 1,58 bar |
| 20 m | 3 bar | 0,63 bar | 2,37 bar |
| 30 m | 4 bar | 0,84 bar | 3,16 bar |
| 40 m | 5 bar | 1,05 bar | 3,95 bar |

La **fraction** ne change pas, la **pression partielle** augmente avec la profondeur.

---

<!-- _class: fs-small -->

# Exercices : loi de Dalton

1. Quelles sont la PpO₂ et la PpN₂ à 25 m à l'air ?
2. À quelle profondeur la PpN₂ atteint-elle 3,2 bar à l'air ?
3. Quelle est la profondeur maximale à l'air pour une PpO₂ de 1,6 bar ?

---

<!-- _class: fs-small -->

# Solution 1

On cherche la pression partielle :

### Pp = F × Pabs

- À 25 m : Pabs = 1 + 2,5 = 3,5 bar
- PpO₂ = 0,21 × 3,5 = **0,735 bar**
- PpN₂ = 0,79 × 3,5 = **2,765 bar**

---

<!-- _class: fs-small -->

# Solution 2

On cherche la pression absolue :

### Pabs = Pp ÷ F

- Pabs = 3,2 ÷ 0,79 ≈ 4,05 bar
- Profondeur ≈ (4,05 - 1) × 10 ≈ **30 m**

---

<!-- _class: fs-small -->

# Solution 3

On cherche la pression absolue :

### Pabs = Pp ÷ F

- Pabs = 1,6 ÷ 0,21 ≈ 7,6 bar
- Profondeur ≈ (7,6 - 1) × 10 ≈ **66 m**

---

# Toxicité des gaz

> Le corps réagit à la **pression partielle** du gaz, pas à sa fraction.

> Tout gaz devient toxique au-delà d'une certaine **pression partielle**.

- O₂ : hyperoxie
- N₂ : narcose
- CO₂ : essoufflement
- CO : air contaminé

---

# O₂ : hyperoxie

- PpO₂ > **1,6 bar** : effet **Paul Bert** (système nerveux)
  - convulsions, parfois sans signe avant-coureur → risque de noyade
  - à l'air, 1,6 bar est atteint vers **66 m**
- PpO₂ > **0,5 bar** pendant des heures : effet **Lorrain Smith** (poumons)
  - toux sèche, difficultés respiratoires
  - risque négligeable en plongée loisir

---

<!-- _class: fs-small -->

# O₂ : signes et conduite à tenir

- Signes de l'effet Paul Bert : **CENTAVIVO**
  - **C**onvulsions, **E**uphorie, **N**ausées, **T**remblements (lèvres, visage), **A**nxiété, **V**ision tunnel, **I**rritabilité, **V**ertiges, **O**reilles (bourdonnements)
- Au moindre signe : remonter à vitesse normale et terminer la plongée
- En cas de convulsions :
  - **ne pas remonter pendant la crise** (risque de surpression pulmonaire)
  - maintenir l'embout en bouche et la tête en arrière
  - remonter une fois la crise passée
- En surface : oxygène, alerte 112

---

# N₂ : narcose

- Ivresse des profondeurs, due à la **PpN₂**
- Premiers signes vers PpN₂ ≈ **3,2 bar** (≈ 30 m à l'air)
- Seuil conventionnel : PpN₂ ≈ **6,4 bar** (≈ 70 m à l'air) : personne n'y échappe
- Sensibilité variable d'un plongeur à l'autre et d'un jour à l'autre
- Facteurs aggravants : froid, stress, fatigue, alcool, médicaments, effort, CO₂

---

<!-- _class: fs-small -->

# N₂ : signes et conduite à tenir

- Signes psychiques : euphorie ou angoisse, idées fixes, excès de confiance, perte de concentration
- Signes physiques : gestes maladroits, réflexes ralentis, mauvaise lecture des instruments
- Le plongeur narcosé **ne s'en rend pas compte** : surveiller son binôme
- Conduite à tenir : **remonter de quelques mètres**, les signes disparaissent
- On peut poursuivre la plongée moins profond, sans redescendre

---

<!-- _class: fs-small -->

# CO₂ : essoufflement

- Le CO₂ est produit par notre corps : il doit être évacué par l'expiration
- S'il n'est pas assez évacué, il s'accumule : c'est l'**essoufflement**
- Causes liées au plongeur : effort, palmage trop intense, stress, froid, lestage inadapté, respiration superficielle
- Causes liées au matériel : détendeur qui respire mal, tuba inadapté
- En profondeur, l'air est plus dense : respirer demande plus d'effort

---

<!-- _class: fs-small -->

# CO₂ : signes et conduite à tenir

- Signes : respiration rapide et superficielle, sensation de manquer d'air, maux de tête, angoisse
- L'essoufflement est **souvent à l'origine d'un autre accident** (panique, remontée rapide) et il **aggrave la narcose**
- Conduite à tenir : arrêter l'effort, prévenir le binôme, expirer à fond, se calmer, remonter lentement
- Prévention : rester calme, respirer lentement et profondément, lestage adapté, détendeur entretenu

---

<!-- _class: fs-small -->

# CO : air contaminé

- Monoxyde de carbone : gaz toxique, inodore, incolore, sans goût
- Produit par une combustion incomplète (moteur, chauffage)
- Contamine la bouteille si la prise d'air du compresseur est près d'un échappement
- Se fixe sur l'hémoglobine **300 fois plus** facilement que l'O₂ → le sang ne transporte plus l'oxygène
- Une trace sans effet en surface devient dangereuse en profondeur : la PpCO est **multipliée par la Pabs**

---

# CO : signes et conduite à tenir

- Signes : maux de tête, vertiges, nausées, faiblesse, perte de connaissance
- Lèvres et joues **rouge cerise** (et non bleues)
- Conduite à tenir : sortir de l'eau, oxygène, alerte 112, caisson selon la gravité
- Prévention : gonfler dans un centre sérieux, prise d'air loin de tout échappement

---

# Résumé des seuils

| Gaz | Seuil | Effet |
|:---|:---|:---|
| O₂ | PpO₂ > 1,6 bar | Hyperoxie : effet Paul Bert (convulsions) |
| O₂ | PpO₂ > 0,5 bar (longtemps) | Hyperoxie : effet Lorrain Smith (poumons) |
| N₂ | PpN₂ > 3,2 bar | Narcose : premiers signes |
| N₂ | PpN₂ > 6,4 bar | Narcose : personne n'y échappe |
| CO₂ | Accumulation | Essoufflement |
| CO | Trace × Pabs | Intoxication |

---

<!-- _class: fs-small -->

# Exercices : toxicité des gaz

4. À 35 m à l'air, ton binôme ne répond plus à tes signes et fixe son manomètre sans réagir. Que se passe-t-il ? Que fais-tu ?
5. Après une plongée à 40 m, ton binôme a mal à la tête, des nausées et les lèvres rouges. Que se passe-t-il ? Que fais-tu ?
6. Lors d'une plongée profonde, ton binôme a des tremblements des lèvres puis des convulsions. Que fais-tu ?

---

<!-- _class: fs-small -->

# Solution 4

- **Narcose** probable : à 35 m, PpN₂ = 0,79 × 4,5 ≈ 3,6 bar, au-delà de 3,2 bar
- Attirer son attention et le prendre en charge
- Remonter ensemble de quelques mètres jusqu'à disparition des signes
- Poursuivre la plongée moins profond, sans redescendre

---

<!-- _class: fs-small -->

# Solution 5

- **Intoxication au CO** probable : air contaminé
- À 40 m, Pabs = 5 bar → la PpCO est **5 fois plus élevée** qu'en surface
- Oxygène, alerte 112, caisson selon la gravité
- Mettre la bouteille de côté et prévenir le centre de gonflage

---

<!-- _class: fs-small -->

# Solution 6

- **Hyperoxie** probable : effet Paul Bert
- **Ne pas remonter pendant la crise** : risque de surpression pulmonaire
- Maintenir l'embout en bouche et la tête en arrière
- Remonter une fois la crise passée
- En surface : oxygène, alerte 112

---

<!--
_paginate: skip
_class: lead
-->

# Questions ?
