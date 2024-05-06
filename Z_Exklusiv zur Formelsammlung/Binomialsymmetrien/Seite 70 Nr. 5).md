$\overrightarrow{OA}=\begin{pmatrix}1\\1\\2\end{pmatrix}$; $\overrightarrow{OB}=\begin{pmatrix}3\\5\\-2\end{pmatrix}$; $\overrightarrow{OC}=\begin{pmatrix}2\\3\\2\end{pmatrix}$; $\overrightarrow{OD}=\begin{pmatrix}-4\\-9\\14\end{pmatrix}$

---
$$
\begin{align}
	\overrightarrow{AB}&=\overrightarrow{OB}-\overrightarrow{OA}\\
		&=\begin{pmatrix}3\\5\\-2\end{pmatrix}-\begin{pmatrix}1\\1\\2\end{pmatrix}\\
	&=\begin{pmatrix}2\\4\\-4\end{pmatrix}\\\\
\end{align}
$$

$$
\begin{align}
	\overrightarrow{BC}&=\overrightarrow{OC}-\overrightarrow{OB}\\
		&=\begin{pmatrix}2\\3\\2\end{pmatrix}-\begin{pmatrix}3\\5\\-2\end{pmatrix}\\
	&=\begin{pmatrix}-1\\-2\\4\end{pmatrix}
\end{align}
$$

$$
\begin{align}
	\overrightarrow{CD}&=\overrightarrow{OD}-\overrightarrow{OC}\\
		&=\begin{pmatrix}-4\\-9\\14\end{pmatrix}-\begin{pmatrix}2\\3\\2\end{pmatrix}\\
	&=\begin{pmatrix}-6\\-12\\12\end{pmatrix}
\end{align}
$$

$$
\begin{align}
	\overrightarrow{DA}&=\overrightarrow{OA}-\overrightarrow{OD}\\
		&=\begin{pmatrix}1\\1\\2\end{pmatrix}-\begin{pmatrix}-4\\-9\\14\end{pmatrix}\\
	&=\begin{pmatrix}5\\10\\-12\end{pmatrix}
\end{align}
$$

$$
\begin{array}{}
	\overrightarrow{AB}=\begin{pmatrix}2\\4\\-4\end{pmatrix}&&
		\overrightarrow{BC}=\begin{pmatrix}-1\\-2\\4\end{pmatrix}\\
	\overrightarrow{CD}=\begin{pmatrix}-6\\-12\\12\end{pmatrix}&&
		\overrightarrow{DA}=\begin{pmatrix}5\\10\\-12\end{pmatrix}
\end{array}
$$

---
Einfach gesehen lul:
$\overrightarrow{AB}=\lambda\cdot\overrightarrow{CD}$

---
$A=\frac{\left|\overrightarrow{AB}\right|+\left|\overrightarrow{CD}\right|}{2}\cdot h$

$$
\begin{align}
	h=\left|\overrightarrow{OS}-\overrightarrow{OA}\right|&&\mid
		\boxed{
			\begin{array}{}
			\overrightarrow{OS}\in g:\vec{x}&&g:\vec{x}\|\overrightarrow{CD}\\
			\overrightarrow{AS}\perp g:\vec{x}&&\overrightarrow{OD}\in g:\vec{x}
		\end{array}
	}
\end{align}
$$
$$
\begin{align}
	g:\vec{x}&=\overrightarrow{OD}+\lambda\cdot\overrightarrow{CD}\\
	&=\begin{pmatrix}-4\\-9\\14\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}-6\\-12\\12\end{pmatrix}\\
\end{align}
$$
$$
\begin{align}
	\overrightarrow{OA}=\begin{pmatrix}1\\1\\2\end{pmatrix}
\end{align}
$$
$$
\begin{align}
	\overrightarrow{CD}\circ\left[\overrightarrow{OX}-\overrightarrow{OA}\right]&=0\\
	\overrightarrow{CD}\circ\overrightarrow{OX}-\overrightarrow{CD}\circ\overrightarrow{OA}&=0&\mid +\overrightarrow{CD}\circ\overrightarrow{OA}\\
	\begin{pmatrix}-6\\-12\\12\end{pmatrix}\circ
		\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}&=
		\begin{pmatrix}-6\\-12\\12\end{pmatrix}\circ
			\begin{pmatrix}1\\1\\2\end{pmatrix}\\
	-6x_1-12x_2+12x_3&=6&&\mid\div (-6)\\
	x_1+2x_2-2x_3&=-1\\\\
	
	g:\vec{x}&=\begin{pmatrix}-4\\-9\\14\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}-6\\-12\\12\end{pmatrix}\\\\
	
	(-4-6\lambda)+2(-9-12\lambda)-2(14+12\lambda)&=-1\\
	\lambda&=-\frac{49}{54}
\end{align}
$$

$$
\begin{align}
	g:\vec{x}&=\begin{pmatrix}-4\\-9\\14\end{pmatrix}+\left(-\frac{49}{54}\right)\cdot
		\begin{pmatrix}-6\\-12\\12\end{pmatrix}\\
	&=\begin{pmatrix}
		-4+\frac{49}{54}\cdot6\\
		-9+\frac{49}{54}\cdot12\\
		14-\frac{49}{54}\cdot12
	\end{pmatrix}\\
	\overrightarrow{OS}&=\begin{pmatrix}
		\frac{13}{9}\\
		\frac{17}{9}\\
		\frac{28}{9}
	\end{pmatrix}\\\\
	h&=\left|\overrightarrow{OS}-\overrightarrow{OA}\right|\\
	&=\left|\begin{pmatrix}
		\frac{13}{9}\\
		\frac{17}{9}\\
		\frac{28}{9}
	\end{pmatrix}-\begin{pmatrix}
		1\\1\\2
	\end{pmatrix}\right|\\
	&=\left|\begin{pmatrix}
		\frac{4}{9}\\
		\frac{8}{9}\\
		\frac{10}{9}
	\end{pmatrix}\right|\\
	&=\sqrt{\left(\frac{4}{9}\right)^2+\left(\frac{8}{9}\right)^2+\left(\frac{10}{9}\right)^2}\\
	&=\sqrt{\frac{4^2}{9^2}+\frac{8^2}{9^2}+\frac{10^2}{9^2}}\\
	&=\sqrt{\frac{16}{9^2}+\frac{64}{9^2}+\frac{100}{9^2}}\\
	&=\sqrt{\frac{180}{9^2}}\\
	&=\frac{\sqrt{180}}{9}\\
	&=\frac{2\sqrt{5}}{3}\approx 1,4901 \left[LE\right]\\\\
	
	A&=\frac{\left|\overrightarrow{AB}\right|+
		\left|\overrightarrow{CD}\right|}{2}\cdot h\\
	A&=\frac{
			\sqrt{2^2+4^2+(-4)^2}+\sqrt{(-6)^2+(-12)^2+12^2}}{2}\cdot \frac{2\sqrt{5}}{3}\\
	&=\frac{\sqrt{4+16+16}+\sqrt{36+144+144}}{2}\cdot \frac{2\sqrt{5}}{3}\\
	&=\frac{6+18}{2}\cdot \frac{2\sqrt{5}}{3}\\
	&=12\cdot \frac{2\sqrt{5}}{3}\\
	&=8\sqrt{5}\approx 17,889 \left[FE\right]
\end{align}
$$