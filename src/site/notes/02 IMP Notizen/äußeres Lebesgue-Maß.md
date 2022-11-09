---
{"dg-publish":true,"permalink":"/02-imp-notizen/aeusseres-lebesgue-mass/"}
---

# äußeres Lebesgue-Maß
## auf $\R$
Für $A \subseteq \mathbb{R}$ setzen wir
$$
\mathcal{C}_A:=\left\{\left(\left(a_i, b_i\right)\right)_{i \in \mathbb{N}}: A \subseteq \bigcup_{i \in \mathbb{N}}\left(a_i, b_i\right)\right\},
$$
und definieren $\lambda^*: \mathcal{P}(\mathbb{R}) \rightarrow[0, \infty]$ durch
$$
\lambda^*(A):=\inf \left\{\sum_{i=0}^{\infty}\left(b_i-a_i\right):\left(\left(a_i, b_i\right)\right)_{i \in \mathbb{N}} \in \mathcal{C}_A\right\} .
$$
Dann ist $\lambda^*$ ein [[02 IMP Notizen/äußeres Maß\|äußeres Maß]] auf $\mathbb{R}$, das sogenannte **äußere Lebesgue-Maß** auf $\mathbb{R}$.

## auf $\R^n$
Ein $n$-dimensionaler Quader ist eine Teilmenge des $\mathbb{R}^n$ der Form
$$
Q=I_1 \times \cdots \times I_n,
$$
wobei $I_1, \ldots, I_n$ beschränkte Intervalle in $\mathbb{R}$ sind. Für einen Quader $Q$ definiert man $\operatorname{vol}(\emptyset):=0$, und ansonsten $\operatorname{vol}(Q):=\Pi_{i=1}^n\left(b_i-a_i\right)$ falls $\bar{Q}:=\left[a_1 \times b_1\right] \times \cdots \times\left[a_n, b_n\right]$. Für eine Teilmenge $A \subseteq \mathbb{R}^n$ setzen wir
$$
\mathcal{Q}_A:=\left\{\left(Q_i\right)_{i \in \mathbb{N}}: Q_i \text { offene Quader und } A \subseteq \bigcup_{i \in \mathbb{N}} Q_i\right\},
$$
und definieren das **äußere Lebesgue-Maß** $\lambda_n^*$ auf $\mathbb{R}^n$ durch
$$
\lambda_n^*(A):=\inf \left\{\sum_{i \in \mathbb{N}} \operatorname{vol}\left(Q_i\right):\left(Q_i\right)_{i \in \mathbb{N}} \in \mathcal{Q}_A\right\} .
$$
Prüfen Sie, dass gilt
(i) $\lambda_n^*$ ist ein [[02 IMP Notizen/äußeres Maß\|äußeres Maß]] auf $\mathbb{R}^n$.
(ii) $\lambda_n^*(Q)=\operatorname{vol}(Q)$ für alle $n$-dimensionalen Quader $Q$.