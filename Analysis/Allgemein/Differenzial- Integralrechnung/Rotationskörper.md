Rotationskörper sind Körper, welche durch eine Oberfunktion $f(x)$ um eine Achse rotiert wird und somit diese Oberfunktion die Form bildet. Für das Volumen von Zylindern gilt nach wie vor $V=\pi r^2h$.
Wird die Oberfunktion nun mit Zylindern mit Höhe $\Delta x$ angenähert, dessen Volumina dadurch $V=\pi f(x_i)^2\cdot \Delta x$ heißt, gilt zunächst: $\sum \pi f(x_i)^2\cdot \Delta x$. Desto niedriger hier die höhe ist, desto genauer wird die Annäherung. Hier wird daraus folgend, dass $\Delta x\to 0$, die Summe $\int^{b}_{a}\left(\pi f(x)^2\right)dx$ annimmt.

Eine [[Funktion(en)]] $f$ ist gegeben, welche Grenzfunktion eines Körpers in einem Intervall heißt.
$f(x)$ ist hier unten beispielsweise als $0,1x^{3}-x^{2}+2,5x$ für $0\le x\le 5$ [definiert](Definitionsbereich).
```desmos-graph
left=0; right=5;
    top=2; bottom=0;
    ---
f(x)=0.1x^3-x^2+2.5x
0\le y\le f\left(x\right)
```

Für Volumina eines Rotationskörpers gilt nach wie vor die oben beschriebene Formel $V=\int^{b}_{a}\left(\pi\cdot f(x)^2\right)dx=\pi\int^{b}_{a}f(x)^2dx$. Setzen wir nun $f$ ein, wird zunächst $f^2$ gebildet und anschließend als [Integral](Integration) ([Rechenweg](obsidian://open?vault=Obsidian-Mathematik-Formelsammlung&file=Analysis%2FAllgemein%2FDifferenzial-%20Integralrechnung%2FFl%C3%A4cheninhalte%20zwischen%20zwei%20Funktionen)) standartüblich verrechnet.
Es gilt:
$$
\begin{align}
	V&=\pi\int^{b}_{a}f(x)^2~dx\\
	&=\pi\int^{5}_{0}\left(0,1x^{3}-x^{2}+2,5x\right)^2~dx\\
	&=\pi\int^{5}_{0}
		\left(0,01x^{6}-0,2x^{5}+1,5x^{4}-5x^{3}+6,25x^{2}\right)~dx\\
	&=\pi\left[
		\frac{0,01}{7}x^7
		-\frac{0,2}{6}x^{6}
		+\frac{1,5}{5}x^{5}
		-\frac{5}{4}x^{4}
		+\frac{6,25}{3}x^{3}
		\right]^{5}_{0}\\
	&=\pi\left[
		\frac{1}{700}x^7
		-\frac{2}{60}x^{6}
		+\frac{15}{50}x^{5}
		-\frac{5}{4}x^{4}
		+\frac{625}{300}x^{3}
		\right]^{5}_{0}\\
	&=\pi\left[
		\frac{1}{700}x^7
		-\frac{1}{30}x^{6}
		+\frac{3}{10}x^{5}
		-\frac{5}{4}x^{4}
		+\frac{25}{12}x^{3}
		\right]^{5}_{0}\\
	
	&=\pi\left(
		\frac{1}{700}\cdot5^7
		-\frac{1}{30}\cdot5^{6}
		+\frac{3}{10}\cdot5^{5}
		-\frac{5}{4}\cdot5^{4}
		+\frac{25}{12}\cdot5^{3}
			-\left(
			\frac{1}{700}\cdot0^7
		-\frac{1}{30}\cdot0^{6}
		+\frac{3}{10}\cdot0^{5}
		-\frac{5}{4}\cdot0^{4}
		+\frac{25}{12}\cdot0^{3}
			\right)\right)\\
	&=\pi\left(
		\frac{1}{700}\cdot5^7
		-\frac{1}{30}\cdot5^{6}
		+\frac{3}{10}\cdot5^{5}
		-\frac{5}{4}\cdot5^{4}
		+\frac{25}{12}\cdot5^{3}\right)\\
	&=\frac{625}{84}\pi\approx 23,375
\end{align}
$$

Daraus ergibt sich, dass das Volumen des Rotationskörpes der Funktion $f$ von $0$ bis $5$ um die $x$-Achse ungefähr $23,375~\left[VE\right]$ beträgt.

---
## Rotationskörper zwischen zwei Grenzfunktionen
Beispielsweise soll ein Rohr aus dem folgendem Rotationskörper gebildet werden:
```desmos-graph
left=-1; right=5;
    top=2; bottom=0;
    ---
f\left(x\right)=0.2x+1
g\left(x\right)=0.5\sqrt{x+1}+0.4
g\left(x\right)\le y\le f\left(x\right)\left\{0\le x\le3\right\}
```

Zu beachten ist, dass die Funktionen laut der Formel zuvor quadriert werden, ehe die Terme vereint werden.
$f(x)=0,2x+1$ ist hier die obere, und $g(x)=0,5\sqrt{x+1}+0,4$ die untere Grenzfunktion. $V=\pi\int^{b}_{a}f(x)^2~dx-\pi\int^{b}_{a}g(x)^2$. Danach muss nichts weiteres bedacht werden, außer dass das Integral korrekt gebildet wird.

---
## Rotationskörper um die $y$-Achse
Für Rotationskörper um die $y$-Achse kann die selbe Formel wie oben verwendet werden, allerdings muss zunächst die Abhängigkeit der Funktion (hier also $f$) nicht auf $x$, sondern $y$ sein muss. Folglich ergibt sich:
$$V=\pi\int^{b}_{a}f(y)^2~dy$$

$f(y)$ heißt hier [[Umkehrfunktion]] von $f(x)$. Es gilt also $f(y)\equiv \overline{f}(x)$.

Visuell dargestellt ist diese Rotation auf $f(x)=x^3+0,5$ für $0,5\le x\le 1,5$:
```desmos-graph
left=-2; right=2;
    top=2; bottom=0;
    ---
f(x)=x^3+0.5
y\ge f\left(x\right)\left\{0\le x\right\}\left\{0.5\le y\le1.5\right\}
```
Erkennbar sind die Grenzen $a=0,5$ und $b=1,5$.

Bilden wir zunächst die Umkehrfunktion $\overline{f}(x)$:
$$
\begin{align}
	f(x)&=x^3+0,5\\\\
	x&=y^3+0,5&&\mid -0,5\\
	y^3&=x-0,5&&\mid \sqrt[3]{}\\
	y&=\sqrt[3]{x-0,5}
\end{align}
$$
Verwenden wir nun die Umkehrfunktion für die Formel, ist dies identisch wie die Rotation um die $y$-Achse, weil weiterhin die Grenzen beibehalten werden, und sich der Flächeninhalt nicht geändert hat.
```desmos-graph
left=-1; right=2;
    top=2; bottom=-1;
    ---
f(x)=(x-0.5)^{1/3}
0\le y\le\sqrt[3]{x-0.5}\left\{0.5\le x\le1.5\right\}
```

Das Weiterrechnen erfolgt wie oben beschrieben ohne weitere Bedingungen.

---