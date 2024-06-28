Eine Vierfeldertafel stellt Wahrscheinlichkeiten zwischen zwei Ereignissen dar, welche sonst auch durch ein Baumdiagramm dargestellt werden könnten.
Für die [Ereignisse](Ereignis(se)) $A$ und $B$ gilt folgende Vierfeldertafel:
$$
\begin{array}{r|ccc}
	&A&\overline{A}&\sum\\ \hline
	B&\textcolor{orange}{P(A\cap B)} &\textcolor{orange}{P(\overline{A}\cap B) }& \textcolor{green}{P(B)}\\
	\overline{B} &\textcolor{orange}{P(A\cap \overline{B})} &\textcolor{orange}{P(\overline{A}\cap \overline{B})} &\textcolor{green}{P(\overline{B})} \\
	\sum&\textcolor{red}{P(A)} & \textcolor{red}{P(\overline{A})}& 1
\end{array}
$$
Alle hier jeweils farbig markierten Felder ergeben in der Summe $1$.
Zusätzlich ist zu sagen, dass eine Lücke durch Addition oder Subtraktion gefüllt werden kann. Beispielsweise ist folgende Tafel gegeben:
$$
\begin{array}{r|ccc}
	&T&\overline{T}&\sum\\ \hline
	L&x_1 &0,3 & x_2\\
	\overline{L} &0,1&x_3 &x_4 \\
	\sum&0,3 & 0,7& 1
\end{array}
$$
$x_1$ ergibt sich hier als $0,2$, da die Spalte zu dem Ereignis $T$ in der letzten Zeile angibt, dass diese $0,3$ als Summe annehmen soll. Somit ist $x_1+0,1=0,3~~\Rightarrow x_1=0,2$.

---