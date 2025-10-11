Ein Experiment heißt binomialverteilt, wenn dieses als ein Bernoulli-Experiment einzustufen ist. ([[Ungeordnetes ziehen mit zurücklegen (Bernoulli)]]).
Grundsätzlich gilt:
$$P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}\cdot p^{k}\cdot (1-p)^{n-k}$$
Für $P(X\le k)$ wird jedes zutreffende $k$ einzeln eingesetzt und anschließend addiert. Folglich ist:
$$
\begin{align}
	P(X\le k)=P(X=0)+P(X=1)+(X=2)+\cdots+P(X=k)
\end{align}
$$

>Die Binomialverteilung ist für uns nicht stetig, da $n!$ nur für $\mathbb{N}$ definiert ist.

---
### Taschenrechner
Der Taschenrechner verfügt über die Binomialverteilung mittels den Werten von $n$, $p$, und $k$. Die Verwendung des Taschenrechners wird mittels $P(X=k)=B_{n;p}(k)$ formal dargestellt.. Der Taschenrechner fragt hier nach den oben genannten Werten und gibt einem dann den Wert der Wahrscheinlichkeit $P$.
Für Ungleichungen als Menge gibt es die Möglichkeit einer kumulierten Binomialverteilung, bei welcher nur das Format von $P(X\le k)$ akzeptabel ist. Beschrieben wird so wie bei der einfachen Binomialverteilung folgendes:
$$P(X\le k)=F_{n;p}(k)$$
Diese Ungleichungen können in komplexen Formen nicht mit $\le k$ gegeben sein, weshalb andere umgeformt werden müssen. Gegenwahrscheinlichkeiten werden benutzt, um $\ge$ zu $\le$ verändern. Sei $P(X\ge 10)$, so gilt ebenfalls $1-P(X\le 9)$. Hierzu gilt $P(X\ge a)=1-P(X\le a-1)$. **Dies funktioniert aber nur, da hier $k\in\mathbb{N}_0$**. Diese Werte können durch einen Zahlenstrahl ebenfalls visualisiert werden, wodurch Grenzen aufgestellt werden können.

Beispielsweise ist $P(4\le X\le 18)$ gegeben, welches durch das Einsetzen der oberen Grenze minus das Einsetzen der unteren (minus 1) erzielt werden kann.
$P(4\le X\le 18)=P(X\le 18)-P(X<4)=P(X\le 18)-P(X\le3)$

---