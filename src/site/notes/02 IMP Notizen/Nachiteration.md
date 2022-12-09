---
{"dg-publish":true,"permalink":"/02-imp-notizen/nachiteration/"}
---

# Algo 4.9 Nachiteration
- Gegeben: $A\in\mathbb{R}^{n\times n}, \quad b\in\mathbb{R}^n$

- Berechne [[02 IMP Notizen/LR-Zerlegung\|LR-Zerlegung]] $PA=LR$ (einfache Genauigkeit)
- Setze $d_0=b$, $x_0=0$. 
- Für $I=0,1,2,3,...$ berechne
	- $z_i$ aus $Lz_i=Pd_i$ (einfache Genauigkeit)
	- $w_i$ aus $Rw_i=Pd_i$ (einfache Genauigkeit)
	- $x_{i+1} =0= x_i+w_i$ (doppelte Genauigkeit)
	- $d_{i+1}=b-Ax_{i+1}$ (doppelte Genauigkeit)
- end. 




