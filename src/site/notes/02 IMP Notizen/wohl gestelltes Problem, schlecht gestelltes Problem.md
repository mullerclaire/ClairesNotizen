---
{"dg-publish":true,"permalink":"/02-imp-notizen/wohl-gestelltes-problem-schlecht-gestelltes-problem/"}
---

# wohl gestelltes Problem, schlecht gestelltes Problem 
Ein [[02 IMP Notizen/numerisches Problem\|numerisches Problem]] heißt **wohlgestellt**, falls es eine Konstante $L_{abs}\geq0$ gibt, so dass $$\|f(\tilde{x})-f(x)\|\leq L_{abs}\|\tilde{x}-x\|+\mathcal{o}(\|\tilde{x}-x\|)\quad (\text{für }\tilde{x}\to x).$$

Existiert keine solche Konstante, heißt $(f,x)$ **schlecht gestellt**. 

Dabei ist obige Ungleichung eine asymptotische Abschätzung mit $$g\in o(\varepsilon) \iff |\frac{g(\varepsilon)}{\varepsilon}|\to 0 \quad\text{für }\varepsilon\to 0, $$ d.h. für ein $\delta>0$ ist das numerische Problem Lipschitz-stetig für $\|\tilde{x}-x\|<\delta$ unter Vernachlässigung von Störungstermen höherer Ordnung. 

$L_{abs}$ beschreibt *Fehlerverstärkung* im Grenzfall sehr kleiner Störungen.