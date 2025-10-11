Falls eine Funktion gegeben ist, welche eine [Y-Achsensymmetrie](Symmetrie.md ) besitzt, so kann man durch die Substitution Nullstellen finden.

Für $f(x)=0,5x^{4}-2x^{2}+1$ kann jedes $x$ als $x^2$ dargestellt werden.
$$\begin{aligned}
f(x)&=0,5x^{4}-2x^{2}+1\\
f(x)&=0,5x^{2^2}-2x^{2^1}+1
\end{aligned}$$
Nehmen wir nun für den Vorgang an, dass $q=x^2$, so entsteht folgende neue Funktion:
$$\begin{aligned}
f(q)&=0,5q^{2}-2q+1\\
\end{aligned}$$
Diese kann nun einfacher nach Nullstellen untersucht werden.
$$q_1=2-\sqrt{2}\quad\vee\quad q_2=2+\sqrt{2}$$
Da wir $q=x^2$ angenommen haben, so muss für jede erhaltene Nullstelle $x=\pm\sqrt{q}$ bestimmt werden.
$$ \begin{aligned}
q_1 &= x^2 &|\sqrt{x}\\
x_{2,3}&=\pm \sqrt{q_1}
\end{aligned} $$
$$ \begin{aligned}
q_2 &= x^2 &|\sqrt{x}\\
x_{1,4}&=\pm \sqrt{q_2}
\end{aligned} $$
Die Funktion $f$ hat somit die folgenden Nullstellen:
$$\begin{array}
	&x_{1}=-\sqrt{q_{2}} && \vee && x_{2}=-\sqrt{q_{1}} &&\vee\\ x_{3}=\sqrt{q_{1}}&&
		\vee &&x_{4}=\sqrt{q_{2}}\\
	&&\Downarrow\\
	x_{1}=-\sqrt{2+\sqrt{2}}&&\vee&&
	x_{2}=-\sqrt{2-\sqrt{2}}&&\vee\\ 
	x_{3}=\sqrt{2-\sqrt{2}}&&\vee&& 
	x_{4}=\sqrt{2+\sqrt{2}}
\end{array}$$

---