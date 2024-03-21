Der Erwartungswert gibt den Durchschnitt der Zufallsgröße $X$ mit dessen zugehörigen Wahrscheinlichkeit an. Somit ist der Erwartungswert die der durch $x_i$ dargestellten Menge nach $P(X=x_i)$ gegeben.

Für den folgenden generalisierten Ausdruck ist der Erwartungswert $\mu$ definiert:
$$
\begin{align}
	&\begin{array}{c|l|c|c|c|c|c}
		x_i&x_1&x_2&x_3&\cdots&x_m\\\hline
		P(X=x_i)&P(X=x_1)&P(X=x_2)&P(X=x_3)&\cdots&P(X=x_m)
	\end{array}\\
	\\
	&\mu=E(X)=\boxed{\sum^{m}_{i=1}x_i\cdot P(X=x_i)}\\&~~~~~~~~~~~~~~~~~=
	x_1\cdot P(X=x_1)+
	x_2\cdot P(X=x_2)+\cdots
\end{align}
$$

---
### Beispiel
Zwei 2-seitige Würfel werden geworfen. Für $X:\text{"Augensumme"}$ gilt folgende [[Wahrscheinlichkeitsverteilung]]:
$$\begin{array}{c|c}
x_i&2&3&4\\\hline
P(X=x_i)&\frac{1}{4}&\frac{2}{4}&\frac{1}{4}
\end{array}$$
Der Erwartungswert ist folglich:
$$
\begin{align}
	\mu&=2\cdot\frac{1}{4}+3\cdot\frac{2}{4}+4\cdot\frac{1}{4}\\
	&=3
\end{align}
$$
Im Durchschnitt würfelt man hier also eine $3$.

---
### Faires Spiel
Ein Experiment heißt *fair*, wenn $\mu$ für dieses exakt $0$ ist und folglich keiner Gewinn macht, für die Menge an Spielversuchen $m\rightarrow\infty$.
Um ein Spiel *fair* zu machen, auch wenn es dies nicht zu Beginn ist, kann ein Gewinn eines [[Ereignis(se)]]s angepasst werden. Dies wird erzielt, indem $\mu$ mit der [[Variable(n)]] des Gewinns aufgestellt wird und gleich $0$ gesetzt wird.
Beispielsweise ist die [[Wahrscheinlichkeitsverteilung]] $\begin{array}{c|c}x_i&2&3&4\\\hline P(X=x_i)&\frac{1}{4}&\frac{2}{4}&\frac{1}{4}\end{array}$ als Experiment mit $\mu=3$ gegeben, wobei $X:\text{"Gewinn in €"}$ ist.
Der aktuelle Gewinn von $2\texteuro$ soll so verändert werden, dass das Spiel *fair* ist.
$$
\begin{array}{c|c}
x_i&w&3&4\\\hline
P(X=x_i)&\frac{1}{4}&\frac{2}{4}&\frac{1}{4}
\end{array}
$$
$$
\begin{align}
	\mu&=w\cdot\frac{1}{4}+3\cdot\frac{2}{4}+4\cdot\frac{1}{4}\\
	\mu(w)&=\frac{w}{4}+\frac{5}{2}\\\\
	
	0&=\mu(w)\\
	0&=\frac{w}{4}+\frac{5}{2}&&\mid-\frac{5}{2}\\
	-\frac{5}{2}&=\frac{w}{4}&&\mid\cdot4\\
	w&=-\frac{5}{2}\cdot4\\
	w&=-10
\end{align}
$$
Folglich muss der Verlust für $w$ bei $10\texteuro$ sein, da hier der Erwartungswert $0$ ist.

---
### $\mu$ für Binomialverteilungen
Der Erwartungswert einer Binomialverteilung befindet sich an der Stelle $\mu=n\cdot p$, wobei $n$ die Stichprobenanzahl, und $p$ die Wahrscheinlichkeit eines Treffers beschreiben.

---