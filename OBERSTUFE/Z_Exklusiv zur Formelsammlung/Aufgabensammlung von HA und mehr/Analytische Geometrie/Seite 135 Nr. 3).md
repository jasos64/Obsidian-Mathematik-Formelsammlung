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
Die Schnittfläche ist ein Trapez. Da der Normalenvektor von $E$ in der $x_1$ $0$ ist, und die Grundseiten parallel der $x_1$-Achse dadurch weiterhin parallel bleiben, so sind zwei Seiten zueinander parallel.

## c)
> Berechnen Sie den Flächeninhalt der Schnittfläche.

$$
\begin{align}
	A_{A'B'C'D'}&=A_{A'B'C'}+A_{A'C'D'}\\
	&=\frac{1}{2}\cdot\left[\left|\overrightarrow{A'B'}
		\times\overrightarrow{A'C'}\right|\right]+
		\frac{1}{2}\cdot\left[\left|\overrightarrow{A'C'}
		\times\overrightarrow{A'D'}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|\overrightarrow{A'B'}
		\times\overrightarrow{A'C'}\right|+
		\left|\overrightarrow{A'C'}
		\times\overrightarrow{A'D'}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|
		\begin{pmatrix}\frac{15}{14}-\left(-\frac{15}{14}\right)\\-\frac{15}{14}-\left(-\frac{15}{14}\right)\\9-\frac{45}{14}-\left(9-\frac{45}{14}\right)\end{pmatrix}\times
		\begin{pmatrix}1,5-\left(-\frac{15}{14}\right)\\1,5-\left(-\frac{15}{14}\right)\\4,5-\left(9-\frac{45}{14}\right)\end{pmatrix}\right|+
		\left|\begin{pmatrix}1,5-\left(-\frac{15}{14}\right)\\1,5-\left(-\frac{15}{14}\right)\\4,5-\left(9-\frac{45}{14}\right)\end{pmatrix}
		\times\begin{pmatrix}-1,5-\left(-\frac{15}{14}\right)\\1,5-\left(-\frac{15}{14}\right)\\4,5-\left(9-\frac{45}{14}\right)\end{pmatrix}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|
		\begin{pmatrix}\frac{15}{7}\\0\\0\end{pmatrix}\times
		\begin{pmatrix}\frac{18}{7}\\\frac{18}{7}\\-\frac{9}{7}\end{pmatrix}\right|+
		\left|\begin{pmatrix}\frac{18}{7}\\\frac{18}{7}\\-\frac{9}{7}\end{pmatrix}
		\times\begin{pmatrix}-\frac{3}{7}\\\frac{18}{7}\\-\frac{9}{7}\end{pmatrix}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|
		\begin{pmatrix}0\\\frac{135}{39}\\\frac{270}{49}\end{pmatrix}\right|+
		\left|\begin{pmatrix}0\\-\frac{675}{196}\\-\frac{675}{98}\end{pmatrix}\right|\right]\\
	&=\frac{1}{2}\cdot\left[
		\sqrt{\left(\frac{135}{39}\right)^2+\left(\frac{270}{49}\right)^2}+\sqrt{\left(-\frac{675}{196}\right)^2+\left(-\frac{675}{98}\right)^2}\right]\\
	&=\frac{45\sqrt{8485}}{1274}+\frac{675\sqrt{5}}{392}\approx7,104~\left[FE\right]
\end{align}
$$

## d)
> Berechnen Sie den Abstand der Spitze $S$ von der Ebene $E$.

$$
\begin{align}
	d(X;E)&=E:\frac{1}{5}\cdot\left|3x_2+4x_3-21\right|\\
	d(S;E)&=E:\frac{1}{5}\cdot\left|3\cdot0+4\cdot9-21\right|=
		\frac{1}{5}\cdot\left|15\right|\\
	&=3~\left[LE\right]
\end{align}
$$

## e)
> Bestimmen Sie das Volumen der Pyramide und der beiden Teilkörper, in die die Pyramide durch die Ebene $E$ zerlegt wurde.

Für das Gesamtvolumen der Pyramide gilt $A=\frac{1}{3}\cdot G\cdot h$. Folglich $A_G=\frac{1}{3}\cdot 36\cdot9=108~\left[VE\right]$.

Für den oberen Teilkörper gilt ebenfalls $A=\frac{1}{3}\cdot G\cdot h$. Aus den vorherigen Aufgaben sehen wir, dass hier $A_o=\frac{1}{3}\cdot \left(\frac{45\sqrt{8485}}{1274}+\frac{675\sqrt{5}}{392}\right)\cdot3=\frac{45\sqrt{8485}}{1274}+\frac{675\sqrt{5}}{392}~\left[VE\right]$ sein muss.
Für den unteren Teilkörper gilt:
$$
\begin{align}
	A_G&=A_u+A_o&&\mid-A_o\\
	A_u&=A_G-A_o\\
	&=108-\frac{45\sqrt{8485}}{1274}-\frac{675\sqrt{5}}{392}\\
	&\approx100,896~\left[VE\right]
\end{align}
$$

---