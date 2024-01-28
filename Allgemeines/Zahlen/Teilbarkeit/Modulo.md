Modulo beschreibt das Teilen einer Zahl mit Rest.
Teilt man $a$ und $b$ aus $\mathbb{N}$ mit $\bmod$, so ist der Rest das Ergebnis dieser Operation.

---
Beispiele:
$$\begin{align}
	a\bmod b&=m&&\text{weil }a-\lfloor\frac{a}{b}\rfloor\cdot b=m\\
	7\bmod{3}&=1&&\text{weil }7-\cancelto{2}{\lfloor\frac{7}{3}\rfloor}\cdot 3=1\\
	
	64\bmod{5}&=4&&\text{weil }64-\cancelto{12}{\lfloor\frac{64}{5}\rfloor}\cdot 5=1\\
\end{align}$$
Daraus folgt für alle $m=0$, dass $a$ und $b$ durch eine Division eine Zahl aus $\mathbb{Z}$ hervorbringt.
Somit gilt für alle Teiler von $a$: $a\bmod T_{a}=0$

---