> Gegeben sind eine quadratische Pyramide mit den Ecken $A(-3\mid-3\mid0)$, $B(3\mid-3\mid0)$, $C(3\mid3\mid0)$, $D(-3\mid3\mid0)$ und der Spitze $S(0\mid0\mid9)$ sowie die Ebene $E:3x_2+4x_3=21$.

## a)
> Berechnen Sie die Koordinaten der Schnittpunkte der Pyramidenkanten mit der Ebene $E$.

Für die Pyramidenkanten gilt:
$$
\begin{align}
	g_{AS}:\vec{x}&=\overrightarrow{OS}
		+\lambda\cdot\overrightarrow{SA}\\
	&=\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}-3-0\\-3-0\\0-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}-3\\-3\\-9\end{pmatrix}\\
	g_{BS}:\vec{x}&=\overrightarrow{OS}
		+\lambda\cdot\overrightarrow{SB}\\
	&=\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}3-0\\-3-0\\0-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}3\\-3\\-9\end{pmatrix}\\
	g_{CS}:\vec{x}&=\overrightarrow{OS}
		+\lambda\cdot\overrightarrow{SC}\\
	&=\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}3-0\\3-0\\0-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}3\\3\\-9\end{pmatrix}\\
	g_{DS}:\vec{x}&=\overrightarrow{OS}
		+\lambda\cdot\overrightarrow{SD}\\
	&=\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}3-0\\3-0\\0-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}-3\\3\\-9\end{pmatrix}
\end{align}
$$
Für das gleichsetzen von Ebenen und Gerade gilt hier:
$$\overrightarrow{OP}=\vec{p} +\frac{d-\vec{n}\circ\vec{p}}{\vec n\circ\vec v}\cdot\vec v$$
Zu nennen ist hier, dass diese Gleichung für den Punkt $P$ durch
![[GeradeInEbene]]
gezeigt wird (Bereich 1).
(ich bin faul und will nicht immer das gleiche machen, deshalb eine Formel für das xdd)


Setzen wir generell ein, so erhalten wir zunächst:
$$
\begin{align}
	\overrightarrow{OP}&=\vec{p} +\frac{d-\vec{n}\circ\vec{p}}{\vec n\circ\vec v}\cdot\vec v\\
	\overrightarrow{OP}&=\overrightarrow{OS} +\frac{21-\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\overrightarrow{OS}}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\vec v}\cdot\vec v\\
	\overrightarrow{OP}&=\begin{pmatrix}0\\0\\9\end{pmatrix} +\frac{21-\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\begin{pmatrix}0\\0\\9\end{pmatrix}}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\vec v}\cdot\vec v=
		\begin{pmatrix}0\\0\\9\end{pmatrix} +\frac{-15}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\vec v}\cdot\vec v
\end{align}
$$
Für jede einzelne Gerade erhalten wir:
$$
\begin{align}
	\overrightarrow{OA'}&=\begin{pmatrix}0\\0\\9\end{pmatrix} +\frac{-15}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\begin{pmatrix}-3\\-3\\-9\end{pmatrix}}\cdot\begin{pmatrix}-3\\-3\\-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\frac{5}{14}\cdot\begin{pmatrix}-3\\-3\\-9\end{pmatrix}\\
	&\approx
		\begin{pmatrix}-1,0714\\-1,0714\\5.7857\end{pmatrix}\\
		\hline\\
	\overrightarrow{OB'}&=\begin{pmatrix}0\\0\\9\end{pmatrix} +\frac{-15}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\begin{pmatrix}3\\-3\\-9\end{pmatrix}}\cdot\begin{pmatrix}3\\-3\\-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\frac{5}{14}\cdot\begin{pmatrix}3\\-3\\-9\end{pmatrix}\\
	&\approx
		\begin{pmatrix}1,0714\\-1,0714\\5.78571428571\end{pmatrix}\\
		\hline\\
	\overrightarrow{OC'}&=\begin{pmatrix}0\\0\\9\end{pmatrix} +\frac{-15}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\begin{pmatrix}3\\3\\-9\end{pmatrix}}\cdot\begin{pmatrix}3\\3\\-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\frac{1}{2}\cdot\begin{pmatrix}3\\3\\-9\end{pmatrix}\\
	&=
		\begin{pmatrix}1,5\\1,5\\4,5\end{pmatrix}\\
		\hline\\
	\overrightarrow{OD'}&=\begin{pmatrix}0\\0\\9\end{pmatrix} +\frac{-15}{\begin{pmatrix}0\\2\\4\end{pmatrix}\circ\begin{pmatrix}-3\\3\\-9\end{pmatrix}}\cdot\begin{pmatrix}-3\\3\\-9\end{pmatrix}=
		\begin{pmatrix}0\\0\\9\end{pmatrix}+\frac{1}{2}\cdot\begin{pmatrix}-3\\3\\-9\end{pmatrix}\\
	&=
		\begin{pmatrix}-1,5\\1,5\\4,5\end{pmatrix}\\
		\hline\\
\end{align}
$$

---
## b)
> Zeichnen Sie die Pyramide mit der Schnittfläche als Schrägbild in ein Koordinatensystem. Beschreiben Sie die Form der Schnittfläche.

![[Pyramide.png]]
Die Schnittfläche ähnelt der eines Trapezes.

## c)
> 