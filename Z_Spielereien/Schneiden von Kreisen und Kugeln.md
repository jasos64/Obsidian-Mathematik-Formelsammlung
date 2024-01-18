Versuchen werde ich hier einen funktionalen Zusammenhang des folgenden Sachverhaltes zu ermitteln:
>Wenn man einen Kreis mit dem Radius $r$ an einer Sekante mit abstand $h$ zu einer parallelen Tangente schneidet, wie wird der Flächeninhalt $A$ verändert.

[[Pasted image 20240103145623.png]]

---
## Beschreibung in Bezügen
Ein Kreis kann durch $x^{2}+y^{2}=r^{2}$ dargestellt werden. Vereinfacht man dies nun auf $y$, so gilt für den Kreis $y=\pm\sqrt{r^{2}-x^{2}}$. Da ich diesen Term folglich als eine Funktion behandeln werde, so muss das $\pm$ aus diesem verschwinden. Dadurch verlieren wir die untere Hälfte des Kreises.

Verschiebt man nun diesen Halbkreis so, dass Nullstellen von $y$ den Schnittpunkten der Sekante in der Distanz zueinander gleich sind, so bildet sich folgende Funktion:
$$a_{o}(x)=\sqrt{r^{2}-x^{2}}+h-r$$
Allerdings muss beachtet werden, dass für $h$ folgender Definitionsbereich gelten muss.
$$D_{1}:0\leq h\leq r$$

---
## Beschreiben des Flächeninhaltes der kleineren Fläche
Da $a_{o}(x)=\sqrt{r^{2}-x^{2}}+h-r$ gültig für den Flächeninhalt ist, und die Fläche der x-Achse identisch ist wie beim Kreis, so müssen die Nullstellen gefunden werden.

$$\begin{align}
0&=\sqrt{r^{2}-x^{2}}+h-r &&|+r-h\\
r-h&=\sqrt{r^{2}-x^{2}}&&|\left(\right)^{2}\\
r^{2}-x^{2}&=(r-h)^{2}\\
r^{2}-x^{2}&=r^{2}-2rh+h^{2}&&|-r^{2}\\
-x^{2}&=-2rh+h^{2}&&|\cdot(-1)\\
x^{2}&=2rh-h^{2}&&|\sqrt{}\\
x_{l,r}&=\mp \sqrt{2rh-h^2}

\end{align}$$
Mit diesem Ausdruck für Nullstellen kann nun der Flächeninhalt der Funktion gebildet werden. Es gilt:
$$A(x)=\bigg|\int^{x_r}_{x_{l}}a_{o}(x)dx\bigg|$$

---
## Berechnung des Flächeninhaltes
Durch $A(x)$ wird der Flächeninhalt dargestellt.
$$\begin{align}
	A_{o}(x)&=\bigg|\int^{x_r}_{x_{l}}a_{o}(x)dx\bigg|\\
	&=\bigg|\int^{x_r}_{x_{l}}\sqrt{r^{2}-x^{2}}+h-r~~dx\bigg|\\
	&=\bigg|\int^{x_r}_{x_{l}}\sqrt{d^{2}-x^{2}}~~dx+\int^{x_r}_{x_{l}}h~~dx+\int^{x_r}_{x_{l}}-r~~dx\bigg|\\
\end{align}$$
Weil die Funktion $a_{o}(x)$ eine y-Achsen Symmetrie besitzt, so kann eine der Integralgrenzen auf $0$ gesetzt werden. Zusätzlich muss das Integral darauf mit $2$ multipliziert werden, da das Intervall davor um die hälfte kleiner gemacht wurde.

