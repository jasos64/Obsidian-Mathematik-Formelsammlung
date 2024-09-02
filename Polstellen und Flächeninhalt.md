## Aufstellen von Bedinungen
Eine Funktion $f:\mathbb{R}\backslash\{p\}\to\mathbb{R},~x\mapsto f(x)$ besitzt eine Polstelle $k$-ter Ordnung bei $x=p$.
Es gilt:
$$\lim_{x\to p}~f(x)=\infty$$
$$\lim_{x\to p}~(x-p)^k\cdot f(x)\neq0$$

Generell soll eventuell gezeigt werden, dass für (alle) solche $f$ ein Flächeninhalt nahe der Stelle $p$ gegen unendlich läuft.
**Versuch zu zeigen**:
$$
\lim_{c\to p}~\int^{c}_{}f(x)~dx\to\infty
$$

---
## Verschiebungen
Eine Fläche wird zwischen $f$ und der $x$-Achse beschrieben. Diese geht von einer beliebigen Stelle $a\neq p$ mit Grenzwert gegen $p$. Die Fläche lautet somit:
$$
A=\lim_{c\to p}~\int^{c}_{a}f(x)~dx
$$

Die nächsten Schritte werden sein, $f$ zu transformieren und den Limes gegen unendlich laufen zu lassen, damit eine Divergenz der Fläche gezeigt werden kann.
Hierfür wird $f$ zunächst um $p$ Stellen verschoben, sodass der Grenzwert $p=0$ wird.
$\lim_{c\to p}~\int^{c-p}_{a-p}f(x+p)~dx$ beschreibt dies, da: $\lim_{c\to p}c-p=0$ und $f(x+p)$ beim Einsetzen von $0$ dazu führt, dass die Polstelle "erreicht" ist.

Es wird die Umkehrfunktion von $f(x+p)$ gesucht.

---
## Definition der Umkehrfunktion
$f$ besitzt eine Umkehrfunktion $f^{-1}(x)$, durch welche gilt $I:~~f^{-1}\left(f(x)\right)=x$.
Es ist bekannt, dass $f(x+p)=y$. Eine Umkehrfunktion von $f$ muss somit durch anwenden von $I$ $x+p=f^{-1}(y)$ lauten.
Es gilt nach Umstellen: $x=f^{-1}(y)-p$.
Durch Rücksubstitution in $I$ ergibt sich das folgende:
$$
\begin{align}
	f^{-1}\left(f(x)\right)&=x
		&&\mid\boxed{\text{Einsetzen von }f(x)}\\
	f^{-1}\left(f(x+p)\right)&=x
		&&\mid\boxed{\text{Einsetzen in }f^{-1}(x)}\\
	f^{-1}\left(f(x+p)\right)-p&=x\\
	x+p-p&=x\\
	x&=x\\
\end{align}
$$
$g(x)=f^{-1}(x)-p$ ist somit eine Umkehrfunktion von $f(x+p)$.

---
## Anwenden der Umkehrfunktion für den Flächeninhalt
Nachdem eine Umkehrfunktion jetzt gegeben ist, welche für alle $f$ verwendet werden kann, wird die Umkehrfunktion verwendet um die Polstelle von $x\to y$ und $y\to x$ zu projizieren. Die Fläche, welche sich vorher gegen $0$ annähert, läuft hier gegen $\infty$.
$$
\begin{align}
	\lim_{c\to p}~\int^{c-p}_{a-p}f(x+p)~dx&\to
		\lim_{c\to \infty}~\int^{c}_{x_i}\left(f^{-1}(x)-p\right)~dx+x_i\cdot\left(f^{-1}(x_i)-p\right)
\end{align}
$$
Anzumerken ist, dass $x_i\coloneqq f^{-1}(x)-p=a$.
Außerdem ist anzumerken, dass eine Funktion wie die folgende nicht vollständig durch diesen Ausdruck bestimmt werden kann, da nur der markierte Bereich verwendet wird:
Sei $h(x)=\frac{x^{2}-x}{x-2}$. Gezeigt ist $h(x+2)$ in rot:
<iframe src="https://www.desmos.com/calculator/lldqdqtseq?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>
Nun in blau ist gezeigt, wie die Fläche aussieht, die diese in rot ersetzen sollte:
<iframe src="https://www.desmos.com/calculator/v9s7xj7ie4?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

Erkennbar ist, dass die Umkehrfunktion von $h$ keine Funktion ist, was dazu führt, dass es zwei mögliche Flächeninhalte gibt, welche durch das Produkt $x_i\cdot\left(f^{-1}(x_i)-p\right)$ erzeugt werden. Hier die Fläche rechts von dem orangenen Flächeninhalt ist die, die aus dem Integral zuvor entsteht.
>Da die beiden Flächen hier beide endlich sind, so sind diese für die Divergenzuntersuchung uninteressant. Es muss nur das Integral einen unendlichen Flächeninhalt besitzen, damit die gesamte Fläche ungegeben heißt.

---
## Grenzwert des Integrals
Nach den zuvor beschriebenen Aspekten reduziert sich der Grenzwert zu dem folgendem:
$$\lim_{c\to \infty}~\int^{c}_{x_i}\left(f^{-1}(x)-p\right)~dx;\quad x_i\coloneqq f^{-1}(x)-p=a$$

$$
\begin{align}
	\lim_{c\to \infty}~\int^{c}_{x_i}\left(f^{-1}(x)-p\right)~dx&=
		\lim_{c\to \infty}~\left(\int^{c}_{x_i}f^{-1}(x)~dx-\int^{c}_{x_i}p~dx\right)\\
	&=\lim_{c\to \infty}~\left(\int^{c}_{x_i}f^{-1}(x)~dx
		-\bigg[px\bigg]^c_{x_i}\right)\\
	&=\lim_{c\to \infty}~\left(\int^{c}_{x_i}f^{-1}(x)~dx
		-\left(pc-px_i\right)\right)\\
	&=\lim_{c\to \infty}~\left(\int^{c}_{x_i}f^{-1}(x)~dx
		-pc+px_i\right)\\
\end{align}
$$

WIP