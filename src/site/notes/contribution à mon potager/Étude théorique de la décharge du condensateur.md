---
{"dg-publish":true,"permalink":"/contribution-a-mon-potager/etude-theorique-de-la-decharge-du-condensateur/"}
---

La loi d'additivité des tensions donne : $u_{r}(t)+u_{c}(t)=0$ soit $Ri(t)+u_{c}(t)=0$.
Or $i(t)=\frac{dq_{(A)}(t)}{dt}$ et $q_{A}(t)=Cu_{c}(t)$ donc $i(t)=RC \times \frac{du_{C}(t)}{dt}$. On obtient l'équation dt dt
différentielle de décharge du condensateur $0=R C \frac{d u c(t)}{d t}+u c(t)$
Dans cette équation figurent la fonction $u_{c}(t)$ et sa dérivée par rapport au temps. C'est une équation différentielle du premier ordre (voir [[contribution à mon potager/loi de vitesse d'ordre 1\|loi de vitesse d'ordre 1]]) à coefficients constants sans second membre.
- La solution de cette équation : $u_{c}(t)=A \times e^{\frac{1}{RC}}$
- la condition initiale à la date $t=0$, $u_{c}(0)=E=A$

La solution de cette équation différentielle est $$u_{c}(t)=E \times e^{-\frac{t}{RC}}$$
On peut montrer à la décharge,à $t=\tau$, $Uc=0,37 \times E$

---
[[contribution à mon potager/étudier la dynamique d'un système électrique\|étudier la dynamique d'un système électrique]]