$$\begin{align}
	A_{o}(x)&=2\bigg|\int^{x_r}_{0}a_{o}(x)dx\bigg|\\
	&=2\cdot\bigg|\int^{x_r}_{0}\sqrt{r^{2}-x^{2}}~~dx+\int^{x_r}_{0}h~~dx+\int^{x_r}_{0}-r~~dx\bigg|\\
	&=2\cdot\bigg|\bigg[
		\frac{1}{2}\cdot\bigg(x\cdot\sqrt{r^{2}-x^{2}}+r^{2}\cdot\sin^{-1}\left(\frac{x}{r}\right)\cdot \text{sgn}(r)\bigg)
	\bigg]^{x_{r}}_{0}+\bigg[hx\bigg]^{x_{r}}_{0}+\bigg[-rx\bigg]^{x_{r}}_{0}\bigg|\\
	
	 &=2\cdot\bigg|\frac{1}{2}\cdot\bigg(\sqrt{2rh-h^2}\cdot\sqrt{r^{2}-\sqrt{2rh-h^2}^{2}}+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)\cdot \text{sgn}(r)\bigg)\\
	 & ~~~~~~-\frac{1}{2}
	 \cdot\bigg(0\cdot\sqrt{r^{2}-0^{2}}+r^{2}\cdot\sin^{-1}\left(\frac{0}{r}\right)\cdot \text{sgn}(r)\bigg)
	 +\left(h\cdot\sqrt{2rh-h^2}-h\cdot0\right)+\left(-r\cdot\sqrt{2rh-h^2}-\left(-r\cdot0\right)\right)\bigg|\\
	 
	 &=2\cdot\bigg|\frac{1}{2}\cdot\bigg(\sqrt{2rh-h^2}\cdot\sqrt{r^{2}-\sqrt{2rh-h^2}^{2}}+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)\cdot \text{sgn}(r)\bigg)\\
	 & ~~~~~~+h\cdot\sqrt{2rh-h^2}-r\cdot\sqrt{2rh-h^2}\bigg|\\
	 
	 &=2\cdot\bigg|\frac{1}{2}\cdot\bigg(\sqrt{2rh-h^2}\cdot\sqrt{r^{2}-2rh+h^2}+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)\cdot \text{sgn}(r)\bigg)+\sqrt{2rh-h^2}\cdot\left(h-r\right)\bigg|\\
	 
	&=\bigg|\sqrt{2rh-h^2}\cdot(r-h)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)+2\cdot\sqrt{2rh-h^2}\cdot\left(h-r\right)\bigg|\\
	
	&=\bigg|\sqrt{2rh-h^2}\cdot\big((r-h)+2(h-r)\big)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)\bigg|\\
	
	&=\bigg|\sqrt{2rh-h^2}\cdot\big(-(h-r)+2(h-r)\big)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)\bigg|\\
	
	&=\bigg|\sqrt{2rh-h^2}\cdot(h-r)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{2rh-h^2}}{r}\right)\bigg|\\
	
	A_{o}(h)&=\bigg|\sqrt{r^{2}-(h-r)^{2}}\cdot(h-r)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(h-r)^{2}}}{r}\right)\bigg|\\
\end{align}$$

Diese Funktion unter Abhängigkeit von $h$ gilt nur, insofern $D_{1}$ erfüllt, und $r>0$ ist.
*Der Betrag kann zusätzlich ebenfalls entfernt werden, da die Funktion in dem Intervall in dem integriert wird immer $\geq0$ ist.*

Wenn man einen Kreis laut der Formel in der hälfte teilt, also $h=r$ ist, so fällt folgendes auf:

$$\begin{align}
A_{o}(h)&=\bigg|\sqrt{r^{2}-(h-r)^{2}}\cdot(h-r)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(h-r)^{2}}}{r}\right)\bigg|\\
A_{o}(r)&=\bigg|\sqrt{r^{2}-(r-r)^{2}}\cdot(r-r)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(r-r)^{2}}}{r}\right)\bigg|\\
&=\bigg|\sqrt{r^{2}-(0)^{2}}\cdot(0)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(0)^{2}}}{r}\right)\bigg|\\
&=\bigg|\sqrt{r^{2}}\cdot0+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}}}{r}\right)\bigg|\\
&=\bigg|r^{2}\cdot\sin^{-1}\left(1\right)\bigg|\\
&=r^{2}\cdot\frac{\pi}{2}=0,5\cdot(\pi r^{2})\Rightarrow 0,5\cdot A_{g}
\end{align}$$


