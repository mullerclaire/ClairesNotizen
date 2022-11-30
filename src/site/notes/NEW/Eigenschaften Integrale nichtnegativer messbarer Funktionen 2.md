---
{"dg-publish":true,"permalink":"/new/eigenschaften-integrale-nichtnegativer-messbarer-funktionen-2/"}
---

# Eigenschaften Integrale nichtnegativer messbarer Funktionen 2
Sei $(X, \mathcal{A}, \mu)$ ein [[02 IMP Notizen/Maßraum\|Maßraum]], $E \in \mathcal{A}, f, g: E \rightarrow[0, \infty]$ [[02 IMP Notizen/A-messbare Funktion\|messbare]] Funktionen.

1. **Produkt mit Indikator-Funktion** Falls $A \subset E$ und $A \in \mathcal{A}$ dann gilt
$$
\int_A f d \mu=\int_E f \mathbf{1}_A d \mu .
$$
2. **Linearkombination** Für alle a, $b \in[0, \infty)$ gilt
$$
\int_E(a f+b g) d \mu=a \int_E f d \mu+b \int_E g d \mu
$$
(mit $0 \cdot \infty=0)$.

3. **Vereinigung disjunkter Mengen:** Falls $A: \mathbb{N} \rightarrow \mathcal{A}$ eine Folge paarweiser disjunkter [[02 IMP Notizen/messbare Menge\|messbarer Mengen]] mit $E=$ $\bigcup_{k \in \mathbb{N}} A_k$ ist, dann gilt
$$
\int_E f d \mu=\sum_k \int_{A_k} f d \mu .
$$
Insbesondere gilt für jede Menge $A \in \mathcal{A}$ mit $A \subset E$
$$
\int_E f d \mu=\int_A f d \mu+\int_{E \backslash A} f d \mu
$$
4. **Nullmengen** Falls $N \subset E$ eine $\mu$-[[02 IMP Notizen/mu-Nullmenge\|Nullmenge]] ist, dann gilt $\int_N f d \mu=0$.
5. **Nullfunktion:** $\int_E f d \mu=0 \Leftrightarrow f=0$ [[NEW/fast überall\|fast überall]].

**Bemerkung**
Aus 4. folgt, dass $\int_N f d \mu=0$ auch dann gilt, wenn $f(x)=\infty \,\forall x \in N$. 

