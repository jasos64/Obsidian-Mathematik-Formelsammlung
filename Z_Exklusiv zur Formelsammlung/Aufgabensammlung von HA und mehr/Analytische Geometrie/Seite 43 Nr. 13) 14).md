# 13)
> Die Vektoren $\vec{a}$, $\vec{b}$ und $\vec{c}$ mit $\vec{a}=\begin{pmatrix}0\\-1\\1\end{pmatrix}$, $\vec{b}=\begin{pmatrix}r\\1\\2\end{pmatrix}$ und $\vec{c}=\begin{pmatrix}3\\s\\1\end{pmatrix}$ spannen einen Spat auf. Berechnen Sie die Parameter $r$ und $s$ so, dass die von $a$ und $b$ aufgespannte Fläche des Spates $9~FE$ und Ihr Volumen $45~VE$ hat.

Für den Flächeninhalt des Parallelogramms $ab$ gilt der Flächeninhalt ist $9$.
$$
\begin{align}
	A_{a;b}&=\left|\vec{a}\times\vec{b}\right|\\
	9&=\left|
		\begin{pmatrix}0\\-1\\1\end{pmatrix}\times
		\begin{pmatrix}r\\1\\2\end{pmatrix}\right|\\
	9&=\left|
		\begin{pmatrix}-1\cdot2-1\cdot1\\1\cdot r-0\cdot2\\0\cdot1-(-1)\cdot r\end{pmatrix}\right|\\
	9&=\left|\begin{pmatrix}-3\\r\\r\end{pmatrix}\right|\\
	9&=\sqrt{(-3)^2+r^2+r^2}&&\mid()^2\\
	81&=9+2r^2&&\mid-9\\
	72&=2r^2&&\mid\div2\\
	r^2&=36&&\mid\sqrt{}\\
	r&=\mp6
\end{align}
$$

>Es kommen für den gesuchten Spat die Werte $-6$ und $6$ für $r$ vor.

Im weiteren wird das gesuchte $s$ unter der Bedingung, dass $r$ $\mp6$ ist, bestimmt. Wir bedenken im weiteren, dass die erste Lösung von $r$ $-6$.
$$
\begin{align}
	V_{a;b;c}&=\left|
		\left[\vec{a}\times\vec{b}\right]\circ\vec{c}\right|\\
	45&=\left|\left[
		\textcolor{green}{\begin{pmatrix}0\\-1\\1\end{pmatrix}\times
		\begin{pmatrix}r\\1\\2\end{pmatrix}}\right]\circ
		\begin{pmatrix}3\\s\\1\end{pmatrix}\right|\\
	45&=\left|\textcolor{green}{\begin{pmatrix}-3\\\textcolor{orange}r\\\textcolor{orange}r\end{pmatrix}}\circ
		\begin{pmatrix}3\\s\\1\end{pmatrix}\right|\\
	45&=\left|\begin{pmatrix}-3\\\textcolor{orange}{\mp6}\\\textcolor{orange}{\mp6}\end{pmatrix}\circ
		\begin{pmatrix}3\\s\\1\end{pmatrix}\right|\\
	45&=\left|-3\cdot3\mp6\cdot s\mp6\cdot1\right|\\
	45&=\left|-9\mp6\mp6s\right|\\\hline\textit{I:}\\
	45&=-(-9\mp6\mp6s)&&\mid\cdot(-1)\\
	-45&=-9\mp6\mp6s&&\mid+9\pm6\\
	\mp6s&=-45+9\pm6\\
	\mp6s&=-36\pm6&&\mid\div(\mp6)\\
	s&=\frac{-36\pm6}{\mp6}\\\\\textit{II:}\\
	45&=-9\mp6\mp6s&&\mid+9\pm6\\
	\mp6s&=45+9\pm6\\
	\mp6s&=54\pm6&&\mid\div(\mp6)\\
	s&=\frac{54\pm6}{\mp6}
\end{align}
$$

Daraus folgt:
$$
\begin{align}
	s=
		\begin{cases}
			-10\text{ oder }5,&\text{wenn }r=-6\\
			-7\text{ oder }8,&\text{wenn }r=6\\
		\end{cases}
