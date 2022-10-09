---
{"Aliases":[],"tags":["LinA/euklidischeUnitäreVektorräume"],"dg-publish":true,"permalink":"/02-all-notes/diagonalisierung-durch-orthogonale-oder-unitaere-matrizen/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# Diagonalisierung durch [[02 All notes/orthogonale Matrix|orthogonale]] oder [[02 All notes/unitäre Matrix|unitäre]] Matrizen
1. Es sei $A \in \operatorname{Sym}_{n}(\mathbf{R})$. Dann existiert $S \in \mathrm{O}_{n}(\mathbf{R})$ mit
$$
S^{-1} \cdot A \cdot S= S^t\cdot A\cdot S= \left(\begin{array}{ccc}
\lambda_{1} & & \\
& \ddots & \\
& & \lambda_{n}
\end{array}\right)
$$
wobei $\lambda_{1}, \ldots, \lambda_{n}$ die $n$ (mit Vielfachheiten gezählt) reellen Eigenwerte von $A$ sind.

2. Es sei $A \in \operatorname{Herm}_{n}(\mathbf{C})$. Dann existiert $S \in \mathrm{U}_{n}(\mathbf{C})$ mit
$$
S^{-1} \cdot A \cdot S= \overline{S}^{t} \cdot A \cdot S= \left(\begin{array}{ccc}
\lambda_{1} & & \\
& \ddots & \\
& & \lambda_{n}
\end{array}\right)
		$$
wobei $\lambda_{1}, \ldots, \lambda_{n}$ die $n$ (mit Vielfachheiten gezählt) reellen Eigenwerte von $A$ sind.