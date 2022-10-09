---
{"dg-publish":true,"permalink":"/02-all-notes/green-sche-identitaeten/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Green'sche Identitäten
Seien 
- $\p(\vec x)$ und $\psi(\vec x)$ zweifach stetig differenzierbare Skalarfelder und
- $V\subset\R^3$ ein von der Oberfläche $S(V)$ umschlossenes Volumen

```ad-equation
title: Erste Green'sche Identität

$$
\int_{V} \mathrm{~d} V(\varphi \Delta \psi+(\vec{\nabla} \psi) \cdot(\vec{\nabla} \varphi))=\oint_{S(V)} \mathrm{d} f \,\varphi \frac{\partial \psi}{\partial n}
$$

```
wobei
- $\mathrm{d}f=|\mathrm{d}\vec f|$ und 
- $\displaystyle\frac{\partial\psi}{\partial n}=\vec\nabla\psi\cdot\vec n(\vec x)$ (Normalableitung)
- mit [[02 All notes/Flächenintegral#Flächennormale|Flächennormale]] $\mathrm{d}\vec f=\mathrm{d}f\vec{n}(\vec{x})$. 

```ad-equation
title: Zweite Green'sche Identität

$$\int_V\mathrm{d}V(\p\Delta\psi-\psi\Delta\p)=\oint_{S(V)}\mathrm{d}f\left(\p\frac{\partial\psi}{\partial n}-\psi\frac{\partial\p}{\partial n}\right)$$

```

^d3e462



___
Tags: #Physik/Elektrodynamik 
Links: 
Nummer: