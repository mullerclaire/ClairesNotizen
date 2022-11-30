---
{"dg-publish":true,"permalink":"/02-imp-notizen/satz-2-9-von-egorov/"}
---

# Satz von Egorov
Sei $(X,\mathcal A, \mu)$ ein [[02 IMP Notizen/Maßraum\|Maßraum]], $E\in\mathcal{A}$ mit $\mu(E)<\infty$. 
Sei $(f_k)_{k\in\N}$ eine Folge messbarer Funktionen $f_k:E\to\R$, die punktweise gegen $f:E\to\R$ konvergiert. 

Dann gibt es für alle $\varepsilon>0$ eine Menge $\mathcal F_\varepsilon\subseteq E$ sodass: 
1. $\mathcal F_\varepsilon\in\mathcal A$ 
2. $\mu(E\setminus F_\varepsilon)\leq\varepsilon$ und
3. $f_k\to f$ gleichmäßig auf $F_\varepsilon$ , d.h. $$\lim_{k\to\infty}\sup_{x\in F_\varepsilon}|f_k(x)-f(x)|=0.$$