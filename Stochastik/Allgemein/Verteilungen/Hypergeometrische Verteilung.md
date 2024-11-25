Eine hypergeometrische Verteilung kann angenommen werden, insofern folgende Bedingungen erfüllt sind:
- Es gibt exakt zwei Ergebnisse
- Die Reihenfolge bei mehrfachen Ziehen ist unwichtig
- Ziehen ohne zurücklegen

Die Hypergeometrische Verteilung wird unter anderem definiert durch:
$$
P(X=k)=
\frac{
	\begin{pmatrix}n\\k\end{pmatrix}\cdot
	\begin{pmatrix}N-n\\K-k\end{pmatrix}}
	{\begin{pmatrix}N\\K\end{pmatrix}}
$$
Hierbei gibt $n$ die Gesamtanzahl der gewollten Elemente an, wobei $k$ die gewünschte Anzahl dieser angibt. $N-n$ gibt folglich die Gesamtanzahl der nicht gewollten Elemente an. $K-k$ gibt hier die gewünschte Anzahl für diese Elemente an. Es resultiert die Gesamtanzahl aller Elemente durch $N$ und die Anzahl der Entnahme eines Elementes aus dem System $K$.

> Eine Urne ist mit $8$ roten und $3$ blauen Bällen gefüllt. Es werden zufällig $5$ Bälle ohne zurücklegen entnommen. Die Anzahl roter gezogener Bälle wird durch die [[Zufallsvariable]] $X$ beschrieben.

Aus dieser Beschreibung resultiert die folgende Verteilung:
$$
P(X=k)=
\frac{
	\begin{pmatrix}8\\k\end{pmatrix}\cdot
	\begin{pmatrix}3\\5-k\end{pmatrix}}
	{\begin{pmatrix}11\\5\end{pmatrix}}
$$

---
## Herleitung
> Nehmen wir an, dass $N$ Elemente aufgereiht sind und von diesen $n$ mit einem uns gewollten Merkmal markiert sind, welche wir $k$ mal erhalten möchten. Es wird $K$-mal ein Element entfernt:

Zu Beginn sind von den markierten Elementen $n$ vorhanden. Für das Ziehen der Markierten Elemente gibt es allgemein $\begin{pmatrix}n\\k\end{pmatrix}$ Möglichkeiten, da jedes Element des Sets $N_M$, welches markierte Elemente enthält, identische Eigenschaften besitzt.
Weil es möglich ist, dass ein Element, welches nicht in $N_M$ ist, gezogen wird, da $k<K$, so gibt es ebenfalls Permutationen unter den nicht markierten Elementen nach $\begin{pmatrix}N-n\\K-k\end{pmatrix}$. Da $N$ die Summe aller Elemente beschreibt, müssen exakt $N-n$ Set-fremde Elemente vorhanden sein. Das gleiche gilt für den Wert $K-k$, der die Anzahl der Ziehungen aus diesen Elementen beschreibt.
$\begin{pmatrix}N\\K\end{pmatrix}$ beschreibt die generelle Anzahl aller möglichen Permutation aus beiden Elementen.

Per Definition der Verteilung ist folgende Version ebenfalls gültig:
$$
P(X=k)=
\frac{
	\begin{pmatrix}n\\k\end{pmatrix}\cdot
	\begin{pmatrix}m\\q\end{pmatrix}}
	{\begin{pmatrix}n+m\\k+q\end{pmatrix}}
$$

---
## Erweiterung auf mehrere Elemente
Die Hypergeometrische Verteilung lässt sich auf endlich viele Elemente erweitern. Dies lässt sich aus der Definition von zwei Elementgruppen schließen, wobei hier weitere auf ähnliche Weise eingebracht werden. Für endliche Elementgruppen $1$ bis $m$ gilt:
$$
P(\{k_1;~k_2;~k_3;~\cdots;~k_m\})=
	\frac{
	\begin{pmatrix}n_1\\k_1\end{pmatrix}\cdot
	\begin{pmatrix}n_2\\k_2\end{pmatrix}\cdot
	\begin{pmatrix}n_3\\k_3\end{pmatrix}\cdot~\cdots~\cdot
	\begin{pmatrix}n_m\\k_m\end{pmatrix}
	}{\begin{pmatrix}n_1+n_2+n_3+\cdots+n_m\\k_1+k_2+k_3+\cdots+k_m\end{pmatrix}}
$$

---