\end{align}
$$

---
# 14)
> Die Punkte $A(3\mid-6\mid1)$, $B(-2\mid-2\mid13)$, $C(6\mid-2\mid5)$ sind Eckpunkte der Grundfläche einer dreiseitigen Pyramide $ABCS$ mit der Spitze $S(-6\mid12\mid1)$.

## a)
> Ermitteln Sie einen Normalenvektor der Ebene, in der die Grundfläche der Pyramide liegt.

$$
\begin{align}
	\vec{n}&=\overrightarrow{AB}\times\overrightarrow{AC}\\
	&=\left[\overrightarrow{OB}-\overrightarrow{OA}\right]\times
	\left[\overrightarrow{OC}-\overrightarrow{OA}\right]=
		\left[
		\begin{pmatrix}-2\\-2\\13\end{pmatrix}-\begin{pmatrix}3\\-6\\1\end{pmatrix}\right]\times
		\left[\begin{pmatrix}6\\-2\\5\end{pmatrix}-
		\begin{pmatrix}3\\-6\\1\end{pmatrix}\right]\\
	&=\begin{pmatrix}-5\\4\\12\end{pmatrix}\times
	\begin{pmatrix}3\\4\\4\end{pmatrix}=
		\begin{pmatrix}-32\\56\\-32\end{pmatrix}\\
	\vec{n}&=8\cdot\begin{pmatrix}-4\\7\\-4\end{pmatrix}
\end{align}
$$

## b)
> Berechnen Sie den Inhalt der Grundfläche.

$$
\begin{align}
	A_{ABC}&=\frac{1}{2}\cdot\left|
		\overrightarrow{AB}\times\overrightarrow{AC}\right|\\
	&=\frac{1}{2}\cdot\left|
		\begin{pmatrix}-5\\4\\12\end{pmatrix}
		\times\begin{pmatrix}3\\4\\4\end{pmatrix}\right|=\frac{1}{2}\cdot\left|
		\begin{pmatrix}-32\\56\\-32\end{pmatrix}\right|
		=36~\left[FE\right]
\end{align}
$$

## c)
> Berechnen Sie das Volumen der dreiseitigen Pyramide $ABCS$.

$$
\begin{align}
	V_{ABCS}&=\frac{1}{6}\cdot\left|\left[
		\overrightarrow{AB}\times
		\overrightarrow{AC}\right]\circ\overrightarrow{AS}\right|\\
	&=\frac{1}{6}\cdot\left|\left[
		\begin{pmatrix}-5\\4\\12\end{pmatrix}
		\times\begin{pmatrix}3\\4\\4\end{pmatrix}\right]\circ
		\begin{pmatrix}-6-3\\12-(-6)\\1-1\end{pmatrix}\right|\\
	&=\frac{1}{6}\cdot\left|\begin{pmatrix}-32\\56\\-32\end{pmatrix}\circ
		\begin{pmatrix}-9\\18\\0\end{pmatrix}\right|\\
	&=\frac{1}{6}\cdot\left|-32\cdot(-9)+56\cdot18-32\cdot0\right|=\frac{1}{6}\cdot\left|1296\right|\\
	V_{ABCS}&=216~\left[VE\right]
\end{align}
$$

## d)
> Ermitteln Sie aus den Ergebnissen der Teilaufgaben b) und c) die Höhe der Pyramide.
> Beschreiben Sie eine Möglichkeit, wie man mithilfe der Ergebnisse aus den beiden Teilaufgaben a) und b) die Pyramidenhöhe ermitteln kann.

### 1
Für Pyramidenvolumina: $V=\frac{1}{3}\cdot G\cdot h$, wobei $G$ der Flächeninhalt der Grundseite, und $h$ die Höhe der Pyramide ist.
Wir erhalten aus den Aufgaben:
$$
\begin{align}
	V&=\frac{1}{3}\cdot G\cdot h\\
	V_{ABCS}&=\frac{1}{3}\cdot A_{ABC}\cdot h\\
	216&=\frac{1}{3}\cdot36\cdot h&&\mid\div12\\
	h&=18~\left[LE\right]
