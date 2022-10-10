---
{"dg-publish":true,"permalink":"/02-imp-notizen/orthogonalisierungsverfahren-von-gram-schmidt/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Orthogonalisierungsverfahren von Gram-Schmidt

Es sei $V$ ein $n$-dimensionaler [[02 IMP Notizen/euklidischer Vektorraum|euklidischer Vektorraum]] bzw. [[02 IMP Notizen/unitärer Vektorraum|unitärer Vektorraum]]. Dann besitzt $V$ eine [[02 IMP Notizen/Orthonormalbasis|Orthonormalbasis]]. 

**Beweis**
Es sei $\mathcal{B}=\left\{b_{1}, \ldots, b_{n}\right\}$ eine beliebige Basis von $V$. Zuerst setzen wir
$$
e_{1}:=\frac{1}{\left\|b_{1}\right\|} b_{1}
$$
Damit gilt $\left\|e_{1}\right\|=1$, d.h. $e_{1}$ ist ein normierter Vektor. Mit einem unbestimmten Skalar $\lambda$ setzen wir weiter
$$
e_{2}^{\prime}:=b_{2}-\lambda e_{1}
$$
Wir bestimmen nun $\lambda$ derart, daB $\left\langle e_{2}^{\prime}, e_{1}\right\rangle=0$ ist, d.h. mit Hilfe der Gleichung
$$
0=\left\langle e_{2}^{\prime}, e_{1}\right\rangle=\left\langle b_{2}-\lambda e_{1}, e_{1}\right\rangle=\left\langle b_{2}, e_{1}\right\rangle-\lambda\left\langle e_{1}, e_{1}\right\rangle=\left\langle b_{2}, e_{1}\right\rangle-\lambda
$$
also
$$
\lambda=\left\langle b_{2}, e_{1}\right\rangle
$$
Damit erhalten wir
$$
e_{2}^{\prime}=b_{2}-\left\langle b_{2}, e_{1}\right\rangle e_{1}
$$
da $b_{1}, b_{2}$ linear unabhängig voneinander sind, ist $e_{2}^{\prime} \neq 0$. Indem wir $\ell_{2}^{\prime}$ normieren, d.h.
$$
e_{2}:=\frac{1}{\left\|e_{2}^{\prime}\right\|} e_{2}^{\prime}
$$
setzen, erhalten wir einen zu $e_{1}$ orthogonalen, normierten Vektor $e_{2}$.
Induktiv konstruieren wir auf diese Weise ein [[02 IMP Notizen/Orthonormalsystem|Orthonormalsystem]] $\left\{e_{1}, \ldots, e_{m}\right\}$, wobei $1 \leq m<n$ gilt. Den nächsten Basisvektor $e_{m+1}$ konstruieren wir wie zuvor durch den Ansatz
$$
e_{m+1}^{\prime}:=b_{m+1}-\lambda_{1} e_{1}-\ldots-\lambda_{m} e_{m}
$$
dabei werden die Skalare $\lambda_{1}, \ldots, \lambda_{m}$ derart bestimmt, daß $e_{m+1}^{\prime}$ auf den Vektoren des Orthonormalsystems $\left\{e_{1}, \ldots, e_{m}\right\}$ senkrecht steht. Dies führt zu
$\left\langle e_{m+1}^{\prime}, e_{1}\right\rangle=0 \Longrightarrow \lambda_{1}=\left\langle b_{m+1}, e_{1}\right\rangle$,
$\left\langle e_{m+1}^{\prime}, e_{m}\right\rangle=0 \Longrightarrow \lambda_{m}=\left\langle b_{m+1}, e_{m}\right\rangle$
also
$$
e_{m+1}^{\prime}=b_{m+1}-\left\langle b_{m+1}, e_{1}\right\rangle e_{1}-\ldots-\left\langle b_{m+1}, e_{m}\right\rangle e_{m}
$$
Aufgrund der linearen Unabhängigkeit von $b_{1}, \ldots, b_{m+1}$ ist $e_{m+1}^{\prime} \neq 0$. Indem wir schließlich $e_{m+1}^{\prime}$ normieren, d.h.
$$
e_{m+1}:=\frac{1}{\left\|e_{m+1}^{\prime}\right\|} e_{m+1}^{\prime}
$$
setzen, erhalten wir einen zu $e_{1}, \ldots, e_{m}$ [[02 IMP Notizen/orthogonal|orthogonal]]en, [[02 IMP Notizen/normiert|normiert]]en Vektor $e_{m+1}$. Nach $n$ Schritten erhält man endlich die gesuchte Orthonormalbasis $\left\{e_{1}, \ldots, e_{n}\right\}$.
