# 1)
> Berechnen Sie zu den Vektoren $\vec a$ und $\vec b$ jeweils einen Vektor $\vec c$, für den $\vec a\circ \vec c=0$ und $\vec b\circ \vec c=0$ gilt und weisen Sie nach, dass er diese Bedingungen erfüllt.

## a)
- $\vec{a}=\begin{pmatrix}2\\1\\0\end{pmatrix}$
- $\vec{b}=\begin{pmatrix}1\\1\\3\end{pmatrix}$

$$
\begin{align}
	\vec{c}&=\vec{a}\times\vec{b}\\
	&=\begin{pmatrix}2\\1\\0\end{pmatrix}\times
		\begin{pmatrix}1\\1\\3\end{pmatrix}\\
	&=\begin{pmatrix}1\cdot3-0\cdot1\\
		0\cdot1-2\cdot3\\2\cdot1-1\cdot1\end{pmatrix}\\
	&=\begin{pmatrix}3\\-6\\1\end{pmatrix}\\\\
	
	\vec{a}\circ\vec{c}&=\begin{pmatrix}2\\1\\0\end{pmatrix}\circ
		\begin{pmatrix}3\\-6\\1\end{pmatrix}\\
	&=2\cdot3-1\cdot6+0\cdot1\\
	&=0\\
	\vec{b}\circ\vec{c}&=\begin{pmatrix}1\\1\\3\end{pmatrix}\circ
		\begin{pmatrix}3\\-6\\1\end{pmatrix}\\
	&=1\cdot3-1\cdot6+3\cdot1\\
	&=0
\end{align}
$$
## b)
- $\vec{a}=\begin{pmatrix}2\\-3\\2\end{pmatrix}$
- $\vec{b}=\begin{pmatrix}1\\1\\-3\end{pmatrix}$

$$
\begin{align}
	\vec{c}&=\vec{a}\times\vec{b}\\
	&=\begin{pmatrix}2\\-3\\2\end{pmatrix}\times
		\begin{pmatrix}1\\1\\-3\end{pmatrix}\\
	&=\begin{pmatrix}-3\cdot(-3)-2\cdot1\\
		2\cdot1-(-3)\cdot2\\2\cdot1-(-3)\cdot1\end{pmatrix}\\
	&=\begin{pmatrix}7\\8\\5\end{pmatrix}\\\\
	
	\vec{a}\circ\vec{c}&=\begin{pmatrix}2\\-3\\2\end{pmatrix}\circ
		\begin{pmatrix}7\\8\\5\end{pmatrix}\\
	&=2\cdot7-3\cdot8+2\cdot5\\
	&=0\\
	\vec{b}\circ\vec{c}&=\begin{pmatrix}1\\1\\-3\end{pmatrix}\circ
		\begin{pmatrix}7\\8\\5\end{pmatrix}\\
	&=1\cdot7+1\cdot8-3\cdot5\\
	&=0
\end{align}
$$
## c)

- $\vec{a}=\begin{pmatrix}9\\3\\1\end{pmatrix}$
- $\vec{b}=\begin{pmatrix}2\\-4\\5\end{pmatrix}$

$$
\begin{align}
	\vec{c}&=\vec{a}\times\vec{b}\\
	&=\begin{pmatrix}9\\3\\1\end{pmatrix}\times
		\begin{pmatrix}2\\-4\\5\end{pmatrix}\\
	&=\begin{pmatrix}3\cdot5-1\cdot(-4)\\
		1\cdot2-9\cdot5\\9\cdot(-4)-3\cdot2\end{pmatrix}\\
	&=\begin{pmatrix}19\\-43\\-42\end{pmatrix}\\\\
	
	\vec{a}\circ\vec{c}&=\begin{pmatrix}9\\3\\1\end{pmatrix}\circ
		\begin{pmatrix}19\\-43\\-42\end{pmatrix}\\
	&=9\cdot19-3\cdot43-1\cdot42\\
	&=0\\
	\vec{b}\circ\vec{c}&=\begin{pmatrix}2\\-4\\5\end{pmatrix}\circ
		\begin{pmatrix}19\\-43\\-42\end{pmatrix}\\
	&=2\cdot19+4\cdot43-5\cdot42\\
	&=0
