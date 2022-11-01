---
{"dg-publish":true,"permalink":"/02-imp-notizen/green-sche-funktion/"}
---

# Green'sche Funktion
Eine symmetrische Funktion $G(\vec x,\vec x')$ mit der Eigenschaft: 
```ad-equation
title: (1) Eigenschaft der Green'schen Funktion
$$\triangle_x G(\vec x,\vec x')=-\delta^{(3)}(\vec x-\vec x'),$$ mit $\triangle_x = \vec\nabla^2_x = \sum_{i=1}^3(\frac{\partial}{\partial x_i})^2.$
```

Aufgrund der Symmetrie gilt (1) auch mit $\triangle_{x'}$. 

Die Lösung von (1) ist 
```ad-equation
title: Green'sche Funktion

$$G(\vec x,\vec x') = \frac{1}{4\pi}\frac{1}{|\vec x-\vec x'|}+f(\vec x,\vec x')$$
```
Die Funktion $f(\vec x,\vec x')$ mit $\triangle_xf(\vec x,\vec x')=0$ in $V$ ist noch unbestimmt, wird aber durch Dirichlet- oder Neumann-Randbedingungen festgelegt. 