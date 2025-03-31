Ein Punkt mit dem Ortsvektor $\overrightarrow{OR}$ wird zu einer Gerade $g:\vec{x}$ auf Abstand untersucht.
Abstände benötigen stets die Verwendung des *Lot*es, wodurch hier ein Punkt mit dem Ortsvektor $\overrightarrow{OS}$ auf der Gerade gesucht wird, dessen Verbindungsvektor zum anderem Punkt (also $\overrightarrow{RS}$ oder $\overrightarrow{SR}$) senkrecht gegen der Gerade ist. Die Länge dieses Verbindungsvektors heißt dann Abstand.
Zusammengefasst lässt sich dies wie folgt beschreiben:
$$
\begin{array}{}
	\overrightarrow{OS}\in g:\vec{x}&& \overrightarrow{RS}\perp g:\vec{x}
\end{array}
$$
Zum Berechnen dieses Punktes $\overrightarrow{OS}$ gibt es mindestens zwei Wege, diesen zu erhalten.

---
## Lotfußpunktverfahren mit laufendem Punkt
Bei diesem Lösungsweg wird ein Punkt $\overrightarrow{OS}$ auf der Gerade so gewählt, dass der Verbindungsvektor zum anderen Punkt (also $\overrightarrow{RS}$ oder $\overrightarrow{SR}$) [skalarmultipliziert](Skalarprodukt.md) gleich $0$ ist, und somit dieser senkrecht zu der Gerade steht.
Jeder Punkt einer Gerade $g:\vec{x}=\begin{pmatrix}p_1\\p_2\\p_3\end{pmatrix}+\lambda\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}$ kann zusammengefasst durch $\overrightarrow{OS}=\begin{pmatrix}p_1+v_1\lambda\\p_2+v_2\lambda\\p_3+v_3\lambda\end{pmatrix}$ ausgedrückt werden. Der Verbindungsvektor $\overrightarrow{RS}$ heißt, insofern $\overrightarrow{OR}$ durch $\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}$ dargestellt werden kann wie folgend:
$$
\begin{align}
	\overrightarrow{RS}&=\overrightarrow{OS}-\overrightarrow{OR}\\
	
	&=\begin{pmatrix}p_1+v_1\lambda\\p_2+v_2\lambda\\p_3+v_3\lambda
		\end{pmatrix}-\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}\\
	
	&=\begin{pmatrix}p_1-r_1+v_1\lambda\\p_2-r_2+v_2\lambda\\p_3-r_3+v_3\lambda\end{pmatrix}
\end{align}
$$
Dieser Verbindungsvektor beschreibt den stationären Punkt $R$ und $S$, der sich entlang der Gerade bewegt. Nun soll ein Wert für $\lambda$ gefunden werden, sodass dieser Verbindungsvektor senkrecht des Richtungsvektors der Gerade ist.
Sei dieser durch $\vec{v}=\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}$ gegeben, so muss folgendes erfüllt sein:
$$
\begin{align}
	\overrightarrow{RS}\circ\overrightarrow{v}&=0\\
	
	\begin{pmatrix}p_1-r_1+v_1\lambda\\p_2-r_2+v_2\lambda\\p_3-r_3+v_3\lambda\end{pmatrix}\circ\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}&=0\\
	
	v_1\left(p_1-r_1+v_1\lambda\right)+v_2\left(p_2-r_2+v_2\lambda\right)+v_3\left(p_3-r_3+v_3\lambda\right)&=0\\
	&~~\vdots\\
	\lambda&=\mu
\end{align}
$$
Eine Lösung dieses Skalarproduktes gibt an, welcher Wert für die Gerade benötigt wird, damit dieser entstehende Ortsvektor die vorherigen Kriterien erfüllt. Hier ist dieser Wert durch $\mu$ ausgedrückt.
Da alle Richtungsvektoren zuvor durch $\begin{pmatrix}p_1-r_1+v_1\lambda\\p_2-r_2+v_2\lambda\\p_3-r_3+v_3\lambda\end{pmatrix}$ beschrieben wurden, muss $\lambda$ mit $\mu$ eingesetzt werden, damit der Verbindungsvektor bestimmt ist. Die Länge von diesem wird anschließend mit dem Betrag bestimmt. Der Erhaltene Wert ist der Abstand zwischen dem Punkt und der Gerade.

---
## Lotfußpunktverfahren mit Hilfsebene
Bei diesem Lösungsweg wird eine Ebene erstellt, durch welche die Gerade $g:\vec{x}=\begin{pmatrix}p_1\\p_2\\p_3\end{pmatrix}+\lambda\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}$ senkrecht verläuft. Der Normalenvektor ist somit ein vielfaches von dem Richtungsvektor.
Zusätzlich wird die Ebene durch den Punkt $\overrightarrow{OR}=\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}$ aufgespannt, wodurch sich generell folgende Koordinatenform bildet:
Es gilt:
$$
\begin{array}{}
	E\perp g:\vec{x}&&\overrightarrow{OR}\in E
\end{array}$$
$\vec{v}$ heißt hier Normalenvektor der Ebene, da $E\perp g:\vec{x}$. $\vec{v}\to\vec{n}$ wäre möglich, werde ich aber hier nicht anwenden.

$$
\begin{align}
	E:v_1x_1+v_2x_2+v_3x_3=
		\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}\circ
		\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}
