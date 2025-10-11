# 2)
> Bei einem Mathetest gibt es zehn Fragen, mit jeweils vier Antworten, von denen nur eine richtig ist. Felix kreuzt bei jeder Frage rein zufällig eine Antwort an. Mit welcher Wahrscheinlichkeit hat er:

Wir notieren:
- $X:\text{"Anzahl richtig"}$
- $X\sim\mathcal{B}(10;0,25)$
- $n=10$
- $p=0,25$

## a)
> genau drei richtige Antworten,

$$
\begin{align}
	P(X=3)&=\begin{pmatrix}10\\3\end{pmatrix}\cdot (0,25)^3\cdot(1-0,25)^{10-3}\\
	&=\begin{pmatrix}10\\3\end{pmatrix}\cdot(0,25)^3\cdot(0,75)^{7}\\
	&\approx0,2503
\end{align}
$$

## b)
> genau drei richtige Antworten,

$$
\begin{align}
	P(X\ge3)&=1-P(X\le2)\\
	&=1-F_{10;0,25}(2)\\
	&\approx0,4744
\end{align}
$$


## c)
> höchstens 2 richtige Antworten,

$$
\begin{align}
	P(X\le2)&=F_{10;0,25}(2)\\
	&\approx0,5256
\end{align}
$$

## d)
> mehr als drei richtige Antworten?

$$
\begin{align}
	P(X>3)&=1-P(X\le3)\\
	&\approx0,224
\end{align}
$$

---
# 3)
> Aus der Prüfstatistik eines Kugelschreiberherstellers geht hervor, dass $3\%$ der produzierten Kugelschreiber defekt sind. Mit welcher Wahrscheinlichkeit
- $X:\text{"Anzahl kaputt"}$

## a)
> ist von $15$ Kugelschreibern keiner defekt,
- $X\sim\mathcal{B}(15;0,03)$
$$
\begin{align}
	P(X=0)&=\begin{pmatrix}15\\0\end{pmatrix}\cdot (0,03)^0\cdot(1-0,03)^{15-0}\\
	&=0,97^{15}\\
	&\approx0,6333
\end{align}
$$

## b)
> sind von $25$ Kugelschreibern mindestens zwei defekt,
- $X\sim\mathcal{B}(25;0,03)$
$$
\begin{align}
	P(X\le2)&=F_{50;0,03}(2)\\
	&\approx0,8108
\end{align}
$$


## c)
> sind von $50$ Kugelschreibern höchstens zwei defekt,
- $X\sim\mathcal{B}(50;0,03)$
$$
\begin{align}
	P(X\le2)&=F_{10;0,25}(2)\\
	&\approx0,5256
\end{align}
$$

## d)
> beträgt die Anzahl von defekten bei $100$ Kugelschreibern mindestens $2$ und höchstens $4$?
- $X\sim\mathcal{B}(100;0,03)$
$$
\begin{align}
	P(2\le X\le4)&=P(X\le4)-P(X\le1)\\
	&=F_{100;0,03}(4)-F_{100;0,03}(1)\\
	&\approx0,6232
\end{align}
$$
