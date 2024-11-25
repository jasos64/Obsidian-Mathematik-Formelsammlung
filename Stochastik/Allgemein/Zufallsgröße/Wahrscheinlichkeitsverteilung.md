Eine Wahrscheinlichkeitsverteilung beschreibt die Wahrscheinlichkeit jedes [[Ereignis(se)]]s mit dessen Wirkung.
Als Beispiel zur Veranschaulichung:
Zwei 2-seitige Würfel werden geworfen. Für die [[Zufallsvariable]] ist hier der Wurfbetrag vorhergesehen.
$$\Omega=\{(1;1),(1;2),(2;1),(2;2)\}$$
Diese Ergebnismenge wird nun passend der Zufallsgröße umgeformt:
$$
\begin{array}{c|c}
	\text{Ergebnisse}&\text{Augensumme } (x_i)&\left|E\right|\\\hline
	\{(1;1)\}&2&1\\
	\{(1;2),(2;1)\}&3&2\\
	\{(2;2)\}&4&1\\
\end{array}
$$
Hiermit kann nun die Wahrscheinlichkeitsverteilung beschrieben werden, mit welcher die [[Varianz]] und der [[Erwartungswert]] berechnet werden kann:
$$
\begin{array}{c|c}
x_i&2&3&4\\\hline
P(X=x_i)&\frac{1}{4}&\frac{2}{4}&\frac{1}{4}
\end{array}
$$

---
### Generalisiertes Beispiel mit Einsatz
Ein Glücksrad wird mit einem Einsatz von $v$ gedreht, für welches Ereignisse $E_1;E_2;E_3;\cdots; E_i$ mit jeweiligen [[Wahrscheinlichkeit]]en von $p_1;p_2;p_3;\cdots;p_i$ vorhanden sind. Die jeweiligen Gewinne sind jeweils $g_1;g_2;g_3;\cdots;g_i$.
Sei $X$ die Menge an Gewinn, die eine Person nach Durchführung dieses Experimentes erhält, so gilt für die Wahrscheinlichkeitsverteilung die folgende:
$$
\begin{array}{c|c}
x_i&g_1-v&g_2-v&g_3-v&\cdots&g_i-v\\\hline
P(X=x_i)&P(E_1)\Leftrightarrow p_1&P(E_2)\Leftrightarrow p_2&P(E_3)\Leftrightarrow p_3&\cdots&p_i
\end{array}
$$
Von jedem Gewinnbetrag muss der Einsatz abgezogen werden, damit dieser für die Verteilung mitgezählt wird.

---