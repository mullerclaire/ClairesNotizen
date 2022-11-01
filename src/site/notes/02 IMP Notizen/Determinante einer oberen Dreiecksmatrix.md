---
{"dg-publish":true,"permalink":"/02-imp-notizen/determinante-einer-oberen-dreiecksmatrix/"}
---

# Determinante einer oberen Dreiecksmatrix
Es sei $A=\left(\alpha_{k, j}\right)_{1 \leq k, j \leq n} \in \mathrm{M}_n(K)$ eine obere Dreiecksmatrix, d.h.
$$
A=\left(\begin{array}{cccc}
\alpha_{1,1} & \cdots & & \alpha_{1, n} \\
0 & \ddots & & \vdots \\
\vdots & \ddots & \ddots & \vdots \\
0 & \cdots & 0 & \alpha_{n, n}
\end{array}\right) .
$$
Dann gilt
$$
\operatorname{det}(A)=\alpha_{1,1} \cdot \ldots \cdot \alpha_{n, n} .
$$
___
**Beweis**
Es ist
$$
\operatorname{det}(A)=\sum_{\pi \in S_n} \operatorname{sgn}(\pi) \alpha_{1, \pi(1)} \cdot \ldots \cdot \alpha_{n, \pi(n)} .
$$
Ist nun $\pi \in S_n, \pi \neq$ id, so existiert ein $k \in\{1, \ldots, n\}$ mit $k>\pi(k)$; das zugehörige $\alpha_{k, \pi(k)}$ ist dann Null. Somit liefert in obiger Summe höchstens $\pi=$ id einen von Null verschiedenen Beitrag, d.h.
$$
\operatorname{det}(A)=\alpha_{1,1} \cdot \ldots \cdot \alpha_{n, n} .
$$