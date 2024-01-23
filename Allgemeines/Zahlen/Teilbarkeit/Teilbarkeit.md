Die Teilbarkeit einer Zahl $a$ gibt an, welche Zahl $b$ aus $\mathbb{N}$ mit dieser dividiert werden kann, ohne dass das Ergebnis diesen Zahlenbereich der natürlichen Zahlen verlässt ($n$).
Beschreiben lässt sich dies mit folgendem Ausdruck:
$$\frac{a}{b}=n\quad \{a;b;n\}\in\mathbb{N}$$

Teilbarkeiten von $a$ werden wie folgt beschrieben:
$$T_{a}=\{n_{1}~;~n_{2}~;~\cdots~;~n_{m}\}$$ 
Um zu beschreiben, dass eine Zahl $b$ ein Teiler einer anderen Zahl $a$ ist, so schreibt man:
$$a\mid b$$

---
## ggT
Der *größte gemeinsame Teiler* beschreibt einen gemeinsamen Teiler zweier Zahlen in $\mathbb{N}$ der möglichst groß ist.
$$\begin{align}
	T_{10}&=\{1;2;5;10\}\\
	T_{25}&=\{1;5;25\}\\
	ggT(10,25)&=5
\end{align}$$
um den $ggT$ bei Zahlen anzuwenden, so wendet man zunächst die [[Primfaktorzerlegung]] an um diese in seine Primfaktoren aufzuteilen.
$$\begin{align}
	10&=2^{1}\cdot5^{1}\\
	25&=5^{2}
\end{align}$$
Um nun den größten gemeinsamen Teiler dieser zwei Zahlen zu finden, so vergleicht man die Potenzen aller Faktoren.
Da einige Faktoren nur in einer der beiden Zahlen vorhanden sind, weshalb sie nicht in allen existieren, so können sie mit Potenz $0$ beschrieben werden.
$$\begin{align}
	10&=2^{1}\cdot5^{1}\\
	25&=2^{0}\cdot5^{2}
\end{align}$$
Der $ggT$ ist nun folgendes:
$$ggT(10,25)=2^{min(0,1)}\cdot5^{min(1,2)}=2^{0}\cdot5^{1}=5$$
Die $min()$ Darstellung beschreibt das Wählen des kleinsten Wertes aus der beschrieben Wertemenge. $min(3,40,76)=3$.

---
## kgV
Das *kleinste gemeinsame Vielfache* ist ein Wert der bei vielfachen mehrerer Zahlen am kleinsten ist.
$$\begin{align}
	10,20,30,40,50\\
	25,50,75,100\\
	kgV(10,25)&=50
\end{align}$$ Zur Berechnung dieses können die Zahlen in Primfaktoren aufgeteilt werden.
$$\begin{align}
	10&=2^{1}\cdot5^{1}\\
	25&=2^{0}\cdot5^{2}
\end{align}$$
Nun wird von diesen Faktoren jeder multipliziert, der die höhere Potenz hat.
$$kgV(10,25)=2^{max(0,1)}\cdot5^{max(1,2)}=2^{1}\cdot5^{2}=2\cdot25=50$$
Die $max()$ Darstellung beschreibt das Wählen des größten Wertes aus der beschrieben Wertemenge. $max(3,40,76)=76$.

---
