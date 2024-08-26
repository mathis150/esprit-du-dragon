---
description: Créé le 06/03/2024 par Mathis.
---

# Comment ça marche ?

Le système de version a pour objectif de définir les différentes évolutions du système de jeu, dans le but de permettre à chaque joueur de se sentir le mieux pendant le JDR.

Cela comprend les ennemies, les statistiques, les équipements, les items, etc.

Cela peut aussi toucher l'univers, de manière général, dans lequel les joueurs évoluent.



## Comprendre le système de version :&#x20;

Le système de version s'écrit : Version (Ou V) A.B.C.D

A : Il signifie la version d'un système complet, par exemple, si je viens à refaire de 0 le système, nous passerons de la Version 1 à la Version 2.

B : Cela parle d'une évolution majeure du système de jeu, principalement de nouvelles fonctionnalités ou nouveaux équipements ou ennemies. (Cela peut aussi comprendre le C et le D)

C : Cela parle des évolutions mineures, cela peut être un ajout léger de nouveau contenu, ou bien de rééquilibrage pour permettre au jeu de mieux se passer.

D : Cela correspond à la résolution de bug ou d'incohérence, l'objectif est d'alors, permettre aux joueurs de se sentir plus à l'aise avec les campagnes, les quête, mais aussi le lore.



## À quoi ressemble une note de version ?

Voici un exemple de note de version :

```verilog
// Publication de changelog du XX/XX/XX
[+] Nouveau moyen d'utiliser les enchantements (Simplification et équilibrage des fonctionnalités.
[-] Le système précédent n'existe plus.

[+] De nouvelles armures sont disponible de les magasins.
    - X armures légendaires (X armures de rang SS, X armures de rang A)
    - X armures mythiques (X armures de rang SSS, X armures de rang X)
    - X armures simples (X armures de rang D, X armures de rang B)
[~] Certaines armures ont vue leurs statistiques et enchantements changer.
    - [NERF] L'armure X a vue une baisse de de vitalité. 80HP -> 55HP
    - [BOOST] L'armure X a vue une augmentation de force. 2 de force -> 8 de force | Rang A -> Rang SS | Rang Rare -> Rang Mythique
    
[+] De nouveaux ennemies sont apparus dans le lore.
    - X, [descriptions simple]. Voir dans la catégorie: Bestiaire > Créatures [Type] > X

...
```

<mark style="color:orange;">On peut y voir plusieurs éléments.</mark>

<mark style="color:orange;">Le \[+] correspond à un ajout d'éléments.</mark>

<mark style="color:orange;">Le \[-] correspond à une suppression d'élément.</mark>

<mark style="color:orange;">Le \[\~] correspond à une modification d'un élément existant.</mark>

<mark style="color:orange;">Certains éléments se voient ajouter un listing pour les détailler. Et les éléments spécifiques d'un listing reçoivent \[BOOST] s'ils ont des améliorations et \[NERF] s'ils ont des régressions.</mark>
