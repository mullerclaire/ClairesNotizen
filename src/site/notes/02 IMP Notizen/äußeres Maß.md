---
{"dg-publish":true,"permalink":"/02-imp-notizen/aeusseres-mass/"}
---

# äußeres Maß
Abbildung $\mu^*:2^X\to[0,\infty]$ heißt **äußeres Maß** auf $X$, falls gilt: 

1. **Leere Menge**: $\mu^*(\emptyset)=0$
2. **Monotonie**: $A\subseteq B\subseteq X\implies\mu^*(A)\leq\mu^*(B)$
3. **$\sigma$-[[02 IMP Notizen/Sigma-Subadditivität\|Subadditivität]]/Halbadditivität**: $\forall A,B,A_i\subset X$: $$\mu^*\left(\displaystyle\bigcup_1^\infty A_i\right)\leq\sum_1^\infty \mu^*(A_i)$$
- Jedes [[02 IMP Notizen/Maß\|Maß]] auf $\mathcal{P}(X)$ ist ein äußeres Maß (Satz 9.4), 
- aber es existieren äußere Maße, die keine Maße sind.
