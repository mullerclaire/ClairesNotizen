---
{"dg-publish":true,"permalink":"/02-imp-notizen/multipolentwicklung/"}
---

# Multipolentwicklung
## Potential im Fernfeld
Taylor-Entwicklung vom Potential 
## Spezialfälle/Multipolmomente
Def: 
1. Monopolmoment (Gesamtladung): $$q=\int\d^3x'\rho(\vec x')$$
2. Dipolmoment: $$\vec p=\int\d^3x'\vec x'\rho(\vec x)$$
3. Quadrupolmoment (Quadrupoltensor):  
	1. Diskret: $$Q_{k l}=\sum_{i=1}^{n} q_{i}\left(3 r_{i k} r_{i l}-\left(r_{i}\right)^{2} \delta_{k l}\right)$$ mit $3 r_{i k} r_{i l}-\left(r_{i}\right)^{2} \delta_{k l}=\displaystyle\sum_{k=1}^n\sum_{l=1}^n\left(3 r_{i k} r_{i l}-\left(r_{i}\right)^{2} \delta_{k l}\right)$
	2. Kontinuierlich: $$Q_{i j}=\int \mathrm{d}^{3} x^{\prime} \rho\left(\vec{x}^{\prime}\right)\left(3 x_{i}^{\prime} x_{j}^{\prime}-\vec{x}^{2} \delta_{i j}\right)$$
4. Multipolenentwicklung in der Fernfeldnäherung: $$\phi(\vec x )\overset{|\vec x|\gg R}{\approx}\frac{1}{4\pi\e_0}\left(\frac{q}{|\vec x|}+\frac{\vec x\cdot\vec p}{|\vec x|^3}+\frac{1}{2}\sum_{i,j=1}^{3}Q_{ij}\frac{x_ix_j}{|\vec x|^5}+...\right)$$