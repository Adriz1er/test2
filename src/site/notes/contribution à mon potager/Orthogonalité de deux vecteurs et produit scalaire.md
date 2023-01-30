---
{"dg-publish":true,"permalink":"/contribution à mon potager/Orthogonalité de deux vecteurs et produit scalaire/"}
---

Deux vecteurs $\vec{u}$ et $\vec{v}$ sont orthogonaux si, et seulement si, leur produit scalaire est nul.
## Exercice [28 p.102-103](https://premium.lelivrescolaire.fr/page/11915862)
$ABCDEFGH$ est le cube ci-dessous. Les points $I$, $J$, $K$ et $L$ sont les milieux respectifs des côtés $[AB]$, $[EF]$, $[GH]$ et $[CD]$.
![Applications directes|200](https://assets.lls.fr/pages/40796423/MAT.SPE.3.INF09_v1.svg)
On se place dans le cube utilisé dans les exercices **24** à **26** d'arête 4. Calculer chaque produit scalaire puis une valeur approchée d'une mesure de l'angle formé par les deux vecteurs donnés.
1. $\overrightarrow{AD}⋅\overrightarrow{AL}$
2. $\overrightarrow{AI}⋅\overrightarrow{JH}$
3. $\overrightarrow{CA}⋅\overrightarrow{CF}$
4. $\overrightarrow{EK}⋅\overrightarrow{EL}$
### mes réponses
1. $(AD)$ et $(Al)$ ne sont pas orthogonales (voir [[contribution à mon potager/orthogonalité dans l'espace\|orthogonalité dans l'espace]]), et
	1. $\overrightarrow{AD}.\overrightarrow{AL}={AD}\times{AD}$ (puisque [[contribution à mon potager/formule du projeté orthogonal\|formule du projeté orthogonal]] et [[Commun 2/produit scalaire dans un repère\|produit scalaire dans un repère]])
	2. or $\overrightarrow{AD}.\overrightarrow{AL}=AD.AL.\cos(\overrightarrow{AD};\overrightarrow{AL})$ (voir [[contribution à mon potager/le produit scalaire dans l'espace\|le produit scalaire dans l'espace]])
	3. d'après le théorème de pythagore dans $ADL$ rectangle en $D$ : $$AL^{2}=AD^{2}+DL^{2}=4^{2}+2^{2}=20$$ $$\iff AL=\sqrt{ 20 }=2\sqrt{ 5 }$$ Ainsi, $\cos(\overrightarrow{AI};\overrightarrow{AL})=\frac{16}{4 \times 2\sqrt{ 5 }}\approx 26,6°$
2. $\overrightarrow{AI}.\overrightarrow{JH}=\overrightarrow{AI}.\overrightarrow{ID}=(\overrightarrow{IB}.\overrightarrow{ID})$, or d'après [[contribution à mon potager/le produit scalaire dans l'espace#Propriété\|le produit scalaire dans l'espace#Propriété]] c'est égale à $-IB \times IA=-4$
3. $\overrightarrow{CA}.\overrightarrow{CF}$, $=(\overrightarrow{CB}+\overrightarrow{BA}).(\overrightarrow{CG}+\overrightarrow{GF})=0+\overrightarrow{CB}.\overrightarrow{GF}+0+0$ (car $\overrightarrow{CB}\bot\overrightarrow{CG}$, $\overrightarrow{BA}\bot\overrightarrow{GF}$ et $\overrightarrow{BA}\bot\overrightarrow{CG}$) $= 4\times 4=16$ donc $\overrightarrow{CA}$ et $\overrightarrow{CF}$ ne sont orthogonaux
4. $\overrightarrow{EK}.\overrightarrow{EL}=(\overrightarrow{EH}+\overrightarrow{HK}).(\overrightarrow{EH}+\overrightarrow{HD}+\overrightarrow{DL})$, on distribue : $$\overrightarrow{EH}.\overrightarrow{EH}+\overrightarrow{EH}.\overrightarrow{HD}+\overrightarrow{EH}.\overrightarrow{DL}+\overrightarrow{HK}.\overrightarrow{EH}+\overrightarrow{HK}.\overrightarrow{HD}+\overrightarrow{HK}.\overrightarrow{DL}$$ $$EH.EH+$$
## exercice 30 p.102
Dans chacun des cas suivants, déterminer si les vecteurs $\vec{u}$ et $\vec{v}$ sont orthogonaux.
1. $\vec{u}\begin{pmatrix}1\\1\\-2\end{pmatrix}\text{ et }\vec{v}\begin{pmatrix}0\\4\\2\end{pmatrix}$
2. $\vec{u}\begin{pmatrix}11\\2\\ \frac{3}{2}\end{pmatrix}\text{ et }\vec{v}\begin{pmatrix}4\\-25\\4\end{pmatrix}$
3. $\vec{u}\begin{pmatrix}1\\3\\-4\end{pmatrix} \text{ et }\vec{v}\begin{pmatrix}2\\-1\\ -\frac{1}{4}\end{pmatrix}$
4. $\vec{u}\begin{pmatrix}1\\ \sqrt{ 3 }\\ -\sqrt{ 2 }\end{pmatrix}\text{ et }\vec{v}\begin{pmatrix}\sqrt{ 3 }\\-1\\\sqrt{ 8 }\end{pmatrix}$
### mes réponses
1. $\vec{u}.\vec{v}=1 \times 0+1 \times 4+ -2 \times 2=0$
2. $\vec{u}.\vec{v}=11 \times 4+2 \times -25+6=0$ donc $\vec{u}\bot\vec{v}$
 
---
[[Orthogonalité et produit scalaire\|Orthogonalité et produit scalaire]]