---
{"dg-publish":true,"permalink":"/new/integral-einer-nichtnegativen-messbaren-funktion/"}
---

# Integral einer nichtnegativen messbaren Funktion
Sei $(X, \mathcal{A}, \mu)$ ein [[02 IMP Notizen/Maßraum\|Maßraum]], $E \in \mathcal{A}, f: E \rightarrow[0, \infty]$ [[02 IMP Notizen/A-messbare Funktion\|messbar]].

- Das **Integral** von $f$ über $E$ ist definiert durch
$$
\int_E f d \mu:=\sup \left\{\int_E \varphi d \mu \mid \varphi: E \rightarrow[0, \infty) \text { einfach }, \varphi \leq f\right\}
$$
Die Funktion $f$ heißt **$\mu$-integrierbar**, falls $\int_E f d \mu<\infty$.

- Für $A \subset E, A \in \mathcal{A}$, definiert man
$$
\int_A f d \mu=\int_A f\mid_A d \mu
$$

___
**Bemerkung**
- $\int_E f d \mu \in[0, \infty]$ für alle messbaren Funktionen $f: E \rightarrow[0, \infty]$.
- Aus der Monotonie folgt sofort, dass für einfache Funktionen die [[NEW/Integral einer einfachen Funktion\|obige Definition des Integrals]] mit der früheren [[02 IMP Notizen/einfache Funktion\|Definition 2.10]] übereinstimmt.

---
Siehe auch: 
- [[02 IMP Notizen/einfache Funktion\|einfache Funktion]]