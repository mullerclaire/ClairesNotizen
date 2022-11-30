---
{"dg-publish":true,"permalink":"/02-imp-notizen/stoerungssatz/"}
---

# Störungssatz
Für eine submultiplikative und [[02 IMP Notizen/verträgliche Matrixnorm\|verträgliche Matrixnorm]] $\|\cdot\|$ sei $\operatorname{cond}(A) \frac{\|\Delta A\|}{\|A\|}<1$ und $x+\Delta x$ die Lösung von
$$
(A+\Delta A)(x+\Delta x)=b+\Delta b
$$
mit $b \neq 0$. Dann gilt
$$
\frac{\|\Delta x\|}{\|x\|} \leq \operatorname{cond}(A)\left(1-\operatorname{cond}(A) \frac{\|\Delta A\|}{\|A\|}\right)^{-1}\left(\frac{\|\Delta A\|}{\|A\|}+\frac{\|\Delta b\|}{\|b\|}\right)
$$
___
Wenn
$$
\operatorname{cond}(A) \frac{\|\Delta A\|}{\|A\|}=\left\|A^{-1}\right\| \cdot\|\Delta A\| \ll 1
$$
gilt
$$
\frac{\|\Delta x\|}{\|x\|} \leq \operatorname{cond}(A) \cdot \text { eps. }
$$
Auf einem Rechner mit Maschinengenauigkeit eps seien die Daten $A$ und $b$ mit relativen Fehlern $\leq$ eps behaftet. Der Störungssatz liefert dann, dass man wegen der Kondition der Aufgabe $(A, b) \rightarrow x=A^{-1} b$ einen unvermeidbaren Fehler der Größenordnung
$$
\operatorname{cond}(A) \cdot \text { eps }
$$
erwartet.