---
{"dg-publish":true,"permalink":"/cours lycée/Mouvement circulaire/"}
---

# un repère adapté : le repère de Frenet
Le **repère de Frenet** utilise deux vecteurs unitaires partant dun point $M$ en mouvement : 
- le **vecteur tangeantiel $\vec{u}_{t}$**, tangent à la trajectoire et orienté dans le sens du mouvement
- le **vecteur normal $\vec{u}_{n}$**, perpendiculaire à $\vec{u}_{t}$ et orienté vers l'intérieur de la courbure de la trjectoire 
Pour une **trajectoire circulaire** de centre $O$ et de rayon $R$ : 
- le vecteur position $\overrightarrow{OM}(t)$ est colinéaire à $\vec{u}_{n}$ et de sens contraire : $$\overrightarrow{OM}(t)=-R\vec{u}_{n}$$
- le vecteur vitesse est colinéaire à $\vec{u}_{t}$ et de même sens : $$\vec{v}(t)=v(t)\vec{u}_{t}$$
- le vecteur accélération $\vec{a}(t)$ a une coordonnée tangentielle selon $\vec{u}_{t}$ et une coordonnée normale selon $\vec{u}_{n}$ : $$\vec{a}(t)=\frac{dv}{dt}(t)\vec{u}_{t}+\frac{v(t)^{2}}{R}\vec{u}_{n}$$
# mouvement circulaire uniforme
Si le mouvement est uniforme, $v(t)$ est constante, donc $\frac{dv}{dt}(t)=0$.
L'accélération est, dans ce cas, dirigée selon le vecteur normal $\vec{u}_{n}$ : 
$$
\vec{a}(t)=\frac{v^{2}}{R}\vec{u}_{n}
$$
## mouvement circulaire non-uniforme
Si le mouvement est circulaire non-uniforme, l'accélération $\vec{a}(t)$ a des coordonnées selon les deux vecteurs unitaires du repère de Frenet^[[[Mouvement circulaire#un repère adapté : le repère de Frenet\|[Mouvement circulaire#un repère adapté : le repère de Frenet]]] : 
$$
\vec{a}(t)=\frac{dv}{dt}(t)\vec{u}_{t}+\frac{v(t)^{2}}{R}\vec{u}_{n}
$$