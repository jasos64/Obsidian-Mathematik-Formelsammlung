a)
Gegeben ist $0,985^{12}$. Es ist laut Aufgabenstellung eine Binomialverteilung mit Verteilung $X: \textit{Anzahl fehlerhafter Flaschen}$ gegeben. Zusätzlich gilt $n=12$ und $p=0,015\Rightarrow q=0,985$ ist.
Da mit eingesetzten Variablen steht: $q^n$ lässt sich beschreiben, dass dieses Ergebnis für $P(X=0)$ steht. Eine mögliche Aufgabenstellung kann hier lauten:
"Ein Kleinladen bestellt sich wöchentlich eine solche $12$-er Kiste. Geben Sie die Wahrscheinlichkeit an, dass alle dieser $12$ Flaschen mindestens $750ml$ besitzen.".
Dies stellt daher eine Aufgabe dar, da $P(X=0)$ hier gesucht ist, und $P(X=0)=\begin{pmatrix}n\\0\end{pmatrix}\cdot p^0\cdot q^{n-0}=q^n$.

---
b)
- $X:\text{Anzahl fehlerhafte Flaschen}$
- $n=50$
- $p=0,015$
$P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}\cdot p^k\cdot\left(1-p\right)^{n-k}$
$$
\begin{align}
	\boxed{Bernouli}\quad P(A)=P(X=3)&=\begin{pmatrix}50\\3\end{pmatrix}\cdot 0,015^3\cdot\left(1-0,015\right)^{50-3}\\
		&=19600\cdot\frac{27}{8000000}\cdot\left(0,985\right)^{47}\\
		&\approx0,000321=0,0321\%\\
		\text{Die Wahrscheinlichkeit, dass exakt 3 Flaschen unter }&\text{750ml gefüllt sind, beträgt ungefähr 0,0321\%}\\\\
	\boxed{Bernouli}\quad P(B)=P(X\ge 1)=1-P(X=0)&=1-\begin{pmatrix}50\\0\end{pmatrix}\cdot 0,015^0\cdot\left(1-0,015\right)^{50-0}\\
		&=1-0,985^{50}\approx0,5303\\
		\text{Die Wahrscheinlichkeit, dass exakt mindestens eine Flaschen unter }&\text{750ml gefüllt ist, beträgt ungefähr 53,03\%}\\\\\\
	\boxed{Nicht~~Bernouli}\quad P(C)&=0,985^{49}\cdot0,015\approx0,00715\\
	\text{Die Wahrscheinlichkeit, dass nur die letzte gezogene Flasche unter }&\text{750ml gefüllt ist, beträgt ungefähr 0,715\%}​
\end{align}
$$

---
c)
- $X:\text{Anzahl fehlerhafte Flaschen}$
- $Y:\text{Anzahl fehlerhafter Kisten}$
- $E:\text{Eine Kiste ist beschädigt}$
- $P(E)=P(X>0)=1-P(X=0)=1-B_{12;0,015}(0)\approx0,1659$

$$
\begin{align}
	P(Y=k)&=\begin{pmatrix}n\\k\end{pmatrix}\cdot
		P(E)^k\cdot\left(1-P(E)\right)^{n-k}\\
	P(Y>150\cdot3\%)&=P(Y>4,5)\\
	\Rightarrow P(Y\ge5)&=1-P(Y\le4)=1-F_{150;~P(E)}(4)\\
	&\approx1,000
\end{align}
$$

>Die Wahrscheinlichkeit eine fehlerhafte Kiste zu ziehen berechnet sich daraus, wie hoch die Wahrscheinlichkeit ist, generell mindestens 1 der 12 Flaschen fehlerhaft zu haben. Daher hier zunächst $P(X\ge1)$. Diese Wahrscheinlichkeit wird für die weitere Verteilung verwendet, welche die Kisten generell beschreibt. $150\cdot3\%$ ist hier der gesuchte mindestwert.

