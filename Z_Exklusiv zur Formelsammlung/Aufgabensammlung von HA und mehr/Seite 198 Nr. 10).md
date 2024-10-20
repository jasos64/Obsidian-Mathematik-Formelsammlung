> Bestimmen Sie die Tangentialebenen an die Kugel $K$, die parallel zur Ebene $E$ sind. Bestimmen Sie auch die Koordinaten der Berührpunkte.

![[ParalleleTangentialebenenaufgenerellenKugeln]]


![[GeradeInKugel]]

---
## a)
- $E:3x_1-6x_2+2x_3=0$
- $K:x_1^2+x_2^2+x_3^2=196$
Daraus resultiert:
- $\vec n=\begin{pmatrix}3\\-6\\2\end{pmatrix}$
- $r=14$
- $M(0\mid0\mid0)\Rightarrow\overrightarrow{OM}=\begin{pmatrix}0\\0\\0\end{pmatrix}$

Von oben:
Die Tangentialebenen lauten:
$$
\begin{align}
	F_{1;2}:\vec{n}\circ\overrightarrow{OX}&=
		\vec{n}\circ\overrightarrow{OM}\pm r\cdot \left|\vec{n}\right|\\
	\begin{pmatrix}3\\-6\\2\end{pmatrix}\circ\overrightarrow{OX}&=
		\begin{pmatrix}3\\-6\\2\end{pmatrix}
		\circ\begin{pmatrix}0\\0\\0\end{pmatrix}\pm \underbrace{14\cdot \left|\begin{pmatrix}3\\-6\\2\end{pmatrix}\right|}_{=98}\\
	3x_1-6x_2+2x_3&={}\pm98
\end{align}
$$
Die Tangentialebenen lauten $3x_1-6x_2+2x_3={}\pm98$.

---
Die Berührpunkte der Tangentialebenen werden mittels einer zu $F$ senkrechten normierten Lotgerade bestimmt:
$$
\begin{align}
	\overrightarrow{OS_{1;2}}&=\overrightarrow{OM}\pm
		\frac{r}{\left|\overrightarrow{n}\right|}\cdot\overrightarrow{n}\\
	&=\begin{pmatrix}0\\0\\0\end{pmatrix}\pm
		\underbrace{\frac{14}{\left|\begin{pmatrix}3\\-6\\2\end{pmatrix}\right|}}_{=2}
		\cdot\begin{pmatrix}3\\-6\\2\end{pmatrix}\\
	&=\pm\begin{pmatrix}6\\-12\\4\end{pmatrix}
\end{align}
$$
Daraus resultieren die Berührpunkte
- $S_1(6\mid-12\mid4)$
- $S_2(-6\mid12\mid-4)$

---
---
## b)
- $E:\vec x\circ\begin{pmatrix}7\\-4\\-4\end{pmatrix}=0$
- $K:\left[\vec x-\begin{pmatrix}2\\7\\9\end{pmatrix}\right]^2=81$
Daraus resultiert:
- $\vec n=\begin{pmatrix}7\\-4\\-4\end{pmatrix}$
- $r=9$
- $\overrightarrow{OM}=\begin{pmatrix}2\\7\\9\end{pmatrix}$

Von oben:
Die Tangentialebenen lauten:
$$
\begin{align}
	F_{1;2}:\vec{n}\circ\overrightarrow{OX}&=
		\vec{n}\circ\overrightarrow{OM}\pm r\cdot \left|\vec{n}\right|\\
	\begin{pmatrix}7\\-4\\-4\end{pmatrix}\circ\overrightarrow{OX}&=
		\underbrace{\begin{pmatrix}7\\-4\\-4\end{pmatrix}
		\circ\begin{pmatrix}2\\7\\9\end{pmatrix}}_{-50}\pm \underbrace{9\cdot \left|\begin{pmatrix}7\\-4\\-4\end{pmatrix}\right|}_{=81}\\
	7x_1-4x_2-4x_3&=-50\pm81
