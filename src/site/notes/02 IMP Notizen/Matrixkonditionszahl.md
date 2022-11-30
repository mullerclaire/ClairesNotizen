---
{"dg-publish":true,"permalink":"/02-imp-notizen/matrixkonditionszahl/"}
---

# Matrixkonditionszahl
Für $A \in \mathbb{R}^{n \times n}$ mit $\operatorname{det}(A) \neq 0$ heißt
$$
\operatorname{cond}(A):=\left\|A^{-1}\right\|\|A\|
$$
die **Kondition der Matrix A bezüglich der Norm $\|\cdot\|$**.
$$
\frac{\|\Delta x\|}{\|x\|} \leq \operatorname{cond}(A) \frac{\|\Delta b\|}{\|b\|} \quad \text { mit } \quad \kappa_{r e l}=\operatorname{cond}(A)=\|A\|\left\|A^{-1}\right\|
$$
Da die Abschätzung für die relative Kondition scharf ist, beschreibt $\text{cond}(A)$ die schlimmstmögliche Fehlerverstärkung für Eingangsfehler in $b \in \mathbb{R}^n$.

Es gilt:
$$
1 \leq\|I\|=\left\|A A^{-1}\right\| \leq\|A\|\left\|A^{-1}\right\|=\operatorname{cond}(A),
$$
d.h., die Kondition einer Matrix ist mindestens gleich Eins.
Außerdem gilt $\left\|A^{-1}\right\|=\sup _{x \neq 0} \frac{\left\|A^{-1} x\right\|}{\|x\|}=\sup _{y \neq 0} \frac{\|y\|}{\|A y\|}=\frac{1}{\inf _{y \neq 0} \frac{\|A y\|}{\|y\|}}$ und damit
$$
\operatorname{cond}(A)=\frac{\sup _{\|x\|=1}\|A x\|}{\inf _{\|x\|=1}\|A x\|} \in[1, \infty)
$$
Damit erhält man (siehe Übungen):
$A \neq 0$ ist numerisch singulär, wenn $\operatorname{cond}(A) \ggg 1$
und für $\operatorname{det}(A)=0$ setzt man $\operatorname{cond}(A)=\infty$. Zudem gilt:
$$
\operatorname{cond}(\alpha A)=\operatorname{cond}(A) \quad \text { für } 0 \neq \alpha \in \mathbb{R}
$$
d.h., die Kondition einer Matrix ist skalierungsinvariant.
In diesem Kontext wird klar, warum die Kondition einer Matrix besser geeignet ist als die Determinante, um die Lösbarkeit eines linearen Gleichungssystems zu beurteilen.