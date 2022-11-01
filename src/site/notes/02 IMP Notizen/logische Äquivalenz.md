---
{"dg-publish":true,"permalink":"/02-imp-notizen/logische-aequivalenz/"}
---

# Äquivalenz
Zwei [[02 IMP Notizen/Def 2.4 Formel der Aussagenlogik|Formeln]] $\p,\psi\in\mathsf{AL}$ sind _äquivalent_ (wir schreiben $\p\equiv\psi$), wenn sie von den selben [[02 IMP Notizen/Def 2.5 Interpretation|Interpretationen]] erfüllt werden, d.h., wenn für alle Interpretationen $\mathcal I$ gilt: $\mathcal I\models \p \iff \mathcal I \models \psi$.
Zwei Formelnmengen $\Phi,\Psi\in\mathsf{AL}$ sind _äquivalent_ (wir schreiben $\Phi\equiv\psi$), wenn sie von den selben Interpretationen erfüllt werden, d.h., wenn für alle Interpretationen $\mathcal I$ gilt: $\mathcal I \models \Phi \iff \mathcal I \models \Psi$.

- Zwei Formeln $\p,\psi\in\mathsf{AL}$ sind genau dann äquivalent, wenn in den letzten Spalten ihrer Wahrheitstafeln jeweils die gleichen Einträge stehen. 
- Für endliche Formelnmenge $\Phi=\{\p_1,...,\p_m\},\Psi=\{\psi_1,..,\psi_n\}\subseteq\mathsf{AL}$ gilt:

$$\Phi\equiv\Psi\iff \bigwedge\limits_{i=1}^m
\p_1\equiv \bigwedge\limits_{j=1}^n\psi_j.$$

