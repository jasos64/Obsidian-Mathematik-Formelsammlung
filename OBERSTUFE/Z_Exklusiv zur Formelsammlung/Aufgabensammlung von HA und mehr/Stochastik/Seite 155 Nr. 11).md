> Die Firma EISafe stellt Sicherungen mit einer Ausschussquote von $5\%$ her.

## a)
> Der Produktion werden $50$ Sicherungen zur Prüfzwecken entnommen. Bestimmen Sie die Wahrscheinlichkeit für die Ereignisse:

- $X:\text{"Anzahl defekt"}$
- $X\sim\mathcal{B}(50;0,05)$

A: "genau drei Sicherungen sind defekt"
$$
\begin{align}
	P(X=3)&=\begin{pmatrix}50\\3\end{pmatrix}\cdot (0,05)^3\cdot(1-0,05)^{50-3}\\
	&=\begin{pmatrix}50\\3\end{pmatrix}\cdot (0,05)^3\cdot(0,95)^{47}\\
	&\approx0,2199
\end{align}
$$

B: "höchstens drei Sicherungen sind defekt"
$$
\begin{align}
	P(X\le3)&=F_{50;0,05}(3)\\
	&\approx0,7604
\end{align}
$$

C: "alle Sicherungen sind in Ordnung"
$$
\begin{align}
	P(X=0)&=\begin{pmatrix}50\\0\end{pmatrix}\cdot (0,05)^0\cdot(1-0,05)^{50-0}\\
	&=0,95^{50}\\
	&\approx0,0769
\end{align}
$$

D: "nur die letzten drei entnommenen Sicherungen sind defekt"
$$
\begin{align}
	P(D)&=(0,05)^{3}\cdot(1-0,05)^{50-3}\\
	&=(0,05)^{3}\cdot(0,95)^{47}\\
	&\approx0,000011
\end{align}
$$

---
## b)
> Ein Elektrogroßhändler erhält von EISafe zwölf Sendungen. Jeder Sendung entnimmt er zwei Sicherungen und überprüft sie. Er nimmt eine Sendung nur an, wenn er bei der Kontrolle nur einwandfreie Sicherungen findet.
> Wie groß ist die Wahrscheinlichkeit, dass die erste Sendung angenommen wird?
> Mit welcher Wahrscheinlichkeit werden mindestens zehn Sendungen angenommen?

Eine Sendung wird angenommen, wenn keine der zwei Sicherung defekt ist.
Die Wahrscheinlichkeit hierfür liegt bei:
$$
\begin{align}
	P(X=0)&=\begin{pmatrix}2\\0\end{pmatrix}\cdot (0,05)^0\cdot(1-0,05)^{2}\\
	&=0,95^{2}\\
	&\approx0,9025
\end{align}
$$

Es folgt die Verteilung $Y$:
- $Y:\text{"Anzahl angenommene Sendungen"}$
- $Y\sim\mathcal{B}(12;0,9025)$

> Die Wahrscheinlichkeit, dass die erste Sendung angenommen wird liegt bei $90,25\%$.

---
$$
\begin{align}
	P(X\ge10)&=1-P(X\le9)\\
	&=1-F_{12;0,9025}(9)\\
	&\approx0,8954
\end{align}
$$

---
---
# Seite 156
Die Binomialverteilung links besitzt die Parameter von $B$:
- $n=20$
- $p=0,5$
(Weil es Werte bis $20$ gibt, und $10$ ein Maximum besitzt. $\frac{10}{20}=\frac{1}{2}$)

Die Binomialverteilung rechts besitzt die Parameter von $E$:
- $n=15$
- $p=0,5$
(Weil es Werte bis $15$ gibt, und $10$ ein Maximum besitzt. $\frac{10}{15}=\frac{2}{3}$)

---