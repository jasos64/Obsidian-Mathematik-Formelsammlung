Die Varianz beschreibt, inwiefern die [[Wahrscheinlichkeitsverteilung]] mit dessen [[Erwartungswert]] zusammenhängt. Insofern der Erwartungswert durch eine weitläufige Wahrscheinlichkeitsverteilung mittig zu diesen liegt, wo sich allerdings kein Element der Wertemenge $x_i$ befindet, so ist diese Verteilung mit ihrer Varianz größer als eine, bei der der Erwartungswert $\mu$ von Mengenelementen von $x_i$ umgeben ist.
Berechnet wird dies mit der Varianz $V(X)$.

Für eine Verteilung von 
$$
\begin{array}{c|l|c|c|c|c|c}
	x_i&x_1&x_2&x_3&\cdots&x_m\\\hline
	P(X=x_i)&P(X=x_1)&P(X=x_2)&P(X=x_3)&\cdots&P(X=x_m)
\end{array}$$
gilt für die Varianz das folgende:
$$
\begin{align}
	V(X)&=\boxed{\sum^{m}_{i=1}\left(x_i-\mu\right)^2\cdot P(X=x_i)}\\
	&=\left(x_1-\mu\right)^2\cdot P(X=x_1)+\left(x_2-\mu\right)^2\cdot P(X=x_2)+\cdots\\
	&~~~~~\cdots\left(x_m-\mu\right)^2\cdot P(X=x_m)
\end{align}
$$
Desto größer $V(X)$ ist, desto größer ist das Streuverhalten der Verteilung, folglich sind Zufallsexperimente mit einer niedrigen Varianz risikounfreundlicher.

---