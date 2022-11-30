---
{"dg-publish":true,"permalink":"/new/elementare-eigenschaften-der-einfachen-funktionen/"}
---

# elementare Eigenschaften der einfachen Funktionen
$\operatorname{Sei}(X, \mathcal{A}, \mu)$ ein Maßraum, $E \in \mathcal{A}$
1. *Summe von Indikator-Funktionen:* $\varphi: E \rightarrow \mathbb{R}$ ist genau dann einfach, wenn $F: \mathbb{N} \rightarrow \mathcal{A}$ und $c: \mathbb{N} \rightarrow[0, \infty)$ existieren, sodass $F_j \cap F_k=\emptyset$ für $j \neq k$ und
$$
\varphi(x)=\sum_{h \in \mathbb{N}} c_h \mathbf{1}_{F_h}(x) .
$$
1. *Linearkombination:* Falls $\varphi, \psi: E \rightarrow \mathbb{R}$ einfach sind, und $a, b \geq 0$, dann $\operatorname{sind} a \varphi+b \psi, \varphi \psi$, $\max \{\varphi, \psi\}$ und $\min \{\varphi, \psi\}$ einfach. Es gilt
$$
\int_E(a \varphi+b \psi) d \mu=a \int_E \varphi d \mu+b \int_E \psi d \mu .
$$
1. *Produkt mit Indikator-Funktionen:* Falls $\varphi: E \rightarrow \mathbb{R}$ einfach ist, $A \subset E$ und $A \in \mathcal{A}$, dann ist $\varphi \mathbf{1}_A: E \rightarrow \mathbb{R}$ einfach und
$$
\int_A \varphi d \mu=\int_E \varphi \mathbf{1}_A d \mu
$$
1. *Vereinigung disjunkter Mengen:* Falls $\varphi: E \rightarrow \mathbb{R}$ einfach ist und $A: \mathbb{N} \rightarrow \mathcal{A}$ eine Folge paarweiser disjunkter messbarer Mengen mit $E:=\bigcup_{k \in \mathbb{N}} A_k$ ist, dann gilt
$$
\int_E \varphi d \mu=\sum_k \int_{A_k} \varphi d \mu .
$$
Insbesondere gilt für jede Menge $A \in \mathcal{A}$ mit $A \subset E$
$$
\int_E \varphi d \mu=\int_A \varphi d \mu+\int_{E \backslash A} \varphi d \mu .
$$
1. *Monotonie:* Falls $\varphi, \psi: E \rightarrow \mathbb{R}$ einfach sind, und $\varphi \leq \psi$, dann gilt:
$$
\int_E \varphi d \mu \leq \int_E \psi d \mu
$$
