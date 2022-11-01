---
{"dg-publish":true,"permalink":"/02-imp-notizen/viii-1-freie-wellengleichung/"}
---

# VIII.1 Freie Wellengleichung
Ohne Quellen ($\rho=\vec{j}=0$) lauten die Maxwell-Gleichungen in linearen, homogenen Medien: $$\vec B=\mu_r\mu_0\vec H, \quad\vec D=\epsilon_r\epsilon_0\vec E,$$ mit $\mu_r,\epsilon_r$ die Beschreibung der Medien, und: 
- $\vec\nabla\cdot\vec E=0$, 
- $\vec\nabla\cdot\vec B=0$, 
- $\vec\nabla\times\vec E=-\partial_t\vec B$, 
- $\vec\nabla\times\vec B=(\epsilon_r\epsilon_0\mu_r\mu_0)\partial_t\vec E$.  

Aus $\epsilon_0\mu_0=\frac{1}{c^2}$ und $n=\sqrt{\epsilon_r\mu_r}$ (Brechungsindex) ergibt sich $\frac{1}{u}:=\sqrt{\epsilon_r\mu_r\epsilon_0\mu_0}=\frac{n}{c}$. 

Vakuum: $n=1$

$\vec E$ und $\vec B$ sind in diesen Gleichungen über ihre Rotationen gekoppelt, können aber durch erneute Rotation entkoppelt werden. 

$\begin{aligned} 0 &=\vec{\nabla} \times\left(\vec{\nabla} \times \vec{E}+\partial_{t} \vec{B}\right) \\ &=\vec{\nabla}(\vec{\nabla} \cdot \vec{E})-\Delta \vec{E}+\frac{n^{2}}{c^{2}} \partial_{t}^{2} \vec{E}=\left(\frac{n^{2}}{c^{2}} \partial_{t}^{2}-\Delta\right) \vec{E} \\ 0 &=\vec{\nabla} \times\left(\vec{\nabla} \times \vec{B}-\frac{n^{2}}{c^{2}} \partial_{t} \vec{E}\right) \\ &=\vec{\nabla}(\vec{\nabla} \cdot \vec{B})-\Delta \vec{B}+\frac{n^{2}}{c^{2}} \partial_{t}^{2} \vec{B}=\left(\frac{n^{2}}{c^{2}} \partial_{t}^{2}-\Delta\right) \vec{B} \end{aligned}$

Das heißt, beide Felder erfüllen identische freie Wellengleichungen: 
$$\square\vec E=0$$ und $$\square\vec B=0$$ mit dem [[02 IMP Notizen/Nabla-Operatoren#D'Alembert-Operator|D'alembert-Operator]] $\square$.

Bemerkungen zum Medium: 
- Hier wurde $n=1$ (Vakuum) gesetzt. 
- Übergang zu Wellen in homogenen linearen Medien: Änderung der Ausbreitungsgeschwindigkeit $c\to u=\frac{c}{n}$. 

Das heißt, $\vec E$, $\vec B$ und $A^\mu$ ([[Lorenz-Eichung|Lorenz-Eichung]]) erfüllen dieselbe freie (od. homogene) Wellengleichung $\square\psi(\vec x,t)=0$. 
