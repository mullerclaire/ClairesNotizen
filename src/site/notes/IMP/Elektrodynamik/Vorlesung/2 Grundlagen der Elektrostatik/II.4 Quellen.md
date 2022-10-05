---
{"Aliases":[],"tags":[null],"dg-publish":true,"permalink":"/imp/elektrodynamik/vorlesung/2-grundlagen-der-elektrostatik/ii-4-quellen/","dgHomeLink":true,"dgPassFrontmatter":true}
---

# II.4 Quellen
Am Ort der Punktladungen gelten die Betrachtungen aus [[IMP/Elektrodynamik/Vorlesung/2 Grundlagen der Elektrostatik/II.3 Elektrisches Feld|II.3 Elektrisches Feld]] nicht, weil $\vec E(\vec x)$ bei $\vec x = 0$ singulär ist. 

Um dies umzugehen benutzen wir den Gauss'schen Integralsatz mit einer Kugel um die Punktladung. 

Dann verschwindet $\vec\nabla\cdot\vec E$ überall bis auf $\vec x=0$ wo es singulär ist. 

Die [[02 All notes/Ladungsdichte|Ladungsdichte]] ist $$\rho(\vec x)=q\delta(\vec x).$$
Damit gilt für $\vec\nabla\cdot\vec E$: 
```ad-equation
title: Erste Maxwell-Gleichung der Elektrostatik

$$\vec\nabla\cdot\vec E = \frac{1}{\e_0}\rho(\vec x).$$

In Integralform mit dem [[Gauss'scher Satz|Gauss'schen Satz]] ergibt sich: $$\int_V\mathrm{d}^3x\vec\nabla\cdot\vec E=\frac{1}{\e_0}Q_V=\frac{1}{\e_0}\int_V\mathrm{d}^3x\rho(\vec x)$$

```

Die Gesamtladung $Q_V$ im Gebiet $V$ wird bestimmt durch das elektrische Feld auf dem Rand $\partial V$.

___
Tags: #Physik/Elektrodynamik 
Links: 
Einheitensystem: [[02 All notes/Einheitensysteme für die Elektrodynamik#SI-System|Einheitensysteme für die Elektrodynamik#SI-System]]