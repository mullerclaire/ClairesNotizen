---
{"dg-publish":true,"permalink":"/02-all-notes/cramersche-regel/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Cramersche Regel
Gegeben sei das lineare Gleichungssystem (S)
$$\alpha_{1,1} \xi_1+\cdots+\alpha_{1, n} \xi_n=\beta_1$$
$$\vdots$$
$$\alpha_{m, 1} \xi_1+\cdots+\alpha_{m, n} \xi_n=\beta_n$$
mit quadratischer Koeffizientenmatrix $A=\left(\alpha_{k, j}\right)_{1 \leq k, j \leq n} \in \mathrm{M}_n(K)$, welche $\operatorname{det}(A) \neq 0$ erfüllt. Dann besitzt $(S)$ genau eine Lösung ${ }^t\left(\xi_1, \ldots, \xi_n\right) \in K^n$ gegeben durch
$$
\xi_j=\frac{1}{\operatorname{det}(A)} \sum_{k=1}^n \beta_k M_{k, j}=\frac{1}{\operatorname{det}(A)}\left|\begin{array}{ccccc}
\alpha_{1,1} & \cdots & \beta_1 & \cdots & \alpha_{1, n} \\
\vdots & & \vdots & & \vdots \\
\alpha_{n, 1} & \cdots & \beta_n & \cdots & \alpha_{n, n}
\end{array}\right| \quad(j=1, \ldots, n)
$$
dabei steht rechter Hand die Determinante der Matrix, die aus A entsteht, indem der j-te Spaltenvektor von $A$ durch den Spaltenvektor $\left(\beta_k\right)_{1 \leq k \leq n} \in K^n$ ersetzt wird.