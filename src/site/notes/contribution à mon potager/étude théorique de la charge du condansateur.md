---
{"dg-publish":true,"permalink":"/contribution-a-mon-potager/etude-theorique-de-la-charge-du-condansateur/"}
---

La loi d'additivité des tensions donne : $u_{r}(t)+u_{c}(t)=E$ soit $Ri(t)+u_{c}(t)=E$. 
Or $i(t)=\frac{dq(t)}{dt}$ et $q_{A}=C \times u_{C}$ (voir [[contribution à mon potager/capacité du condensateur\|capacité du condensateur]]) donc $i(t)=RC \frac{du_{c(t)}}{dt}$. On obtient l'équation différentielle de charge du condensateur $$E=RC \frac{du_{c(t)}}{dt}+u_{c}(t)$$
Dans cette équation figurent la fonction $u_{c}(t)$ et sa dérivée par rapport au temps. C'est une équation différentielle linéaire du premier ordre (voir [[contribution à mon potager/loi de vitesse d'ordre 1\|loi de vitesse d'ordre 1]]) à coefficients constants avec un second membre constant.
La solution de cette équation est la somme de la solution générale de l'équation sans second membre + la solution particulière :
$$u_{c}(t)=(u_{c}(t))g+(u_{c})p$$
- La solution particulière doit être vérifiée à chaque instant $t$ donc $(u_{c})p=E$.
- La solution générale de l'équation $RC \frac{du_{c(t)}}{dt}+u_{c}(t)$ est : $(u_{c}(t))g=A \times c^{\frac{1}{RC}}$
- La solution de l'équation différentielle est $u_{c}(t)=A \times e^{\frac{1}{RC}}+E$.
- La condition initiale $u_{c}(0)=0$ permet de déterminer la constant $A$ : $u_{c}(0)=A+E=0$ donc $A=-E$
- La solution de cette équation différentielle est : $u_{c}(t)=E(1-e^{-\frac{t}{RC}})$

On peut montrer que lors de la charge, à $t=\tau$, $u_{c}=0,63 \times E$

---
[[contribution à mon potager/étudier la dynamique d'un système électrique\|étudier la dynamique d'un système électrique]]