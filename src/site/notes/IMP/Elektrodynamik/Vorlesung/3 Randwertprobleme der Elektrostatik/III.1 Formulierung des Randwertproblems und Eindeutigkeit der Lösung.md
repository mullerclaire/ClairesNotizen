---
{"Aliases":[],"tags":[null],"dg-publish":true,"permalink":"/imp/elektrodynamik/vorlesung/3-randwertprobleme-der-elektrostatik/iii-1-formulierung-des-randwertproblems-und-eindeutigkeit-der-loesung/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# III.1 Formulierung des Randwertproblems und Eindeutigkeit der Lösung
**Ziele:** 
- zu klären, ob die [[IMP/Elektrodynamik/Vorlesung/2 Grundlagen der Elektrostatik/II.5 Elektrostatisches Potential#Konstruktion der Poisson-Gleichung|Poisson-Gleichung]] eine eindeutige Lösung hat 
- Lösungsmethoden finden in Anwesenheit von Randbedingungen.

# Formulierung und Eindeutigkeit
## Randwertproblem der Poisson-Gleichung
_Gegegeben:_
1. $\rho(\vec x)$ auf kompaktem Gebiet $V\subset\R^3$ mit Rand $\partial V$
2. Randbedingungen für $\phi(\vec x)|_{\partial V}$. 

_Gesucht:_
$\phi(\vec x)$ mit $\vec x\in V\subset\R^3$

Wir wollen verstehen, unter welchen Randbedingungen eine eindeutige Lösung vorliegt. Die [[02 All notes/Green'sche Identitäten#^d3e462|zweite Greensche Identität]] führt uns zur Lösung für das gesuchte elektrisches Potential: $$\phi(\vec{x})=\underbrace{\frac{1}{4 \pi \epsilon_{0}} \int_{V} \mathrm{~d}^{3} x^{\prime} \frac{\rho\left(\vec{x}^{\prime}\right)}{\left|\vec{x}-\vec{x}^{\prime}\right|}}_{\text {Coulombpotential }}+\underbrace{\frac{1}{4 \pi} \int_{\partial V} \mathrm{~d} f\left\{\frac{1}{\left|\vec{x}-\vec{x}^{\prime}\right|} \frac{\partial \phi}{\partial n^{\prime}}-\phi\left(\vec{x}^{\prime}\right) \frac{\partial}{\partial n^{\prime}} \frac{1}{\left|\vec{x}-\vec{x}^{\prime}\right|}\right\}}_\text{Randbeiträge}$$
Bemerkungen: 
- Ladungen außerhalb von $V$ gehen nur implizit über Randbedingungen ein; das Potential wird auf $V$ durch $\rho(\vec x)$ bestimmt und auf $\partial V$ durch die Randbedingungen. 
- Ist $V$ ladungsfrei, so bestimmen die Randwerte von $\phi$ oder $\frac{\partial\phi}{\partial n}$ das Feld in $V$. 
- Ist $V$ der gesamte Raum, so verschwinden die Randbeiträge. 
- Man sollte _entweder_ $\phi$ _oder_ $\frac{\partial\phi}{\partial n}$ auf $\partial V$ angeben, nicht beide, sonst ist das Problem überbestimmt. 

## Klassifikation der Randbedingungen
1. **Dirichlet-Randbedingungen**: Das _Potential_ ist auf dem Rand gegeben $$\phi(\vec x) = \omega(\vec x)$$ für $\vec x\in\partial V$. 
2. **Neumann-Randbedingungen**: Die Normalableitung $\frac{\partial \phi}{\partial n}$, d.h. $$E_\perp=\vec n\cdot\vec E=-\vec n\cdot\vec\nabla\phi=-\frac{\partial \phi}{\partial n}=\nu(\vec x)$$ ist auf dem Rand gegeben. 
==Mit diesen Randbedingungen wird die Lösung der Poisson-Gleichung eindeutig bestimmt.==

siehe Beweis im [[ED.pdf]] Seite 33. 