---
{"dg-publish":true,"permalink":"/contribution-a-mon-potager/suite-geometrique/"}
---

Une suite $(v_{n})$ est dite **géométrique** lorsqu'il existe un nombre réel non nul $q$ tel que, pour tout entier naturel $n$, $v_{n+1}=q \times v_{n}$. 
Le nombre réel $q$ est **la raison** de la suite ($v_{n}$).

Exemple : une [[contribution à mon potager/suite géométrique\|suite géométrique]] de raison $\frac{1}{2}$ et de premier terme $v_{0}=1$. On peut en déduire que : $$v_{n+1}=\frac{1}{2}v_{n}$$et qu'ainsi : $v_{0}=1$, $v_{1}=\frac{1}{2}$, $v_{2}=\frac{1}{4}$, $\dots$
## Propriété

<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




### démonstration
1. Cas où $n\ge p$ : de $v_{p}$ à $v_{n}$, on multiplie $n-p$ fois la raison donc on a $v_{n}=v_{p}\times q^{n-p}$.
2. Cas où $n\le p$ : avec la formule précédente, on peut écrire $v_{p}=v_{n}\times q^{p-n}$ d'où $v_{n}=\frac{v_{p}}{q^{p-n}}=v_{p}\times q^{n-p}$.
# Propriété
Si $(v_{n})$ est une [[contribution à mon potager/suite géométrique\|suite géométrique]] de raison non nulle $q$ alors, pour tous entiers naturels $n$ et $p$, $v_{n}=v_{p}\times q^{n-p}$
En particulier, $v_{n}=v_{0}\times q^{n}$. ^8a6d91

---
[[contribution à mon potager/publiée ou presque/mathématiques\|mathématiques]]

</div></div>

### méthode
Pour montrer qu'une suite est géométrique, on peut :
utiliser la définition du cours, ce qui permet :
- calculer $v_{n+1}$ ; l'exprimer en fonction de $v_{n}$, ce qui permet de déterminer le réel $q$ tel que $v_{n+1}=qv_{n}$.

---
#🌲 [[contribution à mon potager/publiée ou presque/mathématiques\|mathématiques]]