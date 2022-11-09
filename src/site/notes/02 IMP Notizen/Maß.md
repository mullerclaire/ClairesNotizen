---
{"dg-publish":true,"permalink":"/02-imp-notizen/mass/"}
---

# Maß
Sei $\mathcal R$ ein Ring auf $X$, $\mu:\mathcal{R}\to[0,\infty]$ eine Abbildung.

Ein [[02 IMP Notizen/Prämaß\|Prämaß]] $\mu:\mathcal{A}\to[0,\infty]$ auf einer $\sigma$-Algebra $\cal A$ heißt ==Maß== auf $\cal A$. 

___
**Bemerkung**
Die Menge aller Maße auf einer $\sigma$-[[02 IMP Notizen/σ-Algebra\|Algebra]] $\mathcal A$ bildet einen Kegel, d.h. für Maße $\mu, \nu:\mathcal A\to[0,\infty]$ und $\alpha\geq0$ sind auch $\mu+\nu:A\mapsto\mu(A)+\nu(A)$ und $\alpha\mu:A\mapsto\alpha\mu(A)$ Maße auf $\mathcal A$. 
___


<div class="transclusion internal-embed is-loaded"><div class="markdown-embed">




# Prämaß
Sei $\mathcal R$ ein Ring auf $X$, $\mu:\mathcal{R}\to[0,\infty]$ eine Abbildung.

$\mu$ heißt ==Prämaß== oder ==$\sigma$-Inhalt== auf $\mathcal R$, falls 
1. $\mu(\emptyset)=0$
2. $\mu$ ist $\sigma$-additiv: für disjunkte $A_1,A_2,...\in\cal R$ mit $\dot{\bigcup}_1^{\infty} A_i\in\cal R$ gilt $\mu\left(\bigcup_1^\infty A_i\right)=\sum_1^\infty\mu(A_i)$


</div></div>


___
- $\sigma$-Additivität -> Additivität
- jedes Maß ist monoton

---
**Beispiele**
- [[02 IMP Notizen/Zählmaß\|Zählmaß]]
- [[02 IMP Notizen/Punktmaß\|Punktmaß]]