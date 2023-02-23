---
{"dg-publish":true,"permalink":"/contribution à mon potager/publiée ou presque/cours lycée/satellite en mouvement circulaire/"}
---

# utilisation du repère de Frenet
Soit un satellite **en mouvement circulaire** autour du centre $O$ de l'astre attracteur de masse $M$. La distance $r=OP$ est une constante.
Le vecteur unitaire $\vec{u}$ est de même direction que le vecteur normal $\vec{u}_{n}$ de la base de Frenet, de sens opposé : $\vec{u}=-\vec{u}_{n}$
En notant $\vec{v}(t)$ la vitesse du système dans le référentiel d'étude, l'accélération s'écrit dans le repère de Frenet : $\vec{a}=\frac{dv}{dt} \vec{u}_{t}+ \frac{v^{2}}{r} \vec{u}_{n}$
![Pasted image 20230223101931.png|250](/img/user/Pasted%20image%2020230223101931.png)

La [[contribution à mon potager/publiée ou presque/cours lycée/deuxième loi de Newton\|deuxième loi de Newton]] fournit donc la relation suivante : 
$$
\frac{dv}{dt}\vec{u}_{t}+ \frac{v^{2}}{r} \vec{u}_{n}=-G \frac{M}{r^{2}} \vec{u} \text{ avec } \vec{u}=-\vec{u}_{n}
$$
En projection sur les vecteurs $\vec{u}_{t}$ et $\vec{u}_{n}$, cela donne : 
$$
\frac{dv}{dt}=0 \text{ sur } \vec{u}_{t} \text{ et } \frac{v^{2}}{r}=G \frac{M}{r^{2}} \text{ sur } \vec{u}_{n}
$$
## vitesse d'un satellite en mouvement circulaire
La première égalité $\frac{dv}{dt}=0$ implique que **$v$ est une constante** : le mouvement circulaire d'un satellite est donc **uniforme**.
La deuxième égalité $\frac{v^{2}}{r}=G \frac{M}{r^{2}}$ donne : 
$$
v^{2}=G \frac{M}{r} \text{ d'où } v=\sqrt{ G \frac{M}{r} }
$$
Le vecteur vitesse d'un satellite en mouvement circulaire est donc : 
$$
\vec{v}=\sqrt{ G \frac{M}{r} }\vec{u}_{t}
$$
### période de révolution d'un satellite en mouvement circulaire
La **période de révolution** d'un satellite est la durée qu'il met pour faire un tour de l'astre attracteur dans le référentiel astrocentrique.

Pour un mouvement circulaire de rayon $r$, la distance parcourue en un tour est $2 \pi r$. La norme $v$ (constante) de la vitesse du satellite est donc liée à sa période de révolution $T$ par la relation $v=\frac{2 \pi r}{T}$.
Or on a vu que $v=\sqrt{ G \frac{M}{r} }$. Cela donne l'égalité $\frac{2\pi r}{T}=\sqrt{ G \frac{M}{r} }$.
En prenant l'inverse, on obtient $\frac{T}{2\pi r}=\sqrt{ \frac{r}{GM} }$, ce qui donne : 
$$
T=2 \pi r \sqrt{ \frac{r}{GM} } \text{ soit encore } T=2\pi \sqrt{ \frac{r^{3}}{GM} }
$$

En élevant au carré la relation, on obtient $T^{2}=4\pi^{2} \frac{r^{3}}{GM}$, qui donne : 
$$
\frac{T^{2}}{r^{3}}=\frac{4\pi^{2}}{GM}
$$
Cette égalité est la ==troisième loi de Kepler==.