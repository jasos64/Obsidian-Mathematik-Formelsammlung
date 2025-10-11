# Analysis
> Die Temperaturveränderung eines Topfes kann mit der Funktionenschar $t_a(x)=\left(-\frac{16}{5a}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}$ für $a\ge10$ dargestellt werden. Mittels eines Drehknopfes kann der Topf kurzzeitig, oder Langzeitig aufgeheizt werden. Die Einheit von $t_a(x)$ ist $\left[\frac{\textdegree C}{min}\right]$ (Grad Celsius pro Minute). $x$ gibt die Zeit in Minuten nach Einschalten des Heizmechanismus an an.
> Der Raum (und somit der Topf zu Beginn auch), hat eine Temperatur von $20\textdegree C$.

> Abb. 1: $t_{10}(x)$
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,25,-10,10]
disableZoom: true
grid: true
---
f(x)=(-(16/50)x^2+(16/5)*x)*exp(-0.2x)
```

### a)
> Erklären Sie, wieso $t_a(x)$ nicht mehr als $2$ Nullstellen haben kann. Bestimmen Sie zusätzlich die Punkte $P_{1;2}$, die die Nullstellen sind.

### b)
> Zeigen Sie, dass die Extrema von $t_{10}(x)$ einen $x$ Abstand von $10\sqrt{2}$ haben.

### c)
> Bestimmen Sie den Zeitpunkt der größten Temperaturveränderung von $t_{10}(x)$, und zeichnen Sie diese in Abb. 1 ein. Geben Sie die Tangentengleichung an dieser Stelle an.

### d)
> Überprüfen Sie, ob $T_a(x)=\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\cdot e^{-0,2x}+\frac{100a-800}{a}$ eine Stammfunktion ist, die den Sachverhalt optimal darstellt.

### e)
> Für $\lim_{a\to\infty}~t_a(x)=\frac{16}{5}x\cdot e^{-0,2x}$. Bestätigen Sie diese Aussage anhand des Funktionsterms.
> Bestimmen Sie die Wertemenge der Endtemperaturen für $\lim_{x\to\infty}$ des Topfes unter allen möglichen $a$. Nutzen Sie $T_a(x)$ aus Aufgabe d).

---
# Lösungen
### a)
$t_a(x)$ kann nicht mehr als zwei Nullstellen haben, da ein Produkt zweier Funktionen gegeben ist, und für Nullstellen jeweils mindestens ein Faktor null werden muss.
$\left(-\frac{16}{5a}x^2+\frac{16}{5}x\right)$ besitzt maximal zwei Nullstellen, $e^{-0,2x}$
ist immer $>0$.
$$
\begin{align}
	&&0&=t_a(x)\\
	&&0&=\left(-\frac{16}{5a}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}\\
	\text{I:}&&\quad0&=e^{-0,2x}\Rightarrow x\in\{\}\\
	\text{II:}&&\quad-\frac{16}{5a}x^2+\frac{16}{5}x&=0\\
	\text{II}_1:&&\quad x_1&=0\\
	\text{II}_2:&&\quad-\frac{16}{5a}x+\frac{16}{5}&=0\\
	&&\quad-\frac{16}{5a}x&=-\frac{16}{5}\\
	&&\quad x_2&=a
\end{align}
$$
Die Punkte sind somit $P_1(0\mid0)$ und $P_2(a\mid0)$.

### b)
$$
\begin{align}
	t_a(x)&=\left(-\frac{16}{5a}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}\\
	t_{10}(x)&=\left(-\frac{16}{50}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}\\
	t_{10}'(x)&=
		\left(-\frac{16}{25}x+\frac{16}{5}\right)\cdot e^{-0,2x}+
		\left(-\frac{16}{50}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}\cdot(-0,2)\\
		&=\left(\left(-\frac{16}{25}x+\frac{16}{5}\right)-0,2
		\left(-\frac{16}{50}x^2+\frac{16}{5}x\right)\right)\cdot e^{-0,2x}\\
		&=\left(-\frac{16}{25}x+\frac{16}{5}+\frac{8}{125}x^2-\frac{16}{25}x\right)\cdot e^{-0,2x}\\
		&=\left(\frac{8}{125}x^2-\frac{32}{25}x+\frac{16}{5}\right)\cdot e^{-0,2x}\\\hline\\
	\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad f_{10}'(x)=0\\
	0&=f_{10}'(x)\\
	0&=\left(\frac{8}{125}x^2-\frac{32}{25}x+\frac{16}{5}\right)\cdot e^{-0,2x}&&\mid\boxed{e^{-0,2x}>0}\\
	0&=\frac{8}{125}x^2-\frac{32}{25}x+\frac{16}{5}&&\mid\cdot\frac{125}{8}\\
	0&=x^2-20x+50\\
	x_{1;2}&=-\frac{-20}{2}\mp\sqrt{\left(\frac{-20}{2}\right)^2-50}\\
	&=10\mp\sqrt{100-50}=10\mp\sqrt{50}\\
	x_1&=10-\sqrt{50}\\
	x_2&=10+\sqrt{50}\\\hline\\
	d&=\left|x_2-x_1\right|=\left|(10+\sqrt{50})-(10-\sqrt{50})\right|=\left|10+\sqrt{50}-10+\sqrt{50}\right|\\
	&=\left|2\sqrt{50}\right|=\sqrt{4\cdot50}=\sqrt{2\cdot100}
		=\sqrt{100}\cdot\sqrt{2}=10\sqrt{2}
\end{align}
$$

### c)
$$
\begin{align}
	f_{10}'(x)&=\left(\frac{8}{125}x^2-\frac{32}{25}x+\frac{16}{5}\right)\cdot e^{-0,2x}\\
	f_{10}''(x)&=\left(\frac{16}{125}x-\frac{32}{25}\right)\cdot e^{-0,2x}+\left(\frac{8}{125}x^2-\frac{32}{25}x+\frac{16}{5}\right)\cdot e^{-0,2x}\cdot(-0,2)\\
	&=\left(\left(\frac{16}{125}x-\frac{32}{25}\right)-0,2\left(\frac{8}{125}x^2-\frac{32}{25}x+\frac{16}{5}\right)\right)\cdot e^{-0,2x}\\
	&=\left(\frac{16}{125}x-\frac{32}{25}-\frac{8}{625}x^2+\frac{32}{125}x-\frac{16}{25}\right)\cdot e^{-0,2x}\\
	&=\left(-\frac{8}{625}x^2+\frac{48}{125}x-\frac{48}{25}\right)\cdot e^{-0,2x}\\\hline\\
	\text{Notwendiges Kriterium}&\text{ für Wendestellen:}\quad f_{10}''(x)=0\\
	0&=f_{10}''(x)\\
	0&=\left(-\frac{8}{625}x^2+\frac{48}{125}x-\frac{48}{25}\right)\cdot e^{-0,2x}&&\mid\boxed{e^{-0,2x}>0}\\
	0&=-\frac{8}{625}x^2+\frac{48}{125}x-\frac{48}{25}&&\mid\cdot\left(-\frac{625}8\right)\\
	0&=x^2-30x+150\\
	x_{1;2}&=-\frac{-30}{2}\mp\sqrt{\left(\frac{-30}{2}\right)^2-150}\\
	&=15\mp\sqrt{\frac{900}{4}-150}=15\mp\sqrt{75}\\
	x_1&=15-\sqrt{75}\approx6,340\\
	x_2&=15+\sqrt{75}\approx23,660\\\hline\\
	
	f_{10}'(x_1)&=\left(\frac{8}{125}\left(15-\sqrt{75}\right)^2-\frac{32}{25}\left(15-\sqrt{75}\right)+\frac{16}{5}\right)\cdot e^{-0,2\left(15-\sqrt{75}\right)}\approx-0,659\\
	f_{10}'(x_2)&=\left(\frac{8}{125}\left(15+\sqrt{75}\right)^2-\frac{32}{25}\left(15+\sqrt{75}\right)+\frac{16}{5}\right)\cdot e^{-0,2\left(15+\sqrt{75}\right)}\approx0,077
\end{align}
$$
Da $\left|f_{10}'(x_1)\right|>\left|f_{10}'(x_2)\right|$, so betrachten wir die Stelle $x_1=15-\sqrt{75}$:
$$
\begin{align}
	g(x)&=m\cdot(x-x_0)+y_0\\
	&=f_{10}'(x_1)\cdot(x-(15-\sqrt{75}))+f_{10}(x_1)
\end{align}
$$

### d)
$$
\begin{align}
	T_a(x)&=\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\cdot e^{-0,2x}+\frac{100a-800}{a}\\
	T_a'(x)&=\left(\frac{32}{a}x+\frac{160-16a}{a}\right)\cdot e^{-0,2x}+\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\cdot e^{-0,2x}\cdot(-0,2)\\
	&=\left(\left(\frac{32}{a}x+\frac{160-16a}{a}\right)-0,2\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\right)\cdot e^{-0,2x}\\
	&=\left(\frac{32}{a}x+\frac{160-16a}{a}-\frac{16}{5a}x^{2}-\frac{160-16a}{5a}x-\frac{800-80a}{5a}\right)\cdot e^{-0,2x}\\
	&=\left(-\frac{16}{5a}x^{2}+\frac{16}{5}x\right)\cdot e^{-0,2x}=t_a(x)\\\hline\\
	T_a(0)&\stackrel{!}{=}20\\
	T_a(0)&=\left(\frac{16}{a}\cdot0^{2}+\frac{160-16a}{a}\cdot0+\frac{800-80a}{a}\right)\cdot e^{-0,2\cdot0}+\frac{100a-800}{a}\\
	&=\frac{800-80a}{a}+\frac{100a-800}{a}=
		\frac{800-800-80a+100a}{a}=
		\frac{20a}{a}=20
\end{align}
$$

### e)
$$
\begin{align}
	t_a(x)&=\left(-\frac{16}{5a}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}\\
	\lim_{a\to\infty}t_a(x)&=\lim_{a\to\infty}\left(\underbrace{-\frac{16}{5a}x^2}_{=0}+\frac{16}{5}x\right)\cdot e^{-0,2x}\\
	\lim_{a\to\infty}t_a(x)&=\frac{16}{5}x\cdot e^{-0,2x}
\end{align}
$$
Das quadratische Polynom wird durch $\frac{1}{a}$ mit $a\to\infty$ zu $0$, weshalb dieser wegfällt. Dies ist der einzige Term mit $a$, der Rest bleibt unverändert.

$$
\begin{align}
	T_a(x)&=\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\cdot e^{-0,2x}+\frac{100a-800}{a}\\
	\lim_{x\to\infty}T_a(x)&=
		\lim_{x\to\infty}\left[\underbrace{\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\cdot e^{-0,2x}}_{=0}+\frac{100a-800}{a}\right]\\
	\lim_{x\to\infty}T_a(x)&=\frac{100a-800}{a}\\\hline\\
	
	g_1\coloneqq\lim_{x\to\infty}T_{10}(x)&=\frac{1000-800}{10}=\frac{200}{10}=20\\
	g_2\coloneqq
	\lim_{a\to\infty}\lim_{x\to\infty}T_a(x)
		&=\lim_{a\to\infty}\frac{100a-800}{a}=\lim_{a\to\infty}\left[\frac{100a}{a}-\frac{800}{a}\right]\\
	&=\lim_{a\to\infty}\left[100-\underbrace{\frac{800}{a}}_{=0}\right]=100
\end{align}
$$
Alle Temperaturwerte liegen somit mit $\lim_{x\to\infty}$ auf dem Wertebereich $W=\{y\in\mathbb{R}\mid20<y<100\}$, wenn $a\in\left[10;\infty\right)$