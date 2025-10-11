>Das Städtchen Ickshausen soll eine nördliche Umgehungsstraße erhalten. Die Lage des Ortskerns sowie der Verlauf der alten und der neuen Straße können in einem Koordinatensystem veranschaulicht werden, wobei der Ortskern in dessen Ursprung liegt. Die alte Straße verläuft entlang der $x$-Achse in West-Ost-Richtung genau durch die Ortsmitte. Die Umgehungsstraße soll die Punkte $P( - 2 |0)$ und $Q (2|0)$ über den Punkt $R (0|2)$ verbinden und ohne Knick in den alten Straßenverlauf übergehen.

## a)
>Leiten Sie eine Gleichung einer ganzrationalen Funktion vierten Grades her, deren Graph symmetrisch zur y-Achse verläuft und den neuen Straßenverlauf beschreibt

Von oben gilt:
- $f(-2)=0$
- $f(2)=0$
- $f(0)=2$
- $f'(-2)=0$
- $f'(2)=0$
- $f(x)=ax^4+bx^3+cx^2+dx+e$
- $f'(x)=4ax^3+3bx^2+2cx+d$

Daraus resultiert folgendes Gleichungssystem:
$$
\left(\begin{array}{(ccccc|c)}
	a&b&c&d&e&\\\hline
	16&-8&4&-2&1&0\\
	16&8&4&2&1&0\\
	0&0&0&0&1&2\\
	-32&12&-4&1&0&0\\
	32&12&4&1&0&0\\
\end{array}\right)
$$
Aus der dritten Zeile erkennt man, dass $e=2$ ist. Dies für alle anderen Zeilen eingesetzt und umgestellt führt dazu, dass das LGS nun folgendermaßen aussieht:
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	16&8&4&2&-2\\
	-32&12&-4&1&0\\
	32&12&4&1&0\\
\end{array}\right)
$$

Die Umformung, welche gerade durchgeführt wurde, lässt sich am Beispiel der ersten darstellen, und für jede weitere Zeile anwenden:
$$
\begin{align}
	16a-8b+4c-2d+e&=0&&\boxed{e=2}\\
	16a-8b+4c-2d+2&=0&&\mid-2\\
	16a-8b+4c-2d&=-2
\end{align}
$$

## Umwandlung des LGS
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	16&8&4&2&-2\\
	-32&12&-4&1&0\\
	32&12&4&1&0\\
\end{array}\right)
	\begin{array}{c}
		\\ \mid\cdot (-1);~~II+I\\ \\ \\ \\ 
	\end{array}
$$
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	0&16&0&4&0\\
	-32&12&-4&1&0\\
	32&12&4&1&0\\
\end{array}\right)
	\begin{array}{c}
		\\ \mid\cdot 2;~~I+III\\ \\ \\ \\ 
	\end{array}
$$
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	0&16&0&4&0\\
	0&-4&4&-3&-4\\
	32&12&4&1&0\\
\end{array}\right)
	\begin{array}{c}
		\\ \mid\cdot (-2);~~I+IV\\ \\ \\ \\ 
	\end{array}
$$
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	0&16&0&4&0\\
	0&-4&4&-3&-4\\
	0&28&-4&5&4\\
\end{array}\right)
	\begin{array}{c}
		\\ \\ \mid\cdot (\frac{1}{4});~~III+II \\ \\ \\ 
	\end{array}
$$
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	0&16&0&4&0\\
	0&0&4&-2&-4\\
	0&28&-4&5&4\\
\end{array}\right)
	\begin{array}{c}
		\\ \\ \mid\cdot (\frac{-7}{4});~~IV+II \\ \\ \\ 
	\end{array}
$$
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	0&16&0&4&0\\
	0&0&4&-2&-4\\
	0&0&-4&-2&4\\
\end{array}\right)
	\begin{array}{c}
		\\ \\  \\~~IV+II \\ \\ 
	\end{array}
$$
$$
\left(\begin{array}{(cccc|c)}
	a&b&c&d&\\\hline
	16&-8&4&-2&-2\\
	0&16&0&4&0\\
	0&0&4&-2&-4\\
	0&0&0&-4&0\\
\end{array}\right)
	\begin{array}{c}
		\\ \\  \\~~IV+II \\ \\ 
	\end{array}
