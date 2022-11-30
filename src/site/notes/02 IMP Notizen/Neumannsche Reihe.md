---
{"dg-publish":true,"permalink":"/02-imp-notizen/neumannsche-reihe/"}
---

# Neumannsche Reihe
Sei $C \in \mathbb{R}^{n \times n}$ wobei $\|C\|<1$ mit einer [[submultiplikativ\|submultiplikativ]]en Norm. Dann ist $(I-C)$ invertierbar und man erhält
$$
(I-C)^{-1}=\sum_{k=0}^{\infty} C^k
$$
Weiterhin gilt
$$
\left\|(I-C)^{-1}\right\| \leq \frac{1}{1-\|C\|} .
$$
___
**Beweis**
1. Zeige zunächst: $\sum_{k=0}^{\infty} C^k$ existiert.
Sei $q=\|C\|<1$. Dann gilt (da $\|\cdot\|$ submultiplikativ)
$$
\left\|\sum_{k=0}^m C^k\right\| \leq \sum_{k=0}^m\left\|C^k\right\| \leq \sum_{k=0}^m\|C\|^k=\sum_{k=0}^m q^k=\frac{1-q^{m+1}}{1-q}
$$
(Partialsummen der geometrischen Reihe)
$$
\Rightarrow \lim _{m \rightarrow \infty} \sum_{k=0}^m C^k \text { existiert }
$$
2. Zeige (6): Es gilt:
$$
\begin{aligned}
(I-C) \sum_{k=0}^{\infty} C^k &=(I-C) \lim _{m \rightarrow \infty} \sum_{k=0}^m C^k=\lim _{m \rightarrow \infty}(I-C) \sum_{k=0}^m C^k \\
&=\lim _{m \rightarrow \infty}\left(C^0-C^{m+1}\right)=I \\
\text { da }\left\|C^{m+1}\right\| \leq\|C\|^{m+1} \rightarrow 0 \text { für } m \rightarrow \infty
\end{aligned}
$$
3. Aus 1. folgt:
$$
\left\|\sum_{k=0}^m C^k\right\| \leq \frac{1-q^{m+1}}{1-q} \leq \frac{1}{1-\|C\|}
$$
Die Neumannsche Reihe kann genutzt werden, um für eine gestörten Matrix $\tilde{A}=A+\Delta A$ die Existenz einer Inversen und damit die Lösbarkeit eines entsprechenden Gleichungssystems zu zeigen.