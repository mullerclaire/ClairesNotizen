---
{"dg-publish":true,"permalink":"/02-imp-notizen/rueckwaertsstabilitaet/"}
---

# Rückwärtsstabilität
Die [[Implementierung\|Implementierung]] $\tilde{f}$ heißt **rückwärts stabil**, wenn für alle $x$ aus dem Definitionsbereich von $f$ und $\Delta x$ mit $\tilde{f}(x)=f(x+\Delta x)$ die Abschätzung $$\left|\frac{\Delta x}{x}\right|\leq C_R \, eps$$ für moderates, von $x$ unabhängiges $C_R$ gilt. 

> _"Ein rückwärtsstabiler Algorithmus liefert genau das richtige Resultat zu ungefähr der richtigen Eingabe."_

Mit einer Rückwärtsanalyse können Fehler von Teilschritte einer Implementation auf Eingabefehler zurückgespielt werden. Durch den Vergleich von Eingabefehler und Rückwärtsfehler können die Ergebnisse direkt bewertet werden. Alternativ ergibt sich eine Abschätzung des Vorwärtsfehlers durch Multiplikation mit der Kondition.

Dabei gilt:
- Notwendig: $\tilde{f}(U)$ im Bild von $f$ ! Gilt dies nicht, ist eine Rückwärtsanalyse nicht möglich und der Algorithmus ist instabil im Sinne der Rückwärtsanalyse.
- Ist $f$ nicht injektiv, kann es mehr als ein $\hat{x}$ geben. Dann wählt man $\hat{x}$ so dass $\|\hat{x}-x\|$ minimal wird.
Zudem gilt für eine rückwärts stabile Implementation
$$
\left|\frac{\tilde{f}(x)-f(x)}{f(x)}\right|=\left|\frac{f(x+\Delta x)-f(x)}{f(x)}\right| \approx \kappa_{r e l}\left|\frac{x+\Delta x-x}{x}\right| \leq C_R \kappa_{r e l} \text { eps }
$$
Also: Jeder rückwärts stabile Algorithmus ist auch vorwärts stabil. Die Umkehrung gilt im allgemeinen nicht!

Die Untersuchung von Kondition und Stabilität kann sehr aufwändig und technisch sein. Insbesondere ist die Verkettung stabiler Teilschritte nicht notwendigerweise stabil.