# Analytische Geometrie
> Der Flughafen von Moosheim mit einer asphaltierten Start- und Landebahn wird mit einigen Punkten vereinfacht dargestellt. Der Boden wird durch die $x_1x_2$-Ebene modelliert, die Start- und Landebahn durch die Punkte $A_p(-75\sqrt{2}\mid-100\sqrt{2}\mid0)$, $B_p(1425\sqrt{2}\mid1400\sqrt{2}\mid0)$, $C_p(1400\sqrt{2}\mid1425\sqrt{2}\mid0)$ und $D_p(-100\sqrt{2}\mid-75\sqrt{2}\mid0)$.
> Die Stadt kann mit den Punkten $A_s(-1400\mid2800\mid0)$, $B_s(-1000\mid0\mid0)$, $C_s(-400\mid-200\mid0)$ und $D_s(1000\mid2000\mid0)$ mit dem Viereck $A_sB_sC_sD_s$ eingegrenzt werden.
> 
> Eingehender Flugverkehr landet in Nord-Westlicher Richtung.
> Eine Längeneinheit entspricht einem Meter in der Realität. Die $x_1$-Achse zeigt nach Norden, die $x_2$-Achse nach Westen

### a)
> Zeichnen Sie die Stadt, die Start- und Landebahn sowie die Einflugsrichtung und Himmelsrichtungen in das gegebenen Koordinatensystem ein.
> Dieses ist eine Betrachtung orthogonal zum Boden, mit $x_3=0$.

![[AnaGeo-FlughafenKoordinatensystem0.png|1500]]

### b)
> Beweisen Sie rechnerisch, dass die Stadtgrenzen ein Trapez mit dem Flächeninhalt $4~000~000~\left[m^2\right]$ bilden.

### c)
> Auf der Landebahn landendende Flugzeuge bewegen sich pro Sekunde mit dem Richtungsvektor $\vec r=\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}$ auf den Landepunkt $O(0\mid0\mid0)$ zu.
> Erstellen Sie die Geradengleichung, auf der sich Flugzeuge zum landen befinden. Berechnen Sie auch, ob ein Anflugswinkel von angesetzten $3,6\degree$ ausreichend eingehalten wird.

### d)
> Auf dem Punkt $C_s$ befindet sich ein Wall mit Aussichtsturm. Personen können von diesem in $20$ Metern Höhe landende Flugzeuge betrachten.
> Bestimmen Sie, welche Entfernung von dem Aussichtspunkt zu einem landenden Flugzeug besteht, wenn sich dieses mit der Kugelgleichung $\left[\overrightarrow{OX}-\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\cdot t\right]^2=60^2$ entlang der Gerade bewegt. Das Flugzeug wird hier als Kugel modellhaft dargestellt, wobei $t$ in Sekunden ist (Begründung siehe Aufgabe c)). Geben Sie anschließend die Anzahl an Sekunden vor der planmäßigen Landung des Flugzeuges an, wenn es die geringste Entfernung zum Aussichtspunkt hat.

### e)
> Im Laufe des Tages verändert sich die Richtung des Sonnenlichts. Die Sonne strahlt in Richtung $\vec{l}_\theta=\begin{pmatrix}100\sin(\theta)\\100\sqrt{2}\cos(\theta)\\-100\sin(\theta)\end{pmatrix}$, wobei $\theta$ den Sonnenstand zwischen $0^\degree$ (Morgens) und $180\degree$ (Abends) beschreibt.
> Es ladet ein Flugzeug zu einer beliebigen Uhrzeit;
> Bestimmen Sie die Ebene, in der sich das Schattenbild des Flugzeugs bewegt, welches sich entlang der Anflugsgerade (c)) dem Flughafen nähert. Bestimmen Sie anschließend die Gerade, die der Schatten des Flugzeugs auf dem Boden beim entlangfliegen bildet.

---
# Lösungen
### a)
![[AnaGeo-FlughafenKoordinatensystem1.png|500]]

### b)
Für ein Trapez gilt, dass mindestens ein Seitenpaar parallel zueinander sein muss.
Es gilt:
$$
\begin{align}
	\overrightarrow{B_sC_s}&=\lambda\cdot\overrightarrow{D_sA_s}\\
	\begin{pmatrix}-400\\-200\\0\end{pmatrix}-
		\begin{pmatrix}-1000\\0\\0\end{pmatrix}&=\lambda\cdot\left[
		\begin{pmatrix}-1400\\2800\\0\end{pmatrix}-
			\begin{pmatrix}1000\\2000\\0\end{pmatrix}\right]\\
	\begin{pmatrix}600\\-200\\0\end{pmatrix}
	&=\lambda\cdot\begin{pmatrix}-2400\\800\\0\end{pmatrix}=
		-\frac14\cdot\begin{pmatrix}-2400\\800\\0\end{pmatrix}\\
	\begin{pmatrix}600\\-200\\0\end{pmatrix}
	&=\begin{pmatrix}600\\-200\\0\end{pmatrix}
