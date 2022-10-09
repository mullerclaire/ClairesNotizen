---
{"Aliases":[],"tags":["LinA/lineareGleichungssysteme"],"dg-publish":true,"permalink":"/02-all-notes/entwicklungssatz-von-laplace/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# Entwicklungssatz von Laplace

Es sei $A=\left(\alpha_{k, j}\right)_{1 \leq k, j \leq n} \in \mathrm{M}_n(K)$ eine quadratische Matrix. 

- Dann besteht die Formel **Entwicklung nach der $k$-ten Zeile von $A$** $(k=1, \ldots, n)$
$$
\begin{aligned}
\operatorname{det}(A) &=\sum_{j=1}^n \alpha_{k, j}(-1)^{k+j} \operatorname{det}\left(A_{k, j}\right) \\
&=\sum_{j=1}^n \alpha_{k, j} \mathrm{M}_{k, j}
\end{aligned}
$$
- Analog besteht die Formel **Entwicklung nach der $j$-ten Spalte von $A$** $(j=1, \ldots, n)$
$$
\begin{aligned}
\operatorname{det}(A) &=\sum_{k=1}^n \alpha_{k, j}(-1)^{k+j} \operatorname{det}\left(A_{k, j}\right) \\
&=\sum_{k=1}^n \alpha_{k, j} \mathrm{M}_{k, j}
\end{aligned}
$$
___
Enthält: 
- [[02 All notes/Adjunkte|Minor]]
- [[02 All notes/algebraisches Komplement eines Matrixelements|algebraisches Komplement eines Matrixelements]]