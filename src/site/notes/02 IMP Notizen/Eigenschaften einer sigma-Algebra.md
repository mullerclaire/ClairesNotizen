---
{"dg-publish":true,"permalink":"/02-imp-notizen/eigenschaften-einer-sigma-algebra/"}
---

# Lemma 1.3 Eigenschaften einer $\sigma$-Algebra
Sei $X$ eine nichtleere Menge, $\mathcal A$ eine [[02 IMP Notizen/σ-Algebra\|σ-Algebra]] über X. Dann gilt 
1. $A,B\in\mathcal A\implies (A\cup B\in\mathcal A \land A\setminus B\in\mathcal A)$
2. $X, \emptyset\in\mathcal A$
3. Falls $A_k\in\mathcal A$ für alle $k\in\N$, dann ist $\displaystyle\bigcap_{k\in\N}A_k\in\mathcal A$.

**Beweis von 1**
- Seien $A, B \in \mathcal{A}$. Wir betrachten die Folge $A_0:=A, A_1:=B$ und $A_j=A$ für alle $j \geq 2$. Dann gilt $A_j \in \mathcal{A}$ für alle $j$, und aus [[02 IMP Notizen/σ-Algebra#Vereinigung abzählbar vieler Mengen\|σ-Algebra#Vereinigung abzählbar vieler Mengen]] folgt, dass $A \cup B=\bigcup_{j=0}^{\infty} A_j \in \mathcal{A}$. Außerdem gilt
$$
A^c \in \mathcal{A} \Rightarrow A^c \cup B \in \mathcal{A} \Rightarrow\left(A^c \cup B\right)^c=A \cap B^c=B \backslash A \in \mathcal{A}
$$
- Nach der Definition gibt es eine Menge $A \in \mathcal{A}$. Dann gilt $A^c \in \mathcal{A}$ und aus $(i)(a)$ folgt, dass $X=A \cup A^c \in \mathcal{A}$ und daher auch $\emptyset=X^c \in \mathcal{A}$ gilt.
- Für alle $j \in \mathbb{N}$ sei $A_j \in \mathcal{A}$. Dann gilt:
$$
\forall j \in \mathbb{N}: A_j^c \in \mathcal{A} \Rightarrow \forall j: A_j^c \in \mathcal{A} \Rightarrow \bigcup_{i=0}^{\infty} A_j^c \in \mathcal{A} \Rightarrow \bigcap_{i=0}^{\infty} A_j=\left(\bigcup_{i=0}^{\infty} A_j^c\right)^c \in \mathcal{A}
$$