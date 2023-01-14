---
{"dg-publish":true,"permalink":"/contribution-a-mon-potager/suite-numerique/"}
---

Soit $n_{0}\in N$,
Une **suite numérique** $u$ est une fonction définie pour tout entier naturel $n\ge n_{0}$ à valeurs dans $R$. Pour chaque $n\ge n_{0}$, on associe le nombre noté $u(n)$,ou encore $u_{n}$. La suite est notée $(u_{n})_{n\ge n_{0}}$ ou, plus simplement, ($u_{n}$).
## suite explicite
Une suite est définie **explicitement** lorsque l'on peut calculer n'importe quel terme de la suite directement en fonction de $n$.On donne alors l'expression du **terme général** $u_{n}$ en fonction de $n$. 
Ce qui implique qu'il existe une *fonction* telle que $u_{n}=f(n)$.

Exemple : soit une suite $(u_{n})$ définie par : $$u_{n}=\frac{2n+1}{n+5}$$ alors on peut calculer $u_{0}$ :
$$u_{0}=\frac{2 \times 0 +1}{0+5}$$
### suite récurrente
Une suite est définie **par récurrence** lorsqu'elle est définie par la donnée de son premier terme et d'une relation qui permet de calculer un terme à partir du terme précédent. On donne donc l'expression de $u_{n+1}$ en fonction de $u_{n}$.Cette relation est appelée **relation de récurrence**.
Ce qui implique qu'il existe une fonction $f$ telle que $u_{n+1}=f(u_{n})$.

On a soit une fonction $(v_{n})$ définie par récurrence, avec un *premier terme connu*. Pour calculer $v_{1}$, on utilise le terme précédent $v_{0}$. Par exemple : $(v_{n})$ définie par : 
- $v_{0}=3$
- $v_{n+1}=2v_{n}-5n$
alors on peut calculer $v_{1}$ :
$$v_{1}=2v_{0}-5 \times 0=2 \times 3-5 \times 0=6$$

---
#🌲 [[contribution à mon potager/publiée ou presque/mathématiques\|mathématiques]]