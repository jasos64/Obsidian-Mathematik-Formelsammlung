Die Fakultät ist ein Operator, bei welchem von einer [natürlichen Zahl](Zahlensets) alle davorliegenden Zahlen [multipliziert](Multiplikation) werden.
Es ist folgendermaßen definiert:
$$
n!=n\cdot (n-1)!
$$
Alternativ gilt für Zahlen $n$ aus $\mathbb{N}^+$ folgendes:
$$
n!\coloneqq\prod^{n}_{k=1}k= 1\cdot2\cdot3\cdot\,\cdots\,\cdot n
$$
Zusätzlich dazu ist $0!$ als $1$ definiert. $0!=1$
Dies zeigt sich mit der oben stehenden Definition:
$$
\begin{align}
	n!&=n\cdot (n-1)!&&\mid\boxed{n=1}\\
	1!&=1\cdot (1-1)!\\
	1&=0!
\end{align}
$$

---
### Gamma-Funktion
Es existiert eine Erweiterung der Fakultät für Zahlen aus $\mathbb{R}$ und $\mathbb{C}$. Diese ist folgendermaßen definiert:
$$
\Gamma(z)=\int^{\infty}_{0}t^{z-1}e^{-t}\,dt\qquad z\in\mathbb{C}\backslash\{\mathbb{Z}^{0-}\}
$$

---