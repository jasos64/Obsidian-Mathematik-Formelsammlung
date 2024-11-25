Mit der Partialbruchzerlegung kann eine gebrochen Rationale [Funktion](Funktion(en)) in eine Summe von Brüchen ausgedrückt werden.
Zunächst werde ich annehmen, dass die [[Nullstellen]] der Nennerfunktion alle einzeln vorhanden sind und nicht mehrfach. Auch werde ich annehmen, dass der Grad der Zählerfunktion kleiner als die Nennerfunktion ist.

---
Für eine bessere Erklärung werde ich eine Beispielfunktion bereitstellen.
Sei $f$ wie folgt gegeben, die in Partialbrüche zerlegt werden soll:
$$f(x)=\frac{x^2-3x-1}{x^{3}+8x^{2}-20x}$$
Zunächst wird jede Nullstelle der Nennerfunktion bestimmt. Die Linearfaktoren werden der Übersichtlichkeit aufgeschrieben. Zusätzlich wird jede Nullstelle als einzelnen Nenner mit einer [Variable](Variable(n)) beschrieben und gleichgestellt:
$$\frac{x^2-3x-1}{\left(x+10\right)\left(x\right)\left(x-2\right)}=\frac{A}{x+10}+\frac{B}{x}+\frac{C}{x-2}$$
Die Nennerfunktion wird multipliziert und es wird vereinfacht, sodass man einen [[Koeffizientenvergleich]] durchführen kann.
$$\begin{align}
	\frac{x^2-3x-1}{\left(x+10\right)\left(x\right)\left(x-2\right)}&=\frac{A}{x+10}+\frac{B}{x}+\frac{C}{x-2}&&\mid\cdot\left(x+10\right)\left(x\right)\left(x-2\right)\\
	
	x^2-3x-1&=\frac{A\cancel{\left(x+10\right)}\left(x\right)\left(x-2\right)}{\cancel{x+10}}+\frac{B\left(x+10\right)\cancel{\left(x\right)}\left(x-2\right)}{\cancel{x}}+\frac{C\left(x+10\right)\left(x\right)\cancel{\left(x-2\right)}}{\cancel{x-2}}\\
	
	x^2-3x-1&=A\left(x\right)\left(x-2\right)
	+B\left(x+10\right)\left(x-2\right)
	+C\left(x+10\right)\left(x\right)\\
	
	x^2-3x-1&=A\left(x^2-2x\right)
	+B\left(x^2+8x-20\right)
	+C\left(x^2+10x\right)\\
	
	x^2-3x-1&=Ax^2-2Ax
	+Bx^2+8Bx-20B
	+Cx^2+10Cx\\
	
	x^2-3x-1&=\left(A+B+C\right)x^2+
	\left(-2A+8B+10C\right)x+
	\left(-20B\right)
\end{align}$$
Damit dieser Term nun Äquivalent wird, so müssen die Faktoren der Polynome übereinstimmen. Um eine Kombination zu finden, mit der die Äquivalenz existent ist, wird ein [Gleichungssystem](LGS) angefertigt und gelöst.
$$\begin{align}&\left(
	\begin{array}{ccc|c}
		A&B&C&1\\
		-2A&8B&10C&-3\\
		0&-20B&0&-1
	\end{array}\right)
	\\
	&~~~~~~~~~~~~~~~~~~~~~\downarrow\\
	&\begin{array}{}
		A=\frac{43}{40}&\wedge&
		B=\frac{1}{20}&\wedge&
		C=-\frac{1}{8}
	\end{array}
\end{align}
$$
Für die Partialbruchzerlegung gilt also folgendes:
$$\begin{align}
	\frac{x^2-3x-1}{\left(x+10\right)\left(x\right)\left(x-2\right)}&=\frac{A}{x+10}+\frac{B}{x}+\frac{C}{x-2}\\
	
	&=\frac{\frac{43}{40}}{x+10}+\frac{\frac{1}{20}}{x}+\frac{-\frac{1}{8}}{x-2}\\
	
	&=\frac{43}{40x+400}+\frac{1}{20x}-\frac{1}{8x-16}\\
\end{align}$$

---
## Doppelte Nullstellen
Nehmen wir an, dass eine gebrochen rationale Funktion wie $f(x)=\frac{g(x)}{(x+3)^2\cdot(x-2)}$ gegeben ist, dann ist der Aufbau der Partialbruchzerlegung die folgende:
$$
\frac{g(x)}{(x+3)^2\cdot(x-2)}=\frac{A}{x+3}+\frac{B}{(x+3)^2}+\frac{C}{x-2}
$$