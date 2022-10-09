---
{"Aliases":["elektrisches Feld"],"tags":["Physik/Elektrodynamik"],"dg-publish":true,"permalink":"/02-all-notes/ii-3-elektrisches-feld/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# II.3 Elektrisches Feld
## Allgemeines
Wenn man in einem Raum viele Ladungen $q_j$ hat ($j=1,\ldots,N$), dann wird der Raum von einem **Elektrischen Feld** gefüllt. 

Für eine Testladung $q$ bedeutet das, dass sie die Kraft $\vec F$ erfährt, welche proportional zu $q$ ist und sich an jedem Raumpunkt verändert: $$\vec F = q\cdot\vec E(\vec x).$$
Mit $\vec E$ das elektrische Feld, das den Raum füllt und unabhängig von der Testladung existiert: $$\vec E(\vec x) = \sum_{j=1}^N\frac{q_j(\vec x-\vec x_j)}{4\pi\e_0|\vec x-\vec x_j|^3}.$$
## Grenzfall sehr vieler Punktladungen
In diesem Fall benutzt man die [[Ladungsverteilung|Ladungsverteilung]] $\rho(\vec x)$ und das elektrische Feld wird zu: 
```ad-equation
title: Elektrisches Coulomb-Feld

$$\vec E(\vec x) = \int\mathrm{d}^3y\frac{\rho(\vec y)(\vec x-\vec y)}{4\pi\e_0|\vec x-\vec y|^3}$$

```

^0deff7

## Differentielle Eigenschaften
```ad-equation
title: Differentielle Eigenschaften des Elektrischen Feldes

$$\text{div}\,\vec E = \vec\nabla\cdot\vec E=0$$ und $$\text{rot}\,\vec E = \vec\nabla\times\vec E=\vec 0$$

```

^ef1230

___
Tags: #Physik/Elektrodynamik 
Einheitensystem: [[02 All notes/Einheitensysteme für die Elektrodynamik#SI-System|Einheitensysteme für die Elektrodynamik#SI-System]]
Links: [[02 All notes/II.2 Coulombgesetz|II.2 Coulombgesetz]]