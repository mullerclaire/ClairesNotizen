---
{"dg-publish":true,"permalink":"/02-imp-notizen/satz-der-monotonen-konvergenz/"}
---

# Satz der monotonen Konvergenz

$\operatorname{Sei}(X, \mathcal{A}, \mu)$ ein Maßraum, $E \in \mathcal{A}$
1. Sei $f_k: E \rightarrow[0, \infty]$ eine monoton wachsende Folge messbarer Funktionen. Das heißt, für alle $k \in \mathbb{N}$ ist $f_k$ messbar und $f_k \leq f_{k+1}$.
   Dann gilt
$$
\lim _{k \rightarrow \infty} \int_E f_k d \mu=\int_E \lim _{k \rightarrow \infty} f_k d \mu .
$$
2. Sei $g_k: E \rightarrow[0, \infty]$ eine Folge messbarer Funktionen.
   Dann gilt
$$
\sum_{k \in \mathbb{N}} \int_E g_k d \mu=\int_E \sum_{k \in \mathbb{N}} g_k d \mu
$$