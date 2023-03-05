---
{"dg-publish":true,"permalink":"/cours lycée/fonction continue/"}
---

Soient $f$ une fonction définie sur un intervalle $I$ et $a$ un réel appartenant à $I$ ; avec les deux caractéristiques suivantes :
1. $f$ est **continue en $\alpha$** lorsque $f$ admet une limite en $\alpha$ et que cette limite est $f(\alpha)$.
2. $f$ est **continue** sur un intervalle $I$ lorsqu'elle est continue en $\alpha$ pour tout $\alpha∈I$.
{ #f23907}


La *première caractéristique* implique que pour étudier la *continuité d'une fonction* en $a$, on doive (dans R) : calculer la limite de $f$ en $a$ pour $x<a$, et calculer la limite de $f$ en $a$ pour $x>a$ ; et comparer avec $f(a)$. Si $\lim_{x \to a \cap x > a}=\lim_{x \to a \cap x < a}=f(a)$ alors $f$ est **continue** en $a$.


- Toute fonction **dérivable** sur un intervalle $I$ est continue sur $I$.
- Les fonctions de **référence** (polynômes, valeur absolue, exponentielle, racine carrée, etc.) sont [continues](fonction continue#^f23907) sur leur *intervalle de définition*.
- La **somme** et le **produit** de fonctions continues sur un intervalle $I$ sont continues sur *cet intervalle*.
- Si $f$ et $g$ sont continues sur $I$ et si $g$ ne s'annule pas sur $I$, alors $\frac{f}{g}$ est continue sur $I$.

Ces propriétés impliquent lorsqu'elles sont vraies la [continuité](fonction continue) de la fonction sur l'intervalle auxquelles elles font références ; sauf dans ce cas pour **racine carré** qui est *strictement positive*, et si avec une **division** le *quotient* s'annule en $I$.