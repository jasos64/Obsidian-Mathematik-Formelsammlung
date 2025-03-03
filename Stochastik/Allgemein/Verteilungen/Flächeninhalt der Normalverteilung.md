Da [Wahrscheinlichkeiten](Wahrscheinlichkeit) einer Normalverteilung über vorhandene Flächeninhalte bestimmt werden, so liegt generell folgendes für eine normalverteilte [[Zufallsvariable]] $X$ vor:
$$
P(k_1\le X\le k_2)=\int^{k_2}_{k_1}\frac{1}{\sigma\cdot\sqrt{2\pi}}\cdot e^{-\frac{1}{2}\cdot\left(\frac{x-\mu}{\sigma}\right)^2}~dx
$$
Wir erkennen das Integral mit den gegebenen Grenzen $k_1$ und $k_2$. Der Integrand ist die generelle Normalverteilung, die nach der Integrationsvariable $x$ integriert wird.
> Da es unendlich viele Normalverteilungen gibt, wird hier die standardisierte Normalverteilung verwendet, damit es eine Integrationsfunktion gibt.

Wir erhalten demnach die folgende Form:
$$
P(k_1\le X\le k_2)=\int^{\frac{k_2-\mu}{\sigma}}_{\frac{k_1-\mu}{\sigma}}\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}z^2}~dz
$$
> Wichtig zu erläutern sind hier die geänderten Integrationsgrenzen, die aus der Standardisierung $Z=\frac{X-\mu}{\sigma}$ folgt.

Die Stammfunktion von $\varphi$ wird folgendermaßen definiert:
$$
\Phi(k)=\int^{k}_{-\infty}\varphi(x)~dx
$$
Im folgenden wird das oben stehende Integral umgeschrieben:
$$
\begin{align}
	P(k_1\le X\le k_2)&=\int^{\frac{k_2-\mu}{\sigma}}_{\frac{k_1-\mu}{\sigma}}\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}z^2}~dz\\
	P(X\le k_2)-P(X\le k_1)&=\int^{\frac{k_2-\mu}{\sigma}}_{-\infty}\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}z^2}~dz-\int^{\frac{k_1-\mu}{\sigma}}_{-\infty}\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}z^2}~dz
\end{align}
$$
Alle $4$ Ausdrücke sind im Wert und der Tatsache identisch. Wir erkennen, dass die beiden Integrale nach der oben stehenden Form umgeschrieben werden kann:
$$
\begin{align}
	P(k_1\le X\le k_2)&=\int^{\frac{k_2-\mu}{\sigma}}_{-\infty}\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}z^2}~dz-\int^{\frac{k_1-\mu}{\sigma}}_{-\infty}\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}z^2}~dz\\
	P(k_1\le X\le k_2)&=\Phi\left(\frac{k_2-\mu}{\sigma}\right)-\Phi\left(\frac{k_1-\mu}{\sigma}\right)
\end{align}
$$
> Dieser Zusammenhang gilt für alle normalverteilten Zufallsvariablen. Die Verteilung wird zum Beginn standardisiert und in die Stammfunktion $\Phi$ eingesetzt. $\Phi(x)$ lässt sich in Tabellen ablesen.

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-4,4,0,0.4]
disableZoom: true
grid: true
---
f(x)=1/(2*PI)^0.5*exp(-0.5x^2)
```

---