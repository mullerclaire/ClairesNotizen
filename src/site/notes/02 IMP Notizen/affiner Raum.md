---
{"dg-publish":true,"permalink":"/02-imp-notizen/affiner-raum/"}
---

# affiner Raum
Eine _Menge_ M, auf der der $K$-[[02 IMP Notizen/Vektorraum|Vektorraum]] $V$ [[02 IMP Notizen/einfach transitiv|einfach transitiv]] [[02 IMP Notizen/Wirkung|operiert]], heißt ein **affiner Raum** (mit zugehörigem $K$-Vektorraum $V$). 
___
==Beispiel:== Sei $G=V$ ein $K$-Vektorraum (bzw. die dem $K$-Vektorraum zugrunde liegende abelsche Gruppe) und $M=V$. Dann wird durch
$$
(x, v) \mapsto v+x\quad(x, v \in V)
$$
eine Operation von $V$ auf sich selbst gegeben.
___
Wir bezeichnen den bis auf Bijektivität eindeutig bestimmten affinen Raum mit zugehörigen $K$-Vektorraum $V$ durch $\mathbf{A}(V)$. 

Die Elemente von $\mathbf{A}(V)$ nennen wir **Punkte** ($O,P,Q,R...$)

Die [[02 IMP Notizen/einfach transitiv|einfach transitive]] Wirkung $\bullet$ von $V$ auf $\mathbf{A}(V)$ bezeichnen wir durch ein $+$-Zeichen ($\neq$ Addition von Vektoren): $$x\bullet P= P+x.$$ Punkt $P+x$ wird erhalten durch "Anheften des Vektors $x\in V$ an den Punkt $P\in\mathbf{A}(V)$". 

Ist $Q=P+x$, so nennen wir den eindeutig bestimmten Vektor $x\in V$ mithilfe dessen $Q$ aus $P$ hervorgeht, den **Verbindungsvektor von $P$ nach $Q$**: $$x = \overrightarrow{PQ}.$$
Indem wir schließlich einen Punkt $O\in\mathbf{A}(V)$ fixieren, stellt sich die Bijektion $$\psi=\psi_O:V\to\mathbf A(V)$$ dar durch $$x\mapsto P=O+x.$$
Die Umkehrabbildung $$\p=\p_O:\mathbf A(V)\to V$$ ist gegeben durch die Zuordnung $$P\mapsto\overrightarrow{OP}.$$
Die Bijektion $\p_O$ ist nicht [[kanonisch|kanonisch]], da sie von der Wahl des Punktes $O$ abhängt. 