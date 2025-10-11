## Aufgabe 3
> Ein Sportler trainiert in einer Kletterhalle. Die Situation wird in einem geeigneten Koordinatensystem modelliert, wobei eine Längeneinheit einem Meter in der Realität entspricht.
> Die $x_1x_2$-Ebene stellt den Hallenboden dar. Der Kletterer steht zunächst auf dem Startpunkt $\left(0\mid0\mid0\right)$. Er klettert an der Wand $PQRS$ hoch, greift von dort auf die Wand $RSTU$ über und hangelt sich an ihr nach vorne bis zur Kante $\overline{TU}$.

> Die ebenen Vierecke $PQRS$ und $RSTU$ haben die Eckpunkte $P\left(0\mid-2\mid0\right)$, $Q\left(-2\mid0\mid0\right)$, $R\left(-1\mid2\mid4\right)$, $S\left(1\mid0\mid4\right)$, $T\left(2\mid3\mid4,5\right)$ und $U\left(0\mid5\mid4,5\right)$.
> Das Viereck $PQRS$ liegt in der Ebene $E$.

---
### a
#### a1)
>Berechnen Sie die Länge der Kante $\overline{PQ}$.

Gegeben ist:
- $\overrightarrow{OP}=\begin{pmatrix}0\\-2\\0\end{pmatrix}$
- $\overrightarrow{OQ}=\begin{pmatrix}-2\\0\\0\end{pmatrix}$

$$
\begin{align}
	\left|\overrightarrow{PQ}\right|&=
		\left|\overrightarrow{OQ}-\overrightarrow{OP}\right|\\
	&=\left|\begin{pmatrix}-2\\0\\0\end{pmatrix}
		-\begin{pmatrix}0\\-2\\0\end{pmatrix}\right|\\
	&=\left|\begin{pmatrix}-2-0\\0-(-2)\\0-0\end{pmatrix}\right|\\
	&=\left|\begin{pmatrix}-2\\2\\0\end{pmatrix}\right|\\
	&=\sqrt{(-2)^2+2^2+0^2}\\
	&=\sqrt{2^2+2^2}=\sqrt{8}=\sqrt{4\cdot2}
		=2\sqrt{2}\approx2,828\left[LE\right]
\end{align}$$
Die Länge der Kante $\overline{PQ}$ ist $2\sqrt{2}\left[LE\right]$ lang.

---
#### a2)
> Zeigen Sie, dass das Viereck $PQRS$ ein Parallelogramm, aber kein Rechteck ist.

Verbindungsvektoren des Vierecks $PQRS$ lauten:
- $\overrightarrow{PQ}=\begin{pmatrix}-2\\2\\0\end{pmatrix}$
- $\overrightarrow{QR}=\begin{pmatrix}1\\2\\4\end{pmatrix}$
- $\overrightarrow{RS}=\begin{pmatrix}2\\-2\\0\end{pmatrix}$
- $\overrightarrow{SP}=\begin{pmatrix}-1\\-2\\-4\end{pmatrix}$
Es ist erkennbar, dass $\overrightarrow{PQ}=-\overrightarrow{RS}$ und $\overrightarrow{QR}=-\overrightarrow{SP}$ ist. Somit gilt: $\bigg\{\overrightarrow{PQ}\parallel\overrightarrow{RS}\bigg\}\bigvee\bigg\{\overrightarrow{QR}\parallel\overrightarrow{SP}\bigg\}\bigvee\bigg\{\left|\overrightarrow{PQ}\right|=\left|\overrightarrow{RS}\right|\bigg\}\bigvee\bigg\{\left|\overrightarrow{QR}\right|=\left|\overrightarrow{SP}\right|\bigg\}$
>Um ein Rechteck auszuschließen darf ein beliebiger Winkel nicht rechter Winkel heißen.

Zu zeigen:
$$
\begin{align}
	\angle\bigg\{\overrightarrow{PQ};\overrightarrow{QR}\bigg\}&\ne 90\degree\\
	\overrightarrow{PQ}\circ\overrightarrow{QR}&\ne0\\
	\begin{pmatrix}-2\\2\\0\end{pmatrix}\circ
		\begin{pmatrix}1\\2\\4\end{pmatrix}&\ne0\\
	-2\cdot1+2\cdot2+0\cdot4&\ne0\\
	\underbrace{-2+4}_{=2}&\ne0
