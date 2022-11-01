---
{"dg-publish":true,"permalink":"/02-imp-notizen/iv-5-kraft-drehmoment-und-energie-des-b-feldes/"}
---

# IV.5 Kraft, Drehmoment und Energie des B-Feldes
Im Raum wirkt eine gegebene magnetische Induktion $\vec B(\vec x)$ mit einer Kraft $\vec F=\displaystyle\int\d^3x\,\vec j(\vec x)\times\vec B(\vec x)$ und einem [[02 IMP Notizen/Drehmoment|Drehmoment]] $\vec M= \displaystyle\int\d^3x\,\vec x\times\left(\vec j(\vec x)\times\vec B(\vec x)\right)$ auf eine [[02 IMP Notizen/Stromdichte|Stromdichte]]. 

### homogenes $\vec B$-Feld ($\vec B=\vec B_0=const.$)

#### Kraft auf eine stationäre Stromdichte
Ein homogenes B-Feld übt *keine Kraft* auf eine **stationäre Stromdichte** $\vec j(\vec x)$ aus. 

Das Verschwinden des Integrals folgt aus der Überlegung $\vec{j}=(\vec{j} \cdot \vec{\nabla}) \vec{x}$, der Quellenfreiheit der Stromstärke und deren Lokalisierung, da
$$
\int d^{3} x \vec{j}(\vec{x})=\int d^{3} x(\vec{j} \cdot \vec{\nabla}) \vec{x} \stackrel{P . I .}{=}-\int d^{3} x \underbrace{(\vec{\nabla} \vec{j})}_{=0} \vec{x}=0
$$
#### Drehmoment auf eine lokalisierte Stromdichte
$$\vec M=\left(\frac{1}{2}\int\d^3x\,\vec x\times\vec j(\vec x)\right)\times\vec B_0$$
Wir definieren das magnetische Moment $\vec m$ einer lokalisierten Stromdichte als:
```ad-definition
title: magnetisches Moment einer lokalisierten Stromdichte
$$\vec m:=\frac{1}{2}\int\d^3x\,\vec x\times\vec j(\vec x)$$

```

Damit lautet das Drehmoment: 
```ad-equation
title: Drehmoment einer lokaliserten Stromdichte in einem homogenen $\vec B$-Feld

$$\vec M=\vec m\times\vec B_0$$

```
#### Fernfeld des Vektorpotentials
$$\vec{A}(\vec{x})=\frac{\mu_{0}}{4 \pi} \frac{\vec{m} \times \vec{x}}{|\vec{x}|^{3}}+\ldots$$
### schwach inhomogenes Feld

