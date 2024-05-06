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
Bei diesem Lösungsweg wird ein Punkt $\overrightarrow{OS}$ auf der Gerade so gewählt, dass der Verbindungsvektor zum anderen Punkt (also $\overrightarrow{RS}$ oder $\overrightarrow{SR}$) [skalarmultipliziert](Skalarprodukt) gleich $0$ ist, und somit dieser senkrecht zu der Gerade steht.
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
Der Verbindungsvektor zwischen dem Punkt außerhalb der Gerade und $\overrightarrow{OS}$ ist in der Länge der Abstand der berechnet werden soll. Der Richtungsvektor dieser beiden Punkte wird gebildet und anschließend in der Länge bestimmt.

---