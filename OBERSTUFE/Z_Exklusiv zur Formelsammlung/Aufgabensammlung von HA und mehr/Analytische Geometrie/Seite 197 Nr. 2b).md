> Zeigen Sie, dass die Ebene $E$ die Kugel $K$ schneidet, und bestimmen Sie den Mittelpunkt  und den Radius des Schnittkreises.

- $K:(x_1+3)^2+(x_2-4)^2+(x_3-2)^2=15$
- $E:~3x_1-2x_2-6x_3=-53,5$
	- $E_0:\frac{1}{7}\cdot\left[3x_1-2x_2-6x_3+53,5\right]=0$

Aus $K$ erkennt man: $M(-3\mid4\mid2)$
>Zu zeigen ist, dass der Abstand des Mittelpunktes zu $E$ kleiner als der Radius ist.

$$
\begin{align}
	d(M;E)&=\left|\frac{1}{7}\cdot\left[3\cdot(-3)-2\cdot4-6\cdot2+53,5\right]\right|\\
	&=\left|\frac{1}{7}\cdot24,5\right|\\
	&=3,5<\sqrt{15}
\end{align}
$$
Für den Mittelpunkt des Schnittkreises gilt:
$$
\begin{align}
	\overrightarrow{OM'}&=\overrightarrow{OM}+\overrightarrow{n}\cdot
		\frac{d-\overrightarrow{n}\circ\overrightarrow{OM}}{\left|\overrightarrow{n}\right|^2}\\
		&=\begin{pmatrix}
				-3\\4\\2
			\end{pmatrix}+
			\begin{pmatrix}
				3\\-2\\-6
			\end{pmatrix}\cdot
			\frac{-1}{2}\\
		&=\begin{pmatrix}
				-4,5\\5\\5
			\end{pmatrix}
\end{align}
$$

Der Radius des Kreises ist durch $r'=\sqrt{r^2-d^2}$ beschrieben, wobei dadurch $r'=\sqrt{15-12,25}=\frac{\sqrt{11}}{2}\approx1,658$ ist.

---