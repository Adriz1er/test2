---
{"dg-publish":true,"permalink":"/cours lycée/forme exponentientielle d'un nombre complexe/"}
---

Soit $z\in C$, avec $r=\mid z\mid$ et $\theta=arg z+2k\pi$ $(k\in Z)$
On note *la forme exponentielle imaginaire* : 
$$
z=re ^{i\theta}
$$
Remarque : On a posé : 
$$
e^{i\theta}=\cos\theta+i\sin\theta
$$
Exemple : 
$$
z=1+\sqrt{ 3 }
$$
$$|z|=2$$
$$
\begin{cases}
\cos\theta=\frac{1}{2} \\
\sin\theta=\frac{\sqrt{ 3 }}{2}
\end{cases} \text{ donc }\theta=\frac{\pi}{3}(+2k\pi)
$$
$$
\text{Donc } z=1+i\sqrt{ 3 }
$$
$$
=2\left( \cos \frac{\pi}{3} +i\sin \frac{\pi}{3}\right)=2e^{i\frac{\pi}{3}}
$$
## propriété
Soient $z, z^{'}\in C$ avec $z=re ^{i\theta}$ et $z=r^{'}e ^{i\theta^{'}}$, alors on a : 
$$
zz^{'}=rr^{'} \times e^{i(\theta+\theta^{'})}
$$
$$
z^{n}=r^{n}e^{in \theta}
$$
$$
\frac{z}{z^{'}}=\frac{r}{r^{'}}e^{i(\theta-\theta^{'})}
$$
Remarque : On retrouve les formules de trigo, avec $r=1$ et $r^{'}=1$
$$
z=e^{i\theta}=\cos\theta+i \sin\theta
$$
$$
z^{'}=e^{i \phi}=\cos (\theta+4)+i \sin (\theta+4)
$$
$$zz^{'}=e^{i(\theta+ \phi)}=\cos(\theta+4)+i \sin \theta+4$$
Or d'un autre côté,
# propriété : formules d'Euler
On rapelle que $e^{i\theta}=\cos\theta+i \sin\theta$ $$\iff e^{-i\theta}=\cos\theta-i \sin\theta$$
d'où $e^{i\theta}+e^{-i\theta}=2\cos\theta$ et $$\cos\theta=\frac{e^{i\theta}+e^{-i\theta}}{2}$$
de même, $e^{i\theta}-e^{-i\theta}=2i \sin\theta$ et $$\sin\theta= \frac{e^{i\theta}-e^{-i\theta}}{2i}$$
# formules de moivre
$\forall \in Z$, $\forall\theta\in R$,
$$\cos n\theta+i\sin n\theta=(\cos\theta+i\sin\theta)^{n}$$
## démonstration
Par récurrence, sur $n \in N$ : 
$$P_{n}: e^{in\theta}=(\cos\theta+i\sin\theta)^{n}$$
	initialisation : 
		$P_{0}$ : $e^{i0 \theta}=e^{0}=1$
		or $$\cos n\theta+i\sin n\theta=(\cos\theta+i\sin\theta)^{n}$$
	héréditée : 
		On suppose un $k\in N$ tel que $P_{k}$ est vraie. On veut que $P_{k+1}$ le soit aussi.
	$$e^{i\theta(k+1)}=e^{i\theta k} \times e^{i\theta}$$
		Par récurrence $$e^{i\theta k}=(\cos\theta+i\sin\theta)^{k}$$
		On sait que $$e^{i\theta}=\cos\theta+i\sin\theta$$
		Donc $$e^{i\theta(k+1)}=(\cos\theta+i\sin\theta)^{k} \times (\cos\theta+i\sin\theta)$$
		$$=(\cos\theta+i\sin\theta)^{k+1}$$
		Donc $P_{k+1}$ vraie
	Conclusion : 
		On a démontré par récurrence que $P_{n}$ vraie $\forall n \in N$.
Or $$\cos ^{2}\theta+\sin ^{2}\theta=1$$
donc $$\cos ^{2}\theta -\sin ^{2}\theta$$
$$=\cos ^{2}\theta-(1-\cos ^{2}\theta)$$
$$=2\cos ^{2}\theta-1$$
Finalement $$e^{i2\theta}=2\cos ^{2}\theta-1+i(2\cos\theta \sin\theta)$$
et par identification : $$\cos{2}\theta=2 \cos ^{2}\theta-1$$
$$\sin 2\theta=2\cos\theta \sin\theta$$

---
Remarque : $z=a+ib=\mid z\mid e^{i\theta}$
$$z \times e^{i\theta^{'}}=\mid z\mid e^{i\theta} \times e^{i\theta^{'}}=\mid z\mid e^{i(\theta+\theta^{'})}$$
> Multiplier par $e^{i\theta^{'}}$, c'est faire une rotation d'angle $\theta^{'}$ et de centre $O$.
