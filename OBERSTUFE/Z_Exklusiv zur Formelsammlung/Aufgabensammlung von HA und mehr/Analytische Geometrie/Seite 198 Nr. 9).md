> Zeigen Sie, dass sich die Kugeln $K_1=\vec x^2=49$ und $K_2=\left[\vec{x}-\begin{pmatrix}3\\9\\4,5\end{pmatrix}\right]^2=\frac{49}{4}$ berühren.
> Bestimmen Sie die Koordinaten des Berührpunktes und geben Sie eine Gleichung der gemeinsamen Tangentialebene an.

Von oben gegeben ist:
- $r_1=7$
- $r_2=3,5$
- $M_1(0\mid0\mid0)$
- $M_2(3\mid9\mid4,5)$

Um zu zeigen, dass sich beide Kugeln berühren, so muss folgendes gelten: $|\overrightarrow{M_1M_2}|=r_1+r_2$.
$$
\begin{align}
	|\overrightarrow{M_1M_2}|&=|\overrightarrow{OM_2}-\overrightarrow{OM_1}|\\
	&=\left|\begin{pmatrix}3\\9\\4,5\end{pmatrix}-\begin{pmatrix}0\\0\\0\end{pmatrix}\right|\\
	&=\left|\begin{pmatrix}3\\9\\4,5\end{pmatrix}\right|\\
	&=\sqrt{3^2+9^2+4,5^2}=10,5\\\\
	r_1+r_2&=7+3,5\\
	&=10,5\\
	\Rightarrow\quad|\overrightarrow{M_1M_2}|&=r_1+r_2
\end{align}
$$

Dadurch ist gezeigt, dass sich die Kugeln berühren.

![[GeradeInKugel]]

$$
\begin{align}
	\overrightarrow{OS_1}&=\overrightarrow{OM_1}+
		\frac{r_1}{\left|\overrightarrow{M_1M_2}\right|}
		\cdot\overrightarrow{M_1M_2}\\
	&=\begin{pmatrix}0\\0\\0\end{pmatrix}+
		\frac{7}{\left|\begin{pmatrix}3\\9\\4,5\end{pmatrix}\right|}
		\cdot\begin{pmatrix}3\\9\\4,5\end{pmatrix}\\
	&=\frac{7}{10,5}
		\cdot\begin{pmatrix}3\\9\\4,5\end{pmatrix}\\
	&=\begin{pmatrix}2\\6\\3\end{pmatrix}\\
	&\Rightarrow S(2\mid6\mid3)
\end{align}
$$

Die Tangentialebene lautet:
$$
\begin{align}
	E:\overrightarrow{M_1M_2}\circ\left[\overrightarrow{OX}-\overrightarrow{OS}\right]&=0\\
	3x_1+9x_2+4,5x_3&=73,5
\end{align}
$$

---
---