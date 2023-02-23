---
{"dg-publish":true,"permalink":"/contribution à mon potager/publiée ou presque/cours lycée/Mouvement dans un champs électrique uniforme/"}
---

# champs électrique créé par un condensateur plan
Si on impose une tension $U$ constante aux bornes du condensateur plan, alors un **champs électrique** $\vec{E}$ uniforme (identique en tout point) et constant dans le temps est créé entre les armatures. Il est perpendiculaire aux plaques, orienté de l'armature positive vers l'armature négative, et a pour norme : 
$$
E=\frac{U}{L}
$$
- $E$ en $V.m^{-1}$ (volt par mètre)
- $U$ en $V$
- $L$ en $m$
## mouvement d'une particule chargée dans un champs uniforme
On étudie une particule chargée de charge électrique $q$ et de masse $m$, modélisée par un point $M$, initialement immobile dans un champs électrique uniforme et constant. On suppose que la particule ne subiera que la force électrique : on se limitera en effet ici aux cas où le poids est nettement inférieur à la force électrique.
La [[contribution à mon potager/publiée ou presque/cours lycée/deuxième loi de Newton\|deuxième loi de Newton]] appliquée dans le référentiel supposé galiléen s'écrit : $m\vec{a}=\vec{F}=q\vec{E}$.
On en déduit que $\vec{a}=\frac{q}{m}\vec{E}$

L'accélération de la particule est constante : son mouvement est **uniformément accéléré**.
La vitesse de la particule étant nulle à l'instant initial ($\vec{v}_{0}=\vec{0}$), le mouvement de la particule s'effectue dans la direction de $\vec{E}$.
Le mouvement est donc **rectiligne** dans la direction de $\vec{E}$.

On choisit un repère composé d'un axe ($O;\vec{i}$) où $O$ est la position initiale de la particule et $\vec{i}$ est colinéaire à $\vec{E}$ et dans le sens du mouvement de la particule. En projection sur cet axe, l'expression de l'accélération donne : $a_{x}=\frac{q}{m}E_{x}$ soit $\frac{dv_{x}}{dt}=\frac{q}{m}E_{x}$
$q$ peut être positive ou négative, de même que $E_{x}$, mais le produit $qE_{x}$ est positif puisque l'axe a été orienté dans le sens du mouvement.
La recherche de la primitive donne $$v_{x}(t)=\frac{q}{m}E_{x}t+C_{1}$$. Comme à $t=0s$, la vitesse de la particule est nulle, $C_{1}=0m.s ^{-1}$.
On en déduit l'**équation horaire de la vitesse** de la particule : 
$$
v_{x}(t)=\frac{q}{m}E_{x}(t)
$$
Cela donne ensuite $$\frac{dx}{dt}(t)=\frac{q}{m}E_{x}(t)$$
On recherche la primitive : 
$$
x(t)=\frac{1}{2}\frac{q}{m}E_{x}t^{2}+C_{2}
$$
Comme $x(0)=0$, on a : $C_{2}=0m$
On en déduit l'**équation horaire de la position** de la particule : 
$$
x(t)=\frac{1}{2} \frac{q}{m}E_{x}t^{2}
$$
### Aspects énergétiques
Le théorème de l'énergie cinétique, appliquée à la particule entre sa position de départ $O$ et une position $M$ quelconque, s'écrit : 
$$
E_{c}(M)-E_{c}(O)=W_{OM}(\vec{F})
$$
Puisque $\vec{F}$ est une force constante, son travail entre $O$ et $M$ s'écrit : 
$$
W_{OM}(\vec{F})=\vec{F}.\overrightarrow{OM}
$$
Or $\vec{F}=q\vec{E}=q E_{x} \vec{i}$, d'une part et $\overrightarrow{OM}=x \vec{i}$, d'autre part. Cela donne : 
$$
W_{OM}(\vec{F})=qE_{x}\vec{i}\cdot x\vec{i}=qE_{x}x
$$
Puisque $E_{x}=\frac{U_{OM}}{x}$^[[[Mouvement dans un champs électrique uniforme#champs électrique créé par un condensateur plan\|[Mouvement dans un champs électrique uniforme#champs électrique créé par un condensateur plan]]], ainsi $E_{x}x$ est la **tension électrique** entre $O$ et $M$, notée $U_{OM}$.
Le théorème de l'énergie cinétique donne donc : 
$$
E_{c}(M)-E_{c}(O)=qU_{OM}
$$