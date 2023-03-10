---
{"dg-publish":true,"permalink":"/cours lycée/repère de l'espace/"}
---


# coordonnées d'un point de l'espace
Un repère de l'espace est défini par la donnée d'un point $O$ de l'espace et d'une base $(\vec{i},\vec{j},\vec{k})$ de l'espace.
## définition
On considère un repère $(O;\vec{i},\vec{j},\vec{k})$.  
Pour tout point $M$ de l'espace, il existe un unique triplet de réels $(x;y;z)$ tel que $OM=x\vec{i}+y\vec{j}+z\vec{k}$.  
$x, y$ et $z$ sont les **coordonnées** de M dans le repère $(O;\vec{i},\vec{j},\vec{k})$.
# opérations sur les coordonnées

On considère les points $A(xA;yA;zA)$ et $B(xB;yB;zB)$.  
  
Les coordonnées du vecteur $\overrightarrow{AB}$ sont $\begin{pmatrix}x_{B}-x_{A}\\y_{B}-y_{A}\\z_{B}-z_{A}\end{pmatrix}$
## propriété
On considère les points $A(x_{A};y_{A};z_{A})$ et $B(x_{B};y_{B};z_{B})$. Les coordonnées du milieu $I$ de $[AB]$ sont $(\frac{x_{A}+x_{B}}{2};\frac{y_{A}+y_{B}}{2};\frac{z_{A}+z_{B}}{2})$.
### Propriétés
On considère les vecteurs $\vec{u}\begin{pmatrix}x_{\vec{u}}\\y_{\vec{u}}\\z_{\vec{u}}\end{pmatrix}$,$\vec{v}\begin{pmatrix}x_{\vec{v}}\\y_{\vec{v}}\\z_{\vec{v}}\end{pmatrix}$ et $a$ un nombre réel.
1. Les coordonnées du vecteur $\vec{u}+\vec{v}$ sont $\begin{pmatrix}x_{\vec{u}}+x_{\vec{v}}\\y_{\vec{u}}+y_{\vec{v}}\\z_{\vec{u}}+z_{\vec{v}}\end{pmatrix}$
2. Les coordonnées du vecteur $a\vec{u}$ sont $\begin{pmatrix}ax_{\vec{u}}\\ay_{\vec{u}}\\az_{\vec{u}}\end{pmatrix}$
# représentation paramétrique d'une droite

Soit un $A(x_{A};y_{A};z_{A})$ appartenant à une droite $\Delta$ de vecteur directeur $\vec{u}\begin{pmatrix}a\\b\\c\end{pmatrix}$.
$M(x;y;z)$ appartient à $\Delta$ si, et seulement si, il existe $t\in R$ tel que 
$$ 
\begin{cases} x=at+x_{a}\\y=bt+y_{a}\\z=ct+z_{a}\end{cases}$$
Le système d'équations $$ 
\begin{cases} x=at+x_{a}\\y=bt+y_{a}\\z=ct+z_{a}\end{cases}$$ avec $t$ décrivant $R$ est une **représentation paramétrique** de la droite $\Delta$.