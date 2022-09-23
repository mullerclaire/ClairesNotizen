---
{"dg-publish":true,"permalink":"/imp-aktuell/elektrodynamik/vorlesung/2-grundlagen-der-elektrostatik/ii-5-elektrostatisches-potential/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# II.5 Elektrostatisches Potential
### Exaktheit
Die  [[IMP Aktuell/Elektrodynamik/Vorlesung/2 Grundlagen der Elektrostatik/II.3 Elektrisches Feld#^ef1230|zweite differentielle Eigenschaft]] $\vec\nabla\times\vec E=\vec 0$ des [[IMP Aktuell/Elektrodynamik/Vorlesung/2 Grundlagen der Elektrostatik/II.3 Elektrisches Feld#^0deff7|elektrischen Feldes]] gilt exakt. Dies folgt aus dem [[IMP Aktuell/Elektrodynamik/Zusammenfassungen/mathematische Grundlagen/Stoke'scher Satz|Stoke'schen Satz]]: siehe [[IMP Aktuell/Elektrodynamik/Zusammenfassungen/mathematische Grundlagen/Stoke'scher Satz#^9e8ef4|Beispiel]]. 

## $\vec E$ und $\varphi$ 
$\vec E(\vec x)$ ist ein _konservatives Feld_ und besitzt ein **elektrostatisches Potential**: 
```ad-equation
title: Elektrostatisches Potential

$$\vec E(\vec x)=-\vec\nabla\phi(\vec x)=-\text{grad}\,\phi(\vec x).$$

```
Durch die Unabhängigkeit von Weg erhält man: 
```ad-equation
title: für geschlossene Kurven
$$\oint_{\partial A}\mathrm{d}\vec x\cdot\vec E(\vec x)=0$$

```
## Fall einer Punktladung
```ad-equation
title: elektrostatisches Potential für eine Punktladung

$$\phi(\vec x)=\frac{q}{4\pi\e_0|\vec x|}$$
```
## Beliebige Ladungsverteilungen
Aus dem Superpositionsprinzip folgt das elektrostatische Potential für beliebige Ladungsverteilung: 
```ad-equation
title: Elektrostatische Potential für beliebige diskrete Ladungsverteilungen

$$\phi(\vec x)=\sum_{i=1}^N\frac{q_i}{4\pi\e_0|\vec x-\vec x_i|}$$

```
und für kontinuierliche Ladungsdichten: 
```ad-equation
title: elektrostatisches Potential für kontinuierliche Ladungsdichte $\rho(\vec x)$

$$\phi(\vec x) = \int\mathrm{d}^3y\frac{\rho(\vec y)}{4\pi\e_0|\vec x-\vec y|}$$

```
*Achtung*: Potential nur bis auf globale konstante Verschiebung definiert. Nur Potentialdifferenzen besitzen physikalischen Gehalt. 

## 2. Maxwell-Gleichung der Elektrostatik
```ad-equation
title: Zweite Maxwell-Gleichung der Elektrostatik

$$\vec\nabla\times\vec E=0$$

```
```ad-equation
title: Zweite Maxwell-Gleichung der Elektrostatik: Integralform

$$\oint_\gamma\mathrm{d}\vec x\cdot\vec E=\vec 0$$

```
## Konstruktion der Poisson-Gleichung
Wenn man in den 2 Maxwell-Gleichungen der Elektrostatik das Potential $-\vec\nabla\phi(\vec x)$ einsetzt ergibt sich die **[[Poisson-Gleichung|Poisson-Gleichung]]**: 
```ad-equation
title: Poisson-Gleichung 🐟

$$-\vec\nabla^2\phi(\vec x)=\frac{1}{\e_0}\rho(\vec x)$$

```

oder anders geschrieben: 
```ad-equation
title: Poisson-Gleichung mit Laplace-Operator

$$-\triangle\phi(\vec x)=\frac{1}{\e_0}\rho(\vec x)$$

```
Elektrostatik wird so auf das Auffinden eines skalaren Feldes reduziert, das der Poisson-Gleichung genügt. 