\end{align}
$$
Die Tangentialebenen lauten $7x_1-4x_2-4x_3=-50\pm81$.

---
Die Berührpunkte der Tangentialebenen werden mittels einer zu $F$ senkrechten normierten Lotgerade bestimmt:
$$
\begin{align}
	\overrightarrow{OS_{1;2}}&=\overrightarrow{OM}\pm
		\frac{r}{\left|\overrightarrow{n}\right|}\cdot\overrightarrow{n}\\
	&=\begin{pmatrix}2\\7\\9\end{pmatrix}\pm
		\underbrace{\frac{9}{\left|\begin{pmatrix}7\\-4\\-4\end{pmatrix}\right|}}_{=9}
		\cdot\begin{pmatrix}7\\-4\\-4\end{pmatrix}\\
	&=\begin{pmatrix}2\\7\\9\end{pmatrix}
		\pm\begin{pmatrix}7\\-4\\-4\end{pmatrix}
\end{align}
$$
Daraus resultieren die Berührpunkte
- $S_1(9\mid3\mid45)$
- $S_2(-5\mid11\mid13)$

---
## c)
- $E:7x_1-4x_2-4x_3=0$
- $K:x_1^2+x_2^2+x_3^2+6x_1+12x_3-279=0$

$$
\begin{align}
	K:x_1^2+x_2^2+x_3^2+6x_1+12x_3-279&=0\\
	\underbrace{x_1^2+6x_1}+\underbrace{x_2^2}+
		\underbrace{x_3^2+12x_3}&=279\\
	\underbrace{x_1^2+6x_1+9}+\underbrace{x_2^2}+
		\underbrace{x_3^2+12x_3+36}&=279+9+36\\
	(x_1+3)^2+x_2^2+(x_3+6)^2&=324
\end{align}
$$

Daraus resultiert:
- $\vec n=\begin{pmatrix}7\\-4\\-4\end{pmatrix}$
- $r=18$
- $\overrightarrow{OM}=\begin{pmatrix}-3\\0\\-6\end{pmatrix}$

Von oben:
Die Tangentialebenen lauten:
$$
\begin{align}
	F_{1;2}:\vec{n}\circ\overrightarrow{OX}&=
		\vec{n}\circ\overrightarrow{OM}\pm r\cdot \left|\vec{n}\right|\\
	\begin{pmatrix}7\\-4\\-4\end{pmatrix}\circ\overrightarrow{OX}&=
		\underbrace{\begin{pmatrix}7\\-4\\-4\end{pmatrix}
		\circ\begin{pmatrix}-3\\0\\-6\end{pmatrix}}_{=3}\pm \underbrace{18\cdot \left|\begin{pmatrix}7\\-4\\-4\end{pmatrix}\right|}_{=162}\\
	7x_1-4x_2-4x_3&=3\pm162
\end{align}
$$
Die Tangentialebenen lauten $7x_1-4x_2-4x_3=3\pm162$.

---
Die Berührpunkte der Tangentialebenen werden mittels einer zu $F$ senkrechten normierten Lotgerade bestimmt:
$$
\begin{align}
	\overrightarrow{OS_{1;2}}&=\overrightarrow{OM}\pm
		\frac{r}{\left|\overrightarrow{n}\right|}\cdot\overrightarrow{n}\\
	&=\begin{pmatrix}-3\\0\\-6\end{pmatrix}\pm
		\underbrace{\frac{18}{\left|\begin{pmatrix}7\\-4\\-4\end{pmatrix}\right|}}_{=2}
		\cdot\begin{pmatrix}7\\-4\\-4\end{pmatrix}\\
	&=\begin{pmatrix}-3\\0\\-6\end{pmatrix}
		\pm\begin{pmatrix}14\\-8\\-8\end{pmatrix}
\end{align}
$$
Daraus resultieren die Berührpunkte
- $S_1(11\mid-8\mid-14)$
- $S_2(-17\mid8\mid2)$

---