---
## Verbindungen von $A_{o}(h)$
Da $A_{o}(h)$ den Flächeninhalt des kleineren Segments beschreibt, und dieser von der Gesamtfläche abgezogen wird, so kann man folgenden Schluss ziehen:
$$A_{o+u}=A_{o}(h)+A_{u}$$
$A_{o+u}$ ist hier die Gesamtfläche des Kreises dessen Teilabschnitt getrennt wird. $A_{u}$ ist die untere Fläche nach der Teilung.

Da die Gesamtfläche von $A_{o+u}$ mit $A_{o+u}=\pi\cdot r^{2}$ beschrieben werden kann, so kann folglich der Flächeninhalt der unteren Fläche ausgedrückt werden:
$$\begin{align}
A_{u}&=A_{o+u}-A_{o}(h)\\
A_{u}&=\pi\cdot r^{2}-A_{o}(h)
\end{align}$$

---
## Bildung von $A_{g}(h)$
Da in $A_{o}$ ein Definitionsbereich $D_{1}$ gegeben ist, so werde ich versuchen eine zusammengesetzte Funktion zu finden, welche diesen Bereich erweitert, damit anstelle des halben Kreises, der ganze von $h$ getrennt werden kann.

### Symmetrie
Da es sich bei der Form um einen Kreis handelt, so kann ein größer abgeschnittenes Stück von dem Kreis mit $h>r$ als das Anschneiden von einem kleinerem Stück gesehen werden.

Wenn $h=r$ gilt ist, wie zuvor gezeigt, die hälfte des Kreises auf beiden Seiten getrennt.

Folglich muss wegen der Symmetrie ab der hälfte eine Punktsymmetrie in der Funktion am Ende von $D_{1}$ vorliegen.
Diese Symmetrie führt dazu, dass bei $2r$ die Fläche nun mit der neuen Erweiterung auf $\pi r^{2}$ steigt.

### Bilden der "halben" Punktsymmetrie an dem oberen Ende von $D_{1}$
Anstelle eine Punktsymmetrie an dem Punkt $P\left(r~|~0,5\pi r^{2}\right)$ durch den folgenden Ausdruck an $A_{o}$ zu testen, werde ich die entstehende Bedingung mit dem Punkt $(a~|~b)$ durch
$$\begin{align}
f(a+x)-b&=-f(a-x)+b&&|\\
&\Downarrow\\
f(x)&=2b-f(2a-x)

\end{align}$$
dazu benutzen mir die andere Funktion zu erstellen.

$$\begin{align}
	A_{u}(h)&=-A_{o}(2r-h)+\pi r^{2}\\
	
	&=
	-\sqrt{r^{2}-((2r-h)-r)^{2}}\cdot((2r-h)-r)-r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-((2r-h)-r)^{2}}}{r}\right)+\pi r^{2}\\ 
	
	&=
	-\sqrt{r^{2}-(r-h)^{2}}\cdot(r-h)-r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(r-h)^{2}}}{r}\right)+\pi r^{2}\\
	
	A_{u}(h)&=
	\sqrt{r^{2}-(h-r)^{2}}\cdot(h-r)-r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(h-r)^{2}}}{r}\right)+\pi r^{2}\\
\end{align}$$
Zu bedenken von dieser neuen Funktion ist jetzt, dass der Definitionsbereich dadurch ebenfalls geändert wurde. Nun ist dieser Definitionsbereich der folgende:
$$D_{2}:r\leq h\leq 2r$$

---
### Bilden der bedingten Funktion
Nun sind die für mich wichtigen Funktionshälften fertig definiert und müssen nun vereint werden.
Als Resultat erhält man folgende Funktion:

$$\begin{align}
	A_{g}(h)&=
		\cases{
			A_{o}(h)\quad \text{ wenn }D_{1}\\
			A_{u}(h)\quad \text{ wenn }D_{2}
		}
	\\
	A_{g}(h)&=
		\cases{
			\sqrt{r^{2}-(h-r)^{2}}\cdot(h-r)+r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(h-r)^{2}}}{r}\right) ~~~~~~~~~~~~\text{ wenn }0\leq h\leq r\\
			
			\sqrt{r^{2}-(h-r)^{2}}\cdot(h-r)-r^{2}\cdot\sin^{-1}\left(\frac{\sqrt{r^{2}-(h-r)^{2}}}{r}\right)+\pi r^{2} ~\text{ wenn }r\leq h\leq 2r
		}
