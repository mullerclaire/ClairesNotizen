---
{"dg-publish":true,"permalink":"/02-imp-notizen/iv-4-vektorpotential/"}
---

# IV.4 Vektorpotential
## Definition
Wir haben gesehen, dass die magnetische Induktion sich als Rotation eines Vektorfeldes schreiben lässt: $$\vec B(\vec x)=\vec\nabla_x\times\frac{\mu_0}{4\pi}\int\d^3y\frac{\vec j(\vec y)}{|\vec x-\vec y|}=\vec\nabla_x\times\vec A.$$
$\vec A(\vec x)$ wird **Vektorpotential** genannt. Es ist nicht eindeutig: siehe nächster Abschnitt. 

```ad-equation
title: Vektorpotential

$$\vec A(\vec x)=\frac{\mu_0}{4\pi}\int\d^3y\frac{\vec j(\vec y)}{|\vec x-\vec y|}$$

```
## Eichtransformationen
```ad-equation
title: Eichtransformation
Es ist die Addition eines beliebigen Gradientenfeldes zum Vektorpotential: 

$$\vec A'(\vec x')=\vec A(\vec x)+\vec\nabla\Lambda(\vec x)$$

Sie lässt das $\vec B$-Feld invariant ! 
```
Die jeweiligen Vektorpotentiale sind physikalisch äquivalent (weil sie nicht messbar sind), was eine wichtige Eigenschaft des Elektromagnetismus ist. 

### Eichfixierung/Eichwahl
Sie dient dazu, das Randwertproblem der Magnetostatik zu vereinfachen: man will nämlich dabei keine unphysikalische Freiheitsgrade bestimmen müssen. 
Bedingunen: 
- Eichung sollte unphysikalische Freiheitsgrade in $\vec A$ eliminieren.
- Eichung darf nicht zu restriktiv sein, d.h. jedes Feld $\vec B(\vec x)$ muss sich realisieren lassen. 
Gebräuchliche Eichungen: 
```ad-definition
title: Coulomb-Eichung

$\vec\nabla\cdot\vec A(\vec x)=0$

```
```ad-definition
title: Axiale Eichung

$\vec n\cdot\vec A(\vec x)=0$ mit festem $\vec n$. 

```
## Poisson-Gleichungen
Mithilfe des Vektorpotentials in der Coulomb-Eichung reduzieren sich die Maxwell-Gleichungen der Magnetostatik auf drei Poisson-Gleichungen. 

```ad-equation
title: Poisson-Gleichungen der Magnetostatik

$$\triangle\vec A(\vec x)=-\mu_0\vec j(\vec x)$$

```
*Bemerkungen:*
- Eine Gleichung für jede Komponente von $\vec A$ und $\vec j$. Jede Komponente kann getrennt beobachtet werden.  
- Sie sind analog zur [[02 IMP Notizen/Poisson-Gleichung der Elektrostatik\|Poisson-Gleichung der Elektrostatik]]. 

## Grundproblem der Magnetostatik
*Gegeben:*
- $\vec j(\vec x)$ im Raumbereich $V$
- Randbedingungen auf $\partial V$

*Gesucht:*
- Lösungen von $\triangle\vec A(\vec x)=-\mu_0\vec j(\vec x)$, die die Randbedingungen erfüllen. 

Welche Randbedingungen auftreten wird im Kapitel V erklärt. 