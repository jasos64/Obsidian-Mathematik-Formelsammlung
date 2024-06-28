# 1

- $X:\textit{Geworfene Zahl}$
- $Y:\textit{Gewinn in }\texteuro$

$$
\begin{array}{c|c}
y_i&-1&0,5&2\\\hline
P(X=y_i)&\frac{3}{6}&\frac{2}{6}&\frac{1}{6}
\end{array}
$$
## a)
$$
\begin{align}
	\mu&=-1\cdot\frac{3}{6}+0,5\cdot\frac{2}{6}+2\cdot\frac{1}{6}\\
	&=-\frac{3}{6}+\frac{1}{6}+\frac{2}{6}\\
	&=0
\end{align}
$$
Weil der Erwartungswert hier $0$ ist, so heißt das Spiel fair.

## b)
Es wird ein Einsatz gesucht, damit nach dem $10.$ mal spielen ein Gewinn von $8\texteuro$ erwartet wird. Es schließt sich ein Gewinn pro Spiel von $0,8\texteuro$.
$$
\begin{array}{c|c}
x_i&-a&1,5-a&3-a\\\hline
P(X=x_i)&\frac{3}{6}&\frac{2}{6}&\frac{1}{6}
\end{array}
$$
$$
\begin{align}
	0,8&=\frac{3}{6}\cdot\left(-a\right)+
		\frac{2}{6}\cdot\left(\frac{3}{2}-a\right)+
		\frac{1}{6}\cdot\left(3-a\right)\\
	0,8&=-\frac{3}{6}a+
		\frac{6}{12}-\frac{2}{6}a-
		\frac{3}{6}-\frac{1}{6}a\\
	0,8&=\frac{-3-2-1}{6}\cdot a+\frac{6}{12}+\frac{3}{6}\\
	0,8&=-a+1&&\mid -1\\&&&\mid\cdot\left(-1\right)\\
	a&=0,2
\end{align}
$$
Der Einsatz müsste bei $0,2\texteuro$ liegen, damit der oben genannte Gewinn statistisch gesehen angenommen wird.

## c)
Aus Aufgabenstellung folgt eine Binomialverteilung mit:
$n=50$ und $p=\frac{1}{6}$.
$X$ sei hier die Anzahl der geworfenen $6$-en.
<iframe src="https://www.desmos.com/calculator/rhkfb9u2x5?embed" width="750" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

- $P(X=6)=\begin{pmatrix}50\\6\end{pmatrix}\cdot\left(\frac{1}{6}\right)^6\cdot\left(\frac{5}{6}\right)^{44}\approx0,112$
- $P(4\le X\le12)=P(X\le12)-P(X\le3)=F_{50;\frac{1}{6}}(12)-F_{50;\frac{1}{6}}(3)\approx0,914$
- $P(X>42)=1-P(X\le 42)\approx9,9699556399\cdot10^{−27}$

## d)
Die Normalverteilung beschreibt ein zum Erwartungswert symmetrischen Wahrscheinlichkeitswert. Die 1. Sigmaumgebung wird durch die Wendestellen beschrieben.
Die Binomialverteilung ist nicht immer symmetrisch. Außerdem ist anzumerken, dass sich die Binomialverteilung auf $n\in \mathbb{N}$ bezieht, nicht auf $\mathbb{R}$, wie die Normalverteilung es macht.

## e)
Zur Approximation der Binomialverteilung $B_{50;\frac{1}{6}}(k)$ wird hier überprüft, ob die Varianz einen gewissen Wert überschreitet. Hier heißt dieser einmal $9$.
$$
\begin{align}
	\sigma^2&=50\cdot\frac{1}{6}\cdot\frac{5}{6}\\
	&=50\cdot\frac{5}{36}\approx6,94<9
\end{align}
$$
Da hier der Wert nicht erreicht wird, kann die Normalverteilung für ungenauere Werte verwendet werden, aber eine gute Approximation liegt nicht vor.
<iframe src="https://www.desmos.com/calculator/ksm5w9dpdi?embed" width="750" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

---
# 2
## a)
Es wird $100$ mal geworfen, die Wahrscheinlichkeit, dass eine $6$ geworfen wird beträgt $\frac{1}{6}$. Daraus schließt sich für $\varphi_{\mu;\sigma}$:
$$
\begin{align}
	\sigma&=\sqrt{100\cdot\frac{1}{6}\cdot\frac{5}{6}}\\
	&=\sqrt{\frac{125}{9​}}\\
	\sigma&=\frac{\sqrt{125}}{3}\approx3,727\\\\
	
	\mu&=100\cdot\frac{1}{6}\\
	\mu&=\frac{50}{3}\approx16,667\\\\​
	
	\varphi_{\frac{50}{3};\frac{\sqrt{125}}{3}}(x)&=
		\frac{1}{\frac{\sqrt{125}}{3}\cdot\sqrt{2\pi}}e^{-\frac{1}{2}\left(\frac{x-\frac{50}{3}}{\frac{\sqrt{125}}{3}}\right)^2}\\
	B_{100;\frac{1}{6}}(x)&=
		\begin{pmatrix}
			100\\x
		\end{pmatrix}\cdot\left(\frac{1}{6}\right)^x\cdot\left(\frac{5}{6}\right)^{100-x}
