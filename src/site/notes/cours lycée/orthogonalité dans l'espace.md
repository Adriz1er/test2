---
{"dg-publish":true,"permalink":"/cours lycée/orthogonalité dans l'espace/"}
---

-   **Deux droites sont dites orthogonales** lorsque leurs parallèles respectives passant par un même point sont perpendiculaires.
-   **Deux vecteurs non nuls sont orthogonaux** lorsque les droites dirigées par ces vecteurs sont orthogonales.
-   **Une droite est orthogonale à un plan** lorsqu'elle est orthogonale à toutes les droites de ce plan.
## propriété
Deux droites sont orthogonales si, et seulement si, leurs vecteurs directeurs respectifs sont orthogonaux.
## Propriété
Une droite est orthogonale à un plan si, et seulement si, un vecteur directeur de la droite est orthogonal à une base de ce plan.
## définition
On considère une droite orthogonale à un plan.  
Tout vecteur directeur de cette droite est appelé **vecteur normal au plan**.
## propriété
Une droite est orthogonale à un plan si elle est orthogonale à deux droites sécantes de ce plan.
## Exercice [25p.102-103]
$ABCDEFGH$ est le cube ci-dessous. Les points $I$, $J$, $K$ et $L$ sont les milieux respectifs des côtés $[AB]$, $[EF]$, $[GH]$ et $[CD]$.
![Applications directes|200](https://assets.lls.fr/pages/40796423/MAT.SPE.3.INF09_v1.svg)
Dans chaque cas, déterminer si le plan et la droite données sont orthogonaux. Justifer la réponse.
1. $(DCG)$ et $(IL)$.
2. $(ABF)$ et $(HJ)$.  
3. $(EFC)$ et $(KI)$.
4. $(ABC)$ et $(DK)$.
### mes réponses
1. $(DCG)\bot(IL)$ car $(IL)\bot(DCG)$ (voir [[cours lycée/orthogonalité dans l'espace#Propriété\|orthogonalité dans l'espace#Propriété]])
2. $(ABF)\text{ et }(HJ)$ ne sont par orthogonaux
3. $(EFC)\bot(KI)$, car : 
	1. or $(BG)\bot(FC)$, $(EF)$ et $(FC)$ sont sécants dans $(EFC)$ donc $(BG)\bot(EFC)$
		1. or $(KI)\parallel(GB) \text{ donc }(KI)\bot(EFC)$ (voir [[cours lycée/orthogonalité dans l'espace#propriété\|orthogonalité dans l'espace#propriété]])
4. $(DK)$ n'est pas orthogonal à $(ABC)$

---
[[Orthogonalité et produit scalaire\|Orthogonalité et produit scalaire]]

Soient $\vec{u}$ et $\vec{v}$ deux vecteurs de l'espace. Lorsqu'ils ne sont pas nuls, on définit leur **produit scalaire** par $\vec{u}⋅\vec{v}=∥\vec{u}∥×∥\vec{v}∥×cos(\vec{u};\vec{v})$.  
Lorsque l'un des vecteurs est nul, alors $\vec{u}⋅\vec{v}=0$.
## Propriété
Soient $\vec{u}$ et $\vec{v}$ deux vecteurs non nuls. On pose trois points $O$, $A$ et $B$ tels que $\vec{u}=\overrightarrow{OA}$ et $\vec{v}=\overrightarrow{OB}$. On appelle $H$ le point de $(OA)$ tel que $(BH)⊥(OA)$. Alors :
$$\vec{u}.\vec{v}=\begin{cases}OA \times OH \text{ si }H\in[OA)\\-OA \times OH \text{ sinon}
\end{cases}$$
## propriétés
Soient $\vec{u}$, $\vec{v}$ et $\vec{w}$ trois vecteurs et $\lambda$ un réel quelconque. Le produit scalaire est : 
- symétrique : $\vec{u}.\vec{v}=\vec{v}.\vec{u}$ ;
- *bilinéaire* :
	- linéaire à gauche : $(\vec{u}+\lambda\vec{v}).\vec{w}=\vec{u}.\vec{w}+\lambda \times \vec{v}.\vec{w}$
	- linéaire à droite : $\vec{u}.(\lambda \vec{v}+\vec{w})=\lambda \times \vec{u}.\vec{v}+\vec{u}.\vec{w}$
## propriétés
Soient $\vec{u}$ et $\vec{v}$ deux vecteurs. On a alors des formules de polarisation :
$$\vec{u}.\vec{v}=\frac{1}{2}[\mid\vec{u}\mid^{2}+\mid\vec{v}\mid^{2}-\mid\vec{u}-\vec{v}\mid^{2}]$$
$$\text{et }\vec{u}.\vec{v}=\frac{1}{2}[\mid\vec{u}+\vec{v}\mid^{2}-\mid\vec{u}^{2}\mid-\mid\vec{v}\mid^{2}]$$

---
[[Orthogonalité et produit scalaire\|Orthogonalité et produit scalaire]]

---
dg-publish: true
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
1. $(AD)$ et $(Al)$ ne sont pas orthogonales (voir [[cours lycée/orthogonalité dans l'espace\|orthogonalité dans l'espace]]), et
	1. $\overrightarrow{AD}.\overrightarrow{AL}={AD}\times{AD}$ (puisque [[contribution à mon potager/formule du projeté orthogonal\|formule du projeté orthogonal]] et [[Commun 2/produit scalaire dans un repère\|produit scalaire dans un repère]])
	2. or $\overrightarrow{AD}.\overrightarrow{AL}=AD.AL.\cos(\overrightarrow{AD};\overrightarrow{AL})$ (voir [[cours lycée/orthogonalité dans l'espace\|orthogonalité dans l'espace]])
	3. d'après le théorème de pythagore dans $ADL$ rectangle en $D$ : $$AL^{2}=AD^{2}+DL^{2}=4^{2}+2^{2}=20$$ $$\iff AL=\sqrt{ 20 }=2\sqrt{ 5 }$$ Ainsi, $\cos(\overrightarrow{AI};\overrightarrow{AL})=\frac{16}{4 \times 2\sqrt{ 5 }}\approx 26,6°$
2. $\overrightarrow{AI}.\overrightarrow{JH}=\overrightarrow{AI}.\overrightarrow{ID}=(\overrightarrow{IB}.\overrightarrow{ID})$, or d'après [[cours lycée/orthogonalité dans l'espace#Propriété\|orthogonalité dans l'espace#Propriété]] c'est égale à $-IB \times IA=-4$
3. $\overrightarrow{CA}.\overrightarrow{CF}$, $=(\overrightarrow{CB}+\overrightarrow{BA}).(\overrightarrow{CG}+\overrightarrow{GF})=0+\overrightarrow{CB}.\overrightarrow{GF}+0+0$ (car $\overrightarrow{CB}\bot\overrightarrow{CG}$, $\overrightarrow{BA}\bot\overrightarrow{GF}$ et $\overrightarrow{BA}\bot\overrightarrow{CG}$) $= 4\times 4=16$ donc $\overrightarrow{CA}$ et $\overrightarrow{CF}$ ne sont orthogonaux
4. $\overrightarrow{EK}.\overrightarrow{EL}=(\overrightarrow{EH}+\overrightarrow{HK}).(\overrightarrow{EH}+\overrightarrow{HD}+\overrightarrow{DL})$, on distribue : $$\overrightarrow{EH}.\overrightarrow{EH}+\overrightarrow{EH}.\overrightarrow{HD}+\overrightarrow{EH}.\overrightarrow{DL}+\overrightarrow{HK}.\overrightarrow{EH}+\overrightarrow{HK}.\overrightarrow{HD}+\overrightarrow{HK}.\overrightarrow{DL}$$ $$EH.EH+0+0+0+0+HK.DL=4\times 4+2 \times 2=20$$
## exercice 30 p.102
Dans chacun des cas suivants, déterminer si les vecteurs $\vec{u}$ et $\vec{v}$ sont orthogonaux.
1. $\vec{u}\begin{pmatrix}1\\1\\-2\end{pmatrix}\text{ et }\vec{v}\begin{pmatrix}0\\4\\2\end{pmatrix}$
2. $\vec{u}\begin{pmatrix}11\\2\\ \frac{3}{2}\end{pmatrix}\text{ et }\vec{v}\begin{pmatrix}4\\-25\\4\end{pmatrix}$
3. $\vec{u}\begin{pmatrix}1\\3\\-4\end{pmatrix} \text{ et }\vec{v}\begin{pmatrix}2\\-1\\ -\frac{1}{4}\end{pmatrix}$
4. $\vec{u}\begin{pmatrix}1\\ \sqrt{ 3 }\\ -\sqrt{ 2 }\end{pmatrix}\text{ et }\vec{v}\begin{pmatrix}\sqrt{ 3 }\\-1\\\sqrt{ 8 }\end{pmatrix}$
### mes réponses
1. $\vec{u}.\vec{v}=1 \times 0+1 \times 4+ -2 \times 2=0$ donc $\vec{u}\bot\vec{v}$
2. $\vec{u}.\vec{v}=11 \times 4+2 \times -25+6=0$ donc $\vec{u}\bot\vec{v}$
3. $\vec{u}.\vec{v}=2-3+1=0$ donc $\vec{u}\bot\vec{v}$
4. $\vec{u}.\vec{v}=1 \times \sqrt{ 3 }-\sqrt{ 3 }-\sqrt{ 2 } \times \sqrt{ 8 }=-\sqrt{ 2 } \times \sqrt{ 8 }$
 
---
[[Orthogonalité et produit scalaire\|Orthogonalité et produit scalaire]]