\end{align}
$$
Mit $\lambda=-\frac{1}{4}$ sind die Verbindungsvektoren gleich, somit sind die beiden Verbindungsvektoren aufgrund ihres Vielfachen parallel zueinander, und die Form $A_sB_sC_sD_s$ ist ein Trapez.
Für den Flächeninhalt gilt (Anwendung Spatprodukt):
$$
\begin{align}
	A&=\frac{1}{2}\cdot\left|
		\overrightarrow{A_sB_s}\times\overrightarrow{A_sC_s}\right|
		+\frac{1}{2}\cdot\left|\overrightarrow{A_sC_s}\times\overrightarrow{A_sD_s}\right|=
		
	\frac{1}{2}\cdot\left|
		\begin{pmatrix}-1000+1400\\-2800\\0\end{pmatrix}
		\times\begin{pmatrix}-400+1400\\-200-2800\\0\end{pmatrix}\right|
		+\frac{1}{2}\cdot\left|\begin{pmatrix}-400+1400\\-200-2800\\0\end{pmatrix}
		\times\begin{pmatrix}1000+1400\\2000-2800\\0\end{pmatrix}\right|\\
	&=\frac{1}{2}\cdot\left|
		\begin{pmatrix}400\\-2800\\0\end{pmatrix}
		\times\begin{pmatrix}1000\\-3000\\0\end{pmatrix}\right|
		+\frac{1}{2}\cdot\left|\begin{pmatrix}1000\\-3000\\0\end{pmatrix}
		\times\begin{pmatrix}2400\\-800\\0\end{pmatrix}\right|=
	\frac{1}{2}\cdot\left|
		\begin{pmatrix}0\\0\\1~600~000\end{pmatrix}
		\right|
		+\frac{1}{2}\cdot\left|\begin{pmatrix}0\\0\\6~400~000\end{pmatrix}
		\right|\\
	&=\frac{1}{2}\cdot1~600~000+\frac{1}{2}\cdot6~400~000=4~000~000~\left[m^2\right]
\end{align}
$$

### c)
Eine der unendlich vielen Anfluggeraden ist:
$$g:\vec x=t\cdot\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}$$
Für den Schnittwinkel mit der Bodenebene $E:x_3=0$ gilt:
$$
\begin{align}
	\alpha=\angle(g;E)&=\sin^{-1}\left(\left|\frac{\vec n_E\circ\vec r_g}{\left|\vec n_E\right|\cdot\left|\vec r_g\right|}\right|\right)=
	
		\sin^{-1}\left(\left|\frac{\begin{pmatrix}0\\0\\1\end{pmatrix}
		\circ\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}}{\left|\begin{pmatrix}0\\0\\1\end{pmatrix}\right|\cdot\left|\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\right|}\right|\right)\\
	&=\sin^{-1}\left(\left|\frac{-\frac{\sqrt{482}}5}{\sqrt{\left(\frac{247}{5}\right)^2+\left(\frac{247}{5}\right)^2+\left(-\frac{\sqrt{482}}5\right)^2}}\right|\right)=
		\sin^{-1}\left(\left|\frac{-\frac{\sqrt{482}}5}{70}\right|\right)\\
	\alpha&\approx3,596\degree
\end{align}
$$
Weil $\alpha\approx3.596\degree\approx3,6\degree$, so folgt der Anflugwinkel ungefähr den vorgesehenen $3,6\degree$.

### d)
Der Aussichtspunkt ist $P(-400\mid-200\mid20)$.
Der kürzeste Abstand zu der Kugel, ist ebenfalls der kürzeste Abstand zur Gerade. Dadurch gibt es zwei mindestens zwei Möglichkeiten den Zeitpunkt der kürzesten Distanz auszurechnen:
1. Kürzester Abstand mittels der Geradengleichung
	1. Hier mit Hilfsebene
2. Kürzester Abstand mittels der Kugelgleichung
	1. $P$ in die Kugelgleichung einsetzen, und mit Ignoranz des Radius nach $t$ auflösen. Anschließend ableiten, da das Minimum des entstehenden Terms dem Minimum der Entfernung entspricht.

