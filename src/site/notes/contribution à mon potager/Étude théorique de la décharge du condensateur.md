---
{"dg-publish":true,"permalink":"/contribution à mon potager/Étude théorique de la décharge du condensateur/"}
---

La loi d'additivité des tensions donne : $u_{r}(t)+u_{c}(t)=0$ soit $Ri(t)+u_{c}(t)=0$.
Or $i(t)=\frac{dq(t)}{dt}$ et $q(t)=Cu_{c}(t)$ donc $i(t)=RC \times \frac{du_{C}(t)}{dt}$. 
$u_{r}=R \times C \times \frac{du_{c}}{dt}$
On obtient l'équation
différentielle de décharge du condensateur $0=R C \frac{d u c(t)}{d t}+u c(t)$
Dans cette équation figurent la fonction $u_{c}(t)$ et sa dérivée par rapport au temps. C'est une équation différentielle du premier ordre (voir [[contribution à mon potager/loi de vitesse d'ordre 1\|loi de vitesse d'ordre 1]]) à coefficients constants (sans 2° membre) : $\frac{du_{c}}{dt}=-\frac{1}{RC}u_{c}$
- La solution de cette équation : $u_{c}(t)=p \times e^{\frac{1}{RC}}$
- la condition initiale à la date $t=0$, $u_{c}(0)=E=p$ (voir [[contribution à mon potager/lois d'électricités de bases#Loi des nœuds\|lois d'électricités de bases#Loi des nœuds]])

La solution de cette équation différentielle est $$u_{c}(t)=E \times e^{-\frac{t}{RC}}$$
On peut montrer à la décharge,à $t=\tau$, 
## Première méthode
$u_{c}(t)=E \times e^{\frac{-\tau}{\tau}=E}\times e^{-1}$ 
$u_{c}=0,37 \times E$
## Deuxième méthode : tracé de la tangeante au temps initial
$\frac{du_{c}}{dt}(t)=-\frac{1}{\tau}\times E \times e^{-t/\tau}$
à $t=0$, $\frac{du_{c}}{dt}(t=0)=-\frac{1}{\tau}\times E \times e^{-0/\tau}=-\frac{E}{\tau}$ 
puisque $(e^{ax})''=ae^{ax}$

---
[[contribution à mon potager/étudier la dynamique d'un système électrique\|étudier la dynamique d'un système électrique]]