Mit dem Gaußschem Lösungsverfahren kann ein [[LGS]] gelöst werden.

---
## Idee
Ein Gleichungssystem mit den Zeilen $\text{I}$, $\text{II}$, und $\text{III}$ seien gegeben.
Folglich sind für alle diese Zeilen folgende [[Äquivalenzumformung(en)]] möglich:
>Additionen zwischen zwei Zeilen
>Subtraktionen zwischen zwei Zeilen
>Multiplikation eines Faktors ($\neq0$) mit einer Zeile

Durch diese Operationen wird die Lösung des Gleichungssystems nicht verändert **(Insofern man sich nirgendswo verrechnet)**.

---
## Ablauf
Sei folgendes LGS gegeben welches gelöst werden soll:
$$\begin{vmatrix}
1x_1-2x_2=3\\
-2x_1+1x_2=0
\end{vmatrix}$$ 
### Taschenrechner
Dieses System kann so mit dem Taschenrechner gelöst werden.
>Menü
>A
>1
>2

---
### Schriftlich

Um sauberer mit diesem zu arbeiten stellt man dieses in der [Matrixschreibweise]([[LGS Darstellungen]]) dar.
$$\left(\begin{array}{ccc|c}
&1&-2& 3 \\
&-2&1& 0
\end{array}
\right)
$$
Nun wird versucht durch [[Äquivalenzumformung(en)]] eine [[Variable(n)]] in einer Gleichung zu entfernen um somit das System zu lösen.
$$
\begin{align}
	&\left(
		\begin{array}{ccc|c}
			&1&-2&3 \\
			&-2&1& 0
		\end{array}
	\right)
	\begin{array}{}
		&|\cdot 2\\
		&
	\end{array}
	\\
	\\
	&\left(
		\begin{array}{ccc|c}
			&2&-4&6 \\
			&-2&1& 0
		\end{array}
	\right)
	\begin{array}{}
		&|\text{ I}+\text{II}\\
		&
	\end{array}
	\\
	\\
	&\left(
		\begin{array}{ccc|c}
			&0&-3&-6 \\
			&-2&1& 0
		\end{array}
	\right)
\end{align}$$
Durch diese Umformungen ist die erste Gleichung nun berechenbar.
$$\begin{align}
\text{I: }0x_1-3x_2&=-6\\
-3x_2&=-6&|\divsymbol(-3)\\
x_2&=-2&
\end{align}$$
Da $x_2$ nun einen Wert hat, so kann man diesen in die weiteren Gleichungen einsetzen um weitere Variablen zu finden.
$$\begin{align}
\text{II: }-2x_1+x_2&=0\\
-2x_1-2&=0&&|+2\\
-2x_1&=2&&|\divsymbol \left(-2 \right)\\
x_1&=-1
\end{align}$$

---
### Ergebnis
Folglich sind die Lösungen von
$$
\begin{align}
	\begin{vmatrix}
		1x_1-2x_2=3\\
		-2x_1+1x_2=0
	\end{vmatrix}
	\\ \\
	x_1=-1\quad\wedge\quad x_2=&-2
\end{align}$$

---
