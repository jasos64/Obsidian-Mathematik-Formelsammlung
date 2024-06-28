# 1 Stochastik
## a)
>Berechnen Sie, welchen prozentualen Anteil die lackierten Tische, die unlackierten Tische sowie die unlackierten Stühle haben. Bekannt ist, dass lackierte Stühle 30% der Produktion ausmachen. Insgesamt beträgt der Anteil von Tischen zu Stühlen 30:70 und der Anteil von lackierten und unlackierten Produkten ist ausgeglichen. Verdeutlichen Sie Ihre Lösung auch graphisch.

Gegeben aus dem Text gilt folgendes:
- $L:\textit{ Lackiert}$
- $T:\textit{ Tisch}$
- $P(T)=0,3$
- $P(\overline{T})=0,7$
- $P(\overline{T}\cap L)=0,3$
- $P(T\cap L)+P(\overline{T}\cap L)=P(T\cap \overline{L})+P(\overline{T}\cap \overline{L})$

Eine Vierfeldertafel beschreibt Wahrscheinlichkeiten nach:
$$
\begin{array}{r|cc|c}
	&T&\overline{T}&\sum\\ \hline
	L&P(T\cap L) &P(\overline{T}\cap L) & P(L)\\
	\overline{L} &P(T\cap \overline{L}) &P(\overline{T}\cap \overline{L}) &P(\overline{L}) \\
	\sum&P(T) & P(\overline{T})& 1
\end{array}
$$
Dies eingesetzt bildet sich zu dem folgenden:
$$
\begin{array}{r|cc|c}
	&T&\overline{T}&\sum\\ \hline
	L&P(T\cap L) &0,3 & P(L)\\
	\overline{L} &P(T\cap \overline{L})
		&\textcolor{orange}{0,4} &P(\overline{L}) \\
	\sum&0,3 & 0,7& 1
\end{array}
$$
Da oben beschrieben ist, dass $P(T\cap L)+P(\overline{T}\cap L)=P(T\cap \overline{L})+P(\overline{T}\cap \overline{L})$ ist, können die Verteilungen für $P(T\cap L)$ und $P(T\cap \overline{L})$ dementsprechend bestimmt werden.
$$
\begin{align}
	P(T\cap L)+P(\overline{T}\cap L)&=P(T\cap \overline{L})+P(\overline{T}\cap \overline{L})\\
	P(T\cap L)+0,3&=P(T\cap \overline{L})+0,4\\
	P(T\cap L)-P(T\cap \overline{L})&=0,1
\end{align}
$$
Da zusätzlich gilt, dass die Summe jedes Endergebnisses $1$ ist, so ergibt sich zusätzlich:
$$
\begin{align}
	P(T\cap L)+P(\overline{T}\cap L)+P(T\cap \overline{L})+P(\overline{T}\cap \overline{L})&=1\\
	P(T\cap L)+0,3+P(T\cap \overline{L})+0,4&=1\\
	P(T\cap L)+P(T\cap \overline{L})&=0,3
\end{align}
$$
Es ergeben sich insgesamt zwei Bedingungen für die beiden Wahrscheinlichkeiten. Es kann ein Gleichungssystem erstellt werden, welches dann folgende Lösung besitzt:
$$
\left[\begin{array}{ccc}
	P(T\cap L)&-&P(T\cap \overline{L})&=&0,1\\
	P(T\cap L)&+&P(T\cap \overline{L})&=&0,3
\end{array}\right]
$$
$$
\begin{align}
	P(T\cap L)&=0,2\\
	P(T\cap \overline{L})&=0,1
\end{align}$$
Diese Lösungen werden nun in die Tafel oben ergänzt, sodass diese nun vollständig ist.
$$
\begin{array}{r|cc|c}
	&T&\overline{T}&\sum\\ \hline
	L&\textcolor{green}{0,2} &0,3 & \textcolor{orange}{0,5}\\
	\overline{L} &\textcolor{green}{0,1} 
		&0,4 &\textcolor{orange}{0,5} \\
	\sum&0,3 & 0,7& 1
\end{array}
$$

Der Anteil der lackierten Tische beträgt $P(T\cap L)=20\%$.
Der Anteil der unlackierten Tische beträgt $P(T\cap \overline{L})=10\%$.
Der Anteil der unlackierten Stühle beträgt $P(\overline{T}\cap \overline{L})=40\%$.

## b)
Der Anteil der lackierten Stühle von Stühlen beträgt $P_{\overline{T}}(L)=\frac{P(\overline{T}\cap L)}{P(\overline{T})}=\frac{0,3}{0,7}=\frac{3}{7}\approx42,9\%$.
Der Anteil an Tischen von unlackierten Produkten beträgt $\frac{P(T)}{P(\overline{L})}=\frac{0,3}{0,5}=\frac{3}{5}=60\%$.

## c)
Für diese Unteraufgabe wird eine Binomialverteilung mit Zufallsvariable $X$ angenommen, welche die Anzahl an lackierten (Stühlen) beschreibt. Für die Wahrscheinlichkeit $p$ gilt:
$P_{\overline{T}}(L)=\frac{P(\overline{T}\cap L)}{P(\overline{T})}=\frac{0,3}{0,7}=\frac{3}{7}$.

- $P(X\le2)=F_{4;\frac{3}{7}}(2)\approx0,3599$
- $P(X\ge 3)=1-P(X\le2)=1-F_{6;\frac{3}{7}}(2)\approx0,5148$
- $P(4\le X\le6)=P(X\le6)-P(X\le 3)=F_{8;\frac{3}{7}}(6)-F_{8;\frac{3}{7}}(3)\approx0,4595$

## d)
Themenbereich nicht behandelt