\end{align}
$$

---
# 2)
> Für die Ebenen $E$ sind Normalenvektoren zu ermitteln. Geben Sie zu jeder Ebene drei mögliche Normalenvektoren an.

## a)
$$
\begin{align}
	E:\vec{x}&=\begin{pmatrix}2\\1\\-1\end{pmatrix}
		+r\cdot\begin{pmatrix}4\\2\\6\end{pmatrix}
		+s\cdot\begin{pmatrix}-2\\2\\4\end{pmatrix}\\\\
	\vec{n}&=\begin{pmatrix}4\\2\\6\end{pmatrix}\times
		\begin{pmatrix}-2\\2\\4\end{pmatrix}\\
		&=\begin{pmatrix}-4\\-28\\12\end{pmatrix}\\\\
	\vec n_1&=\begin{pmatrix}-4\\-28\\12\end{pmatrix}\\
	\vec n_2&=\begin{pmatrix}4\\28\\-12\end{pmatrix}\\
	\vec n_3&=\begin{pmatrix}1\\7\\-3\end{pmatrix}
\end{align}
$$

## b)
$$
\begin{align}
	E:\vec{x}&=\begin{pmatrix}1\\0\\0\end{pmatrix}
		+r\cdot\begin{pmatrix}-1\\1\\1\end{pmatrix}
		+s\cdot\begin{pmatrix}-2\\2\\4\end{pmatrix}\\\\
	\vec{n}&=\begin{pmatrix}-1\\1\\1\end{pmatrix}\times
		\begin{pmatrix}-2\\2\\4\end{pmatrix}\\
		&=\begin{pmatrix}2\\2\\0\end{pmatrix}\\\\
	\vec n_1&=\begin{pmatrix}1\\1\\0\end{pmatrix}\\
	\vec n_2&=\begin{pmatrix}2\\2\\0\end{pmatrix}\\
	\vec n_3&=\begin{pmatrix}3\\3\\0\end{pmatrix}
\end{align}
$$

---
# 3)
> Berechnen Sie für die Vektoren $\vec{a}=\begin{pmatrix}2\\1\\5\end{pmatrix}$, $\vec{b}=\begin{pmatrix}3\\2\\1\end{pmatrix}$ und $\vec{c}=\begin{pmatrix}-1\\5\\0\end{pmatrix}$ die Vektorprodukte

## a)
> $\vec{a}\times\vec{b}$, $\vec{b}\times\vec{c}$ und $\vec{c}\times\vec{a}$

$$
\begin{align}
	\vec{a}\times\vec{b}&=
		\begin{pmatrix}2\\1\\5\end{pmatrix}\times
		\begin{pmatrix}3\\2\\1\end{pmatrix}=
		\begin{pmatrix}-9\\13\\1\end{pmatrix}\\
	\vec{b}\times\vec{c}&=
		\begin{pmatrix}3\\2\\1\end{pmatrix}\times
		\begin{pmatrix}-1\\5\\0\end{pmatrix}=
		\begin{pmatrix}-5\\-1\\17\end{pmatrix}\\
	\vec{c}\times\vec{a}&=
		\begin{pmatrix}-1\\5\\0\end{pmatrix}\times
		\begin{pmatrix}2\\1\\5\end{pmatrix}=
		\begin{pmatrix}25\\5\\-11\end{pmatrix}
\end{align}
$$
## b)
> $\vec{a}\times(\vec{b}\times\vec{c})$ und $(\vec{a}\times\vec{b})\times\vec{c}$


