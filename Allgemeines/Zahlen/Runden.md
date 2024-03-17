Wenn eine Zahl gegeben ist, dessen [[Dezimale(n)]] unerwünscht lang sind und diese für eine ungefähre Lösung unwichtig sind, so kann gerundet werden.
Zahlen werden auf der gewünschten Dezimale von 5 bis 9 auf quasi 10 gesetzt, wodurch die Dezimale davor erhöht wird.
$a=2,183$ auf die 1. Dezimale gerundet ist $a$ ungefähr $a\approx2,2$.

---
### Rundungsklammern
Die Gaußklammer kann verwendet werden, um eine Zahl auf seine nächst größte oder kleinste [Ganze Zahl](Zahlensets) zu setzen.
>- Für $\lceil~\rceil$ wird der Klammerinhalt auf die nächst **größte** Ganze Zahl gesetzt.
>- Für $\lfloor~\rfloor$ wird der Klammerinhalt auf die nächst **kleinste** Ganze Zahl gesetzt.

Um eine Zahl digital zu runden, kann man die Dezimalen der Zahl selbst durch $10^{n}$ verschieben, um anschließend die restlichen Dezimalen zu entfernen.
$$
\begin{align}
	a_u&=\textcolor{green}{2,34}561&&\mid\cdot10^2\\
	10^2a_u&=\textcolor{green}{234},561&&\mid\lfloor\rfloor\\
	\lfloor10^2a_u\rfloor&=\lfloor\textcolor{green}{234}\cancel{,561}\rfloor\\
	10^2a_u&=\textcolor{green}{234}&&\mid\cdot10^{-2}\\
	a_g&=\textcolor{green}{2,34}\\\\
	
	a_g&=\frac{\lfloor a_u\cdot10^n\rfloor}{10^n}
\end{align}
$$

---