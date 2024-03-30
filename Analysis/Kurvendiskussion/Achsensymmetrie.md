## Y-Achse
Wenn der [Funktionsterm](Funktion(en)) nur Polynome mit geraden Graden besitzt, dann ist der Graph von $f$ achsensymmetrisch zur y-Achse und umgekehrt.
$f(x)=f(-x)$

---
## Ursprung
Wenn der Funktionsterm nur Polynome mit ungeraden Graden besitzt, dann ist der Graph von f punktsymmetrisch zum Ursprung und umgekehrt.
$f(x)=-f(-x)$

---
## "Geradensymmetrie"
Wenn ein Funktionsterm zu einer Gerade $x=a$ eine Symmetrie besitzt, dann gilt:
$$\exists a\in \mathbb{R},f(a-x)\equiv f(a+x)$$

---
## "Punktsymmetrie auf $P(a\mid b)$"
Eine [[Funktion(en)]] ist Punktsymmetrisch zu einem Punkt $P(a\mid b)$, insofern folgendes eintrifft:
$$\exists \{a;b\}\in \mathbb{R},-f(a-x)+b\equiv f(a+x)-b$$
Insofern die Verschiebung der Funktion auf die Stelle $x=a$ gesetzt ist, und folglich nur $b$ danach verschoben werden muss, so muss der Abstand der beiden Terme (links und rechts) in der Differenz eine konstante ergeben, da die Abstände identisch für alle $x$ ist. Die Steigung ist somit für alle $x$ ebenfalls gleich $0$.
Erweitert man den Ausdruck oben nun mit dem der [[Ableitung]], lässt sich folgendes zur Berechnung von $a$ darstellen.
$$
\begin{align}
	-f(a-x)+b-(f(a+x)-b)&\equiv0\\
	-f(a-x)+b-f(a+x)+b&\equiv0\\
	\frac{d}{dx}\bigg[f(a-x)-b+f(a+x)-b\bigg]&\equiv0\\
	f'(a-x)+f'(a+x)&\equiv0
\end{align}
$$

---