\end{align}$$
Da neben $h$ auch $r$ verändert betrachtet werden kann, so kann $A_{g}$ durch $A_{g}(h,r)$ ebenfalls ausgedrückt werden. Die Bedingungen bleiben hierbei allerdings bestehen.


![[desmos-graph.svg]]

---
---
---
# Schneiden von Kugeln in $\mathbb{R}^{3}$
Versuchen werde ich hier einen funktionalen Zusammenhang des folgenden Sachverhaltes zu ermitteln:
>Wenn man eine Kugel mit dem Radius $r$ an einer Ebene mit abstand $h$ zu einer parallelen Tangierenden Ebene schneidet, wie wird der Flächeninhalt $A$ verändert.

---
## Beschreibung in Bezügen
Erneut werde ich das Kugelsegment mit einer Funktion darstellen, mit welchem das Volumen ermittelt werden kann.

Eine Kugel kann durch $x^{2}+y^{2}+z^{2}=r^{2}$ dargestellt werden. Vereinfacht man dies nun auf $y$, so gilt für den Kreis $z=\pm\sqrt{r^{2}-x^{2}-y^{2}}$ 
Da ich mich von Volumina in $\mathbb{R}^{3}$ direkt aus diesem Auszug fernhalten möchte, so werde ich die Bezugsfunktion $a_{o}(x)=\sqrt{r^{2}-x^{2}}+h-r$ für die Segmentgröße eines Kreises als Rotationskörper um die y-Achse verwenden um somit das Volumen der getrennten Kugel auszudrücken.

---
## Bildung einer geeigneten Umkehrfunktion
Wenn $a_{o}(x)=\sqrt{r^{2}-x^{2}}+h-r$ die um die y-Achse gedrehte Funktion ist, so werde ich diese zu $a_{o}^{-1}(x)$ umwandeln, um diese anschließend um die x-Achse rotieren zu lassen um einfacher mit dieser zu arbeiten.

$$\begin{align}
a_{o}(x)&=\sqrt{r^{2}-x^{2}}+h-r\\
y&=\sqrt{r^{2}-x^{2}}+h-r&&|-h+r\\
y-h+r&=\sqrt{r^{2}-x^{2}}&&|()^{2}\\
\left(y-h+r\right)^{2}&=r^{2}-x^{2}&&|-r^{2}\\ 
-r^{2}+\left(y-h+r\right)^{2}&=-x^{2}&&|\cdot(-1)\\
r^{2}-\left(y-h+r\right)^{2}&=x^{2}&&|\sqrt{}\\
x&=\pm \sqrt{r^{2}-\left(y-h+r\right)^{2}}\\
&\Downarrow\\
a_{o}^{-1}(x)&=\sqrt{r^{2}-\left(x-h+r\right)^{2}}
\end{align}$$

Die negative Version des Wurzelterms entfällt hier, da dieser für weitere Arbeiten unwichtig ist.

---
## Bilden der Rotationskörpervolumina
Die Darstellung von generellen Rotationskörpern ist die folgende:
$$V=\pi\cdot\int^{b}_{a}f(x)^2~dx$$
Die Grenzwerte unseres Integrals liegen hierbei bei $a=0$ und $b=h$, da das von $a_{o}$ existente Maximum auf der y-Achse liegt und dabei die höhe $h$ hat. $a_{o}(0)=h$. Durch die Umkehrfunktion ist dieser Punkt nun eine Nullstelle, welche als Intervallgrenzen gewertet werden kann. $a_{o}^{-1}(h)=0$. Die Nullstelle welche zuvor bei $x_{l,r}=\sqrt{2rh-h^{2}}$ lag, ist nun bei der Stelle $a_{o}^{-1}(0)$. Dadurch werden die Grenzen für das Integral klar.

