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
	\sum^{n+1}_{k=0}
		\begin{pmatrix}
			n+1\\k
		\end{pmatrix}
	\cdot x^ky^{(n+1)-k}\\
	
	&=
	\sum^{n}_{k=0}
		\begin{pmatrix}
			n+1\\k
		\end{pmatrix}
	\cdot x^ky^{n+1-k}
		+\begin{pmatrix}n+1\\n+1
		\end{pmatrix}
	\cdot x^{n+1}y^{n+1-(n+1)}\\
	
	&=
	\sum^{n}_{k=0}
		\left(
		\begin{pmatrix}n\\k-1\end{pmatrix}+
		\begin{pmatrix}n\\k\end{pmatrix}
		\right)
	\cdot x^ky^{n+1-k}
		+\begin{pmatrix}n+1\\n+1
		\end{pmatrix}
	\cdot x^{n+1}y^{n+1-(n+1)}\\
	
	&=
	\sum^{n}_{k=0}
	\begin{pmatrix}n\\k-1\end{pmatrix}
	\cdot x^ky^{n+1-k}
		+
		\textcolor{orange}{\sum^{n}_{k=0}\begin{pmatrix}n\\k\end{pmatrix}\cdot x^ky^{n+1-k}}+
		\begin{pmatrix}n+1\\n+1
		\end{pmatrix}
	\cdot x^{n+1}y^{n+1-(n+1)}\\
	
	&\stackrel{IV}{=}
		\textcolor{orange}{(x+y)^n}+
		\sum^{n}_{k=0}
	\begin{pmatrix}n\\k-1\end{pmatrix}
	\cdot x^ky^{n+1-k}+\begin{pmatrix}n+1\\n+1
		\end{pmatrix}
	\cdot x^{n+1}y^{n+1-(n+1)}\\
	
	&=
		(x+y)^n+
		\sum^{n}_{k=0}
	\begin{pmatrix}n\\k-1\end{pmatrix}
	\cdot x^ky^{n+1-k}+x\cdot x^{n}\\
	
	&=
		(x+y)^n+
		\sum^{n}_{k=0}
	\begin{pmatrix}n\\k-1\end{pmatrix}
	\cdot x^ky^{n+1-k}+x\cdot x^{n}\\
\end{align}
$$
