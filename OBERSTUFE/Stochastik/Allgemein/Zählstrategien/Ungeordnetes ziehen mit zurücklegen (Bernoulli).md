Ein Experiment heißt Bernoulli-Experiment, wenn es in diesem nur exakt zwei Ergebnisse als Resultate gibt, welche bei einer Verkettung eine unveränderte Wahrscheinlichkeit aufweist. Es handelt sich hierbei um ein ziehen mit zurücklegen.

Für einen $n$ stufigen Prozess wird gefragt, wie eine Wahrscheinlichkeit $p$ eines [[Ereignis(se)]]s $E$ vorzufinden ist. Da es sich um ein ziehen mit zurücklegen handelt, gilt die Pfadregel, dass für das verkettete Ereignis die Wahrscheinlichkeiten multipliziert werden. Für $p$ existiert durch die Angabe der exakt zwei Ereignisse nur das Kompliment von $p$, $q=1-p$. Diese sind pro Stufe der Kette identisch, und können durch den folgenden Ausdruck ausgedrückt werden:
$$P(E)=p^a\cdot q^b$$
Für ein Ereignis bestehend aus $a$ Elementen mit einer jeweiligen Wahrscheinlichkeit von $p$, und $b$ nicht $a$-Elementen, mit einer komplementären Wahrscheinlichkeit von $q=1-p$. Weil pro Stufe $n_1$ $1$ Element gezogen wird, und somit gegen Ende der $n$ Stufen $n$ Elemente gezogen wurden, kann dies durch ebenfalls zusammengefasst werden zu:
$$
\begin{align}
	P(E)&=p^a\cdot q^b&&\bigg|\boxed{
	\begin{align}
		n&=a+b\\
		b&=n-a
	\end{align}}\\
	P(E)&=p^{a}\cdot q^{n-a}\\
	P(E)&=p^{k}\cdot q^{n-k}
\end{align}
$$
$k$ Elemente werden durch $p$ gezogen, übrig bleiben hier die $n-k$ weiteren Elemente, welche durch $q$ gezogen werden müssen.
Dazu zu bedenken ist zusätzlich die Anzahl an Permutationen, welche durch das Ziehen auftreten.
	Durch Pfadregel ist $P(ABB)=P(BAB)=(BBA)$, wodurch die Permutationen hier als Faktor eines Pfades gesehen werden können.
Verwendet wird hier der Binomialkoeffizient ([[Ungeordnetes ziehen ohne zurücklegen (Binomialkoeffizient)]]), welcher dies unter $n$-Stellen mit $k$-Elementen ausdrückt. Vereint ist dies die Formel zu der Binomialverteilung als Ergebnis einer Bernoulli-Kette.
$P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}\cdot p^{k}\cdot q^{n-k}$, wobei $k$ die Anzahl der von $p$ entnommenen Elemente darstellt. Alternativ kann ebenfalls folgendes benutzt werden, um die Abhängigkeit von $q$ zu entfernen:
$$
P(X=k)=\begin{pmatrix}n\\k\end{pmatrix}\cdot p^{k}\cdot (1-p)^{n-k}
$$

---
### Beispiel
Unter einer großen Menge an Schülern tragen annähernd $45\%$ eine kürzere Hose zum Frühlingsbeginn in der Schule. Wenn nun stichprobenartig $20$ dieser Schüler auf deren Hosen Art untersucht werden, wie hoch ist die Wahrscheinlichkeit, dass genau 15 dieser eine kurze Hose tragen?
$$\boxed{
\begin{align}
	X&:\text{"Schüler trägt kurze Hose"}\\
	p&=0,45\\
	n&=20\\
	k&=15
\end{align}}$$
$$
\begin{align}
	P(X=k)&=\begin{pmatrix}n\\k\end{pmatrix}
	\cdot p^{k}\cdot (1-p)^{n-k}\\
	
	P(X=15)&=\begin{pmatrix}20\\15\end{pmatrix}
	\cdot\left(\frac{45}{100}\right)^{15}\cdot
	\left(1-\frac{45}{100}\right)^{20-15}\\
	
	P(X=15)&=\begin{pmatrix}20\\15\end{pmatrix}
	\cdot\left(\frac{45}{100}\right)^{15}\cdot
	\left(\frac{55}{100}\right)^{5}\\
	
	P(X=15)&\approx 0,0049\approx 0,49\%
\end{align}
$$

---