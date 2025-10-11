> Gegeben ist die Funktionenschar $f_t$ mit $f_t(x)=x^3-tx;\quad t>0$.

## a)
> Skizzieren Sie die Graphen der Schar für verschiedene Parameter $t$ in ein gemeinsames Koordinatensystem. Was bewirkt eine Erhöhung des Parameters?

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-2,2,-2,2]
disableZoom: true
grid: true
---
f(x)=x^3-x
f(x)=x^3-2x
f(x)=x^3-3x
```
- $\textcolor{Blue}{f_1(x)}$
- $\textcolor{Red}{f_2(x)}$
- $\textcolor{Green}{f_3(x)}$
Die Erhöhung des Parameters $t$ bewirkt einen Anstieg der minimalen Steigung an der Stelle $x=0$.

---
## b)
> Für welchen Wert $t$ verläuft der Graph von $f_t$ durch $P(1\mid-3)$?

Es gilt $f_t(1)=-3$:
$$
\begin{align}
	-3&=f_t(1)\\
	-3&=1^3-t\cdot1&&\mid -1\\
	-4&=-t&&\mid\cdot(-1)\\
	t&=4
\end{align}
$$
Damit $f_t$ durch $P$ geht, muss $t=4$ sein. Folglich geht $f_4(x)$ durch $P$.

---
## c)
> Welche Steigung hat der Graph von $f_t$ im Ursprung?

Es gilt $f_t'(0)$:
$$
\begin{align}
	f_t(x)&=x^3-tx\\
	f_t'(x)&=3x^2-t\\
	f_t'(0)&=3\cdot0^2-t\\
	f_t'(0)&=-t
\end{align}
$$
Die Steigung im Ursprung ist $-t$. Dadurch ist die Steigung durch $t>0$ immer negativ.

---
## d)
> Für welchen Wert von $t$ hat der Graph von $f_t$ an der Stelle $2$ die Steigung $8$?

Es gilt $f_t'(2)=8$:
$$
\begin{align}
	8&=f_t'(2)\\
	8&=3\cdot2^2-t&&\mid-12\\
	-4&=-t&&\mid\cdot(-1)\\
	t&=4
\end{align}
$$

---
---