Dieser Vorgang ermöglicht es einem [[Nullstellen]] einer [[Funktion(en)]] durch eine wiederholte Rechnung zu ermitteln. Dieser Vorgang wird von Taschenrechnern verwendet um Nullstellen zu finden.

## Der Vorgang
>Eine Funktion besitzt eine Nullstelle, so kann eine Nullstelle angenähert werden, indem der folgende Ausdruck wiederholt durchgeführt wird:

$$x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}$$

---
## Herleitung
Eine Tangente wird an einem Punkt $P\left(a\mid f(a)\right)$ angelegt zu dieser eine Nullstelle der x-Achse gefunden werden soll.
Die Tangentenfunktion $t(x)$ kann durch $f'\left(a\right)\left(x-a\right)+f\left(a\right)$ ausgedrückt werden.

Da der Schnittpunkt von $t$ und x-Achse gesucht wird ist:
$$\begin{align}
	0&=t(x)\\
	0&=f'\left(a\right)\left(x-a\right)+f\left(a\right)&&\mid-f(a)\\
	-f(a)&=f'\left(a\right)\left(x-a\right)&&\mid\divsymbol f'(a)\\
	\frac{-f(a)}{f'(a)}&=x-a&&\mid+a\\
	x&=a-\frac{f(a)}{f'(a)}
\end{align}$$

---