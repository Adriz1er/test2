---
{"dg-publish":true,"permalink":"/contribution à mon potager/publiée ou presque/cours lycée/vecteur position, vitesse et accélération/"}
---

# vecteur position $\overrightarrow{OM}(t)$
Le rôle du vecteur position $\overrightarrow{OM}$ est de définir la position d'un point à un instant $t$ ; il relie **l'origine du repère au point** Les coordonnées $\binom{x}{y}$ du vecteur position correspondent aux coordonnées de la position d'un point
$$\overrightarrow{OM} \begin{pmatrix} x(t)\\y(t)\\z(t)
\end{pmatrix}$$
{ #26bb81}


Les expressions de $x$, $y$ et $z$ en fonction du temps $t$ sont appelées les  **équations horaires de la position**.
# vecteur vitesse $\vec{v}(t)$
Il a pour caractéristiques : 
$\vec{v}(t) \begin{cases} \text{ direction : tangeant au mouvement}\\ \text{ sens : le sens du mouvement}\\ \text{ norme : la valeur de la vitesse instantanée au point considéré}\end{cases}$
Le vecteur vitesse $\vec{v}(t)$ est la dérivée du vecteur position $\overrightarrow{OM}(t)$ par rapport au temps $t$ : 
$$
\vec{v}=\frac{d\overrightarrow{OM}}{dt}(t) \text{ de coordonnées } \begin{pmatrix}
v_{x}(t)=\frac{dx}{dt}(t)\\v_{y}(t)=\frac{dy}{dt}(t)
\end{pmatrix}
$$
{ #ae330b}


Sa norme est ||$\vec{v}(t)$||$=\sqrt{v_{x}(t)²+v_{y}(t)²}$

A noter qu'on peut l'obtenir graphiquement.
# vecteur accélération
$$
\vec{a}(t)=\frac{d\vec{v}}{dt}(t)
$$
{ #a31fb8}


comme 
<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/contribution-a-mon-potager/publiee-ou-presque/cours-lycee/vecteur-position-vitesse-et-acceleration/#ae330b" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



$
\vec{v}=\frac{d\overrightarrow{OM}}{dt}(t) \text{ de coordonnées } \begin{pmatrix}
v_{x}(t)=\frac{dx}{dt}(t)\\v_{y}(t)=\frac{dy}{dt}(t)
\end{pmatrix}
$

</div></div>

le vecteur accélération est la **dérivée seconde du vecteur position** $\overrightarrow{OM}(t)$ par rapport au temps $t$ : 
$$
\vec{a}(t)= \frac{d^{2}\overrightarrow{OM}}{dt^{2}}(t)
$$
Les coordonnées du vecteur accélération sont donc : 
$$
\begin{pmatrix}
a_{x}(t)=\frac{dv_{x}}{dt}(t)\\a_{y}(t)=\frac{dv_{y}}{dt}(t)
\end{pmatrix}
\text{ ou }
\begin{pmatrix}
a_{x}(t)=\frac{d^{2}x}{dt^{2}}(t)\\a_{y}(t)=\frac{d^{2}y}{dt^{2}}(t)
\end{pmatrix}
$$
Sa norme est ||$\vec{a}(t)$||$=\sqrt{a_{x}(t)²+a_{y}(t)²}$
# détermination graphique
On peut construire la vitesse moyenne approximativement comme la vitesse moyenne entre le point d'avant $M(t-\Delta t)$ et le point d'après $M(t+\Delta t)$ : 
$$
\vec{v}(t)=\frac{\overrightarrow{M(t-\Delta t)M(t+\Delta t)}}{2\Delta t}=\overrightarrow{OM}(t+\Delta t)-\frac{\overrightarrow{OM}(t-\Delta t)}{2\Delta t}
$$

On a : 
- $$\Delta \vec{v}(t)=\vec{v}(t+\Delta t)-\vec{v}(t-\Delta t)$$
- $$\vec{a}(t)=\frac{\vec{v}(t+\Delta t)-\vec{v}(t-\Delta t)}{2\Delta t}=\frac{\Delta \vec{v}(t)}{2\Delta t}$$
- $$a(t)=\frac{\Delta v(t)}{2\Delta t}$$