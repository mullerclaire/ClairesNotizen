---
{"dg-publish":true,"permalink":"/02-imp-notizen/sprungfunktion/","dgHomeLink":true,"dgPassFrontmatter":false}
---

# Sprungfunktion
## allgemeine Definition
Wir betrachten das Integral: 
$$G(x,\epsilon)=\int_{-\infty}^x\mathrm{d}x'\,g_\epsilon(x) = \frac{1}{\pi}\left[\arctan\frac{x}{\epsilon}+\frac{\pi}{2}\right]$$
![Capture d’écran 2022-02-25 à 12.49.02.png|200](data:image/png;base64,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)
Damit definieren wir die Sprungfunktion: 
```ad-equation
title: Sprungfunktion

$$\theta(x):=\lim_{\epsilon\to0}G(x,\epsilon)=\begin{cases}1 & x>0\\ 0 & x<0\end{cases}$$

```

## Definition als Integral über die [[02 IMP Notizen/Deltafunktion|Deltafunktion]]
Es gilt: 
$$\theta(x)=\int_{-\infty}^x\mathrm{d}x'\delta(x')$$ und
```ad-equation
title: Sprungfunktion und Deltafunktion

$$\delta(x)=\frac{\mathrm{d}\theta(x)}{\mathrm{d}x}.$$
```
Anschließend können wir also die Sprungfunktion auf einfacher Weise so schreiben: 
```ad-equation
title: Sprungfunktion

$$\theta(x)=\begin{cases}1 & x>0\\\frac{1}{2} & x=0\\ 0 & x<0\end{cases}$$

```
(oder anstatt 1/2 einen anderen Wert festlegen)
Dies impliziert insbesondere, dass $$\int_0^\infty\mathrm{d}x\,\delta(x)=\frac{1}{2}$$

___
Tags: #Physik/Elektrodynamik 