$$
Aus $IV:$
$-4d=0\Rightarrow d=0$

Aus $III:$
$$
\begin{align}
	4c-2d&=-4&&\mid \boxed{d=0}\\
	4c&=-4&&\mid\div4\\
	c&=-1
\end{align}
$$
Aus $II:$
$$
\begin{align}
	16b+4d&=0&&\mid \boxed{d=0}\\
	16b&=0&&\mid\div16\\
	b&=0
\end{align}
$$
Aus $I:$
$$
\begin{align}
	16a-8b+4c-2d&=-2&&\mid \boxed{b=0;~ c=-1;~ d=0}\\
	16a-8\cdot0+4\cdot(-1)-2\cdot0&=-2\\
	16a-4&=-2&&\mid+4\\
	16a&=2&&\mid\div16\\
	a&=\frac{2}{16}=\frac{1}{8}
\end{align}
$$
Daraus gegeben ist die gesuchte Funktion $f(x)=\frac{1}{8}x^4-x^2+2$.
$f(x)$ ist hier unter $D=\{x\in\mathbb{R}\mid -2\le x\le 2\}$ definiert.
Damit in diesem Intervall $\left[-2;2\right]$ der nördlich gelegenste Punkt als $R$ bewiesen werden kann, muss folgendes gelten:
- $f'(0)=0$
- $f''(0)<0$

## Beweis des nördlichsten Punktes $R$
$$
\begin{align}
	\textit{Notwendiges Kriterium für lokale Extrema:}~f'(x)&=0\\\\
	
	0&=f'(x)\\
	0&=\frac{1}{2}x^3-2x\\
	0&=x\left(\frac{1}{2}x^2-2\right)\\\\
	x_2&=0~~\bigvee~~0=\frac{1}{2}x^2-2\\\\
	0&=\frac{1}{2}x^2-2\\
	2&=\frac{1}{2}x^2\\
	x^2=4\\
	x_{1;3}&=\pm 2
\end{align}
$$
$$
\begin{align}
	\textit{Hinreichendes Kriterium für lokale Extrema:}
		~f''(x)&\ne0\\
	f''(x)&=\frac{3}{2}x^2-2\\
	f''(0)&=-2<0\\
	f''(2)&=4>0\\
	f''(-2)&=4>0
\end{align}
$$
Da hier $f''(0)<0$ ist, so handelt es sich um ein lokales Maximum. Da die Funktion $f$ zusätzlich stetig ist, so kann nur das Extremum bei $x=0$ auf dem Intervall das globale Maximum des Intervalls sein. Die Minima, welche sich an den Stellen $x=\pm2$ befinden sind Teil der Intervallgrenzen. Es kann durch Stetigkeit folglich kein weiterer Punkt höher als $R$ auf dem Intervall sein.

Es soll genau einen Punkt $S$ auf $f$ geben, welcher von Westen gesehen eine links-rechts Kurve verbindet. Gemeint ist hier eine links-rechts Wendestelle von $f$, mit dessen Koordinaten.
$f''(x)=\frac{3}{2}x^{2}-2$ ist an dieser Stelle $0$, und besitzt eine negative Steigung.
$$
\begin{align}
	&=\frac{3}{2}x^{2}-2\\\\
	0&=f''(x)\\
	0&=\frac{3}{2}x^{2}-2\\
	2&=\frac{3}{2}x^{2}\\
	2\cdot\frac{2}{3}&=x^2\\
	x^2&=\frac{4}{3}\\
	x_{1;2}&=\pm\sqrt{\frac{4}{3}}=\pm\frac{2}{\sqrt{3}}=\pm\frac{2\sqrt{3}}{3}