\end{align}
$$
Es wird die Ähnlichkeit von $P(X=15)$ überprüft:
$$
\begin{align}
	\varphi_{\frac{50}{3};\frac{\sqrt{125}}{3}}(15)&=
		\frac{1}{\frac{\sqrt{125}}{3}\cdot\sqrt{2\pi}}e^{-\frac{1}{2}\left(\frac{15-\frac{50}{3}}{\frac{\sqrt{125}}{3}}\right)^2}\approx0,0969
	\\\\
	B_{100;\frac{1}{6}}(15)&=
		\begin{pmatrix}
			100\\15
		\end{pmatrix}\cdot\left(\frac{1}{6}\right)^{15}\cdot\left(\frac{5}{6}\right)^{100-15}\approx0,100
\end{align}
$$
Die Werte sind ähnlich.

## b)
$$
\begin{align}
	\varphi_{\frac{50}{3};\frac{\sqrt{125}}{3}}(x)&=0,02\\
	\frac{1}{\frac{\sqrt{125}}{3}\cdot\sqrt{2\pi}}e^{-\frac{1}{2}\left(\frac{x-\frac{50}{3}}{\frac{\sqrt{125}}{3}}\right)^2}=0,02\\
	e^{-\frac{1}{2}\left(\frac{x-\frac{50}{3}}
		{\frac{\sqrt{125}}{3}}\right)^2}&=
			\frac{2}{100}\cdot\frac{\sqrt{125}}{3}\cdot\sqrt{2\pi}\\
	e^{-\frac{1}{2}\left(\frac{x-\frac{50}{3}}
		{\frac{\sqrt{125}}{3}}\right)^2}&=
			\frac{\sqrt{125\cdot2\pi}}{150}\\
	e^{-\frac{1}{2}\left(\frac{x-\frac{50}{3}}
		{\frac{\sqrt{125}}{3}}\right)^2}&=
			\frac{\sqrt{250\pi}}{150}\\
	-\frac{1}{2}\left(\frac{x-\frac{50}{3}}
		{\frac{\sqrt{125}}{3}}\right)^2&=
			\ln\left(\frac{\sqrt{250\pi}}{150}\right)\\
	\left(\frac{x-\frac{50}{3}}
		{\frac{\sqrt{125}}{3}}\right)^2&=
			-2\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)\\
	\frac{(x-\frac{50}{3})^2}
		{\frac{125}{9}}&=
			-2\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)\\
	\frac{x^2-\frac{100}{3}x+\frac{2500}{9}}
		{\frac{125}{9}}&=
		-2\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)\\
	\frac{9}{125}x^2-\frac{900}{3\cdot125}x+\frac{2500}{125}&=
		-2\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)\\
	\frac{9}{125}x^2-\frac{12}{5}x+20&=
		-2\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)\\
	\frac{9}{125}x^2-\frac{12}{5}x+20
		+2\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)&=0\\
	x^2-\frac{12}{5}\cdot\frac{125}{9}x+20\cdot\frac{125}{9}
		+2\cdot\frac{125}{9}\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)&=0\\
	x^2-\frac{100}{3}x+\frac{2500}{9}+\frac{250}{9}\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)&=0\\\\
	
\end{align}
$$
Für Nullstellen gilt:
$$
\begin{align}
	x_{1;2}&=-\frac{p}{2}\pm\sqrt{\left(\frac{p}{2}\right)^2-q}\\
	&=-\frac{-\frac{100}{3}}{2}\pm\sqrt{\left(\frac{-\frac{100}{3}}{2}\right)^{2}-\left(\frac{2500}{9}+\frac{125}{9}\cdot2\ln\left(\frac{\sqrt{250\pi}}{150}\right)\right)}\\
	&=\frac{50}{3}\pm\sqrt{\frac{2500}{9}​-\frac{2500}{9}-\frac{250}{9}\cdot\ln\left(\frac{\sqrt{250\pi}}{150}\right)}\\
	&=\frac{50}{3}\pm\sqrt{-\frac{250}{9}\ln\left(\frac{\sqrt{250\pi}}{150}\right)}\\
	x_1&\approx9,840\\
	x_2&\approx23,4923\\
\end{align}
$$
Es würde aussagen, dass im Intervall $\left[x_1;x_2\right]$ die Wahrscheinlichkeit ist, eine sechs zu würfeln größer gleich $0,02$ ist.

## c)
Die Wendestellen einer Normalverteilung bilden sich aus der 1. Sigmaumgebung zusammen.
Folglich lauten die Stellen $\frac{50}{3}\pm\frac{\sqrt{125}}{3}$.
- $W_1\approx12,9399$
- $W_2\approx20,3934$

## d)
Die Wendestellen geben die erste Sigmaumgebung an, welche ungefähr $68\%$ des Flächeninhaltes der Gesamtverteilung beinhaltet. Es lässt sich zur Aufgabe vorher sagen, dass mindestens $60\%$ der Wurfmengen an sechsen sich im Intervall $\left[W_1;W_2\right]$ befinden.