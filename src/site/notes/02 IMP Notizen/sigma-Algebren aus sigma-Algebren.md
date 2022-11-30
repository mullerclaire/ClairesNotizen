---
{"dg-publish":true,"permalink":"/02-imp-notizen/sigma-algebren-aus-sigma-algebren/"}
---

# Lemma 1.4 sigma-Algebren aus sigma-Algebren
1. Sei $I$ eine beliebige Indexmenge und für jedes $\alpha\in I$ sei $\mathcal{A}_\alpha\subseteq\mathcal{P}(X)$ eine [[02 IMP Notizen/Sigma-Algebra\|Sigma-Algebra]] über $X$. 
	1. $\mathcal{A}=\displaystyle\bigcap_{\alpha\in I}\mathcal{A}_\alpha$ ist eine σ-Algebra
	2. $\mathcal{A}=\displaystyle\bigcup_{\alpha\in I}\mathcal{A}_\alpha$ ist *__keine__* σ-Algebra
2. Sei $Y \subseteq X$ und A eine $\sigma$-Algebra anf $X$. Dann ist $A_y:=\{A \cap Y: A \in A\}$ eine $\sigma$-Algebra auf Y, sog. [[02 IMP Notizen/Spur Sigma-Algebra\|Spur Sigma-Algebra]].
3. Sei $Z$ eine Menge mit $\sigma$-Algebra $\mathcal{A}_Z$. Für jede Abbildung $T: X \rightarrow Z$ ist $$
\mathcal{A}_T:=\left\{T^{-1}(A): A \in \mathcal{A}_Z\right\}$$ eine $\sigma$-Algebra aus $X$.