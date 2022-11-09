---
{"dg-publish":true,"permalink":"/02-imp-notizen/taylor-entwicklung-von-feldern/"}
---

# Taylor Entwicklung von Feldern
## Taylor-Entwicklung einer differenzierbaren Funktion $f:\R\to\R$ um $x=x_0$
$$f(x)=\sum_{n=0}^N\frac{1}{n!}f^{(n)}(x_0)(x-x_0)^n+R_N(x-x_0)$$

## Taylor-Entwicklung von Feldern (mehrere Variablen)

Sei $\p(\vec x)$ ein [[Skalarfeld\|Skalarfeld]]. Wir wollen $\p(\vec x+\Delta\vec x)$ entwickeln. 

```ad-equation
title: Taylor-Entwicklung für skalare Felder

$$\p(\vec x+\Delta\vec x)=\sum_{n=0}^\infty\frac{1}{n!}(\Delta\vec x\cdot\vec\nabla_x)^n\p(\vec x)=\exp(\Delta\vec x\cdot\vec\nabla_x)\p(\vec x)$$
```

```ad-equation
title: Restglied Taylor-Entwicklung für skalare Felder
Wenn man nach $N$ Glieder abbricht:

$$R_N(\vec x)=\frac{1}{(N+1)!}(\Delta\vec x\cdot\vec\nabla_x)^{N+1}\p(\vec x+\xi\cdot\Delta\vec x)$$
```


