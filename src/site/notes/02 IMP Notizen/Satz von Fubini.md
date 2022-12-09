---
{"dg-publish":true,"permalink":"/02-imp-notizen/satz-von-fubini/"}
---

# Satz von Fubini

- Sei $E\subseteq\R^{n+m}$ [[02 IMP Notizen/Lebesgue-messbare Mengen\|Lebesgue-messbar]]. 
- Für $x\in\R^n$ sei $E_x:=\{y\in\R^m\mid (x,y)\in E\}$. 

Dann gibt es eine [[02 IMP Notizen/Lebesgue-Nullmenge\|Lebesgue-Nullmenge]] $N\subseteq\mathbb{R}^n$, sodass
1. Für alle $x\in\R^n\setminus N$ ist $E_x$ $\lambda_m$-[[02 IMP Notizen/Lebesgue-messbare Mengen\|messbar]]. 
2. Die Funktion $f:\R^n\to[0,\infty]$, $$f(x)=\begin{cases} \lambda_m(E_x) & \text{falls } y\notin N \\ 0 &\text{falls } x\in N\end{cases}$$ ist [[02 IMP Notizen/Lebesgue-messbare Abbildung\|Lebesgue-messbar]]. 
3. $\displaystyle\lambda_{n+m}(E)=\int_{\R^n} f(x)\,\d\lambda_n(x)$

