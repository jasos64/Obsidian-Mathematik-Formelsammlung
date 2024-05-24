[[Vektor(en)]] beisitzen bereits bekannte Eigenschaften, allerdings gibt es Operationen, die für Vektoren nicht definiert sind. Hier folgt eine Liste möglicher und unmöglicher Operationen an Vektoren.

---
## Definierte Operationen
Additionen/Subtraktionen mit Vektoren sind anwendbar, da diese die einzelnen Komponenten addiert/subtrahiert.
$$\begin{pmatrix}a\\b\\c\end{pmatrix}\pm\begin{pmatrix}d\\f\\g\end{pmatrix}=\begin{pmatrix}a\pm d\\b\pm f\\c\pm g\end{pmatrix}$$

---
Multiplikationen mit einem Skalar sind anwendbar, da diese jede Zahl mit dem Faktor multipliziert.
$$r\cdot\begin{pmatrix}a\\b\\c\end{pmatrix}=\begin{pmatrix}a\cdot r\\b\cdot r\\c\cdot r\end{pmatrix}$$

---
Aus den beiden oberen folgend ist das Zusammenfügen und Trennen einer Vektorfolge ebenfalls möglich:
$$
\begin{align}
	\begin{pmatrix}p_1\\p_2\\p_3\end{pmatrix}\pm
		\lambda\cdot\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}=
	\begin{pmatrix}p_1\pm v_1\lambda\\p_2\pm v_2\lambda\\
		p_3\pm v_3\lambda\end{pmatrix}
\end{align}
$$

---
Eine Multiplikation zweier Vektoren sind nicht im normalen Sinne möglich wie $\begin{pmatrix}a\\b\\c\end{pmatrix}\cdot\begin{pmatrix}d\\e\\f\end{pmatrix}=\begin{pmatrix}a\cdot d\\b\cdot e\\c\cdot f\end{pmatrix}$ nicht möglich. Der beschrieben Ausdruck hier deutet auf das [[Skalarprodukt]] hin, wodurch dies $\begin{pmatrix}a\\b\\c\end{pmatrix}\cdot\begin{pmatrix}d\\e\\f\end{pmatrix}=a\cdot d+b\cdot e+c\cdot f$ ist. Das Ergebnis ist somit ein Skalar, also eine Zahl.

---
Ein Produkt eines Vektors, welches einen Vektor als Ergebnis erzielt, ist das [[Kreuzprodukt]]. mehr ist unter dem hierfür erstellten Eintrag lesbar.

---
Das Distributivgesetz gilt für Vektoroperationen hinsichtlich eines Skalars und dessen Produktes. Somit ist es möglich den folgenden Ausdruck wie folgt umzuformen.
$$
\begin{align}
	\vec{n}\circ\left[\vec{x}-\vec{p}\right]\equiv
		\vec{n}\circ\vec{x}-\vec{n}\circ\vec{p}
\end{align}
$$

---
---
## Undefinierte Operationen
Ein Vektor kann nicht mit einer Zahl addiert werden.
$z+\vec{n}=\textit{ERROR}$

---
Ein Vektor kann durch die Abwesenheit der einfachen Multiplikation zwischen Vektoren nicht nicht als Nenner in einem Bruch stehen. Sei $Z$ hier ein Vektor oder ein Skalar, und $\vec{n}$ ein Vektor:
$\frac{Z}{\vec{n}}=\textit{ERROR}$

---
