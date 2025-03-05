> Die Punkte $A(1\mid2\mid5)$, $B(3\mid4\mid-1)$, $C(2\mid0\mid3)$ und $D(3\mid1\mid0)$ sind Eckpunkte eines Trapezes. berechnen Sie seinen Flächeninhalt

$$
\begin{align}
	A_{ABCD}&=A_{ABC}+A_{ACD}\\
	&=\frac{1}{2}\cdot\left[\left|\overrightarrow{AB}
		\times\overrightarrow{AC}\right|\right]+
		\frac{1}{2}\cdot\left[\left|\overrightarrow{AC}
		\times\overrightarrow{AD}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|\overrightarrow{AB}
		\times\overrightarrow{AC}\right|+
		\left|\overrightarrow{AC}
		\times\overrightarrow{AD}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|
		\begin{pmatrix}3-1\\4-2\\-1-5\end{pmatrix}\times
		\begin{pmatrix}2-1\\0-2\\3-5\end{pmatrix}\right|+
		\left|\begin{pmatrix}2-1\\0-2\\3-5\end{pmatrix}
		\times\begin{pmatrix}3-1\\1-2\\0-5\end{pmatrix}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|
		\begin{pmatrix}2\\2\\-6\end{pmatrix}\times
		\begin{pmatrix}1\\-2\\-2\end{pmatrix}\right|+
		\left|\begin{pmatrix}1\\-2\\-2\end{pmatrix}
		\times\begin{pmatrix}2\\-1\\-5\end{pmatrix}\right|\right]\\
	&=\frac{1}{2}\cdot\left[\left|
		\begin{pmatrix}-16\\-2\\-6\end{pmatrix}\right|+
		\left|\begin{pmatrix}8\\1\\3\end{pmatrix}\right|\right]\\
	&=\frac{1}{2}\cdot\left[
		\sqrt{(-16)^2+(-2)^2+(-6)^2}+\sqrt{8^2+1^2+3^2}\right]\\
	&=\frac{1}{2}\cdot\left[
		\sqrt{(-16)^2+(-2)^2+(-6)^2}+\sqrt{8^2+1^2+3^2}\right]=\frac{1}{2}\cdot3\sqrt{74}=1,5\sqrt{74}\approx12,9035~\left[FE\right]
\end{align}
$$

---