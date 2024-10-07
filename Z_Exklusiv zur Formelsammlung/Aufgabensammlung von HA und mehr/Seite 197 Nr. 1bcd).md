> Untersuchen Sie, ob die Ebene $E$ die Kugel $K$ schneidet, oder keinen Punkt mit ihr gemeinsam hat.

## b)
- $E:~-3x_1+6x_2-2x_3=27$
- $K:~(x_1-4)^2+(x_2+1)^2+(x_3-2)^2=49$

Durch $\sqrt{49}=7$ folgt ein Radius $r$ der Kugel von $7$.
- $r=7\left[LE\right]$

Der kürzeste Abstand zwischen dem Mittelpunkt der Kugel und der Ebene bestimmt die Lagebeziehung zwischen Kugel $K$ und Ebene $E$.
Dieser Punkt wird weitergehend mit $M'$ beschrieben.

$$
\begin{align}
	q:\vec x=
		\begin{pmatrix}
			m_1\\m_2\\m_3
		\end{pmatrix}
		+\lambda\cdot
		\begin{pmatrix}
			n_1\\n_2\\n_3
		\end{pmatrix}\cdot\frac{1}{\sqrt{n_1^2+n_2^2+n_3^2}}
\end{align}
$$
Der Mittelpunkt lässt sich ablesen, wie auch der Normalenvektor der Ebene.
- $M(4\mid-1\mid2)$
- $\vec n=\begin{pmatrix}-3\\6\\-2\end{pmatrix}$
	- $\vec{n}_0=\begin{pmatrix}-\frac{3}{7}\\\frac{6}{7}\\-\frac{2}{7}\end{pmatrix}$
$$
\begin{align}
	q:\vec x=
		\begin{pmatrix}4\\-1\\2\end{pmatrix}
		+\lambda\cdot\begin{pmatrix}-\frac{3}{7}\\\frac{6}{7}\\-\frac{2}{7}\end{pmatrix}
\end{align}
$$
Setzen wir diese Lotgerade nun in die Ebene ein, so erhalten wir durch bestimmen von $\lambda$ einen Wert, der die Länge des Verbindungsvektors zwischen $M$ und $M'$ beschreibt.

$$
\begin{align}
	E:~-3x_1+6x_2-2x_3&=27\\
	-3\cdot\left(4-\frac{3}{7}\lambda\right)+6\cdot\left(-1+\frac{6}{7}\lambda\right)-2\cdot\left(2-\frac{2}{7}\lambda\right)&=27\\
	-12+\frac{9}{7}\lambda-6+\frac{36}{7}\lambda-4+\frac{4}{7}\lambda&=27\\
	-22+7\lambda&=27&&\mid+22\quad\div7\\
	\lambda&=\frac{49}{7}=7.
\end{align}
$$

Da hier $\lambda=7$, dadurch ist diese Ebene eine Tangentialebene der Kugel $K$.

---
---
## c)
- $E:~2x_1-3x_2+4x_3=30$
- $K:x_1^2-6x_1+x_2^2-2x_2+x_3^2-15=0$

$$
\begin{align}
	x_1^2-6x_1+9+x_2^2-2x_2+1+x_3^2&=15+9+1\\
	\left(x_1-3\right)^2+\left(x_2-1\right)^2+x_3^2&=25
\end{align}
$$
Daraus folgt ein Mittelpunkt $M(3\mid1\mid0)$, und ein Radius $r=5$.

Der Normaleneinheitsvektor der Ebene lautet $\vec{n}_0=\begin{pmatrix}2\\-3\\4\end{pmatrix}\cdot\frac{1}{29}$.
Die normierte Lotgerade lautet somit:
$$
\begin{align}
	q:\vec x=
		\begin{pmatrix}3\\1\\0\end{pmatrix}
		+\lambda\cdot\begin{pmatrix}\frac{2}{\sqrt{29}}\\-\frac{3}{\sqrt{29}}\\\frac{4}{\sqrt{29}}\end{pmatrix}
\end{align}
$$

Diese in $E$ eingesetzt gibt den Abstand der Ebene zu $M$ an:
$$
\begin{align}
	E:~2x_1-3x_2+4x_3&=30\\
	2\cdot\left(3+\frac{2}{\sqrt{29}}\lambda\right)
		-3\cdot\left(1-\frac{3}{\sqrt{29}}\lambda\right)
		+4\cdot\left(\frac{4}{\sqrt{29}}\lambda\right)&=30\\
	6+\frac{4}{\sqrt{29}}\lambda-
		3+\frac{9}{\sqrt{29}}\lambda+
		\frac{16}{\sqrt{29}}\lambda&=30\\
		3+\sqrt{29}\lambda&=30&&\mid-3\quad\div\sqrt{29}\\
	\lambda&=\frac{27\cdot\sqrt{29}}{29}\approx5,0138>r
\end{align}
$$
Da $\lambda>r$, so berührt sich die Ebene und die Kugel nicht.

---
## d)
- $E:\vec{x}\circ\begin{pmatrix}-2\\4\\-3\end{pmatrix}+22=0$
- $K:\left[\vec{x}-\begin{pmatrix}5\\-3\\-7\end{pmatrix}\right]^2=29$

Daraus folgt ein Mittelpunkt $M(5\mid-3\mid-7)$, und ein Radius $r=\sqrt{29}$.

---
Der Normaleneinheitsvektor der Ebene lautet $\vec{n}_0=\begin{pmatrix}-2\\4\\-3\end{pmatrix}\cdot\frac{1}{29}$.
Die normierte Lotgerade lautet somit:
$$
\begin{align}
	q:\vec x=
		\begin{pmatrix}5\\-3\\-7\end{pmatrix}
		+\lambda\cdot\begin{pmatrix}-\frac{2}{\sqrt{29}}\\\frac{4}{\sqrt{29}}\\-\frac{3}{\sqrt{29}}\end{pmatrix}
\end{align}
$$

Diese in $E$ eingesetzt gibt den Abstand der Ebene zu $M$ an:
$$
\begin{align}
	E:\vec{x}\circ\begin{pmatrix}-2\\4\\-3\end{pmatrix}+22=0\\
	-2x_1+4x_2-3x_3&=-22\\
	-2\cdot\left(5-\frac{2}{\sqrt{29}}\lambda\right)
		+4\cdot\left(-3+\frac{4}{\sqrt{29}}\lambda\right)
		-3\cdot\left(-7-\frac{3}{\sqrt{29}}\lambda\right)&=-22\\
	-10+\frac{4}{\sqrt{29}}\lambda
		-12+\frac{16}{\sqrt{29}}\lambda
		+21+\frac{9}{\sqrt{29}}\lambda&=-22\\
	-1+\sqrt{29}\lambda&=-22&&\mid+1\quad\div\sqrt{29}\\
	\lambda&=-\frac{21\cdot\sqrt{29}}{29}\approx-3,8996
\end{align}
$$
Da $\left|\lambda\right|<r$, so schneidet die Ebene $E$ die Kugel $K$.

---