#### d) 1:
Eine Hilfsebene wird im Punkt $P$ senkrecht zur Gerade $g$ aufgestellt:
$$
\begin{align}
	E:\vec{r}\circ\vec x&=\vec{r}\circ\overrightarrow{OP}\\
	\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\circ\vec x&=\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\circ\begin{pmatrix}-400\\-200\\20\end{pmatrix}\\
	\frac{247}{5}x_1+\frac{247}{5}x_2-\frac{\sqrt{482}}{5}x_3&=-29640-4\sqrt{482}
\end{align}
$$
Die Gerade $g:\vec x=t\cdot\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}$ aus Aufgabe c) wird in $E$ eingesetzt und nach der Variable $t$ aufgelöst:
$$
\begin{align}
	E:\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\circ\vec x&=\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\circ\begin{pmatrix}-400\\-200\\20\end{pmatrix}\\
	
	\underbrace{\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\circ\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}}_{=4900}\cdot t&=-29640-4\sqrt{482}&&\mid\div4900\\
	t&=\frac{-29640-4\sqrt{482}}{4900}\approx-6,067
\end{align}
$$

#### d) 2:
Der Aussichtspunkt wird in $\overrightarrow{OX}$ eingesetzt. Anschließend wird der Term ohne Radius betrachtet, da uns der kleinste Wert dieser Gleichung interessiert. Hierdurch kommt die Ableitung ins Spiel, mit der wir den Zeitpunkt bestimmen:
$$
\begin{align}
	\left[\overrightarrow{OX}-\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\cdot t\right]^2&=60^2\\
	\Rightarrow\qquad
	f(t)&=\left[\overrightarrow{OC_s}-\vec r\cdot t\right]^2=
		\left[\overrightarrow{OC_s}-\vec r\cdot t\right]\circ
		\left[\overrightarrow{OC_s}-\vec r\cdot t\right]\\
	&=\overrightarrow{OC_s}\circ\overrightarrow{OC_s}
		-2\cdot\overrightarrow{OC_s}\circ\vec r\cdot t+\vec r\circ\vec r\cdot t^2=
		\left|\overrightarrow{OC_s}\right|^2
		-2\cdot\overrightarrow{OC_s}\circ\vec r\cdot t+
		\left|\vec r\right|^2\cdot t^2\\
	f'(t)&=
		-2\cdot\overrightarrow{OC_s}\circ\vec r+
		2\cdot\left|\vec r\right|^2\cdot t\\\\
	\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad f'(t)=0\\
	0&=f'(t)\\
	0&=-2\cdot\overrightarrow{OC_s}\circ\vec r+
		2\cdot\left|\vec r\right|^2\cdot t&&\mid+2\cdot\overrightarrow{OC_s}\circ\vec r\\
	2\cdot\overrightarrow{OC_s}\circ\vec r&=
		2\cdot\left|\vec r\right|^2\cdot t&&\mid\div
			2\cdot\left|\vec r\right|^2\\
	t&=\frac{2\cdot\overrightarrow{OC_s}\circ\vec r}{2\cdot\left|\vec r\right|^2}=
		\frac{\overrightarrow{OC_s}\circ\vec r}{\left|\vec r\right|^2}\\
	\Rightarrow\qquad t&=\frac{-29640-4\sqrt{482}}{4900}\approx-6,067
\end{align}
$$

#### d) Lösung
Nun haben wir den Zeitpunkt und können sagen, dass sich das Flugzeug ungefähr $6,067$ Sekunden vor dem Aufsetzen auf der Landebahn befindet, wenn es den geringsten Abstand zum Aussichtspunkt hat.
Der Abstand zwischen dem Aussichtspunkt und dem Flugzeug ist hiermit:
$$
\begin{align}
	d_g&=\left|\overrightarrow{OC_s}-\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\cdot t\right|=
		\left|\begin{pmatrix}-400\\-200\\20\end{pmatrix}-\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\cdot \frac{-29640-4\sqrt{482}}{4900}\right|\\
	&=\left|\begin{pmatrix}-400\\-200\\20\end{pmatrix}-\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}\cdot \frac{-29640-4\sqrt{482}}{4900}\right|\\
	d_g&\approx141,58~\left[m\right]
