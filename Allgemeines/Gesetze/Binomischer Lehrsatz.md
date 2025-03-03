Für [Binome](Binom) $n$-ten Grades gilt:
$$
\left(x+y\right)^n=
	\sum^{n}_{k=0}
		\begin{pmatrix}
			n\\k
		\end{pmatrix}
	\cdot x^ky^{n-k}
$$

---
## Beweis
Für natürliche Zahlen $n\ge0$ gilt $\left(x+y\right)^n=\sum^{n}_{k=0}\begin{pmatrix}n\\k\end{pmatrix}\cdot x^ky^{n-k}$.

### Induktionsanfang
Für $n=0$ ergibt sich:
$$
\begin{align}
	\left(x+y\right)^n&\stackrel{!}{=}\sum^{n}_{k=0}
			\begin{pmatrix}
				n\\k
			\end{pmatrix}
		\cdot x^ky^{n-k}\\
		
	\left(x+y\right)^0&\stackrel{!}{=}\sum^{0}_{k=0}
			\begin{pmatrix}
				0\\k
			\end{pmatrix}
		\cdot x^ky^{0-k}\\
		
	\left(x+y\right)^0&\stackrel{!}{=}
		\begin{pmatrix}0\\0\end{pmatrix}x^0y^0\\
	\left(x+y\right)^0&\stackrel{!}{=}
		x^0y^0\\
	1&\equiv 1
\end{align}
$$
Für $n=0$ gilt somit die Aussage.

### Induktionsvoraussetzung
Oben zeigt sich durch $1=1$, dass:
$$\exists n\in\mathbb{N},\quad\left(x+y\right)^n=\sum^{n}_{k=0}\begin{pmatrix}n\\k\end{pmatrix}\cdot x^ky^{n-k}$$

### Induktsionsschritt
Da es ein $n$ gibt, so muss es für alle $n\to n+1$ gelten:
$$
\begin{align}
	\left(x+y\right)^{n+1}&=
	\left(x+y\right)\cdot\left(x+y\right)^{n}\\
	
	&\stackrel{\textbf{IV}}{=}\left(x+y\right)\cdot\sum^{n}_{k=0}\begin{pmatrix}n\\k\end{pmatrix}\cdot x^ky^{n-k}
\end{align}
$$
