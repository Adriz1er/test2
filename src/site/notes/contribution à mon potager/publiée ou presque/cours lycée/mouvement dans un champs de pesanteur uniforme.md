---
{"dg-publish":true,"permalink":"/contribution à mon potager/publiée ou presque/cours lycée/mouvement dans un champs de pesanteur uniforme/"}
---

# position du problème
une masse $m$, modélisée par son centre de masse $M$, soumis à son poids $\vec{P}$ car on néglige toute action de l'air. Un tel système est dit **en chute libre**.
On considère que le mouvement se fait dans une zone suffisamment réduite pour considérer le champs de pesanteur $\vec{g}$ **uniforme**.
L'étude est réalisée dans un *référentiel galiléen*^[[[équilibre d'un système#référentiel galiléen\|[équilibre d'un système#référentiel galiléen]]].
Le système est lancé avec une vitesse initiale $\vec{v}_{0}$.
On cherche à déterminer son mouvement ultérieur.

Dans le cadre du cours, on choisit un repère dont l'origine est $O$ : la **position initiale** de $M$.
Les vecteurs unitaires $\vec{i}$, $\vec{j}$ et $\vec{k}$ sont définis ainsi : 
- le vecteur $\vec{j}$ est vertical *vers le haut* (et donc $\vec{g}=-g\vec{i}$)
- le vecteur $\vec{i}$ est horizontal, tel que le vecteur vitesse initiale $\vec{v}_{0}$ soit dans le plan $(\vec{i};\vec{j})$ et la coordonnée sur $\vec{i}$ de $\vec{v}_{0}$ soit positive
- le vecteur $\vec{k}$ est perpendiculaire à $\vec{i}$ et à $\vec{j}$.