\end{align}
$$
Da der Winkel hier nicht recht ist, so kann $PQRS$ kein Rechteck sein.

---
#### a3)
> Bestimmen Sie eine Gleichung der Ebene $E$ in Koordinatenform.

$$
\begin{align}
	\vec{n}&=\overbrace{\begin{pmatrix}-2\\2\\0\end{pmatrix}}
		^{\overrightarrow{PQ}}
		\times
			\overbrace{\begin{pmatrix}1\\2\\4\end{pmatrix}}
		^{\overrightarrow{QR}}\\
	&=\begin{pmatrix}2\cdot4-0\cdot2\\0\cdot1-(-2)\cdot4\\-2\cdot2-2\cdot1\end{pmatrix}\\
	&=\begin{pmatrix}8\\8\\-6\end{pmatrix}\hat{=}
		\begin{pmatrix}4\\4\\-3\end{pmatrix}
\end{align}
$$

Eine Koordinatenform lautet
$$
\begin{align}
	E:\vec{n}\circ\vec{x}&=\vec{n}\circ\overrightarrow{OP}\\
	\begin{pmatrix}4\\4\\-3\end{pmatrix}\circ
		\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}&=
	\begin{pmatrix}4\\4\\-3\end{pmatrix}\circ
		\begin{pmatrix}0\\-2\\0\end{pmatrix}\\
	
	4x_1+4x_2-3x_3&=-8
\end{align}
$$

---
#### a4)
> Berechnen Sie den Schnittpunkt der Ebene $E$ mit der $x_3$-Achse und geben Sie die Höhe der Wand senkrecht über dem Startpunkt an.

Sei $x_1=0$ und $x_2=0$:
$$
\begin{align}
	E:4x_1+4x_2-3x_3&=-8\\
	4\cdot0+4\cdot0-3x_3&=-8\\
	-3x_3&=-8&&\mid\div(-3)\\
	x_3&=\frac{8}{3}=2,\overline{6}\\\\
	
	P_{x_3}&\left(0\mid0\mid2,\overline{6}\right)
\end{align}
$$
Die Schnittmenge von $E$ und der $x_3$-Achse ist $P_{x_3}\left(0\mid0\mid2,\overline{6}\right)$. Da der Startpunkt auf den Ursprung definiert wird, so muss die Höhe der Wand senkrecht über dem Startpunkt die Höhe $x_3=2,\overline{6}$ haben.

---
#### a5)
> Untersuchen Sie, ob es in der Ebene $E$ einen Punkt $\left(x_1\mid x_2\mid2\right)$ mit ganzzahligen Koordinaten $x_1$ und $x_2$ gibt.

Konstruieren wir eine Gerade $g_s$ so, dass diese parallel zur $x_1x_2$-Ebene liegt, und diese einen Punkt $P_s\left(x_1\mid x_2\mid2\right)$ der Ebene $E$ schneidet, dann sollte diese ausschließlich in $E$ sein.
Um dies zu erreichen benutzen wir $\overrightarrow{PQ}$, da dieser Vektor sowohl parallel zu der Ebene $E$ ist, als auch parallel zur $x_1x_2$-Ebene ist.

Für den Punkt $P_s$ setzen wir $x_2=0$ und $x_3=2$ und lösen nach $x_1$ auf.
$$
\begin{align}
	E:4x_1+4x_2-3x_3&=-8\\
	4x_1+4\cdot0-3\cdot2&=-8\\
	4x_1-6&=-8&&\mid+6\\
	4x_1&=-2&&\mid\div4\\
	x_1&=-0,5\\\\
	P_s&(-0,5\mid0\mid2)
\end{align}
$$

