Für Stochastische Vorgänge, in welchen aus einer [[Menge(en)]] etwas gezogen wird, ohne dass sich im Ende die Menge verändert, so spricht man von einem Ziehen ohne zurücklegen/ohne Wiederholung. Ist die Reihenfolge hierbei unwichtig, so spricht man von einem ungeordnetem Ziehen.
Dies wird mit dem folgendem **Binomialkoeffizienten** beschrieben:

>$n$ Elemente auf $k$ Stellen ohne Reihenfolge gibt es $\begin{pmatrix}n\\k\end{pmatrix}=\frac{n!}{\left(n-k\right)!\cdot k!}$ Möglichkeiten, wie diese auftreten können. Auf einem GTR ist dies durch $\textbf{nCr}$ abrufbar ($n~\textbf{nCr}~k$).

Hergeleitet wird dies mit Hilfe von [[Geordnetes ziehen ohne zurücklegen]], bei welchem die Reihenfolge ebenfalls wichtig ist. Damit die Mengen an Permutationen auf $k$ Stellen entfernt wird, so muss das Ergebnis durch den $nPr$ mit der Menge der möglichen Permutationen $k!$ geteilt werden.

Verwendet wird hier die [[Fakultät]].

---
### Definitionen
Für den Binomialkoeffizienten existieren Werte, die für alle $n$ und $k$ so folgend gelten:
$$
\begin{array}{} \begin{pmatrix}n\\0\end{pmatrix}=1&\begin{pmatrix}n\\1\end{pmatrix}=n
\\
\begin{pmatrix}n\\n\end{pmatrix}=1&\begin{pmatrix}n\\n-1\end{pmatrix}=n
\end{array}
$$
Das untere rechte lässt sich mittels der folgenden Beschreibung definieren:
$$
\begin{align}
	\begin{pmatrix}n\\k\end{pmatrix}
	&\stackrel{?}{=}
	\begin{pmatrix}n\\n-k\end{pmatrix}\\
	
	\frac{n!}{\left(n-k\right)!\cdot k!}&=\frac{n!}{\left(n-(n-k)\right)!\cdot (n-k)!}\\
	
	\frac{n!}{\left(n-k\right)!\cdot k!}&=\frac{n!}{\left(\textcolor{red}{n-n}+k\right)!\cdot (n-k)!}\\
	
	\frac{n!}{\left(n-k\right)!\cdot k!}&=\frac{n!}{k!\cdot (n-k)!}
\end{align}
$$

---
### Wahrscheinlichkeiten
Wenn aus einer Menge Elemente verschiedener Mengen befinden, aus welchen eine Menge allgemein erhalten werden soll, so kann man das folgende dazu verwenden um dieses zu beschreiben:

$5$ Bälle werden hintereinander aus einer Urne mit $\textcolor{red}{3\textbf{ roten Bälle}}$, $\textcolor{orange}{6\textbf{ gelben Bälle}}$ und $\textcolor{teal}{2\textbf{ blauen Bälle}}$ blind gezogen.

$$
\begin{align}
	n&=\textcolor{red}3+\textcolor{orange}6+\textcolor{teal}2=11\\
	k&=5\\
	
	\left|\Omega\right|&=\begin{pmatrix}11\\5\end{pmatrix}
\end{align}
$$
Um die Menge an Möglichkeiten anzugeben, dass bei diesen 5 gezogenen Bällen von $n_r$ roten $k_r$, von $n_g$ $k_g$ gelbe und von $n_b$ $k_b$ blaue Bälle gezogen wurden, kann man das folgende anwenden:
$$
	\textcolor{red}{\begin{pmatrix}n_r\\k_r\end{pmatrix}}\cdot
	\textcolor{orange}{\begin{pmatrix}n_g\\k_g\end{pmatrix}}\cdot
	\textcolor{teal}{\begin{pmatrix}n_b\\k_b\end{pmatrix}}=\left|E\right|
$$
Hierbei zu beachten ist, dass $\textcolor{red}{n_r}+\textcolor{orange}{n_g}+\textcolor{teal}{n_b}=n$, $\textcolor{red}{k_r}+\textcolor{orange}{k_g}+\textcolor{teal}{k_b}=k$ und jeweils $0\le k\le n$ gelten muss.
Für einen Fall, dass 2 rote, 2 gelbe und ein blauer Ball gezogen wird, gibt es folglich $\begin{pmatrix}3\\2\end{pmatrix}\cdot\begin{pmatrix}6\\2\end{pmatrix}\cdot\begin{pmatrix}2\\1\end{pmatrix}=90$ Möglichkeiten. Die Wahrscheinlich hierfür wäre folglich:
$$
\frac{\begin{pmatrix}3\\2\end{pmatrix}\cdot\begin{pmatrix}6\\2\end{pmatrix}\cdot\begin{pmatrix}2\\1\end{pmatrix}}{\begin{pmatrix}11\\5\end{pmatrix}}\approx0,19
$$

---
### Sierpinski-Dreieck
Das [[Sierpinski-Dreieck]] kann verwendet werden um die Werte des Binomialkoeffizienten händisch zu bestimmen.
Hierbei ist die Zeile dann der Wert für $n$, und von links nach rechts $k$.
$$
\begin{array}{}
	&&&&&&1^{0}_{0}&&\\
	&&&&&1^{1}_{0}&&1^{1}_{1}&\\
	&&&&1^{2}_{0}&&2^{2}_{1}&&1^{2}_{2}\\
	&&&1^{3}_{0}&&3^{3}_{1}&&3^{3}_{2}&&1^{3}_{3}\\
	&&1^{4}_{0}&&4^{4}_{1}&&6^{4}_{2}&&4^{4}_{3}&&1^{4}_{4}\\
	&1^{5}_{0}&&5^{5}_{1}&&10^{5}_{2}&&10^{5}_{3}&&5^{5}_{4}&&
	1^{5}_{5}\\
	\cdots&&\cdots&&\cdots&&\cdots&&\cdots&&\cdots&&\cdots\\
	
\end{array}
$$

Als Beispiel sei *5 über 3* gesucht:
$$
\begin{align}
	\begin{pmatrix}5\\3\end{pmatrix}&=\frac{5!}{\left(5-3\right)!\cdot 3!}\\
	&=\frac{5!}{2!\cdot3!}\\
	&=\frac{5\cdot4\cdot\cancel{3!}}{2!\cdot\cancel{3!}}\\
	&=\frac{5\cdot\cancelto{2}{4}}{\cancelto{1}{2}}\\
	&=5\cdot2=10
\end{align}
$$
Dies lässt sich ebenfalls mit dem Dreieck erkennen.
$$
\begin{array}{}
	&&&&&&1^{0}_{0}&&\\
	&&&&&1^{1}_{0}&&1^{1}_{1}&\\
	&&&&1^{2}_{0}&&2^{2}_{1}&&1^{2}_{2}\\
	&&&1^{3}_{0}&&3^{3}_{1}&&3^{3}_{2}&&1^{3}_{3}\\
	&&1^{4}_{0}&&4^{4}_{1}&&6^{4}_{2}&&4^{4}_{3}&&1^{4}_{4}\\
	&1^{5}_{0}&&5^{5}_{1}&&10^{5}_{2}&&\boxed{10^{5}_{3}}&&5^{5}_{4}&&
	1^{5}_{5}
\end{array}
$$

---