Le plan $(O;\vec{i};\vec{j})$ est nommé **plan de tir**.
On note $\alpha$ l'angle formé par $\vec{v}_{0}$ au dessus de l'horizontale. 
Le vecteur vitesse initiale a donc pour coordonnées : 
$$
\begin{cases}
v_{0x}=v_{0}\cos\alpha \\
v_{0y}=v_{0}\sin\alpha \\
v_{0z}=0
\end{cases}
$$
## application de la deuxième loi de Newton
Le système n'étant soumis qu'à son poids $\vec{P}=m\vec{g}$, la deuxième loi de Newton s'écrit $m \vec{a}(t)=\vec{P}$, où $\vec{a}(t)$ est l'accélération du point $M$.
Cela s'écrit donc aussi $m\vec{a}(t)=m \vec{g}$, c'est-à-dire $\vec{a}(t)= \vec{g}$ car $m \neq 0$.
L'accélération^[[[vecteur position, vitesse et accélération#vecteur accélération\|[vecteur position, vitesse et accélération#vecteur accélération]]] est égale au vecteur champs de pesanteur : $\vec{a}(t)=\vec{g}$. Elle est donc constante : le mouvement est **uniformément accéléré**.
{ #655475}



Comme 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/contribution-a-mon-potager/publiee-ou-presque/cours-lycee/vecteur-position-vitesse-et-acceleration/#a31fb8" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



$
\vec{a}(t)=\frac{d\vec{v}}{dt}(t)
$

</div></div>
, la variation du vecteur vitesse $\vec{v}(t)$ est elle-même collinéaire à $\vec{a}$, donc à $\vec{g}$ : elle est verticale.
Le vecteur vitesse $\vec{v}(t)$ n'a donc que des variations verticales ; et (puisque $\vec{v}_{0}$ est dans le plan de tir), donc à tout instant, le mouvement est contenu dans le **plan de tir**.
### équations horaires de la vitesse
$\vec{a}=\vec{g}$^[[[mouvement dans un champs de pesanteur uniforme#^655475\|[mouvement dans un champs de pesanteur uniforme#^655475]]], soit $$\vec{a} \begin{cases}\frac{dv_{x}}{dt}=0\\ \frac{dv_{y}}{dt}=-g\\\frac{dv_{z}}{dt}=0\end{cases}$$ ; Le recherche des primitives donne : $$\begin{cases}v_{x}(t)=C_{1}\\v_{y}(t)=-gt+C_{2}\\ \vec{v}_{z}(t)=C_{3}\end{cases}$$ ; $C_{1}$, $C_{2}$ et $C_{3}$ sont des constantes (appelées **constantes d'intégration**).
**conditions initiales sur la vitesse** : à $t=0s$, $\vec{v}(0)=\vec{v}_{0}$, soit : $$\begin{cases}v_{x}(0)=v_{0x}=v_{0}\cos\alpha \\
v_{y}(0)=v_{0y}=v_{0}\sin\alpha \\
v_{z}(0)=v_{0z}=0\end{cases} \text{ d'où } \begin{cases}
C_{1}=v_{0}\cos\alpha \\
-g \times 0+C_{2}=v_{0}\sin\alpha \\
C_{3}=0
\end{cases}$$
On en déduit les **équations horaires de la vitesse** : 
$$
\begin{cases}
v_{x}(t)=v_{0}\cos\alpha \\
v_{y}(t)=-gt+v_{0}\sin\alpha \\
v_{z}(t)=0
\end{cases}
$$

A noter que : quand le système se trouve au *sommet* de la trajectoire, on a $v_{y}(t_{s})=0$ : 
$$
v_{y}(t_{s})=0=-gt_{s}+v_{0}\sin\alpha \text{, d'où }t_{s}=\frac{v_{0}\sin\alpha}{g}
$$
#### équations horaires de la position
Sachant que $\vec{v}=\frac{d\overrightarrow{OM}}{dt}$ 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/contribution-a-mon-potager/publiee-ou-presque/cours-lycee/vecteur-position-vitesse-et-acceleration/#ae330b" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



$
\vec{v}=\frac{d\overrightarrow{OM}}{dt}(t) \text{ de coordonnées } \begin{pmatrix}
v_{x}(t)=\frac{dx}{dt}(t)\\v_{y}(t)=\frac{dy}{dt}(t)
\end{pmatrix}
$

</div></div>
, on a :  $$\vec{v} \begin{cases}\frac{dx}{dt}(t)=v_{0}\cos\alpha\\ \frac{dy}{dt}(t)=-gt+v_{0}\sin\alpha\\\frac{dz}{dt}(t)=0\end{cases}$$
La recherche des primitives coordonnées par coordonnées donne : 
$$
\begin{cases}
x(t)=v_{0}\cos\alpha+C_{4} \\
y(t)=-\frac{1}{2}gt^{2}+v_{0}\sin\alpha+C_{5} \\
z(t)=0+C_{6}
\end{cases}
\text{, où les }C \text{ représentent des constantes}
$$
Or les **consitions initiales sur la position** indiquent que, par choix du repère, à $t=0s$ le point $M$ est à l'origine du repère d'où : 
$$
\begin{cases}
x(0)=C_{4}=0 \\
y(0)=C_{5}=0 \\
z(0)=C_{6}=0
\end{cases}
$$
On en déduit les **équations horaires de la position** : 
$$
\begin{cases}
x(t)=v_{0}\cos\alpha \times t\\
y(t)=-\frac{1}{2}gt^{2}+v_{0}\sin\alpha \\
z(t)=0
\end{cases}
$$
{ #2f63eb}


##### équation cartésienne de la trajectoire
On peut avoir l'***équation cartésienne de la trajectoire*** en trouvant $t$ : $$\frac{x}{v_{0}\cos\alpha}$$.
On remplace dans la deuxième équation, donne l'***équation cartésienne de la trajectoire*** : 
$$
y(x)=-\frac{1}{2}g\left( \frac{x}{v_{0}\cos\alpha} \right)^{2}+\frac{v_{0}\sin\alpha x}{v_{0}\cos\alpha}
$$
$$
y(x)=-\frac{1}{2}g \frac{x^{2}}{v_{0}^{2}\cos ^{2}\alpha}+\tan\alpha \times x
$$

L'autre solution est la **portée** $x_{p}$ du mouvement, on pose : 
$$
-\frac{1}{2}g \frac{x^{2}}{v_{0}^{2}\cos ^{2}\alpha}+\tan\alpha \times x
$$
qu'on factorise par $x$ : 
$$
x(-\frac{1}{2}g \frac{x}{v_{0}^{2}\cos ^{2}\alpha}+\tan\alpha)
$$
On obtient $x=0$ (qui correspond à la portée $t=0$), et : 
$$
x_{p}=\frac{2v_{0}^{2}\cos ^{2}\alpha \tan\alpha}{g}=\frac{2v_{0}^{2}\cos\alpha \sin\alpha}{g}
$$
soit $x_{p}=v_{0}^{2}\sin{2}\alpha$
Pour une vitesse initiale de norme $v_{0}$ donnée, la portée du tir est maximale si $\sin{2\alpha}$ est maximale, donc pour $2\alpha=90°$, donc pour $\alpha=45°$.
###### énergie mécanique d'un système en mouvement dans le champs de pesanteur uniforme
Le système possède du fait de sont altitude $y$, une **énergie potentielle de pesanteur** $E_{pp}$, définie à une constante près, correspondant à l'énergie d'interaction avec la Terre : 
$$
E_{pp}=mgy
$$
- $E_{pp}$ en $J$
- $m$ en $kg$
- $g$ en $N.kg^{-1}$
- $y$ en mètres $m$

L'énergie peut être décrite grâce à son mouvement à la vitesse $\vec{v}$^[[[mouvement dans un champs de pesanteur uniforme#^2f63eb\|[mouvement dans un champs de pesanteur uniforme#^2f63eb]]] , on a alors : 
$$
E_{c}=\frac{1}{2}mv^{2}
$$
- $v$ en $m.s ^{-1}$

La somme de ces deux énergies est **l'énergie mécanique** $E_{m}$ du système : 
$$
E_{m}=E_{c}+E_{pp}
$$
Puisque le système est soumis uniquement à son poids, qui est une force conservatrice, **son énergie mécanique est constante**.