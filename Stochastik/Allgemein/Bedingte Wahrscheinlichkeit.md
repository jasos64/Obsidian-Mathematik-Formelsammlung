> Die Bedingte [[Wahrscheinlichkeit]] gibt die Wahrscheinlichkeit an, dass ein bestimmtes [Ereignis](Ereignis(se)) eintritt, sobald ein anderes zuvor eingetreten ist.
> Oft im Zusammenhang einer [[Vierfeldertafel]].

Bedingte Wahrscheinlichkeiten werden folgendermaßen definiert:
$$
P_B(A)=\frac{P(A\cap B)}{P(B)}
$$

---
Geben wir die folgende Vierfeldertafel an:
$$
\begin{array}{r|ccc}
	&A&\overline{A}&\sum\\ \hline
	B&P(A\cap B) &P(\overline{A}\cap B) & P(B)\\
	\overline{B} &P(A\cap \overline{B}) &P(\overline{A}\cap \overline{B}) &P(\overline{B}) \\
	\sum&P(A) & P(\overline{A})& 1
\end{array}
$$

Bestimmen wir die Wahrscheinlichkeit, dass $A$ eintritt, nachdem $B$ zuvor eingetreten ist, so erhalten wir $P_B(A)$:
$$
\begin{array}{r|ccc}
	&A&\overline{A}&\sum\\ \hline
	B&\textcolor{green}{P(A\cap B)} &P(\overline{A}\cap B) & \textcolor{red}{P(B)}\\
	\overline{B} &P(A\cap \overline{B}) &P(\overline{A}\cap \overline{B}) &P(\overline{B}) \\
	\sum&P(A) & P(\overline{A})& 1
\end{array}
$$
$$
P_B(A)=\frac{\textcolor{green}{P(A\cap B)}}{\textcolor{red}{P(B)}}
$$

---