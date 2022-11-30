---
{"dg-publish":true,"permalink":"/02-imp-notizen/vorwaertsstabilitaet/"}
---

# Vorwärtsstabilität
Die Implementierung $\tilde f$ heißt vorwärts stabil, wenn für alle $x$ aus dem Definitionsbereich von $f$ ein moderates, von $x$ unabhängiges $C_V$ existiert, so dass $$\left|\frac{\tilde f(x) -f(x)}{f(x)}\right|\leq C_V\,\kappa_\text{rel}\,eps$$ gilt. 

> "_Ein vorwärts stabiler Algorithmus liefert ungefähr das richtige Resultat zu einer richtigen Eingabe._"

Für eine Vorwärtsanalyse werden typischerweise alle Teilschritte einer Implementation bezüglich ihrer Fehlerfortpflanzung untersucht und daraus der Gesamtfehler abgeschätzt. Dabei gilt: Einmal gemachte Fehler pflanzen sich fort (gemäß Stabilität und Kondition der Folgeschritte).

---
Siehe auch:
- [[eps\|eps]]