# 2 Analysis
## a)
Aus wirtschaftlicher Sicht ist ein s-förmiger Kurvenverlauf sinnvoll, da zum Beispiel bei wachsenden Unternehmen Investitionen getätigt werden, welche in späterer Hinsicht dem Unternehmen einen Gewinn einbringen, nachdem diese zuvor einen Verlust darstellen. Für einen s-förmigen Kurvenverlauf ist wichtig, dass die zu beschreibende Funktion mindestens zwei Extrema besitzt. Daraus vorausgesetzt ist, dass die erste Ableitung mindestens zwei Nullstellen besitzt, welche vom Elementaren Wert unterschiedlich sind. Da zu einem Zeitpunkt $x_0=0$ die Kosten **annahmeweise** steigen, so muss für die Funktion $f(x)$ folgendes gelten, neben dem bereits beschriebenem: $f'(0)<0$.

## b)
Die Kostenfunktionsschar $K$ ist gegeben, mit:
$$
\begin{align}
	K_b(x)&=0,25x^3+bx^2+12x+20\\
	K_b'(x)&=0,75x^2+2bx+12
\end{align}
$$
Es werden $b$ gesucht, sodass:
- $K_b'(x)$ mindestens zwei Nullstellen besitzt.
Stellen wir eine Funktion auf, welche von $b$ abhängig ist, und Funktionswerte aller möglichen $b$ auf dessen Nullstellen projiziert, so kann abgelesen werden, welche Werte von $b$ wie viele Nullstellen besitzen, und folglich angeben, welche $b$ in $K_b$ das gewünschte Resultat ergeben.
$$
\begin{align}
	K_b'(x)&=0,75x^2+2bx+12\\
	0&=K_b'(x)\\
	0&=0,75x^2+2bx+12\\
	\\
	x_{1;2}&=\frac{-2b\pm\sqrt{(2b)^2-4\cdot0,75\cdot12}}{2\cdot0,75}\\
	&=\frac{-2b\pm\sqrt{4b^2-36}}{1,5}\\
\end{align}
$$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: true
grid: true
---
f(x)=(-2x+(4x^(2)-36)^0.5)/(1.5)
g(x)=(-2x-(4x^(2)-36)^0.5)/(1.5)
```
(Grafikfehler, da die Werte $-3<b<3$ undefiniert sind, und nicht wie hier verbunden sind).
Man erkennt, dass alle Werte außerhalb von $I=\left[-3;3\right]$ ein s-förmiges Profil besitzen.

---
Es wird die Schar gesucht, wodurch $K_{a;b}(x)=ae^{0,5x}-bx^2$ durch die Punkte $P_1(1\mid11,1898)$ und $P_2(4\mid51,1124)$ geht.
Als Lösungsweg wird hier die Kombination von $a$ und $b$ gesucht, welche getrennt durch einen Punkt gehen. Anschließend muss es eine Schnittstelle geben, welche daraus dann die Werte der Schar gibt.

Zunächst wird die Abhängigkeit von $K$ für den Punkt $P_1$ gegeben:
$$
\begin{align}
	K_{a;b}(x)&=ae^{0,5x}-bx^2\\
	11,1898&=ae^{0,5\cdot1}-b\cdot1^2\\
	11,1898&=ae^{0,5}-b&&\mid -ae^{0,5}\\
	&&&\mid\cdot(-1)\\
	b&=ae^{0,5}-11,1898
\end{align}
$$
Folgend die Abhängigkeit für $P_2$:
$$
\begin{align}
	K_{a;b}(x)&=ae^{0,5x}-bx^2\\
	51,1124&=ae^{0,5\cdot4}-b\cdot4^2\\
	51,1124&=ae^{2}-16b&&\mid-ae^2\\&&&\mid\div(-16)\\
	b&=\frac{ae^{2}-51,1124}{16}
\end{align}
$$
Nun werden diese beiden Abhängigkeiten gleichgesetzt, um den Wert für $a$ zu bestimmen.
$$
\begin{align}
	ae^{0,5}-11,1898&=\frac{ae^{2}-51,1124}{16}\\
	ae^{0,5}-11,1898&=\frac{1}{16}ae^{2}-\frac{51,1124}{16}&&\mid+11,1898\\&&&\mid-\frac{1}{16}ae^2\\
	
	ae^{0,5}-\frac{1}{16}ae^2&=\frac{319811}{40000​}\\
	a\cdot\left(e^{0,5}-\frac{1}{16}e^2\right)&=\frac{319811}{40000​}
		&&\mid\div \left(e^{0,5}-\frac{1}{16}e^2\right)\\
	a&=\frac{319811}{40000\cdot\left(e^{0,5}-\frac{1}{16}e^2\right)}\approx6,736
\end{align}
$$

$a$ ist gegeben, und wird in eine der beiden Abhängigkeiten eingesetzt:
$$
\begin{align}
	b&=ae^{0,5}-11,1898\\
	&=\frac{319811}{40000\cdot\left(e^{0,5}-\frac{1}{16}e^2\right)}e^{0,5}-11,1898\approx−0,0836
\end{align}
$$

Die Funktion $K$ lautet somit:
$$
\begin{align}
	K_{a;b}(x)&=ae^{0,5x}-bx^2\\
	K_{a;b}(x)&=\frac{319811}{40000\cdot\left(e^{0,5}-\frac{1}{16}e^2\right)}\cdot e^{0,5x}-\left(\frac{319811}{40000\cdot\left(e^{0,5}-\frac{1}{16}e^2\right)}e^{0,5}-11,1898\right)x^2\\
	K_{a;b}(x)&\approx 6,736e^{0,5x}+0,0836x^2
\end{align}
$$

---