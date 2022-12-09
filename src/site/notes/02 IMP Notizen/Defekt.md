---
{"dg-publish":true,"permalink":"/02-imp-notizen/defekt/"}
---

# Defekt

Sei $\tilde{x}$ eine Näherungslösung von $Ax=b$. 

Die Größe $$d(\tilde{x})=b-A\tilde{x}$$ bezeichnet den **Defekt** od. **Residuum** des Problems $Ax=b$.

___
$\tilde{x}$ exakte lösung $\Rightarrow d(\tilde{x})=0$.
Je genauer $\tilde{x}_1$ desto kleiner erwarten wir $\|d(\tilde{x})\|$. Doch wie quantifizieren?
___
Problem: Die Norm $\|d(\tilde{x})\|$ kann durch Zeilenskalierung
$$
A x=b \quad \Leftrightarrow D_z A x=D_z b
$$
im Prinzip beliebig modifiziert werden.
___
Einen besseren Anhaltspunkt liefert der Rückivartsfeluler. Wir betrachten dazu das Maß
$$
y(\tilde{x})=\min \{\varepsilon \mid(A+\Delta A) \tilde{x}=b+\Delta b,\|\Delta A\|<\varepsilon\|A\|,\|\Delta b\|<\varepsilon\|b\|\}
$$
für den normweisen relativen Rückwärtsfehler des Problems $A x=b$.