\end{align}
$$
$$
\begin{align}
	f'''(x)&=3x\\\\
	f'''\left(-\frac{2\sqrt{3}}{3}\right)&=-2\sqrt{3}\\
	f'''\left(\frac{2\sqrt{3}}{3}\right)&=2\sqrt{3}
\end{align}
$$
Es gibt ausschließlich auf $f$ diese zwei Wendestellen $\frac{2\sqrt{3}}{3}$ und $-\frac{2\sqrt{3}}{3}$. Hier ist die mit negativen Vorzeichen die gesuchte, da dann die Steigung ebenfalls negativ ist (von $f''(x)$).
Die Koordinaten lauten dann:
$$
\begin{align}
	S\left(-\frac{2\sqrt{3}}{3}~~\bigg|~~
		\frac{1}{8}\cdot\left(-\frac{2\sqrt{3}}{3}\right)^4-\left(-\frac{2\sqrt{3}}{3}\right)^2+2
	\right)\Leftrightarrow S\left(-\frac{2\sqrt{3}}{3}\bigg|\frac{8}{9}\right)
\end{align}
$$

---
# b)

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,2,0,2]
disableZoom: false
grid: true
---
f(x)=1/8x^4-x^2+2
g(x)=0.5x^4-1.5x^3+0.5x^2+2
```
$0.5x^{4}-1.5x^{3}+0.5x^{2}-x+1.875=0$ soll als Lösung(en) Punkte nordöstlich des Punktes $T(1\mid1,125)$ auf $f(x)$ geben.
Zusätzlich ist $g(x)=0.5x^{4}-1.5x^{3}+0.5x^{2}+2$ gegeben.
Nordöstliche Punkte von $T$ werden durch eine Gerade $q(x)=x+0,0125$ beschrieben. Nullstellen dieser Gerade, und $g(x)$ sind folglich nordöstliche Punkte der neuen Umleitung $g$.
Setzen wir dies nun um, so ergibt sich die Gleichung $0.5x^{4}-1.5x^{3}+0.5x^{2}-x+1.875=0$.

---
# c)
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-2,2,0,2]
disableZoom: false
grid: true
---
f(x)=1/8x^4-x^2+2
h(x)=exp(-0.2x)+0.5
```
$h(x)=e^{-0,2x}+0,5$ (rot)

$$
\begin{align}
	A&\approx\int^{0,85}_{-0,62}\frac{1}{8}x^4-x^2+2
		-e^{-0,2x}-0,5~~dx\\
	&\approx\left[\frac{1}{40}x^5-\frac{1}{3}x^3+1,5x
		+\frac{1}{0,2}e^{-0,2x}\right]_{-0,62}^{0,85}\\
	&\approx 5,2997-4,8072\\
	&\approx0,4925\left[km^2\right]\\
	&=492500\left[m^2\right]
\end{align}
$$
Der Quadratmeterpreis beträgt $\frac{7500000}{492500}\texteuro\approx15,2284\frac{\texteuro}{m^2}$.

---
# d)
Der durchschnittliche Abstand der Ortsdurchfahrt und der Umleitung $f$ beträgt $\frac{\int^{2}_{-2}f(x)dx}{4}$.
$$
\begin{align}
	d&=\frac{\int^{2}_{-2}f(x)dx}{4}\\
	&=\frac{1}{2}\cdot\int^{2}_{0}\frac{1}{8}x^4-x^2+2~~dx\\
	&=\frac{1}{2}\cdot
		\left[
			\frac{1}{40}x^5-\frac{1}{3}x^3+2x
		\right]_0^2\\
	&=\frac{1}{2}\cdot\left(
			\frac{1}{40}\cdot2^5-\frac{1}{3}\cdot2^3+2\cdot2-0+0-0
		\right)\\
	&=\frac{1}{2}\cdot\left(
			\frac{32}{15}
		\right)\\
	&=\frac{32}{30}\approx1,06667\left[km\right]
\end{align}
$$
Der durchschnittliche Abstand der beiden Strecken beträgt ungefähr $1,07~km$.

---
Ein Verfahren, mit dem der kürzeste Abstand zwischen dem Ursprung und $f$ bestimmen lässt, ist der folgende: $\sqrt{x^2+f(x)^2}$. Es wird ein Dreieck auf jedem Punkt von $f$ in einem Intervall aufgestellt, dessen Hypotenusen der Wurzelterm sind. Um nun den kürzesten Abstand zu finden, muss man diesen Term ableiten, und auf Minima untersuchen.

---