Konstruiert wird folgend die Geradengleichung, welche anschließend in einem allgemeinem Vektor beschrieben wird.
$$
\begin{align}
	g_s:\vec{x}&=
		\begin{pmatrix}
			-0,5\\0\\2
		\end{pmatrix}
		+\lambda
		\begin{pmatrix}
			-2\\2\\0
		\end{pmatrix}\\
	&=
		\begin{pmatrix}
			-0,5\\0\\2
		\end{pmatrix}
		+\lambda
		\begin{pmatrix}
			-1\\1\\0
		\end{pmatrix}\\
	&=\begin{pmatrix}
			-0,5-\lambda\\0+\lambda\\2+0\lambda
		\end{pmatrix}\\
	&=\begin{pmatrix}
			-0,5-\lambda\\\lambda\\2
		\end{pmatrix}
\end{align}
$$
Es ergibt sich durch diesen Ortsvektor, dass $\lambda$ auf der $x_2$-Komponente für alle $\lambda\in\mathbb{Z}$ ganzzahlig ist.
Allerdings ist $x_1=-0,5-\lambda$ durch die Verschiebung von $0,5$ dann in diesen Werten für Lambda nicht ganzzahlig. Es gibt somit kein Koordinatenpaar, welches ganzzahlig ist.

---
### b
> In der Nähe der Kante $\overline{TU}$ hängt bei $G(3\mid3,5\mid4,5)$ eine Glocke, die mit einer Leine am Hallendach befestigt ist. Zum Abschluss seiner Trainingseinheit läutet der Kletterer diese Glocke mit der einen Hand, während er sich mit der anderen Hand an demjenigen Punkt $K$ auf der Kante $\overline{TU}$ festhält, der den geringsten Abstand zu $G$ hat.

Durch $T$ und $U$ verläuft die Gerade $g:\vec{x}=\overrightarrow{OT}+r\cdot\overrightarrow{TU}=\begin{pmatrix}2\\3\\4,5\end{pmatrix}+r\cdot\begin{pmatrix}-2\\2\\0\end{pmatrix}$.
#### b1)
> Bestimmen Sie den Fußpunkt $F$ des Lotes von $G$ auf $g$.

$$
\begin{align}
	\left[\begin{pmatrix}2\\3\\4,5\end{pmatrix}-
		\begin{pmatrix}3\\3,5\\4,5\end{pmatrix}+
		r\cdot\begin{pmatrix}-2\\2\\0\end{pmatrix}\right]
		\circ\begin{pmatrix}-2\\2\\0\end{pmatrix}&=0\\
	\underbrace{\begin{pmatrix}-1\\-0,5\\0\end{pmatrix}
		\circ\begin{pmatrix}-2\\2\\0\end{pmatrix}}_{=1}+
		r\cdot\underbrace{\begin{pmatrix}-2\\2\\0\end{pmatrix}
		\circ\begin{pmatrix}-2\\2\\0\end{pmatrix}}_{=8}&=0&&\mid-1\\
	8r&=-1&&\mid\div8\\
	r&=\frac{1}{8}
\end{align}
$$
Dieser Wert für $r$ wird in $g$ eingesetzt um den Punkt zu bestimmen.
$$
\begin{align}
	g:\vec{x}&=\begin{pmatrix}2\\3\\4,5\end{pmatrix}+
		r\cdot\begin{pmatrix}-2\\2\\0\end{pmatrix}\\
	\overrightarrow{OF}&=
		\begin{pmatrix}2\\3\\4,5\end{pmatrix}-
			\frac{1}{8}\cdot\begin{pmatrix}-2\\2\\0\end{pmatrix}\\
	&=\begin{pmatrix}2,25\\2,75\\4,5\end{pmatrix}\\
	\\
	F&(2,25\mid2,75\mid4,5)
\end{align}
$$

---
#### b2)
> Begründen Sie, dass $K$ und $F$ nicht identisch sind.

$F$ ist nicht Element der Kante $\overline{TU}$. Der Kletterer kann sich somit nicht an diesem Punkt festhalten.

