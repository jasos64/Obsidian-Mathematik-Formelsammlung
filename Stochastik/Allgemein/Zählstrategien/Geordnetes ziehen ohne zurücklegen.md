Für Stochastische Vorgänge, in welchen aus einer [[Menge(en)]] etwas gezogen wird, ohne dass sich im Ende die Menge verändert, so spricht man von einem Ziehen ohne zurücklegen/ohne Wiederholung.

>$n$ Elemente auf $k$ Stellen gibt es $\frac{n!}{\left(n-k\right)!}$ Möglichkeiten, wie diese auftreten können. Auf einem GTR ist dies durch $\textbf{nPr}$ abrufbar ($n~\textbf{nPr}~k$)

Per Definition des Binomialkoeffizienten ([[Ungeordnetes ziehen ohne zurücklegen (Binomialkoeffizient)]]), lässt sich $\textbf{nPr}$ ebenfalls durch diesen ausdrücken.
$$
\begin{align}
	\textbf{nPr}&=\begin{pmatrix}n\\k\end{pmatrix}\cdot k!\\
	\frac{n!}{\left(n-k\right)!}&=\frac{n!}{\left(n-k\right)!\cdot \textcolor{red}{k!}}\cdot \textcolor{red}{k!}\\
	\frac{n!}{\left(n-k\right)!}&=\frac{n!}{\left(n-k\right)!}
\end{align}
$$

Verwendet wird hier die [[Fakultät]].

---
### Beispiel
$5$ Bälle werden hintereinander aus einer Urne mit $\textcolor{red}{3\textbf{ roten Bälle}}$, $\textcolor{orange}{6\textbf{ gelben Bälle}}$ und $\textcolor{teal}{2\textbf{ blauen Bälle}}$ blind gezogen.

$$
\begin{align}
	n&=\textcolor{red}3+\textcolor{orange}6+\textcolor{teal}2=11\\\\
	k&=5\\
	
	\left|\Omega\right|&=\frac{n!}{\left(n-k\right)!}=\frac{11!}{\left(11-5\right)!}=\frac{11!}{6!}
\end{align}
$$

---