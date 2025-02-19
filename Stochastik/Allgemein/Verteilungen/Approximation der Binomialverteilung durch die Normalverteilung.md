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

[...]