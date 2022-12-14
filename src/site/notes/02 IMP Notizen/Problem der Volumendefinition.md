---
{"dg-publish":true,"permalink":"/02-imp-notizen/problem-der-volumendefinition/"}
---

# Problem der Volumendefinition

## Erwünschte Volumenfunktion: 
$$\mu:A\subset\R^n\to\mu(A)$$ = Volumen von $A\in[0,+\infty]$ mit den folgenden Eigenschaften: 

1. **Translationsinvarianz**: für $x_0\in\R^n$ gilt $\mu(A+x_0)=\mu(A)$.
2. **Geometrisches Volumen**: Ist $W=[a_1,b_1]\times...\times[a_n,b_n]\subset\R^n$ ein Quader, so ist $\mu(W)$ das geometrische Volumen, d.h. $$\mu(W)=\prod_{j=1}^{n}(b_j-a_j).$$
3. **$\sigma$-Additivität**: Sind $A_1,A_2,...$ abzählbar viele disjunkte Teilmengen des $\R^n$, so gilt $$\mu\left(\bigcup_{n=1}^\infty\right)=\sum_{n=1}^\infty\mu(A_n)$$
4. **Monotonie**: $A\subset B \implies \mu(a)\leq\mu(B)$
   Sie folgt aus der $\sigma$-Additivität: $B=A\cup(B\setminus A)$, also $$\mu(B)\overset{(3)}{=}\mu(A)+\mu(B\setminus A)\geq\mu(A)$$

## Satz (Vitali, 1905)
Es existiert keine Funktion $\mu:\mathcal P(\R^n)\to[0,\infty]$  mit den Eigenschaften 1-4, d.h. ein n-dimensionales Volumen kann nicht für alle Teilmengen des $\R^n$ definiert werden. 

**Ausweg** Definiere $\mu$ nur auf "ausgewählten" interessanten (offenen, kompakten...) Teilmengen des $\R^n$.

___

### Beweis
- Angenommen, es existiere eine solche Funktion. 

#### Konstruktion der Menge der Repräsentanten
- Wir betrachten auf $[0,1]^n\subset\R^n$ folgende [[02 IMP Notizen/Äquivalenzrelation\|Äquivalenzrelation]]: $$x\sim y\Longleftrightarrow x-y\in\mathbb Q^n.$$
- Sei $M\subset[0,1]^n$ eine Teilmenge, die aus jeder Äquivalenzklasse genau ein Element enthält ([[02 IMP Notizen/Auswahlaxiom\|Auswahlaxiom]]). Es gilt: 
	- $\forall x\in[0,1]^n, \quad\exists y_x\in M: x\sim y_x.$
	- ($x,y\in M$ mit $x\sim y$) $\implies x=y$.

- **Behauptung 1:** $\forall q,q'\in \Q^n$ mit $q\neq q': (M+q)\cap(M+q')=\emptyset$.
	Beweis: Angenommen es existiert ein $x\in(M+q)\cap(M+q').$  $\implies\exists y,y'\in M: x = y+q=y'+q'$
	$\implies y-y'=q-q'\in\Q^n$ 
	$\implies y\sim y'$
	$\implies y=y'$
	$\implies q=q'.$ Widerspruch ⚡

- **Behauptung 2:** $[0,1]^n\subseteq V:=\displaystyle\bigcup_{q\in\Q^n\cap[-1,1]^n}(M+q)$.
    Beweis: Sei $x\in[0,1]^n$ beliebig. 
    $\implies \exists y_x\in M, q_x\in\Q^n: x=y_x+q_x$
    Wegen $x,y_x\in[0,1]^n$ gilt $q_x=x-y_x\in[-1,1]^n.$
    $\implies x = y_x+q_x\in M+q_x\subseteq V.$

#### Der Widerspruch
- Es gilt $1=\mu([0,1]^n)\leq\mu(V)\leq\mu([-1,2]^n)=\mu([0,3])=3^n$
- Dazu $\mu(V)=\displaystyle\sum_{q\in\Q^n\cap[-1,1]^n}\mu(M+q)=\sum_{q\in\Q^n\cap[-1,1]^n}\mu(M) = \begin{cases}0 & \mu(M)=0\implies 1\leq\mu(V)=0\\ \infty & \mu(M)>0 \implies \infty=\mu(V)\leq 3^n\end{cases}$ Widerspruch ⚡






---
### Archiv Beweis
- Wir betrachten die Menge $$B:=\bigcup_{r\in[-1,1]^n\cap\mathbb Q^n} A+\{r\}.$$
- Da $\mathbb Q^n$ abzählbar ist, ist $B$ die Vereinigung abzählbar vieler Mengen. Des Weiteren gilt: 
	1. $B$ ist eine disjunkte Vereinigung. 
	2. Wir betrachten $\mu(B)$. 
		- Nach Def ist $[0,1]^n\subset B\subset[-1,2]^n$
		- Monotonie: $1\leq\mu(B)\leq 3^n$
		- $\sigma$-Additivität und Translationsinvarianz: $$1\leq\sum_{r\in[-1,1]^n\cap\mathbb Q} \mu(A+\{r\})\leq 3^n$$
			Um $\mu(B)$ zu erhalten, wird $\mu(A)$ unendlich oft addiert. Dies bleibt aber nicht beschränkt, da $\mu(A)>0$. Damit haben wir einen Widerspruch erhalten.  