$$
\begin{align}
	\vec{a}\times(\vec{b}\times\vec{c})&=
		\begin{pmatrix}2\\1\\5\end{pmatrix}\times
		\left[\begin{pmatrix}3\\2\\1\end{pmatrix}\times
		\begin{pmatrix}-1\\5\\0\end{pmatrix}\right]\\
	&=\begin{pmatrix}2\\1\\5\end{pmatrix}\times
		\begin{pmatrix}-5\\-1\\17\end{pmatrix}=
		\begin{pmatrix}-22\\59\\-3\end{pmatrix}\\\\
	(\vec{a}\times\vec{b})\times\vec{c}&=
		\left[\begin{pmatrix}2\\1\\5\end{pmatrix}\times
		\begin{pmatrix}3\\2\\1\end{pmatrix}\right]\times
		\begin{pmatrix}-1\\5\\0\end{pmatrix}\\
	&=\begin{pmatrix}-9\\13\\1\end{pmatrix}\times
		\begin{pmatrix}-1\\5\\0\end{pmatrix}=
		\begin{pmatrix}-5\\-1\\-32\end{pmatrix}
\end{align}
$$

---
# 5)
> Berechnen Sie mithilfe des Vektorprodukts den Flächeninhalt des Parallelogramms $ABCD$ mit $A(1\mid1\mid1)$, $B(0\mid1\mid3)$, $C(-1\mid2\mid3)$ und $D(0\mid2\mid1)$.

$$
\begin{align}
	A_{ABCD}&=\left|
		\overrightarrow{AB}\times\overrightarrow{AD}\right|\\
	&=\left|
		\begin{pmatrix}0-1\\1-1\\3-1\end{pmatrix}
		\times\begin{pmatrix}0-1\\2-1\\1-1\end{pmatrix}\right|\\
	&=\left|
		\begin{pmatrix}-1\\0\\2\end{pmatrix}
		\times\begin{pmatrix}-1\\1\\0\end{pmatrix}\right|=\left|
		\begin{pmatrix}-2\\-2\\-1\end{pmatrix}\right|
		=3~\left[FE\right]
\end{align}
$$

---
# 6)
> Berechnen Sie den Flächeninhalt des Dreiecks $ABC$.

## a)
> $A(4\mid7\mid5)$, $B(0\mid5\mid9)$, $C(8\mid7\mid3)$

$$
\begin{align}
	A_{ABC}&=\frac{1}{2}\cdot\left|
		\overrightarrow{AB}\times\overrightarrow{AC}\right|\\
	&=\frac{1}{2}\cdot\left|
		\begin{pmatrix}0-4\\5-7\\9-5\end{pmatrix}
		\times\begin{pmatrix}8-4\\7-7\\3-5\end{pmatrix}\right|\\
	&=\frac{1}{2}\cdot\left|
		\begin{pmatrix}-4\\-2\\4\end{pmatrix}
		\times\begin{pmatrix}4\\0\\-2\end{pmatrix}\right|=\frac{1}{2}\cdot\left|
		\begin{pmatrix}4\\8\\8\end{pmatrix}\right|
		=6~\left[FE\right]
\end{align}
$$

## b)
> $A(-1\mid0\mid5)$, $B(2\mid2\mid2)$, $C(2\mid2\mid0)$

$$
\begin{align}
	A_{ABC}&=\frac{1}{2}\cdot\left|
		\overrightarrow{BA}\times\overrightarrow{BC}\right|\\
	&=\frac{1}{2}\cdot\left|
		\begin{pmatrix}-1-2\\0-2\\5-2\end{pmatrix}
		\times\begin{pmatrix}2-2\\2-2\\0-2\end{pmatrix}\right|\\
	&=\frac{1}{2}\cdot\left|
		\begin{pmatrix}-3\\-2\\3\end{pmatrix}
		\times\begin{pmatrix}0\\0\\-2\end{pmatrix}\right|=\frac{1}{2}\cdot\left|
		\begin{pmatrix}4\\-6\\0\end{pmatrix}\right|
		=\sqrt{13}~\left[FE\right]
\end{align}
$$

---