---
>Die Füllmenge der Flaschen soll als normalverteilt mit einem Erwartungswert von $750,5ml$ und einer Standartabweichung von $0,23ml$ angenommen werden.

d)
>**Vergleichen** Sie die Normalverteilung mit der Binomialverteilung am Beispiel der Sektflaschen. Gehen Sie dabei auch auf die Begriffe diskret und stetig ein.

>**Überprüfen** Sie, ob sich die Binomialverteilung mit $n=100$ und $p=0,015$ als Normalverteilung approximieren lässt.

~~Eine Normalverteilung gibt als Flächeninhalt an, zu welchem Anteil ein Intervall an Werten einer Zufallsvariable angenommen wird. Laut Beispiel gilt hier die Zufallsvariable $X$ als Füllmenge. Gefragt wäre beispielsweise, dass die durchschnittliche Füllmenge in einer $n$-$\sigma$-Umgebung gesucht ist.
Binomialverteilung gibt die Anzahl/Mächtigkeit eines Eintretenden Ergebnisses an.~~
Zusätzlich anzumerken ist, dass eine Normalverteilung $f(x)$ für $x\in\mathbb{R}$ stetig ist, eine Binomialverteilung $g(x)$ allerdings für $k\in\mathbb{N}$, wodurch jedes $k\in\mathbb{R}\backslash\mathbb{N}$ nicht gegeben ist.

Von oben gilt:
- $n=100$
- $p=0,015$

Sei $\sigma_B$ die Standartabweichung der Binomialverteilung
Zu zeigen: $\sigma_B^2\lessgtr 9$
$$
\begin{align}
	\sigma_B^2&=\sqrt{n\cdot p\cdot(1-p)}^2\\
	&=n\cdot p\cdot(1-p)\\
	&=100\cdot 0,015\cdot(1-0,015)\\
	&=100\cdot 0,015\cdot0,985\\
	&=\frac{591}{400}\approx 1,478 <9
\end{align}
$$
Durch $\sigma_B^2<9$, lässt sich die Binomialverteilung nicht zuverlässig als Approximation einer Normalverteilung verwenden.

---
e)
Normalverteilung $\mathcal{N}(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{1}{2}\cdot\left(\frac{x-\mu}{\sigma}\right)^2}$, mit $\sigma=0,23$ und $\mu=750,5$.
$$
	\mathcal{N}(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{1}{2}\cdot\left(\frac{x-\mu}{\sigma}\right)^2}
$$
$$
\begin{align}
	P\left(X\ge751\right)&\approx 1,486\%\\
	P(750\le X\le751)&\approx 97,029\%
\end{align}
$$

---
---
# 2 Analysis
a)
$$
\begin{align}
	V&=\pi\cdot\int^{8}_{0}\left(\frac{4}{5}\sqrt{x}\right)^2~dx\\
	&=\pi\cdot\int^{8}_{0}\frac{16}{25}x~dx\\
	&=\pi\cdot\left[\frac{8}{25}x^2\right]_0^8\\
	&=\pi\cdot\left(\frac{8}{25}\cdot 8^2-\frac{8}{25}\cdot 0^2\right)\\
	&=\pi\cdot\frac{8}{25}\cdot 64\approx64,340ml
\end{align}
$$
b)
$$
\begin{align}
	100&=\pi\cdot\int^{z}_{0}\left(\frac{4}{5}\sqrt{x}\right)^2~dx\\
	100&=\pi\cdot\int^{z}_{0}\frac{16}{25}x~dx\\
	100&=\pi\cdot\left[\frac{8}{25}x^2\right]_0^z\\
	100&=\pi\cdot\left(\frac{8}{25}z^2-\frac{8}{25}\cdot0^2\right)\\
	100&=\pi\cdot\frac{8}{25}z^2\\
	\frac{625}{2}&=z^2\\
	\frac{625}{2\pi}&=z^2\\
	z&=\sqrt{\frac{625}{2\pi}}\approx9,974cm​
\end{align}
$$
