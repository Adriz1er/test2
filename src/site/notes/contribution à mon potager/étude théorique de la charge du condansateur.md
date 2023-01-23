---
{"dg-publish":true,"permalink":"/contribution à mon potager/étude théorique de la charge du condansateur/"}
---

La loi d'additivité des tensions donne : $u_{r}(t)+u_{c}(t)=E$ avec $u_{R}=R \times i(t)$ (voir [[contribution à mon potager/lois d'électricités de bases#loi d'Ohm\|lois d'électricités de bases#loi d'Ohm]]), or $i(t)=\frac{dq(t)}{dt}$ avec $q=C \times u_{C}$ (voir [[contribution à mon potager/capacité du condensateur\|capacité du condensateur]]) donc $i(t)=C \times \frac{du_{c}}{dt}$, donc $u_{r}(t)=R \times C \times \frac{du_{c}}{dt}$
On obtient l'équation différentielle de charge du condensateur : $R \times C \times \frac{du_{c}}{dt}+u_{c}(t)=E\iff$ 
$$E=RC \frac{du_{c}(t)}{dt}+u_{c}(t)$$
Or on peut caractériser cette équation comme une équation différentielle, car on voit qu'il la fonction $u_{c}(t)$ et sa dérivée par rapport au temps. $$\iff \frac{E}{RC}=\frac{du_{c}}{dt}+\frac{u_{c}(t)}{RC}$$ $$\frac{du_{c}}{dt}=-\frac{u_{c}}{RC}+\frac{E}{RC}$$
On obtient une équation différentielle linéaire du premier ordre (voir [[contribution à mon potager/loi de vitesse d'ordre 1\|loi de vitesse d'ordre 1]]) à coefficients constants avec un second membre constant (voir [[contribution à mon potager/équation différentielle linéaire à coefficients constants\|équation différentielle linéaire à coefficients constants]]). 
Elle se définit par : $y'=-a y+b$ ; on repère que : $y=u_{c}$ ; $a=\frac{1}{RC}$ ; $b=\frac{E}{RC}$
On peut donc d'après [[contribution à mon potager/équation différentielle linéaire à coefficients constants#Propriétée\|équation différentielle linéaire à coefficients constants#Propriétée]] trouver la solution : 
$$p e^{-a x}+\frac{b}{a} \Rightarrow u_{c}=pe^{\frac{-1}{RC}t}+E$$La condition initiale $u_{c}(0)=0$ permet de déterminer la constant $p$ : $u_{c}(0)=p+E=0$ donc $p=-E$. On a : $$u_{c}(t)=-Ee^{\frac{-1}{RC}t}+E=E(-e^{\frac{-1}{RC}t}+1)$$
## 1° méthode pour détermination de $\tau$
On considère que $RC=\tau$ :
$$u_{c}(\tau)=E(1-e^{-\frac{\tau}{\tau}})=E(1-e^{-1})\approx E \times 0,63$$

La solution de cette équation est la somme de la solution générale de l'équation sans second membre + la solution particulière :
$$u_{c}(t)=(u_{c}(t))g+(u_{c})p$$
- La solution particulière doit être vérifiée à chaque instant $t$ donc $(u_{c})p=E$.
- La solution générale de l'équation $RC \frac{du_{c(t)}}{dt}+u_{c}(t)$ est : $(u_{c}(t))g=A \times c^{\frac{1}{RC}}$
- La solution de l'équation différentielle est $u_{c}(t)=A \times e^{\frac{1}{RC}}+E$.
- 
- La solution de cette équation différentielle est : $u_{c}(t)=E(1-e^{-\frac{t}{RC}})$

On peut montrer que lors de la charge, à $t=\tau$, $u_{c}=0,63 \times E$

---
[[contribution à mon potager/étudier la dynamique d'un système électrique\|étudier la dynamique d'un système électrique]]