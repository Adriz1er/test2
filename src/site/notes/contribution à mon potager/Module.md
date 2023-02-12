---
{"dg-publish":true,"permalink":"/contribution à mon potager/Module/"}
---

Rappel : 
<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">



#🌱/cours [[cours_maths_expert\|cours_maths_expert]] [[algèbre\|algèbre]]

---
La ==forme algébrique==, d'un [[nombre complexe\|nombre complexe]], est donc *composée* de **deux parties** (*réelle, imaginaire*), et doit donc *pouvoir s'écrire* avec {**deux** nombres réels}.
^1663044746419
- exemple ; avec $z$ étant un nombre complexe, avec $a$ comme *partie réelle*, avec $i \times b$ comme *partie imaginaire* ($b \in R$): ==$ z=a+ib $== A noter que :
^1663044746425
	- si $a=0$, alors $z=i$ donc $z$ est un ***imaginaire pur***
	- si $b=0$, alors $z=a$, donc $z$ est un **réel**
# Propriété
(Pour tous $z \in C$ et $z' \in C$) : $
z=z' \iff \left\{
    \begin{array}{ll}
        Re(z)=Re(z') \\
        Im(z)=Im(z')
    \end{array}
\right.
$


</div></div>

Soit $z\in C$, le point $M$ représentant du plan représentant $z$ est appelé **l'image de $z$**.
On dit que $z$ est l'**affixe** du point $M$ (ou du vecteur $\overrightarrow{OM}$).
Le **module** de $z$, noté $\mid z\mid$ est la *distance* $OM$.
## Propriété
Si $z=0$ alors $\mid z\mid=0$
Sinon $$\mid z\mid=\sqrt{ a^{2}+b^{2} }$$
### Exemple : 
- $z=1+2i$

$$z=\sqrt{ 1^{2}+2^{2} }$$
$$\mid z\mid=\sqrt{ 1^{2}+2^{2} }=\sqrt{ 1+4 }=\sqrt{ 5 }$$
- $w=-3$
	- $$\mid w\mid=\sqrt{ (-3)^{2}+0^{2} }=\sqrt{ 0 }=3$$
### ex 63 p.69
1. Calculez $z \times \bar{z}$
	1. en déduire l'expression de $\mid z\mid^{2}$
2. Démontrer que $\mid \bar{z}\mid=\mid z\mid$ puis $-\mid z\mid$
	1. puis $\mid-z\mid=\mid z\mid$
#### mes réponses
1. $$(a+ib)(a-ib)$$ $$=a^{2}-aib+aib-(ib)^{2}$$ $$=a^{2}+b^{2}$$
	1. donc $$z \times z=a^{2}+b^{2}=\mid z\mid^{2}$$
2. $$|\bar{z}|=\mid a-ib|$$ $$=\sqrt{ a^{2} +(-b)^{2}}$$ $$\sqrt{ a^{2}+b^{2} }$$ $$\mid{z}\mid$$
	1. $$-\mid z\mid=\mid-(a+ib)\mid=\mid-a-ib\mid$$ $$\sqrt{ (-a)^{2}+(-b)^{2} }$$
3. $$z \times z^{'}=$$ $$ −z = (−a)
2
+ (−b)
2
= a
2 + b2 = z$$
## Propriété
$\forall z, z^{'}\in C$, on a :
$$\mid z\mid^{2}=z \times \bar{{z}}$$
$$\bar{\mid}z\mid=\mid z\mid$$
	$$\mid-z\mid=\mid z\mid$$
	$$\mid z \times z^{'}\mid=\mid z\mid \times \mid z^{'}\mid$$
	$$\mid\frac{z}{z^{'}}\mid=\mid \frac{z\mid}{\mid z\mid} \text{si }z^{'}\neq 0$$
	$$\mid(z^{n})\mid=(\mid z\mid)^{n}$$
### inégalité triangulaire
$$\mid z+z^{'}\mid\le\mid z\mid+\mid z^{'}\mid$$

---
[[nombres complexes et géométrie\|nombres complexes et géométrie]]