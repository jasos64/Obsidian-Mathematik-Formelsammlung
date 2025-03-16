Da [Produkte](Multiplikation) von zwei [Funktionen](Funktion(en)) nicht einfach [integriert](Integration.md) werden können, muss in einem solchen Fall **partiell Integriert** werden.

---
## Vorbereitung der Herleitung
>Ein Produkt $h(x)=f(x)\cdot g(x)$ sei gegeben, wobei $f(x)$ und $g(x)$ auf einem Intervall $I=\left[a;b\right]$ integrierbar sind.

Da die Integrierung (aufleiten) gegenteilig zu der Differenzierung (ableiten) steht, können wir die Produktregel der Differenzierung verwenden.
Es gilt:
$$
\begin{align}
	h(x)&=f(x)\cdot g(x)\\
	h'(x)&=f'(x)\cdot g(x)+f(x)\cdot g'(x)\\
	\frac{d}{dx}\left(f(x)\cdot g(x)\right)&=f'(x)\cdot g(x)+f(x)\cdot g'(x)
\end{align}
$$
Sollten wir nun beide Seiten Integrieren, so erhalten wir in umgeschrieben unsere Startfunktion $h(x)$.
$$
\begin{align}
	h'(x)&=f'(x)\cdot g(x)+f(x)\cdot g'(x)\\
	\int_a^b h'(x)~dx&=\int_a^b f'(x)\cdot g(x)~dx+\int_a^b f(x)\cdot g'(x)~dx
\end{align}
$$
Die linke Seite hebt sich hierdurch auf, da sowohl Differenziert, als auch Integriert wird. Weitergehend wird $h(x)$ durch $f(x)\cdot g(x)$ dargestellt.
$$
\begin{align}
	\int_a^b h'(x)~dx&=\int_a^b f'(x)\cdot g(x)~dx+\int_a^b f(x)\cdot g'(x)~dx\\
	h(x)&=\int_a^b f'(x)\cdot g(x)~dx+\int_a^b f(x)\cdot g'(x)~dx\\
	f(x)\cdot g(x)&=\int_a^b f'(x)\cdot g(x)~dx+\int_a^b f(x)\cdot g'(x)~dx
\end{align}
$$

---
## Endgültige Herleitung
Ändern wir die Perspektive, dass eine Funktion $q(x)=f'(x)\cdot g(x)$ gegeben ist, dann ändern wir die gegebene Gleichung wie folgt:
$$
\begin{align}
	f(x)\cdot g(x)&=\int_a^b f'(x)\cdot g(x)~dx+\int_a^b f(x)\cdot g'(x)~dx&&\mid-\int_a^b f(x)\cdot g'(x)~dx\\
	\int_a^b f'(x)\cdot g(x)~dx&=f(x)\cdot g(x)-\int_a^b f(x)\cdot g'(x)~dx
\end{align}
$$
Die linke Seite ist nun die gesuchte Integration $Q(x)$ von $q(x)$.

---
## Hinweise
>Die Definition der partiellen Integration beinhaltet eine weitere partielle Integration. Um ein Endergebnis zu erhalten, werden die [Faktoren](Multiplikation) $f'(x)$ und $g(x)$ so gewählt, dass $f'(x)$ kein Polynom ist, und $g(x)$ durch ableiten eventuell $0$ wird.

Partielle Integrationen können durch die Definition ineinander existieren.

---