\end{align}
$$
Wichtig zu nennen ist, dass dieser Abstand der kürzeste zwischen dem Aussichtspunkt und der Gerade ist. Da das Flugzeug durch eine Kugel mit dem Radius $60~\left[m\right]$ dargestellt ist, muss dieser dem Abstand abgezogen werden:
$$d_R=d_g-60\approx81,58~\left[m\right]$$
Das Flugzeug befindet sich somit mit der nahestehen Stelle etwa $81,58~\left[m\right]$ vom Aussichtspunkt entfernt.

### e)
Hier ist die Ebene gesucht, die durch den Richtungsvektor des Schattens ($\vec l_\theta$), als auch dem Richtungsvektor der Anflugsgerade ($\vec r$)aufgespannt ist. Wir erhalten durch einsetzen:
$$
\begin{align}
	E_s:\vec x&=\vec p+\lambda\cdot\vec r+\mu\cdot\vec l_\theta\\
	&=\lambda\cdot\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}+\mu\cdot
		\begin{pmatrix}100\sin(\theta)\\100\sqrt{2}\cos(\theta)\\
		-100\sin(\theta)\end{pmatrix}
\end{align}
$$
Der Stützvektor $\vec p$ fällt hier weg, da $O(0\mid0\mid0)$ auf der Anflugsgerade liegt und somit auf $E_s$ liegen muss.
$E_s$ gibt die gesuchte Ebene an.
Der Weg, den der Schatten über den Boden nimmt, ist die Schnittgerade von $E_s$ und der $x_1x_2$-Ebene. Für Schnittgeraden zwischen Parameter und Koordinatenform von Ebenen wird die Parameterform in die Koordinatenform eingesetzt und nach einer Variable umgestellt, und anschließend in die Parameterform substituiert:
$$
\begin{align}
	E_s:\vec x&=\lambda\cdot\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\\textcolor{orange}{-\frac{\sqrt{482}}{5}}\end{pmatrix}+\mu\cdot
		\begin{pmatrix}100\sin(\theta)\\100\sqrt{2}\cos(\theta)\\
		\textcolor{orange}{-100\sin(\theta)}\end{pmatrix}\\
	E_{x_1x_2}:\quad \textcolor{orange}{x_3}&=0\\\hline\\
	-\frac{\sqrt{482}}{5}\cdot\lambda-100\sin(\theta)\cdot\mu&=0&&\mid+100\sin(\theta)\cdot\mu\\
	-\frac{\sqrt{482}}{5}\cdot\lambda&=100\sin(\theta)\cdot\mu
		&&\mid\cdot\left(-\frac{5}{\sqrt{482}}\right)\\
	\lambda&=-\frac{500\sin(\theta)\cdot\mu}{\sqrt{482}}\\\hline\\
	g_s:\vec x&=-\frac{500\sin(\theta)\cdot\mu}{\sqrt{482}}\cdot\begin{pmatrix}\frac{247}{5}\\\frac{247}{5}\\-\frac{\sqrt{482}}{5}\end{pmatrix}+\mu\cdot
		\begin{pmatrix}100\sin(\theta)\\100\sqrt{2}\cos(\theta)\\
		-100\sin(\theta)\end{pmatrix}\\
	&=\mu\cdot\begin{pmatrix}\frac{247}{5}\cdot\frac{-500\sin(\theta)}{\sqrt{482}}\\\frac{247}{5}\cdot\frac{-500\sin(\theta)}{\sqrt{482}}\\-\frac{\sqrt{482}}{5}\cdot\frac{-500\sin(\theta)}{\sqrt{482}}\end{pmatrix}+\mu\cdot
		\begin{pmatrix}100\sin(\theta)\\100\sqrt{2}\cos(\theta)\\
		-100\sin(\theta)\end{pmatrix}=
		
		\mu\cdot\begin{pmatrix}-\frac{24700\sin(\theta)}{\sqrt{482}}\\-\frac{24700\sin(\theta)}{\sqrt{482}}\\100\sin(\theta)\end{pmatrix}+\mu\cdot
		\begin{pmatrix}100\sin(\theta)\\100\sqrt{2}\cos(\theta)\\
		-100\sin(\theta)\end{pmatrix}\\
	g_s:\vec x&=\mu\cdot
		\begin{pmatrix}100\sin(\theta)-\frac{24700\sin(\theta)}{\sqrt{482}}\\100\sqrt{2}\cos(\theta)-\frac{24700\sin(\theta)}{\sqrt{482}}\\
		0\end{pmatrix}
\end{align}
$$
$g_s:\vec x$ ist die gesuchte Schnittgerade.