$$\begin{align}
	V&=\pi\cdot\int^{b}_{a}\left(a_{o}^{-1}(x)\right)^2~dx\\
	
	&=\pi\cdot\int^{h}_{0}
	\left(
		\sqrt{r^{2}-\left(x-h+r\right)^{2}}
	\right)^{2}~dx\\
	
	&=\pi\cdot\int^{h}_{0}
		r^{2}-\left(x-h+r\right)^{2}
	~dx\\
	
	&=\pi\cdot\int^{h}_{0}
		r^{2}-\left(
			x^{2}+h^{2}+r^{2}-2hx+2rx-2hr
		\right)
	~dx\\
	
	&=\pi\cdot\int^{h}_{0}
		r^{2}
		-x^{2}-h^{2}-r^{2}+2hx-2rx+2hr
	~dx\\
	
	&=\pi\cdot\int^{h}_{0}
		-x^{2}-h^{2}+2hx-2rx+2hr
	~dx\\
	&=\pi\cdot\left(
		\int^{h}_{0}
			-x^{2}
		~dx~~+
		\int^{h}_{0}
			-h^{2}
		~dx~~+
		\int^{h}_{0}
			2hx
		~dx~~+
		\int^{h}_{0}
			-2rx
		~dx~~+
		\int^{h}_{0}
			2hr
		~dx
	\right)\\
	
	&=\pi\cdot\left(
		\left[
			-\frac{1}{3}x^{3}
		\right]_{0}^{h}+
		\left[
			-h^{2}x
		\right]_{0}^{h}+
		\left[
			hx^{2}
		\right]_{0}^{h}+
		\left[
			-rx^{2}
		\right]_{0}^{h}+
		\left[
			2hrx
		\right]_{0}^{h}
	\right)\\
	
	&=\pi\cdot\left(
		\left(
			-\frac{1}{3}h^{3}-\left(-\frac{1}{3}0^{3}\right)
		\right)+
		\left(
			-h^{2}h-(-h^{2}\cdot0)
		\right)+
		\left(
			h\cdot h^{2}-\left(h\cdot 0^{2}\right)
		\right)+
		\left(
			-rh^{2}-\left(-r0^{2}\right)
		\right)+
		\left(
			2hrh-\left(2hr0\right)
		\right)
	\right)\\
	
	&=\pi\cdot\left(
		\left(
			-\frac{1}{3}h^{3}
		\right)+
		\left(
			-h^{3}
		\right)+
		\left(
			h^{3}
		\right)+
		\left(
			-rh^{2}
		\right)+
		\left(
			2h^{2}r
		\right)
	\right)\\
	
	&=\pi\cdot\left(
		-\frac{1}{3}h^{3}-h^{3}+h^{3}-h^{2}r+2h^{2}r
	\right)\\
	
	V_{g}(h)&=
		-\frac{\pi}{3}h^{3}+\pi h^{2}r
\end{align}$$
Für $V$ gilt wie bei dem Kreis der gleiche Definitionsbereich. Allerdings da dieser durch eine Polynomfunkion gebildet ist, so ist der Definitionsbereich hier $D_{3}:0\leq h\leq 2r$.

---
## Vergleich der Funktion
$V_{g}(h)$ stellt das Volumen des zunächst kleineren Segments dar, falls die Ebene der $x_{1}, x_{2}$ Ebene zuzutragen ist und die Kugel sich unter ihr mit $h\rightarrow 2r$ der $x_{3}$ Achse steigt nähert.