---
#### b3)
> Künftig soll die Glocke an einem anderen Punkt $G^*$ platziert werden. Der Punkt $G^*$ befindet sich in einer Höhe von $4,5m$ und ist gleich weit von $T$ und $U$ entfernt; sein Abstand vom Mittelpunt $M$ der Kante $\overline{TU}$ beträgt $35cm$
> 
> Ermitteln Sie die Koordinaten des Punktes $M$ und die Koordinaten eines Punktes $G^*$ mit den beschriebenen Eigenschaften.

$$
\begin{align}
	\overrightarrow{OM}&=\overrightarrow{OT}
		+0,5\cdot\overrightarrow{TU}\\
	&=
	\begin{pmatrix}
		2\\3\\4,5
	\end{pmatrix}+0,5
	\begin{pmatrix}
		-2\\2\\0
	\end{pmatrix}\\
	&=
	\begin{pmatrix}
		1\\4\\4,5
	\end{pmatrix}\\
	M&(1\mid4\mid4,5)
\end{align}
$$

Da $M$ die Mitte der Kante beschreibt, und $G^*$ einen gleichen Abstand zu $T$ und $U$ besitzen soll, so muss dieser Punkt $G^*$ das Lot auf dem Punkt $M$ haben. Es gilt einen senkrechten Vektor der Ebene $x_3=4,5$ zu finden, der Koordinaten für solche Punkte angibt.

$$
\begin{align}
	\begin{pmatrix}
		1\\4\\4,5
	\end{pmatrix}\circ
	\begin{pmatrix}
		a_1\\a_2\\a_3
	\end{pmatrix}&=0\\
	a_1+4a_2+4,5a_3&=0&&\boxed{Sei~~a_3=0;~a_1=1}\\
	1+4a_2+4,5\cdot0&=0\\
	1+4a_2&=0&&\mid-1\quad\div4\\
	a_2&=-\frac{1}{4}\\
	\begin{pmatrix}
		a_1\\a_2\\a_3
	\end{pmatrix}&=
	\begin{pmatrix}
		1\\-\frac{1}{4}\\0
	\end{pmatrix}\hat{=}\begin{pmatrix}
		4\\-1\\0
	\end{pmatrix}
\end{align}
$$

Die Gerade aller Punkte lautet somit:
$$
\begin{align}
	h:\vec{x}&=\overrightarrow{OM}+\mu\cdot\begin{pmatrix}
		a_1\\a_2\\a_3
	\end{pmatrix} \\
	&=\begin{pmatrix}
		1\\4\\4,5
	\end{pmatrix}+\mu\cdot\begin{pmatrix}
		4\\-1\\0
	\end{pmatrix}
\end{align}
$$
Normalisieren wir den Richtungsvektor nun, damit Einsetzen von $0,35$ eine Distanz von $0,35m$ von $M$ hervorbringt, kann durch einsetzen der Punkt bestimmt werden, den $G^*$ annimmt.
$$
\begin{align}
	h_0:\vec{x}&=\begin{pmatrix}
		1\\4\\4,5
	\end{pmatrix}+\mu\cdot\frac{1}{\sqrt{17}}\cdot\begin{pmatrix}
		4\\-1\\0
	\end{pmatrix}\\
	&=\begin{pmatrix}
		1\\4\\4,5
	\end{pmatrix}+0,35\cdot\frac{1}{\sqrt{17}}\cdot\begin{pmatrix}
		4\\-1\\0
	\end{pmatrix}\approx\begin{pmatrix}
		1,3395\\3,9151\\4,5
	\end{pmatrix}
\end{align}
$$
Die Glocke hängt somit eventuell auf dem Punkt $G^*(1,3395\mid3,9151\mid4,5)$.

---
### c
> Im Rahmen einer Renovierung wird darüber nachgedacht, den Winkel zwischen den beiden Wänden zu verändern. Für jedes $a\in\mathbb{R}$ ist durch $E_a:~x_1+x_2-ax_3=1-4a$ eine Ebene $E_a$ gegeben. Jede dieser Ebenen enthält die Gerade durch $R$ und $S$.

#### c1)
> Es gibt genau eine Zahl $a$ mit $E_a=E$. Bestimmen Sie diese Zahl.

