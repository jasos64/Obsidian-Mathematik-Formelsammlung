Zwei [[Funktion(en)]] sind gegeben, zwischen welchen ein Flächeninhalt berechnet werden soll.
Grundsätzlich gilt $\int^{b}_{a}f(x)-g(x)~dx$, insofern $f(x)\ge g(x)$

## Eingeschlossener Flächeninhalt
Insofern von einem *eingeschlossenem Flächeninhalt* die Rede ist, wird ein Eingeschlossener Bereich zwischen Schnittstellen der beiden Funktionen gesucht. Im folgendem ist dies visuell dargestellt:
<iframe src="https://www.desmos.com/calculator/tmlitego69?embed" width="1000" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

$$
\boxed{
		\begin{array}{}
		\textcolor{#c74440}{f\left(x\right)=-0,3x^{3}+1,8x^{2}-2,4x+2}&&
		\textcolor{#2d70b3}{g\left(x\right)=x^{2}-6x+10}
		\end{array}
	}\\
$$

---
### Berechnung von einem eingeschlossenem Flächeninhalt
#### 1) Schnittstellen
Für eine Berechnung wird zunächst überprüft, wo Schnittstellen vorhanden sind. Hierzu werden die beiden Funktionen gleich gesetzt und anschließend vereinfacht.
In der Abbildung oben sind folgende Funktionen verwendet worden, mit welchen ich hier zusätzlich die Berechnung weiterführe.

>Hier wurde eine Hilfsfunktion $d$ verwendet, um anhand dieser Nullstellen zu identifizieren, und Vorzeichen zu berechnen. $d$ bleibt hierbei stets fest definiert, wobei die begrenzenden Funktionen $f$ und $g$ ebenfalls mit getauschtem Vorzeichen stehen können.

$$\begin{align}
	f(x)&=g(x)&&\mid-g(x)\\
	d(x)&=g(x)-f(x)\\
	\\
	0&=d(x)\\
	0&=x^{2}-6x+10-\left(-0,3x^{3}+1,8x^2-2,4x+2\right)\\
	0&=x^{2}-6x+10+0,3x^{3}-1,8x^2+2,4x-2\\
	0&=0,3x^3+(1-1,8)x^2+(-6+2,4)x+(10-2)\\
	0&=0,3x^3-0,8x^2-3,6x+8\\
	&~~\vdots\\
	\mathbb{L}&=\bigg\{-\frac{10}{3};2;4\bigg\}
\end{align}
$$
$$
\begin{array}{}
	x_1=-3,\overline{3}&\vee&x_2=2&\vee&x_3=4
\end{array}
$$

Daraus lässt sich sagen, dass $f(-3,\overline{3})=g(-3,\overline{3})$, $f(2)=g(2)$ und $f(4)=g(4)$. Diese resultierenden Stellen sind nun Teil der Integrationsgrenzen $a, b,...$ des Flächeninhaltes.

#### 2) Intervallvorzeichen
Durch die Schnittstellen können nun Intervalle aufgestellt werden, um Vorzeichen in diesem auf jedem zu bestimmen. Dies wird gemacht, damit ein nicht orientierter Flächeninhalt einer Funktion $d(x)=g(x)-f(x)$ gebildet werden kann.

$$
\begin{array}{}
	x_1=-3,\overline{3}&\vee&x_2=2&\vee&x_3=4\\
	\searrow&&\swarrow \qquad\searrow&&\swarrow\\
	&\left[x_1;x_2\right]&&\left[x_2;x_3\right]\\
	&\downarrow&&\downarrow&\\
	&\left[-3,\overline{3};2\right]&&\left[2;4\right]
\end{array}
$$
Weil beide Funktionen in diesen Intervallen stetig sind, so können beide Intervalle benutzt werden.
> Der folgende Schritt aus 2) kann übersprungen werden, insofern der Taschenrechner über Betragsstriche verfügt, welche ein mögliches negatives Vorzeichen positiv machen.

Anschließend der Intervallbildung wird überprüft, welche der beiden Funktionen größer ist als die andere. Dies wird gemacht, um ausschließlich positive Flächeninhalte bei der Integralrechnung zu erhalten. Dies werde ich hier mit der Differenzfunktion $d(x)=g(x)-f(x)$ machen, da diese hier fest definiert ist und mit dieser ebenfalls weitergearbeitet werden kann.
$$
\begin{align}
	&\textbf{Vorzeichen von }d(x)\textbf{ auf }\left[-3,\overline{3};2\right]\text{:}\\
	d(x)&=0,3x^3-0,8x^2-3,6x+8\\
	d(0)&=8>0\\
	&\textit{weil }d(0)>0\textit{, so nach Definition:}\\
	&\forall x\in\left[-3,\overline{3};2\right],g(x)\ge f(x)\\
	\\ \\
	&\textbf{Vorzeichen von }d(x)\textbf{ auf }\left[2;4\right]\text{:}\\
	d(x)&=0,3x^3-0,8x^2-3,6x+8\\
	d(3)&=-1,9<0\\
	&\textit{weil }d(3)<0\textit{, so nach Definition:}\\
	&\forall x\in\left[2;4\right],g(x)\le f(x)
\end{align}
$$

Die Verwendung der Begründung liegt hier zufolge, da:
*für alle x in dem Intervall gilt, dass $g(x)$ gleich oder größer/kleiner als $f(x)$ ist.*
Die Beweisführung ist hier durch die folgende Aufstellung definiert:
$$
\begin{align}
	0&\gtrless d(q)\\
	0&\gtrless g(q)-f(q)&&\mid+f(q)\\
	f(q)&\gtrless g(q)
\end{align}

$$

#### Aufstellen der Intervalle
Mit den bestimmten Vorzeichen von $d(x)=g(x)-f(x)$ in allen Intervallen können nun die Integrale aufgestellt werden. grundsätzlich werden alle Intervalle als jeweilige Integralgrenzen verwendet und addiert. Da hier nun allerdings das Intervall $\left[2;4\right]$ von $d(x)$ negativ ist, muss das Integral dieses Intervalls subtrahiert werden, damit dieses dadurch einer Addition des Integrals gerecht wird.
$$
\textcolor{gray}{\int^{x_3}_{x_2}-d(x)~dx=-\int^{x_3}_{x_2}d(x)~dx}
$$
$\left[-3,\overline{3};2\right],~~\left[2;4\right]$. 

$$
\begin{align}
	\textcolor{green}{+\int^{x_2}_{x_1}d(x)~dx}\textcolor{red}{-\int^{x_3}_{x_2}d(x)~dx}
	&=
	\int^{2}_{-\frac{10}{3}}0,3x^3-0,8x^2-3,6x+8~dx\\
	&\qquad-\int^{4}_{2}0,3x^3-0,8x^2-3,6x+8~dx\\
	&=\left[
		\frac{0,3}{4}x^4-\frac{0,8}{3}x^3-\frac{3,6}{2}x^2+8x
	\right]^{2}_{-\frac{10}{3}}\\
	&\qquad-\left[
		\frac{0,3}{4}x^4-\frac{0,8}{3}x^3-\frac{3,6}{2}x^2+8x
	\right]^{4}_{2}\\
	
	&~~\vdots\\
	&=\frac{15362}{405}\left[\textbf{FE}\right]\approx37,93\left[\textbf{FE}\right]​
\end{align}
$$

Für Taschenrechner mit Beträgen kann dieses Aufteilen erspart werden, da dieser Ausdruck $\textcolor{green}{+\int^{x_2}_{x_1}d(x)~dx}\textcolor{red}{-\int^{x_3}_{x_2}d(x)~dx}$ durch den folgenden ausgedrückt werden kann:
$$
\textcolor{green}{+\int^{x_2}_{x_1}d(x)~dx}\textcolor{red}{-\int^{x_3}_{x_2}d(x)~dx}=\int^{x_3}_{x_1}\left|d(x)\right|~dx
$$
Der Eingeschlossene Flächeninhalt zwischen den Funktionen $f$ und $g$ ist hier also ungefähr $37,93 \left[\text{FE}\right]$.

---
## Genereller Flächeninhalt
Für einen generellen Flächeninhalt werden üblicherweise Grenzen vordefiniert. Beispielsweise soll der Flächeninhalt zwischen $f(x)$ und $g(x)$ in dem Intervall von $\left[\textcolor{orange}a;\textcolor{orange}b\right]$ untersucht werden.
Identisch zu dem **eingeschlossenem Flächeninhalt** wird untersucht, wo Schnittstellen der beiden Funktionen liegen. Der Ablauf hier ist außer die geänderten Grenzen übertragbar.

Beispielsweise seien Schnittstellen wie folgt,  wobei die Intervallgrenzen wie folgt zu diesen Stehen:
$$
x_1<\textcolor{orange}a<x_2<\textcolor{orange}b
$$
Weil das Intervall für den Flächeninhalt über die Nullstelle $x_2$ geht, muss überprüft werden, welche Funktion in diesen größer oder kleiner ist.
>Gebildet werden folglich $\left[\textcolor{orange}a;x_2\right]$ und $\left[x_2;\textcolor{orange}b\right]$.

---