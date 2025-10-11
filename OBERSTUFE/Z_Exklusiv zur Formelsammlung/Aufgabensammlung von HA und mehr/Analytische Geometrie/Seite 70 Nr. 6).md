> Die Punkte $A\left(-7\mid-5\mid2\right)$, $B\left(1\mid9\mid6\right)$, $C\left(5\mid-2\mid-1\right)$ und $D\left(-2\mid0\mid9\right)$ sind die Ecken einer dreiseitigen Pyramide. Berechnen Sie das Volumen der Pyramide

$$
\begin{array}{}
	\overrightarrow{OA}=
		\begin{pmatrix}
			-7\\-5\\2
		\end{pmatrix}
		&
		\overrightarrow{OB}=
		\begin{pmatrix}
			1\\9\\6
		\end{pmatrix}\\
		\overrightarrow{OC}=
		\begin{pmatrix}
			5\\-2\\-1
		\end{pmatrix}
		&
		\overrightarrow{OD}=
		\begin{pmatrix}
			-2\\0\\9
		\end{pmatrix}
\end{array}
$$
$$
\begin{align}
	\overrightarrow{AB}&=\overrightarrow{OB}-\overrightarrow{OA}\\
		&=\begin{pmatrix}1\\9\\6\end{pmatrix}-
			\begin{pmatrix}-7\\-5\\2\end{pmatrix}\\
		&=\begin{pmatrix}1+7\\9+5\\6-2\end{pmatrix}=
			\boxed{\begin{pmatrix}8\\14\\4\end{pmatrix}}\\\\
	\overrightarrow{AC}&=\overrightarrow{OC}-\overrightarrow{OA}\\
		&=\begin{pmatrix}5\\-2\\-1\end{pmatrix}-
			\begin{pmatrix}-7\\-5\\2\end{pmatrix}\\
		&=\begin{pmatrix}5+7\\-2+5\\-1-2\end{pmatrix}=
			\boxed{\begin{pmatrix}12\\3\\-3\end{pmatrix}}\\\\
	\overrightarrow{AD}&=\overrightarrow{OD}-\overrightarrow{OA}\\
		&=\begin{pmatrix}-2\\0\\9\end{pmatrix}-
			\begin{pmatrix}-7\\-5\\2\end{pmatrix}\\
		&=\begin{pmatrix}-2+7\\5\\9-2\end{pmatrix}=
			\boxed{\begin{pmatrix}5\\5\\7\end{pmatrix}}
\end{align}
$$

---
## Rechtfertigung der gegebenen Formel
Für Volumina einer dreiseitigen Pyramide kann hier $V=\frac{1}{6}\cdot\left|\left(\overrightarrow{AB}\times\overrightarrow{AC}\right)\circ\overrightarrow{AD}\right|$ verwendet werden.
Dies ist hergeleitet aus $V=\frac{1}{3}\cdot A_g\cdot h$, wobei $A_g=\frac{1}{2}\cdot\left|\overrightarrow{AB}\times\overrightarrow{AC}\right|$ ist. Die Höhe $h$ kann durch $\left|\frac{\left(\overrightarrow{AB}\times\overrightarrow{AC}\right)\circ\overrightarrow{AD}}{\left|\overrightarrow{AB}\times\overrightarrow{AC}\right|}\right|$ bestimmt werden. Vereint man dies nun, so erhält man den bereits gegebenen Zusammenhang:
$$
\begin{align}
	V&=\frac{1}{3}\cdot A_g\cdot h\\
		&=\frac{1}{3}\cdot\frac{1}{2}\cdot\left|\overrightarrow{AB}\times\overrightarrow{AC}\right|	\cdot\left|\frac{\left(\overrightarrow{AB}\times\overrightarrow{AC}\right)\circ\overrightarrow{AD}}{\left|\overrightarrow{AB}\times\overrightarrow{AC}\right|}\right|\\
	&=\frac{1}{6}\cdot\left|\left(\overrightarrow{AB}\times\overrightarrow{AC}\right)\circ\overrightarrow{AD}\right|
\end{align}
$$

---
## Bestimmung des Volumens
$$
\begin{align}
	V&=\frac{1}{6}\cdot\left|\left(
		\overrightarrow{AB}\times\overrightarrow{AC}\right)
		\circ\overrightarrow{AD}\right|\\
	&=\frac{1}{6}\cdot\left|\left(
		\begin{pmatrix}
			8\\14\\4
		\end{pmatrix}\times
		\begin{pmatrix}
			12\\3\\-3
		\end{pmatrix}\right)\circ
		\begin{pmatrix}
			5\\5\\7
		\end{pmatrix}\right|\\
	&=\frac{1}{6}\cdot\left|
		\begin{pmatrix}
			-54\\72\\-144
		\end{pmatrix}\circ
		\begin{pmatrix}
			5\\5\\7
		\end{pmatrix}\right|\\
	&=\frac{1}{6}\cdot\left|-54\cdot5+72\cdot5-144\cdot7\right|\\
	&=\frac{1}{6}\cdot\left|-918\right|\\
	&=153~~\left[LE\right]^3
\end{align}
$$
Somit ist das Volumen der gegebenen Pyramide $153~~\left[LE\right]^3$.

---