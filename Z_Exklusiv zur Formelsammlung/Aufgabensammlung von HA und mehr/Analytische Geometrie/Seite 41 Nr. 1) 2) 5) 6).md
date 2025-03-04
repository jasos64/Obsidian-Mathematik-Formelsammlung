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
> 