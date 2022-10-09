---
{"Aliases":[],"tags":["LinA/Diagonalisierbarkeit"],"dg-publish":true,"permalink":"/02-all-notes/jordansche-normalform-finden/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# Jordansche Normalform finden
## Jordan-Normalform
- Größe des Jordan-Blocks $J(\lambda_i)$ ist höchtens $d_i$
- $\forall i, \exists$ ein Block der Größe $d_i$: $J_{d_i}(\lambda_i)$
- $\beta_i$ = Anzahl an Blöcken für $\lambda_i$ 
- Summe Größen aller Blöcke $= n$
- Anzahl Blöcke einer Größe $d_i$ = Rang von $(A-\lambda_i\cdot E)^k$, $1\leq k\leq \alpha_i$.
## Jordan-Basis
- Char. Polynom und Eigenwerte
- Minimalpolynom bestimmen
- Ketten von Unterräumen $U_j^{(i)}:=\ker(A-\lambda_i\cdot E)^j$  bis zur Vielfachheit im Minimalpolynom
- $\R^3$ zerlegen, W_1=


## Beispiel
Es sei
$$
A=\left(\begin{array}{ccc}
3 & 4 & 3 \\
-1 & 0 & -1 \\
1 & 2 & 3
\end{array}\right) \in \mathrm{M}_3(\mathbb{R})
$$
Man berechnet sofort
$$
p_A(t)=-(t-2)^3 .
$$
Mit $B:=A-2 \cdot E \in \mathrm{M}_3(\mathbb{R})$ berechnet man sofort
$$
B \neq 0, B^2 \neq 0, B^3=0,
$$
d.h.
$$
m_A(t)=(t-2)^3 .
$$

Mit den Bezeichnungen des [[02 All notes/Satz 2 zur Jordan'schen Normalform|vorhergehenden Satzes]] haben wir
$$
\begin{aligned}
&U_0=\{0\} \\
&U_1=\operatorname{ker}(B)=\left\langle\left(\begin{array}{c}
1 \\
-1 \\
1
\end{array}\right)\right\rangle \\
&U_2=\operatorname{ker}\left(B^2\right)=\left\langle\left(\begin{array}{c}
1 \\
-1 \\
1
\end{array}\right),\left(\begin{array}{c}
0 \\
-1 \\
1
\end{array}\right)\right\rangle
\end{aligned}
$$
Wir haben die Zerlegungen
$$
\begin{aligned}
\mathbb{R}^3 &=U_2 \oplus W_3 \\
&=U_1 \oplus W_2 \oplus W_3 \\
&=U_0 \oplus W_1 \oplus W_2 \oplus W_3
\end{aligned}
$$
Damit wählen wir
$$
\begin{aligned}
&W_3=\left\langle\left(\begin{array}{l}
0 \\
0 \\
1
\end{array}\right)\right\rangle \\
&W_2=B\left(W_3\right)=\left\langle\left(\begin{array}{c}
3 \\
-1 \\
1 \\
2
\end{array}\right)\right\rangle \\
&W_1=B\left(W_2\right)=\left\langle\left(\begin{array}{c}
-2 \\
2
\end{array}\right)\right\rangle
\end{aligned}
$$
Damit setzen wir
$$
S=\left(\begin{array}{ccc}
2 & 3 & 0 \\
-2 & -1 & 0 \\
2 & 1 & 1
\end{array}\right), \quad S^{-1}=\frac{1}{4}\left(\begin{array}{ccc}
-1 & -3 & 0 \\
2 & 2 & 0 \\
0 & 4 & 4
\end{array}\right)
$$
und erhalten
$$
A^{\prime}=S^{-1} \cdot A \cdot S=\left(\begin{array}{lll}
2 & 1 & 0 \\
0 & 2 & 1 \\
0 & 0 & 2
\end{array}\right)
$$
die Jordansche Normalform von $A$.