\end{align}
$$
Die Ebene liegt senkrecht zu der Gerade, wodurch der Ortsvektor $\overrightarrow{OS}$ die Schnittmenge der Ebene und der Gerade ist ($E\cap g:\vec{x}$).
Hierbei ist das Einsetzungsverfahren das einfachste, bei welchem die Gerade in ihre Achsen aufgeteilt in die Koordinatenform eingesetzt wird.
$$
\begin{align}
	E:v_1x_1+v_2x_2+v_3x_3&=
		\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}\circ
		\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}\\
		
	E:v_1(p_1+v_1\lambda)+v_2(p_2+v_2\lambda)+v_3(p_3+v_3\lambda)&=
		\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}\circ
		\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}\\
		&~~\vdots\\
		\lambda&=\mu
\end{align}
$$
Dieser Wert für $\lambda$ gibt an, welcher Wert in die Gerade eingesetzt den Ortsvektor $\overrightarrow{OS}$, der in der Ebene ist, ergibt. Hier ist dieser Wert durch $\mu$ ausgedrückt.
Anstelle die Geraden mit Werten einzusetzen, kann ebenfalls mit den Vektoren zunächst ohne einsetzen der Werte nach $\lambda$ umgestellt werden.
Von dem obigen Definitionen der Ebene und Gerade gilt:
$$
\begin{align}
	E:v_1x_1+v_2x_2+v_3x_3&=
		\begin{pmatrix}r_1\\r_2\\r_3\end{pmatrix}\circ
		\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}\\
	E:~\vec{v}\circ\vec{x}&=\vec{v}\circ\overrightarrow{OR}
\end{align}
$$

$$
\begin{align}
	g:\vec{x}&=\begin{pmatrix}p_1\\p_2\\p_3\end{pmatrix}
		+\lambda\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}\\
	&=\overrightarrow{OP}+\lambda \vec{v}
\end{align}$$
Wird nun wie oben bereits beschrieben die Gerade $g:\vec{x}$ in die Ebene eingesetzt, entsteht folgender Term:

$$
\begin{align}
	E:~\vec{v}\circ\vec{x}&=\vec{v}\circ\overrightarrow{OR}&&\mid \boxed{g:\vec{x}\textit{ in } E}\\
	E:~\vec{v}\circ
		\left(
			\overrightarrow{OP}+\lambda \vec{v}
		\right)
		&=\vec{v}\circ\overrightarrow{OR}\\
	\vec{v}\circ\overrightarrow{OP}
		+ \vec{v}\circ\vec{v}\lambda
		&=\vec{v}\circ\overrightarrow{OR}
			&&\mid\boxed{\vec{v}\circ\vec{v}=
			\left|\vec{v}\right|^2}\\
	\vec{v}\circ\overrightarrow{OP}
		+ \left|\vec{v}\right|^2\lambda
		&=\vec{v}\circ\overrightarrow{OR}&&
			\mid -\left(\vec{v}\circ\overrightarrow{OP}\right)\\
	\left|\vec{v}\right|^2\lambda
		&=\vec{v}\circ\overrightarrow{OR}-\vec{v}\circ\overrightarrow{OP}\\
	\left|\vec{v}\right|^2\lambda
		&=\vec{v}\circ\left(\overrightarrow{OR}-\overrightarrow{OP}\right)&&\mid
			\div \left|\vec{v}\right|^2\\
	\lambda&=\frac{\vec{v}\circ\left(\overrightarrow{OR}-\overrightarrow{OP}\right)}{\left|\vec{v}\right|^2}
\end{align}
$$

Der Verbindungsvektor zwischen dem Punkt außerhalb der Gerade und $\overrightarrow{OS}$ ist in der Länge der Abstand der berechnet werden soll. Der Richtungsvektor dieser beiden Punkte wird gebildet und anschließend in der Länge bestimmt.

---
## Generelle Formel
> Eine Gerade $g:\vec x=\vec p+\lambda\cdot\vec r$ und ein Punkt $\vec q$ sind gegeben, zu denen der Abstand berechnet werden soll.

Wir verwenden eine zu $g$ senkrechte Hilfsebene, die den Punkt $Q$ enthält, und uns den Schnittpunkt des Lotfußpunktes $S$ gibt:
$$
\begin{align}
	\vec r\circ\vec x&=\vec r\circ\vec q\\
	\vec r\circ\left[\vec p+\lambda\cdot\vec r\right]
		&=\vec r\circ\vec q\\
	\vec r\circ\vec p+\lambda\cdot\vec r\circ\vec r
		&=\vec r\circ\vec q&&\mid-\vec r\circ\vec p\\
	\lambda\cdot\textcolor{orange}{\vec r\circ\vec r}
		&=\vec r\circ\vec q-\vec r\circ\vec p\\
	\lambda\cdot\textcolor{orange}{|\vec r|^2}
		&=\vec r\circ\left[\vec q-\vec p\right]&&\mid\div|\vec r|^2\\
	\lambda&=\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\\\\
	\vec s&=\vec p+\lambda\cdot\vec r\\
	\vec s&=\vec p+\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\cdot\vec r
\end{align}
$$
Der Verbindungsvektor $\vec d=\overrightarrow{SQ}$ gibt in der Länge den Abstand zu dem Punkt von der Gerade $g$ an.
$$
\begin{align}
	\vec d&=\overrightarrow{SQ}=\overrightarrow{OQ}-\overrightarrow{OS}\\
	\vec d&=\vec q-\left[\vec{p}+\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\cdot\vec r\right]=
		\vec q-\vec{p}-\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\cdot\vec r\\
	d(g;Q)&=\left|\vec d\right|=\sqrt{
		\left(\vec q_1-\vec{p}_1-\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\cdot\vec r_1\right)^2+
		\left(\vec q_2-\vec{p}_2-\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\cdot\vec r_2\right)^2+
		\left(\vec q_3-\vec{p}_3-\frac{\vec r\circ\left[\vec q-\vec p\right]}{|\vec r|^2}\cdot\vec r_3\right)^2}
\end{align}
$$