Betrachten wir $E_a:~x_1+x_2-ax_3=1-4a$ und vergleichen diese mit $E:4x_1+4x_2-3x_3=-8$ fällt auf, dass die $x_1$ und $x_2$ Abschnitte ein vielfaches von $4$ hier sind. Multiplizieren wir somit $E_a$ mit $4$, so erhalten wir eine ähnliche Version zu $E$, und können $a$ so wählen, dass diese identisch sind.

$$
\begin{align}
	E_a:~x_1+x_2-ax_3&=1-4a&&\mid\cdot4\\
	4x_1+4x_2-4ax_3&=4-16a
\end{align}
$$
$$
\begin{align}
	\begin{array}{ccc}
		-4a&=&-3\\
		4-16a&=&-8
	\end{array}\\\\
		\begin{array}{ccc}
		a&=&\frac{3}{4}\\
		-16a&=&-12
	\end{array}\\\\
		\begin{array}{ccc}
		a&=&\frac{3}{4}\\
		a&=&\frac{3}{4}
	\end{array}
\end{align}
$$
Da für beide $a$ in $E_a$ die gleiche Zahl eingesetzt dazu führt, dass $E_a=E$ ist, so muss $a=0,75$ sein, dass $E_a=E$ ist.

---
#### c2)
> $E_8$ ist diejenige Ebene, in der das Viereck $RSTU$ liegt. Berechnen Sie den Schnittwinkel der Ebenen $E$ und $E_8$.

$$
\begin{align}
	E_8:~x_1+x_2-8x_3&=1-4\cdot8\\
	x_1+x_2-8x_3&=-31\\\\
	\vec{v_8}&=\begin{pmatrix}
1\\1\\-8
\end{pmatrix}
\end{align}
$$
Für Winkel zwischen Ebenen gilt $\cos^{-1}\left(\frac{\vec{v_8}\circ\vec{n}}{|v_8|\cdot|n|}\right)$.
$$
\begin{align}
	\alpha&=\cos^{-1}\left(\frac{\vec{v_8}\circ\vec{n}}{|v_8|\cdot|n|}\right)\\
	&=\cos^{-1}\left(\frac{
		\overbrace{\begin{pmatrix}
			1\\1\\-8
		\end{pmatrix}\circ\begin{pmatrix}
			4\\4\\-3
		\end{pmatrix}}^{=32}}{\underbrace{\left|\begin{pmatrix}
			1\\1\\-8
		\end{pmatrix}\right|\cdot\left|\begin{pmatrix}
			4\\4\\-3
		\end{pmatrix}\right|}_{=\sqrt{2706}}}\right)\\
	&=\cos^{-1}\left(\frac{
		32}{\sqrt{2706}}\right)\\
	&\approx52,0367\degree
\end{align}
$$

---
#### c3)
> Bestimmen Sie alle Zahlen $a$, so dass sich $E$ und $E_a$ unter einem $60\degree$-Winkel schneiden.

$$
\begin{align}
	\alpha&=\cos^{-1}\left(\frac{\vec{v_a}\circ\vec{n}}{|v_a|\cdot|n|}\right)\\
	&=\cos^{-1}\left(\frac{
		\begin{pmatrix}
			1\\1\\-a
		\end{pmatrix}\circ\begin{pmatrix}
			4\\4\\-3
		\end{pmatrix}}{\left|\begin{pmatrix}
			1\\1\\-a
		\end{pmatrix}\right|\cdot\left|\begin{pmatrix}
			4\\4\\-3
		\end{pmatrix}\right|}\right)\\
		
	&=\cos^{-1}\left(\frac{
		8+3a}{\sqrt{1+1+a^2}\cdot\sqrt{41}}\right)\\
	&=\cos^{-1}\left(\frac{
		8+3a}{\sqrt{41+41+41a^2}}\right)
\end{align}
$$
Für Werte $-0,5\le x\le0,5$ ist der Schnittwinkel im Arkuscosinus unter $60\degree$. Somit muss gelten:
$$
\begin{align}
	16+6a<\sqrt{41+41+41a^2}
\end{align}
$$

blablabla, rechnen und so