\end{align}
$$

Die Höhe der Pyramide ist demnach $18$ Längeneinheiten.

### 2
> Da die Höhe zu der Grundfläche unabhängig ist, ist es mit den Ergebnissen aus Teilaufgabe a) und b) nicht möglich, die Höhe zu berechnen. Ein Normalenvektor, der Flächenabhängig ist, und die Fläche allein sind nicht zielführend.
> Folglich müssen wir einen Zusammenhang finden.

> Methode 1:

Wir haben die Ebene $E_{ABC}$ gegeben. Für die Höhe kann hier die hessesche Normalenform von $E$ benutzt werden:
$$
\begin{align}
	E_{ABC}:&&\vec{n}\circ\left[{\overrightarrow{OX}-\overrightarrow{OA}}\right]&=0\\
	E_{H}:&&\frac{1}{\left|\vec{n}\right|}\cdot\vec{n}\circ\left[{\overrightarrow{OX}-\overrightarrow{OA}}\right]&=0
\end{align}
$$
Durch einsetzen kann der Abstand bestimmt werden. Es ist:
$$
\begin{align}
	d(E;S)&=\frac{1}{\left|\vec{n}\right|}\cdot\left|\vec{n}\circ\left[{\overrightarrow{OX}-\overrightarrow{OA}}\right]\right|
\end{align}
$$
Setzen wir unsere Werte ein, so erhalten wir:
$$
\begin{align}
	d(E;S)&=\frac{1}{\left|\vec{n}\right|}\cdot\left|\vec{n}\circ\left[{\overrightarrow{OS}-\overrightarrow{OA}}\right]\right|\\
	&=\frac{1}{\left|\begin{pmatrix}-32\\56\\-32\end{pmatrix}\right|}\cdot\left|\begin{pmatrix}-32\\56\\-32\end{pmatrix}\circ\left[\begin{pmatrix}-6\\12\\1\end{pmatrix}-\begin{pmatrix}3\\-6\\1\end{pmatrix}\right]\right|\\
	&=\frac{1}{72}\cdot\left|\begin{pmatrix}-32\\56\\-32\end{pmatrix}\circ\begin{pmatrix}-9\\18\\0\end{pmatrix}\right|\\
	&=\frac{1}{72}\cdot\left|-32\cdot(-9)+56\cdot18-32\cdot0\right|=\frac{1}{72}\cdot\left|1296\right|\\
	h&=18\\\hline
\end{align}
$$


> Methode 2:

Wir haben für das Volumen einer Pyramide:
$$
\begin{align}
	V&=\frac{1}{3}\cdot G\cdot h&&\mid\cdot\frac{3}{G}\\
	h&=\frac{3\cdot V}{G}
\end{align}
$$
Übertragen wir dies mit dem Spatpodukten, erhalten wir:
$$
\begin{align}
	h&=\frac{3\cdot V}{G}\\
	h&=\frac{3\cdot \frac{1}{6}\cdot\left|\left[
		\overrightarrow{AB}\times
		\overrightarrow{AC}\right]\circ\overrightarrow{AS}\right|}
		{\frac{1}{2}\cdot\left|
		\overrightarrow{AB}\times\overrightarrow{AC}\right|}=
		\frac{\left|\left[
		\overrightarrow{AB}\times
		\overrightarrow{AC}\right]\circ\overrightarrow{AS}\right|}
		{\left|
		\overrightarrow{AB}\times\overrightarrow{AC}\right|}&&\mid
		\boxed{\vec{n}=
		\overrightarrow{AB}\times\overrightarrow{AC}}\\
	h&=\frac{\left|\vec{n}\circ\overrightarrow{AS}\right|}
		{\left|
		\vec{n}\right|}=\frac{1}{\left|\vec{n}\right|}\cdot\left|\vec{n}\circ\overrightarrow{AS}\right|\\
	h&=\frac{1}{\left|\vec{n}\right|}\cdot
		\left|\vec{n}\circ\left[\overrightarrow{OS}-\overrightarrow{OA}\right]\right|
\end{align}
$$
Wir erkennen die hessesche Normalenform aus *Methode 1*.

---