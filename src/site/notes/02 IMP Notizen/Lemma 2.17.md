---
{"dg-publish":true,"permalink":"/02-imp-notizen/lemma-2-17/"}
---

# Lemma 2.17
Sei $(X, \mathcal{A}, \mu)$ ein [[02 IMP Notizen/Maßraum\|Maßraum]], $E \in \mathcal{A}, f: E \rightarrow[0, \infty]$ messbar. Folgendes gilt.
$$
f^{-1}((0, \infty]) \sigma-\text { endlich } \Longrightarrow \quad \int_E f d \mu=\sup _{\varphi \text { einfach, } \varphi \leq f, \varphi \in \mathcal{A}} \int_E \varphi d \mu
$$
wobei
$$
\begin{aligned}
\mathcal{A}:=\{\varphi: F \rightarrow[0, \infty) \mid \exists F \subset E \text { mit } F& \in \mathcal{A}, \mu(F)<\infty, \\
\varphi &\left.=\varphi \mathbf{1}_F \text { und } \# \varphi(F)<\infty,\right\}
\end{aligned}
$$
___
Bemerkung. Sei $(X, \mathcal{A}, \mu)$ ein Maßraum, $E \in \mathcal{A}, f: E \rightarrow[0, \infty]$ messbar. Folgendes gilt.
1. Falls $f^{-1}((0, \infty]) \sigma$-endlich ist, dann existiert eine monoton wachsende Folge einfacher Funktionen $\psi_k: E \rightarrow[0, \infty)$ mit $\# \psi_k(E)<\infty, \int_E \psi_k d \mu<\infty \forall k, \psi_k \rightarrow f$ punktweise fast überall und
$$
\lim _{k \rightarrow \infty} \int_E \psi_k d \mu=\int_E f d \mu
$$
2. Die Annahme " $f^{-1}((0, \infty]) \,\sigma$-endlich" gilt automatisch wenn mindestens eine der folgenden Aussagen gilt:
	1. $E$ ist $\sigma$-endlich
	2. $(X, \mathcal{A}, \mu)=\left(\mathbb{R}^n, \mathcal{M}_n, \mathcal{L}^n\right)$
	3. $f$ ist integrierbar.