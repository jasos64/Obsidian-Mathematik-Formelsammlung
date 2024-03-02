Für Stochastische Vorgänge, in welchen aus einer [[Menge(en)]] etwas gezogen wird, ohne dass sich im Ende die Menge verändert, so spricht man von einem Ziehen mit zurücklegen/mit Wiederholung.

$n$ Elemente auf $k$ Stellen gibt es $n^k$ Möglichkeiten, wie diese in einer Reihenfolge auftreten können.

---
### Beispiel
Folgendes Beispiel einmal mit 3 mal ziehen:
$$\boxed{\textcolor{red}{\textit{ rote Bälle}},~\textcolor{teal}{\textit{ blauer Bälle}},~\textcolor{orange}{\textit{ gelbe Bälle}}}$$
$$
\begin{align}
	n&=\textcolor{red}1+\textcolor{teal}1+\textcolor{orange}1\\
	&=3\\\\
	k&=3\\
	\left|\Omega\right|&=3^3=27\\
\end{align}
$$
$$
\begin{array}{}
	\textcolor{red}{rr}\textcolor{red}r
	&\textcolor{teal}{bbb}
	&\textcolor{orange}{ggg}\\
	
	\textcolor{teal}b\textcolor{red}{rr}
	&\textcolor{orange}g\textcolor{teal}{bb}
	&\textcolor{red}r\textcolor{orange}{gg}\\
	
	\textcolor{red}r\textcolor{teal}b\textcolor{red}r
	&\textcolor{teal}b\textcolor{orange}g\textcolor{teal}b
	&\textcolor{orange}g\textcolor{red}r\textcolor{orange}g\\
	
	\textcolor{red}{rr}\textcolor{teal}b
	&\textcolor{teal}{bb}\textcolor{orange}g
	&\textcolor{orange}{gg}\textcolor{red}r\\
	
	\textcolor{teal}{bb}\textcolor{red}r&\textcolor{orange}{gg}\textcolor{teal}b&\textcolor{red}{rr}\textcolor{orange}g\\
	
	\textcolor{teal}b\textcolor{red}r\textcolor{teal}b&\textcolor{orange}g\textcolor{teal}b\textcolor{orange}g&\textcolor{red}r\textcolor{orange}g\textcolor{red}r\\
	
	\textcolor{red}r\textcolor{teal}{bb}&\textcolor{orange}g\textcolor{teal}{bb}&\textcolor{orange}g\textcolor{red}{rr}\\
	
	\textcolor{red}r\textcolor{teal}b\textcolor{orange}g&\textcolor{teal}b\textcolor{orange}g\textcolor{red}r&\textcolor{orange}g\textcolor{red}r\textcolor{teal}b\\
	
	\textcolor{red}r\textcolor{orange}g\textcolor{teal}b&\textcolor{teal}b\textcolor{red}r\textcolor{orange}g&\textcolor{orange}g\textcolor{teal}b\textcolor{red}r
\end{array}
$$

---
