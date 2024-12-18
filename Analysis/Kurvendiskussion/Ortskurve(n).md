> Eine Ortskurve gibt eine [Funktion](Funktion(en)) an, auf der ein signifikanter Punkt einer [Funktionsschar](Funktionsschar(en)) entlangläuft.

Gegeben sei die Funktionsschar $f_k(x)=0,2x^2-2kx+5k$, für $\{k;x\}\in\mathbb{R}$. Die Ortskurve soll den Extrempunkt beschreiben.

---
## Schritt 1: Herausarbeiten
Da eine Ortskurve mehrere Dinge darstellen kann, so ist es wichtig diese Information aus der Aufgabenstellung herauszuarbeiten. Hier ist nach der Ortskurve des Extrempunktes gesucht.

---
## Schritt 2: Herausarbeiten des notwendigen Kriteriums
Meistens sollen signifikante Punkte einer Funktion dargestellt werden. Hierzu werden diese Stellen berechnet.

Von oben gilt:
- $f_k(x)=0,2x^2-2kx+5k$
- $f'_k(x)=0,4x-2k$
Die Bedingung ist, dass an einer Stelle die Ableitung $f'_k(x)$ Null ist. Es ist also:
$$
\begin{align}
	0&=f'_k(x)\\
	0&=0,4x-2k&&\mid+2k\\
	2k&=0,4x&&\mid \cdot 2,5\\
	x&=5k
\end{align}
$$

Da jede Extremstelle von $f_k$ bei $x=5k$ ist, so lautet der Extrempunkt $E\left(5k\mid f_k(5k)\right)$.
$$
\begin{align}
	f_k(5k)&=0,2(5k)^2-2k\cdot5k+5k\\
	&=5k^2-10k^2+5k\\
	&=-5k^2+5k
\end{align}
$$
Somit ist jeder Extrempunkt $E\left(5k\mid -5k^2+5k\right)$.

---
## Schritt 3: Umwandlung auf $x$
Da die Extrempunkte aktuell mittels des Scharparameters $k$ definiert sind, so müssen wir diese zu $x$ ändern. Da zuvor der Zusammenhang $x=5k$ geschlossen wurde, wandeln wir diese Gleichung zu $k=0,2x$ um, um dieses schlussendlich einzusetzen.
$$
\begin{align}
	&E\left(5k\mid -5k^2+5k\right)\\
	&E\left(5\cdot0,2x\mid -5(0,2x)^2+5\cdot(0,2x)\right)\\
	&E\left(x\mid -0,2x^2+x\right)
\end{align}
$$
Hierdurch lautet die Ortskurve schlussendlich:
$o_e(x)=-0,2x^2+x$.


```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-2,8,-4,4]
disableZoom: true
grid: true
---
f1(x)=0.2x^2-2*0.5x+5*0.5
f2(x)=0.2x^2-2*0.2x+5*0.2
f3(x)=0.2x^2-2*1x+5*1
f4(x)=0.2x^2-2*1.5x+5*1.5
f4(x)=0.2x^2-2*1.25x+5*1.25
g(x)=-0.2x^2+x
```

Der letzte Schritt kann alternativ übersprungen werden, indem nach der Ausarbeitung des notwendigen Kriteriums nach $k$ umgestellt wird, und dieses in $f_k(x)$ eingesetzt wird:
$$
\begin{align}
	f_{0,2x}(x)&=0,2x^2-2\cdot0,2x\cdot x+5\cdot0,2x\\
	&=0,2x^2-0,4x^2+x\\
	&=-0,2x^2+x
\end{align}
$$

---