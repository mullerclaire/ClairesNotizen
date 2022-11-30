---
{"dg-publish":true,"permalink":"/02-imp-notizen/induzierte-matrixnorm/"}
---

# induzierte Matrixnorm
Seien $\|\cdot\|_X: \mathbb{R}^n \rightarrow \mathbb{R}$ und $\|\cdot\|_Y: \mathbb{R}^m \rightarrow \mathbb{R}$ zwei Vektornormen. Dann ist die von $\|\cdot\|_X$ und $\|\cdot\|_Y$ **induzierte Matrixnorm** definiert als
$$
\|A\|:=\sup _{\|x\|_X=1}\|A x\|_Y .
$$
Der entscheidende Begriff ist induziert!
Ist $A \in \mathbb{R}^{n \times n}$, stimmen also Urbild- und Bildraum überein, vereinbaren wir, für beide Räume die gleiche Norm zu verwenden. Sprich: $\|\cdot\|_X=\|\cdot\|_Y$.

Für die induzierte Matrixnorm gilt:
$$
\|A\|=\sup _{\|x\|_X \leq 1}\|A x\|_Y=\sup _{\|x\|_X \neq 0} \frac{\|A x\|_Y}{\|x\|_X} .
$$
Außerdem kann statt sup auch max stehen.