Folglich ist bei $h=2r$ die komplette Kugel über oder in der Ebene, wodurch sich die allgemeine Funktion für Volumina mit Kugeln zeigen sollte:
$$\begin{align}
V_{K}(r)&=\frac{4}{3}\cdot\pi\cdot r^{3}\\
\\
V_{g}(h)&=-\frac{\pi}{3}h^{3}+\pi h^{2}r\\
V_{g}(2r)&=-\frac{\pi}{3}(2r)^{3}+\pi (2r)^{2}r\\
&=-\frac{\pi}{3}2^{3}r^{3}+\pi 2^{2}r^{2}r\\
&=-\frac{8\pi}{3}r^{3}+4\pi r^{3}\\
&=\left(4\pi-\frac{8\pi}{3}\right)\cdot r^{3}\\
&=\left(\frac{12\pi-8\pi}{3}\right)\cdot r^{3}\\
&=\left(\frac{4\pi}{3}\right)\cdot r^{3}\\
&=\frac{4}{3}\cdot\pi\cdot r^{3}
\end{align}$$
In diesem Fall ist $V_{k}(r)\equiv V_{g}(2r)$. Als einen weiteren Test werde ich die Kugel nun mittels meinem Zusammenhang diese halbieren. Erneut sollte eine Kongruenz ersichtlich sein.
$$\begin{align}
V_{K}(r)&=\frac{1}{2}\cdot\frac{4}{3}\cdot\pi\cdot r^{3}\\
\\
V_{g}(h)&=-\frac{\pi}{3}h^{3}+\pi h^{2}r\\
V_{g}(r)&=-\frac{\pi}{3}(r)^{3}+\pi (r)^{2}r\\
&=-\frac{\pi}{3}r^{3}+\pi r^{2}r\\
&=-\frac{\pi}{3}r^{3}+\pi r^{3}\\
&=\left(1-\frac{1}{3}\right)\cdot \pi r^{3}\\
&=\left(\frac{3-1}{3}\right)\cdot \pi r^{3}\\
&=\left(\frac{2}{3}\right)\cdot \pi r^{3}\\ 
&=\left(\frac{1}{2}\cdot\frac{4}{3}\right)\cdot \pi r^{3}\\ 
&=\frac{1}{2}\cdot\frac{4}{3}\cdot\pi\cdot r^{3}
\end{align}$$
Hier in diesem Fall gilt $\frac{1}{2}\cdot V_{K}(r)\equiv V_{g}(\frac{1}{2}\cdot2r)$.
Allerdings gilt nicht durch diesen Aufschrieb, dass $\frac{1}{n}\cdot V_{K}(r)\equiv V_{g}\left(\frac{1}{n}\cdot2r\right)$. Diese These werde ich nun klären:
$$\begin{align}
	\frac{1}{n}\cdot V_{K}(r)&= V_{g}\left(\frac{1}{n}\cdot2r\right)\\
	
	\frac{1}{n}\cdot \frac{4}{3}\cdot\pi\cdot r^{3}
	&\equiv
	-\frac{\pi}{3}\left(\frac{1}{n}\cdot2r\right)^{3}+\pi \left(\frac{1}{n}\cdot2r\right)^{2}r\\
	
	\frac{4}{3n}\cdot\pi r^{3}
	&=
	-\frac{\pi}{3}\left(\frac{1}{n^{3}}\cdot2^{3}r^{3}\right)+\pi \left(\frac{1}{n^{2}}\cdot2^{2}r^{2}\right)r\\
	
	\frac{4}{3n}\cdot\pi r^{3}
	&=
	-\frac{\pi}{3}\cdot\frac{1}{n^{3}}\cdot2^{3}r^{3}+\pi \frac{1}{n^{2}}\cdot2^{2}r^{2}r\\
	
	\frac{4}{3n}\cdot\pi r^{3}
	&=
	-\frac{8}{3n^{3}}\cdot \pi r^{3}+\frac{4}{n^{2}}\cdot \pi r^{3}\\
	
	\frac{4}{3n}\cdot\pi r^{3}
	&=
	\left(
		\frac{4}{n^{2}}-\frac{8}{3n^{3}}
	\right)\cdot \pi r^{3}\\
	
	\frac{4}{3n}\cdot\pi r^{3}
	&=
	\left(
		\frac{12n^{3}-8n^{2}}{3n^{5}}
	\right)\cdot \pi r^{3}
	&&|\cdot\frac{1}{\pi r^{3}}\\
	
	\frac{4}{3n}
	&=
	\frac{12n^{3}-8n^{2}}{3n^{5}} \\
	
	\frac{4}{3n}
	&=
	\frac{n^{2}(12n-8)}{3n^{5}}\\
	
	\frac{4}{3n}
	&=
	\frac{12n-8}{3n^{3}}
	&&|\cdot3n^{3}\\
	
	\frac{12n^{3}}{3n}
	&=
	12n-8\\
	
	4n^{2}
	&=
	12n-8
	&&|-4n^{2}\\
	
	0
	&=
	-4n^{2}+12n-8
	&&|-4n^{2}\\
	
	n_{1,2}&=1,5\pm0,5
\end{align}$$
Weil $\left|\mathbb{L}\right|\neq \infty$, so sind die beiden Aussagen nicht identisch.