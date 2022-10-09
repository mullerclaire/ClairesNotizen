---
{"Aliases":["division d'un polynôme par un monôme","schéma de Hörner"],"tags":["Analysis","LinA"],"dg-publish":true,"permalink":"/02-all-notes/polynom-durch-monom-teilen/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# Polynom durch Monom teilen

**Théorème** Soit $P$ un polynôme avec $\operatorname{deg} P \geqslant 1$ et $x_0 \in \mathbb{R}$. Alors il existe un unique polynome $F$ tel que:
$$
P(x)=f(x) \cdot\left(x-x_0\right)+P\left(x_0\right)
$$
**NB** $\operatorname{deg} F=\operatorname{deg}(P)-1$

**Exemple** division euclidienne de $P(x)=4 x^3+2$ par $x+2$ $\left(x_0=-2\right)$

|     | 4   | 0   | 0   | 2   |
| --- | --- | --- | --- | --- |
| -2  |     | -8  | 16  | -32 |
|     | 4   | -8  | 16  | -30 |

Ainsi $4 x^3+2=\left(1 x^2-8 x+16\right)(x+2)-30$. 