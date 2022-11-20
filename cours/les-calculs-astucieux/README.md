<!--
{% raw %}
-->
# Sommaire📚

- [Astuce 1: Technique de simplification](#astuce-1-technique-de-simplification)
  - [Description](#description)
  - [Exemple](#exemple)
- [Astuce 2: Technique de regroupement](#astuce-2-technique-de-regroupement)
  - [Description](#description-1)
  - [Exemple](#exemple-1)

# Les calculs astucieux💡

Les calculs astucieux sont des techniques de calculs qui sont utilisées pour effectuer des calculs complexes plus rapidement et plus facilement.

## Astuce 1: Technique de simplification

### Description

Cette technique consiste a rechercher des quantités opposées afin de faire apparaitre des zero, on cherche donc a annuler plusieurs termes entre eux.

### Exemple
<!-- $$
\begin{align*}
A &= 5 + 8 - 7 + 14 - 5 - 8 + 7
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AA%20%26%3D%205%20%2B%208%20-%207%20%2B%2014%20-%205%20-%208%20%2B%207%0A%5Cend%7Balign*%7D" />

Nous pouvons apercevoir plusieurs termes qui s'opposent 

<!-- $$
\begin{align*}
A &= {\color{green}5}{\color{cyan}\ +\ 8}{\color{Orchid}\ -\ 7}+14{\color{green}\ -\ 5}{\color{cyan}\ -\ 8}{\color{Orchid}\ +\ 7}
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AA%20%26%3D%20%7B%5Ccolor%7Bgreen%7D5%7D%7B%5Ccolor%7Bcyan%7D%5C%20%2B%5C%208%7D%7B%5Ccolor%7BOrchid%7D%5C%20-%5C%207%7D%2B14%7B%5Ccolor%7Bgreen%7D%5C%20-%5C%205%7D%7B%5Ccolor%7Bcyan%7D%5C%20-%5C%208%7D%7B%5Ccolor%7BOrchid%7D%5C%20%2B%5C%207%7D%0A%5Cend%7Balign*%7D" />

Ces termes peuvent donc etre supprimer, ce qui nous laisse <!-- $+14$ --> <img style="" src="https://latex.codecogs.com/svg.image?\small{\color{White}%2B14">

Parfois, il peut arriver qu'aucun termes ne s'opposent, dans ce cas, il reste possible d'en **créer**.

<!-- $$
\begin{align*}
B &= 8-26+{\color{green}12+14}
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AB%20%26%3D%208-26%2B%7B%5Ccolor%7Bgreen%7D12%2B14%7D%0A%5Cend%7Balign*%7D" />

Ici, on remarque que `12+14` est égale a `26`

<!-- $$
\begin{align*}
B &= 8-26+{\color{green}26}
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AB%20%26%3D%208-26%2B%7B%5Ccolor%7Bgreen%7D26%7D%0A%5Cend%7Balign*%7D" />

Ce qui nous permet de retirer les deux `26` car ils s'annulent et nous donne comme résultat final : <!-- $8$ --> <img style="" src="https://latex.codecogs.com/svg.image?\small{\color{White}8">

## Astuce 2: Technique de regroupement

### Description

Cette technique consiste a regrouper les nombres `ronds` tel que `10, 20, 40`, on cherche donc des nombres avec lesquels les operations sont plus faciles a mener.

### Exemple

<!-- $$
\begin{align*}
C &= {\color{green}20}-26{\color{green}\ +\ 10}+15
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AC%20%26%3D%20%7B%5Ccolor%7Bgreen%7D20%7D-26%7B%5Ccolor%7Bgreen%7D%5C%20%2B%5C%2010%7D%2B15%0A%5Cend%7Balign*%7D" /> 

On peut apercevoir deux nombres ronds, nous les calculons en premier, ce qui simplifie le calcul.

<!-- $$
\begin{align*}
C &= {\color{green}30}-26+15
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AC%20%26%3D%20%7B%5Ccolor%7Bgreen%7D30%7D-26%2B15%0A%5Cend%7Balign*%7D" /> 

Il est également possible de **créer** des nombres ronds : 

<!-- $$
\begin{align*}
D &= {\color{green}1}{\color{cyan}\ +\ 4}{\color{green}\ +\ 9}{\color{cyan}\ +\ 6}-10\\
D &= {\color{green}10}{\color{cyan}\ +\ 10}-10
\end{align*}
$$ -->
<img src="https://latex.codecogs.com/svg.image?\color{white}%5Cbegin%7Balign*%7D%0AD%20%26%3D%20%7B%5Ccolor%7Bgreen%7D1%7D%7B%5Ccolor%7Bcyan%7D%5C%20%2B%5C%204%7D%7B%5Ccolor%7Bgreen%7D%5C%20%2B%5C%209%7D%7B%5Ccolor%7Bcyan%7D%5C%20%2B%5C%206%7D-10%5C%5C%0AD%20%26%3D%20%7B%5Ccolor%7Bgreen%7D10%7D%7B%5Ccolor%7Bcyan%7D%5C%20%2B%5C%2010%7D-10%0A%5Cend%7Balign*%7D" /> 

---

<p align="right"><a href="https://skwalexe.github.io/les-maths/">Accueil 🏠</a> - <a href="../fractions-egales-entre-elles">Section suivante ⏭️</a></p>

---

<p align="right">Cours créé par <a href="https://github.com/SkwalExe/" target="_blank">SkwalExe</a></p>

<!--
{% endraw %}
-->