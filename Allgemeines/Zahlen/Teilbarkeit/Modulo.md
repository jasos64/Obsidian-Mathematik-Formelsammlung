Modulo beschreibt das Teilen einer Zahl mit Rest.

Wird eine Zahl $a \bmod b$ (alternativ auch $a~\%~b$) für $\{a;b\} \in \mathbb{N}$ gerechnet so ist das aus dieser Rechnung resultierende Ergebnis der Rest einer Division mit $a$ und $b$ wobei es sich bei $a$ um den *Dividend* und bei $b$ um den *Divisor* handelt.

---
## Beispiele:
$$\begin{align}
	a\bmod b&=m&&\text{weil }a-\bigg\lfloor\frac{a}{b}\bigg\rfloor\cdot b=m\\
	7\bmod{3}&=1&&\text{weil }7-\cancelto{2}{\bigg\lfloor\frac{7}{3}\bigg\rfloor}\cdot 3=1\\
	
	64\bmod{5}&=4&&\text{weil }64-\cancelto{12}{\bigg\lfloor\frac{64}{5}\bigg\rfloor}\cdot 5=1
\end{align}$$
Daraus folgt für alle $m=0$, dass $a$ und $b$ durch eine Division eine Zahl aus $\mathbb{Z}$ hervorbringen.
Somit gilt für alle Teiler von $a$: $a\bmod T_{a}=0$

---
## Beispiele von höhere Sets
Ich nehme mal an, dass zunächst $\{a;b\}\in\mathbb{Q}$ betrachtet wird und dieses funktioniert.
$$\begin{align}
	a\bmod b&=m&&\text{weil }a-\bigg\lfloor\frac{a}{b}\bigg\rfloor\cdot b=m\\
	7,5\bmod{2,25}&=0,75&&\text{weil }7,5-\cancelto{3}{\bigg\lfloor\frac{7,5}{2,25}\bigg\rfloor}\cdot 2,25=0,75\\
\end{align}$$
Visualisiert erkennt man dies gut, da die grün gefärbten Boxen hier eine Verkürzung von $0,75$ Einheiten bilden.
<iframe src="https://www.desmos.com/calculator/xyveyqh0kz?embed" width="1000" height="500" style="border: 1px solid #ccc" frameborder=10></iframe>
Übergeordnet für höhere Sets würden diese funktionieren.