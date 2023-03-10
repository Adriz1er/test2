---
{"dg-publish":true,"permalink":"/cours lycée/droites et plans de l'espace/"}
---

# Droites de l'espace
Soient $A$ un point de l'espace et $\vec{u}$ un vecteur non nul. L'ensemble des points $M$ de l'espace tels que $\overrightarrow{AM}=λ\vec{u}$ , avec $λ∈R$, est une **droite**.  
$(A,\vec{u})$ est un **repère** de cette droite : on dit que la droite est dirigée par $\vec{u}$.
## définition
Dans l'espace, deux droites peuvent être **coplanaires** ou non.  
Si elles sont coplanaires, alors elles appartiennent à un même plan. Elles peuvent donc être **sécantes** (avoir un point d'intersection) ou **parallèles** (strictement parallèles ou confondues).
![droites coplanaires et droites non-coplanaires.png](/img/user/droites%20coplanaires%20et%20droites%20non-coplanaires.png)
# Plans de l'espace
Soient $A$ un point de l'espace et $\vec{u}$ et $\vec{v}$ deux vecteurs non colinéaires de l'espace (voir [[cours lycée/vecteurs de l'espace\|vecteurs de l'espace]]).
L'ensemble des points $M$ tels que $\overrightarrow{AM}=λ\vec{u}+μ\vec{v}$ (où $λ$ et $μ$ sont des réels) est un **plan de l'espace**. $(A ; \vec{u};\vec{v})$ est un **repère du plan**. On dit que le plan est dirigé par la **base**$(\vec{u},\vec{v})$.
## définitions 
![Screenshot_20230124-111357~2.png](/img/user/Screenshot_20230124-111357~2.png)
### méthode
Pour déterminer l'intersection de deux plans, il faut :
-   justifier qu'ils sont sécants ;
-   déterminer leur droite d'intersection : il suffit alors de déterminer deux points qui appartiennent aux deux plans.

Une droite $d$ est parallèle à un plan $P$ si, et seulement si, il existe une droite $Δ$ du plan $P$ parallèle à $d$.
## théorème
Un plan $P′$ est parallèle à un plan $P$ si, et seulement si, il existe deux droites sécantes de $P′$ parallèles à deux droites sécantes de $P$.  
![](https://assets.lls.fr/pages/40796459/MAT.SPE.2.INF25_v1.svg)
## théorème
Soient $P$ et $P′$ deux plans strictement parallèles. Tout plan $π$ qui coupe l'un de ces plans coupe l'autre et les droites d'intersections obtenues sont parallèles.
![](https://assets.lls.fr/pages/40796459/MAT.SPE.2.INF26_v1.svg)
## théorème du toit (admis)
Soient deux droites $d$ et $d′$ parallèles. Soit un plan $P$ contenant $d$ sécant à un autre plan $P′$ contenant $d′$. Alors la droite $Δ$ intersection de $P$ et $P′$ est parallèle à $d$ et à $d′$.
### méthode
Si deux plans sont sécants, alors leur intersection est une droite.  
On commence donc par chercher :
-   un point commun entre ces deux plans ;
-   un théorème à appliquer en fonction des hypothèses données par l'énoncé ou déterminées au cours de la résolution.