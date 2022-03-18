<!--
{% raw %}
-->
# Sommaire📚
- [Definition](#definition)
- [Propriete](#propriete)
- [Exemples](#exemples)
  - [Exemple 1](#exemple-1)
  - [Exemple 2](#exemple-2)

# Reductions de fractions

## Definition 

Réduire une fraction, c'est l'écrire sous la forme la plus simple possible.

Lorsque c'est le cas, on dit que la fraction est irréductible.

1. Pour réduire une fraction, il faut chercher si le terme du haut et celui du bas appartiennent tout deux a la meme table de multiplication (la table doit etre inférieure aux deux termes. Par exemple, la table de `5` est inférieur a `15`).

1. Pour ensuite les décomposer afin de faire apparaitre le plus grand facteur commun possible en bas et en haut. 

1. On peut ensuite retirer ce facteur commun et on repetera cette opération tant que les termes ne sont pas tout les deux des nombres premiers.

Un nombre premier est un nombre qui n'est divisible que par lui-même et par 1.

Par exemple :
- `5` est un nombre premier car il n'est divisible que par lui-même et par 1.
- `15` n'est pas un nombre premier car il est divisible par `3` et par `5` ->  <!-- $15\div3=5\ \ et\ \ 15\div5=3$ --> <img style="" src="https://latex.codecogs.com/svg.image?\small{\color{White}15%5Cdiv3%3D5%5C%20%5C%20et%5C%20%5C%2015%5Cdiv5%3D3">
  
## Propriete
Quand le terme du haut et du bas sont égaux, la fraction est égale a `1`

<!-- $$
\frac{45}{45}=1
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B45%7D%7B45%7D%3D1">

## Exemples

### Exemple 1

Par exemple, pour la fraction : 

<!-- $$
\frac{15}{35}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B15%7D%7B35%7D">

`15` et `35` font tout les deux partie de la table de `5`, et `5` est inférieur à `15` et `35` alors peut les décomposer de la maniere suivante :

<!-- $$
\frac{3{\color{green}\ \times\ 5}}{7{\color{green}\ \times\ 5}}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B3%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%205%7D%7D%7B7%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%205%7D%7D">

On sait que 

<!-- $$
\frac{a{\color{green}\ \times\ c}}{b{\color{green}\ \times\ c}} =  \frac{a}{b}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7Ba%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%20c%7D%7D%7Bb%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%20c%7D%7D%20%3D%20%20%5Cfrac%7Ba%7D%7Bb%7D">

on peut alors dire que 

<!-- $$
\frac{3{\color{green}\ \times}\ \cancel{{\color{green}5}}}{7{\color{green}\ \times}\ \cancel{\color{green}{5}}} = \frac{3}{7}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B3%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%7D%5C%20%5Ccancel%7B%7B%5Ccolor%7Bgreen%7D5%7D%7D%7D%7B7%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%7D%5C%20%5Ccancel%7B%5Ccolor%7Bgreen%7D%7B5%7D%7D%7D%20%3D%20%5Cfrac%7B3%7D%7B7%7D">


`3` et `7` sont des nombres premiers et ne sont pas égaux alors nous avons trouvé la forme irréductible.


### Exemple 2 

<!-- $$
\frac{81}{54}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B81%7D%7B54%7D">

`81` et `54` font tout les deux partie de la table de `9`.

<!-- $$
\frac{9{\color{green}\ \times\ }\cancel{{\color{green}9}}}{6{\color{green}\ \times\ }\cancel{{\color{green}9}}} = \frac{9}{6}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B9%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%20%7D%5Ccancel%7B%7B%5Ccolor%7Bgreen%7D9%7D%7D%7D%7B6%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%20%7D%5Ccancel%7B%7B%5Ccolor%7Bgreen%7D9%7D%7D%7D%20%3D%20%5Cfrac%7B9%7D%7B6%7D">

`9` et `6` ne sont pas des nombres premiers, ils font encore partie d'une table de multiplication commune : la table de `3`.

<!-- $$
\frac{9}{6} = 
\frac{
3{\color{green}\ \times\ }\cancel{{\color{green}3}}
}{
2{\color{green}\ \times\ }\cancel{{\color{green}3}}
}
$$ --> 

<img style="" src="https://latex.codecogs.com/svg.image?{\color{White}%5Cfrac%7B9%7D%7B6%7D%20%3D%20%0A%5Cfrac%7B%0A3%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%20%7D%5Ccancel%7B%7B%5Ccolor%7Bgreen%7D3%7D%7D%0A%7D%7B%0A2%7B%5Ccolor%7Bgreen%7D%5C%20%5Ctimes%5C%20%7D%5Ccancel%7B%7B%5Ccolor%7Bgreen%7D3%7D%7D%0A%7D">

`3` et `2` sont des nombres premiers, nous avons trouvé la forme irréductible.

<!--
---

<p align="right"><a href="../reduction-de-fractions">Section suivante ⏭️</a></p>
-->

---


<p align="right">Cours créé par <a href="https://github.com/SkwalExe/" target="_blank">SkwalExe</a></p>

<!--
{% endraw %}
-->