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
Zwei 2-seitige Würfel werden geworfen. Für $X:\text{"Augensumme"}$ gilt folgende Wahrscheinlichkeitsverteilung:
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