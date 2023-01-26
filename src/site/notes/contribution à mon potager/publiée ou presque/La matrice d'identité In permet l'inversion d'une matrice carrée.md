---
{"dg-publish":true,"permalink":"/contribution à mon potager/publiée ou presque/La matrice d'identité In permet l'inversion d'une matrice carrée/"}
---

# Propriété
Soit $In=\begin{pmatrix}1 & 0\\0 & 1\end{pmatrix}$ la matrice d'**identité** de taille $n \times n$. Alors pour toute matrice $A$ carrée d'ordre $n$, on a $A \times I=A=I \times A$. On dit que $I$ est le ***neutre*** pour la [[multiplacation matrice\|multiplacation matrice]]
## Inverse
On dit qu'une [[matrice\|matrice]] $A$ est **inversible** lorsqu'il existe une [[matrice\|matrice]] $B$ telle que $A \times B=I$. Si $B$ est l'[[inverse\|inverse]] de $A$ et on note $B=A^{-1}$
### déterminant
Soit $M=\begin{pmatrix}a & b\\c & d\end{pmatrix}$ carré d'ordre 2. Le **déterminant** de $M$ est $\det(M)=ad-cb$
#### Propriété
Soit une [[matrice\|matrice]] $M$ carrée : $$\text{inversible}\iff \det(M) \ne 0$$En particulier pour $M=\begin{pmatrix}a & b\\c & d\end{pmatrix}$ si $M$ inversible alors $$M^{-1}=\frac{1}{\det(M)} \times \begin{pmatrix}d & -b\\-c & a\end{pmatrix}$$
##### Application
Si $A$ est inversible alors $$AX=B \iff A^{-1}AX=A^{-1}B  \iff IX=A^{-1}B \iff X=A^{-1}B$$Et le système a une **unique** solution

---
#🌱 