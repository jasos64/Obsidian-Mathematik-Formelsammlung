> Die [[Normalverteilung]] kann für Approximationen der [[Binomialverteilung]] verwendet werden.

---
## Standarisierung
> Hier im folgenden wird eine Binomialverteilung $X\sim\mathcal{B}_{n;p}\left(k\right)$ standartisiert.

Wir betrachten die genannte Binomialverteilung mit:
$\begin{align}\mathcal{B}_{n;p}\left(k\right)=\begin{pmatrix}n\\k\end{pmatrix}\cdot p^k\cdot(1-p)^{n-k}\end{align}$.
Folgend sind Dupel (2-Tupel) angegeben, die die Verteilung unter $k$ darstellt. Wir haben für alte Dupel $(x\mid y)$.
Der Erwartungswert, und dessen Extremwert der Verteilung wird im ersten Schritt auf die $y$-Achse verschoben.
> Durch die Verschiebung finden wir folgenden Aufbau (vorher zuerst):

$$
\begin{align}
	(k&\mid\mathcal{B}_{n;p})\\
	(k-\mu&\mid\mathcal{B}_{n;p})
\end{align}
$$
beim Betrachten fällt auf, dass für $n\to\infty$ die Standartabweichung steigt, und der Maximalwert sinkt. Beim näheren erkennen wir, dass die Zehrung nach $x$-Achse durch den Term $\frac{1}{\sigma}$ auf der $x$-Komponente entfernt werden kann. Damit der Flächeninhalt weiterhin $1$ ist, so muss diese Stauchung auf $x$ mit dem gleichen Faktor auf $y$ gestreckt werden.
> Es folgt hierdurch folgendes Dupel:

$$
\begin{align}
	(k-\mu&\mid\mathcal{B}_{n;p})\\
	\bigg(\frac{k-\mu}{\sigma}&\mid\sigma\cdot\mathcal{B}_{n;p}\bigg)\\
\end{align}
$$

Es fällt hierbei auf, dass diese Form für $n\to\infty$ die Grenzfunktion $\varphi(x)=\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}x^2}$ besitzt. Im folgenden sind die Differenzen der Dupel zu der Gauss-Funktion mit den Werten Werte $8$, $64$, $250$  und $1000$ für $n$ dargestellt:
![[GausskurveAnnäherung.png]]
Je größer $n$ wird, desto genauer wird die Approximation.

> Allgemein werden geeignete Werte dieser Approximation durch die *Laplace Bedingung* für alle $\sigma^2>9$ gebildet. Somit kann eine Binomialverteilung mit der Standartabweichung $\sigma>3$ durch eine Normalverteilung angenähert werden. $x$ in der Normalverteilung ist hier der beschriebene Term des Dupels $x=\frac{k-\mu}{\sigma}$.

---
## Kumulierte Wahrscheinlichkeiten
> bei kumulierten Wahrscheinlichkeiten kann die von der Normalverteilung bekannten Formel für Wahrscheinlichkeiten benutzt werden.

Es gilt weiterhin (siehe [[Flächeninhalt der Normalverteilung]])
$$
P(k_1\le X\le k_2)=\Phi\left(\frac{k_2-\mu}{\sigma}\right)-\Phi\left(\frac{k_1-\mu}{\sigma}\right)
$$
, man muss aber bedenken, dass die [[Binomialverteilung]] für diskrete Werte definiert ist ($\mathbb{N}$). Bedenken wir, dass die Balken einer Binomialverteilung die Breite von einer Einheit haben und die Mitte dieser bei jeder natürlichen Zahl liegt. Ein Balken an der Stelle $n$ streckt sich somit im Intervall $\left[n-0,5;n+0,5\right]$. Diese Korrektur muss für die Approximation bedacht werden, wodurch sich die Grenzen jeweils verschieben. Es resultiert:
$$
P(k_1\le X\le k_2)=\Phi\left(\frac{k_2+0,5-\mu}{\sigma}\right)-\Phi\left(\frac{k_1-0,5-\mu}{\sigma}\right)
$$
Die obere Grenze wird mit $0,5$ addiert, die untere mit $0,5$ subtrahiert. Für $n\to\infty$ kann diese Korrektur vernachlässigt werden, da die Approximation da der Gaußfunktion gleicht.

---
## Binomialdichte
> Bei der Approximation kann die standardisierte Normalverteilung *nicht* für konkrete Werte benutzt werden.

Da durch die Standardisierung nur eine Verteilungsfunktion ($\varphi(x)=\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}x^2}$) gegeben ist, sind Wahrscheinlichkeiten $P(X=k)$ nicht über diese Standardisierung berechnungsfähig.
> Die Normalverteilung kann allerdings verwendet werden, da diese diese Eigenschaft beibehält und abbildet.

Daraus folgt für eine Annäherung unter der Laplace Bedingung ($\sigma>3$) einer binomialverteilten Zufallsvariable $X$:
$$
P(X=k)\approx \frac{1}{\sigma\cdot\sqrt{2\pi}}\cdot e^{-\frac{1}{2}\cdot\left(\frac{x-\mu}{\sigma}\right)^2}
$$
Es kann ebenfalls durch die folgende Schreibweise ausgedrückt werden:
$$
\begin{align}
	P(X=k)\approx\frac{1}{\sigma}\cdot\varphi\left(\frac{x-\mu}{\sigma}\right)
\end{align}
$$