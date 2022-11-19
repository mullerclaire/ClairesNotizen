---
{"dg-publish":true,"permalink":"/numerische-lineare-algebra/"}
---

# numerische Lineare Algebra
## 1. Einleitung
### 1.1 Lineare Problemstellungen
### 1.2 Numerische Lösungsverfahren

## 2. Das Gauß-Verfahren I
### 2.1 Gaußsche Eliminationsverfahren und LR-Zerlegung
[[Rückwärtssubstitution\|Rückwärtssubstitution]]
[[02 IMP Notizen/Landau-Symbole\|Landau-Symbole]]
[[02 IMP Notizen/LR-Zerlegung#ohne Spaltenpivotisierung\|LR-Zerlegung#ohne Spaltenpivotisierung]]

[[02 IMP Notizen/induzierte Matrixnorm\|induzierte Matrixnorm]]
[[02 IMP Notizen/p-Matrixnormen\|p-Matrixnormen]]
### 2.2 Pivot-Strategien
[[02 IMP Notizen/LR-Zerlegung#mit Spaltenpivotisierung\|LR-Zerlegung#mit Spaltenpivotisierung]]
### 2.3 Cholesky-Verfahren für symmetrisch positiv definite Matrizen
[[Schurkomplement\|Schurkomplement]]
[[Cholesky-Zerlegung\|Cholesky-Zerlegung]]
[[Cholesky-Verfahren\|Cholesky-Verfahren]]

## 3. Fehleranalyse
Die Fehleranalyse kann mit der Dreiecksungleichung in 2 wichtige Konzepte zerlegt werden: $$\|f(x)-\tilde{f}(\tilde{x})\|\leq\|f(x)-f(\tilde{x})\|+\|f(\tilde{x})-\tilde{f}(\tilde{x})\|$$
Gseamtfehler $\leq$ Kondition des Problems + Stabilität des Algorithmus
### 3.1 Kondition eines numerischen Problems
[[02 IMP Notizen/numerisches Problem\|numerisches Problem]]
[[02 IMP Notizen/wohl gestelltes Problem, schlecht gestelltes Problem\|wohl gestelltes Problem, schlecht gestelltes Problem]]

[[02 IMP Notizen/absolute Kondition des Problems\|absolute Kondition des Problems]]
[[02 IMP Notizen/relative Kondition des Problems\|relative Kondition des Problems]]

### 3.2 Stabilität des Algorithmus 
#### Vorwärtsanalyse
[[Vorwärtsstabilität\|Vorwärtsstabilität]]
___
# Alle Notizen
- [[00 General/Templates/simple note/num lin alg template\|num lin alg template]]
- [[02 IMP Notizen/Konditionszahlen\|Konditionszahlen]]
- [[02 IMP Notizen/LR-Zerlegung\|LR-Zerlegung]]
- [[02 IMP Notizen/Landau-Symbole\|Landau-Symbole]]
- [[02 IMP Notizen/absolute Kondition des Problems\|absolute Kondition des Problems]]
- [[02 IMP Notizen/induzierte Matrixnorm\|induzierte Matrixnorm]]
- [[02 IMP Notizen/numerisches Problem\|numerisches Problem]]
- [[02 IMP Notizen/p-Matrixnormen\|p-Matrixnormen]]
- [[02 IMP Notizen/relative Kondition des Problems\|relative Kondition des Problems]]
- [[02 IMP Notizen/wohl gestelltes Problem, schlecht gestelltes Problem\|wohl gestelltes Problem, schlecht gestelltes Problem]]
- [[numerische Lineare Algebra\|numerische Lineare Algebra]]

___
# Übungsblätter
[[Uebungsserie-01.pdf]]
[[Uebungsserie-02.pdf\|Uebungsserie-02.pdf]]
[[Uebungsserie-03.pdf]]
[[Uebungsserie-04.pdf]]
