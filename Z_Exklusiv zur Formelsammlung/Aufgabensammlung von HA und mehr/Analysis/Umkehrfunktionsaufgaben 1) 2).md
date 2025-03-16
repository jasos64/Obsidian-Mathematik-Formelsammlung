# 1)
> Gegeben sind die beiden linearen Funktionen $f_1(x)=-2x+4$ und $f_2(x)=2x-3$.

## a)
> Zeichnen Sie beide Funktionsbilder ein!

```desmos-graph
	left=-4; right=5.5;
    top=5.5; bottom=-4;
    height=400; width=400
    ---
    f_1(x)=-2x+4|#2d70b3
    f_2(x)=2x-3|#388c46
    (0,4)|hidden|#2d70b3|label:`f_1(x)`
    (4,5)|hidden|#388c46|label:`f_2(x)`
```

## b)
> Bestimmen Sie rechnerisch die beiden Umkehrfunktionen!

Für $f_1(x)=-2x+4$ gilt:
$$
\begin{align}
	f_1(x)&=-2x+4\\
	y&=-2x+4&&\mid-4\\
	y-4&=-2x&&\mid\div(-2)\\
	x&=\frac{y-4}{-2}=-\frac{1}{2}y+2&&\mid (x;y)\to (y;x)\\
	y&=-\frac{1}{2}x+2\\
	\overline{f}_1(x)&=-\frac{1}{2}x+2
\end{align}
$$

Für $f_2(x)=2x-3$ gilt:
$$
\begin{align}
	f_2(x)&=2x-3\\
	y&=2x-3&&\mid+3\\
	y+3&=2x&&\mid\div2\\
	x&=\frac{y+3}{2}=\frac{1}{2}y+\frac{3}{2}&&\mid (x;y)\to (y;x)\\
	y&=\frac{1}{2}x+\frac{3}{2}\\
	\overline{f}_2(x)&=\frac{1}{2}x+\frac{3}{2}
\end{align}
$$

## c)
> Zeichnen Sie die Graphen der Umkehrfunktionen ein!

```desmos-graph
	left=-4; right=5.5;
    top=5.5; bottom=-4;
    height=400; width=400
    ---
    f_1(x)=-2x+4|#2d70b3
    g_1(x)=-0.5x+2|dashed|#2d70b3
    f_2(x)=2x-3|#388c46
    g_2(x)=0.5x+1.5|dashed|#388c46
    (0,4)|hidden|#2d70b3|label:`f_1(x)`
    (-1,2.5)|hidden|#2d70b3|label:`\overline{f}_1(x)`
    (4,5)|hidden|#388c46|label:`f_2(x)`
    (4,3.5)|hidden|#388c46|label:`\overline{f}_2(x)`
```

## d)
> Stellen Sie für die einander entsprechenden Funktionen und Umkehrfunktionen folgende Merkmale gegenüber: Definitionsbereich, Wertebereich, Achsenschnittpunkte und Monotonie!

Für $f_1(x)=-2+4$ und $\overline{f}_1(x)=0,5x+2$:
Der Definitionsbereich von $f_1(x)$ ist $D_{f_1}=\mathbb{R}$. Hierdurch ist der Wertebereich von $\overline{f}_1(x)$ ebenfalls $\mathbb{R}$. Wir erhalten $D_{f_1}=\mathbb{R}$ und $W_{\overline{f}_1}=\mathbb{R}$. Der Wertebereich von $f_1(x)$ ist $W_{f_1}=\mathbb{R}$. Hierdurch ist der Definitionsbereich von $\overline{f}_1(x)$ ebenfalls $\mathbb{R}$.
Allgemein erhalten wir:
- $D_{f_1}=\mathbb{R}$; $W_{f_1}=\mathbb{R}$
- $D_{\overline{f}_1}=\mathbb{R}$; $W_{\overline{f}_1}=\mathbb{R}$
($D_{f_1}=W_{\overline{f}_1}$ und $D_{\overline{f}_1}=W_{f_1}$)
Durch $\deg f_1(x)=1$ ist $f_1(x)$ bijektiv und $\overline{f}_1(x)$ wohldefinitert.

Die Achsenschnittpunkte sind für $f_1(x)$:
- $x$-Achse: $2$
- $y$-Achse: $4$
Die Achsenschnittpunkte sind für $\overline{f}_1(x)$:
- $x$-Achse: $4$
- $y$-Achse: $2$
Allgemein sind Nullstellen einer Funktion $f$ die $y$-Achsenschnittpunkte der Umkehrfunktion $\overline{f}$. Dies lässt sich durch die Umwandlung von $(x;y)\to (y;x)$ begründen. Eine Nullstelle ist an der Umkehrfunktion auf der $y$-Achse: $(n;0)\to (0;n)$.

Die Monotonie der Funktion $f_1(x)$ ist streng monoton fallend, wie $\overline{f}_1(x)$ auch (erkennbar durch die Funktionen und Graphen).

Annahmeweise ist eine lineare Funktion $g(x)$ streng monoton fallend, dann gilt: $g'(x)<0$. Für die Umkehrfunktion gilt dann: $\overline{g}'(x)=\frac{1}{g'(\overline{g}(x))}<0$, durch $g'(\overline{g}(x))<0$. Hierdurch ist gezeigt, dass jede streng monoton fallende Funktion in ihrer Umkehrfunktion ebenfalls streng monoton fallend sein muss.

---
Für $f_2(x)=2x-3$ und $\overline{f}_2(x)=0,5x+1,5$:
Der Definitionsbereich von $f_2(x)$ ist $D_{f_1}=\mathbb{R}$. Hierdurch ist der Wertebereich von $\overline{f}_2(x)$ ebenfalls $\mathbb{R}$. Wir erhalten $D_{f_2}=\mathbb{R}$ und $W_{\overline{f}_2}=\mathbb{R}$. Der Wertebereich von $f_2(x)$ ist $W_{f_2}=\mathbb{R}$. Hierdurch ist der Definitionsbereich von $\overline{f}_2(x)$ ebenfalls $\mathbb{R}$.
Allgemein erhalten wir:
- $D_{f_2}=\mathbb{R}$; $W_{f_2}=\mathbb{R}$
- $D_{\overline{f}_2}=\mathbb{R}$; $W_{\overline{f}_2}=\mathbb{R}$
($D_{f_2}=W_{\overline{f}_2}$ und $D_{\overline{f}_2}=W_{f_2}$)
Durch $\deg f_2(x)=1$ ist $f_2(x)$ bijektiv und $\overline{f}_2(x)$ wohldefinitert.

Die Achsenschnittpunkte sind für $f_2(x)$:
- $x$-Achse: $1,5$
- $y$-Achse: $-3$
Die Achsenschnittpunkte sind für $\overline{f}_2(x)$:
- $x$-Achse: $-3$
- $y$-Achse: $1,5$
Allgemein sind Nullstellen einer Funktion $f$ die $y$-Achsenschnittpunkte der Umkehrfunktion $\overline{f}$. Dies lässt sich durch die Umwandlung von $(x;y)\to (y;x)$ begründen. Eine Nullstelle ist an der Umkehrfunktion auf der $y$-Achse: $(n;0)\to (0;n)$.

Die Monotonie der Funktion $f_2(x)$ ist streng monoton steigend, wie $\overline{f}_2(x)$ auch (erkennbar durch die Funktionen und Graphen).
Annahmeweise ist eine lineare Funktion $g(x)$ streng monoton steigend, dann gilt: $g'(x)>0$. Für die Umkehrfunktion gilt dann: $\overline{g}'(x)=\frac{1}{g'(\overline{g}(x))}>0$, durch $g'(\overline{g}(x))>0$. Hierdurch ist gezeigt, dass jede streng monoton steigende Funktion in ihrer Umkehrfunktion ebenfalls streng monoton steigend sein muss.

---
---
# 2)
> Gegeben sind die quadratische Funktion $f_3(x)=(x+2)^2-3$ und die Wurzelfunktion $f_4(x)=\sqrt{4-x}-1$.

## a)
> Zeichnen Sie beide Funktionsbilder ein!

```desmos-graph
	left=-4; right=5.5;
    top=5.5; bottom=-4;
    height=400; width=400
    ---
    f_3(x)=(x+2)^2-3|#2d70b3
    f_4(x)=(4-x)^{0.5}-1|#388c46
    (0,4)|hidden|#2d70b3|label:`f_3(x)`
    (3,0)|hidden|#388c46|label:`f_4(x)`
```

## b)
> Bestimmen Sie rechnerisch die beiden Umkehrfunktionen!

Für $f_3(x)=(x+2)^2-3$ gilt:
$$
\begin{align}
	f_3(x)&=(x+2)^2-3\\
	y&=(x+2)^2-3&&\mid+3\\
	y+3&=(x+2)^2&&\mid\sqrt{}\\
	x+2&=\pm\sqrt{y+3}&&\mid-2\\
	x&=\pm\sqrt{y+3}-2&&\mid (x;y)\to (y;x)\\
	y&=\pm\sqrt{x+3}-2\\
	\overline{f}_3(x)&=\pm\sqrt{x+3}-2
\end{align}
$$

Für $f_4(x)=\sqrt{4-x}-1$ gilt:
$$
\begin{align}
	f_4(x)&=\sqrt{4-x}-1\\
	y&=\sqrt{4-x}-1&&\mid+1\\
	y+1&=\sqrt{4-x}&&\mid()^2\\
	4-x&=(y+1)^2&&\mid-4\\
	-x&=(y+1)^2-4&&\mid\cdot(-1)\\
	x&=-(y+1)^2+4&&\mid (x;y)\to (y;x)\\
	y&=-(x+1)^2+4\\
	\overline{f}_4(x)&=-(x+1)^2+4
\end{align}
$$

## c)
> Zeichnen Sie die Graphen der Umkehrfunktionen ein!

```desmos-graph
	left=-4; right=5.5;
    top=5.5; bottom=-4;
    height=400; width=400
    ---
    f_3(x)=(x+2)^2-3|#2d70b3
    g_{31}(x)=(x+3)^{0.5}-2|dashed|#2d70b3
    g_{32}(x)=-(x+3)^{0.5}-2|dotted|#2d70b3
    f_4(x)=(4-x)^{0.5}-1|#388c46
    g_4(x)=-(x+1)^2+4|x>=-1|dashed|#388c46
    (0,4)|hidden|#2d70b3|label:`f_3(x)`
    (3,0)|hidden|#388c46|label:`f_4(x)`
```

## d)
> Stellen Sie für die einander entsprechenden Funktionen und Umkehrfunktionen folgende Merkmale gegenüber: Definitionsbereich, Wertebereich, Achsenschnittpunkte und Monotonie!

Für $f_3(x)=(x+2)^2-3$ und $\overline{f}_3(x)=\pm\sqrt{x+3}-2$:
Der Definitionsbereich von $f_3(x)$ ist $D_{f_3}=\mathbb{R}$, mit dem Wertebereich $W_{f_3}=\{x\in\mathbb{R}\mid x\ge-3\}$. Hierdurch ist der Definitionsbereich von $\overline{f}_3(x)$ ebenfalls $\{x\in\mathbb{R}\mid x\ge-3\}$.
Da die Funktion $f_3$ nicht injektiv durch $\deg f_3(x)=2$ ist, muss der Definitionsbereich von $f_3(x)$ jeweils der Umkehrfunktion angepasst werden. Wir erhalten:
$$
\begin{align}
	D_{f_3}=W_{\overline{f}_3}&=
	\begin{cases}
		\{x\in\mathbb{R}\mid x\le-2\},&
			\text{wenn }\overline{f}_3(x)=-\sqrt{x+3}-2\\
		 \{x\in\mathbb{R}\mid x\ge-2\},&
			 \text{wenn }\overline{f}_3(x)=\sqrt{x+3}-2
	\end{cases}
\end{align}
$$

Allgemein erhalten wir:
- $D_{f_3}:\textit{Bedingung direkt oben}$; $W_{f_3}=\{x\in\mathbb{R}\mid x\ge-3\}$
- $D_{\overline{f}_3}=\{x\in\mathbb{R}\mid x\ge-3\}$; $W_{\overline{f}_3}:\textit{Bedingung direkt oben}$
($D_{f_1}=W_{\overline{f}_1}$ und $D_{\overline{f}_1}=W_{f_1}$)

Die Achsenschnittpunkte sind für $f_3(x)$:
- $x$-Achse: $-2\mp\sqrt{3}$. (Minus bei erster Bedingung vom Definitionsbereich $D_{f_3}$, plus bei zweiter Bedingung)
- $y$-Achse: $1$, wenn die zweite Bedingung vom Definitionsbereich gilt

Die Achsenschnittpunkte sind für $\overline{f}_1(x)$:
- $x$-Achse: $1$, wenn die zweite Bedingung vom Definitionsbereich gilt
- $y$-Achse: $-2\mp\sqrt{3}$. (Minus bei erster Bedingung vom Definitionsbereich $D_{f_3}$, plus bei zweiter Bedingung)

Allgemein sind Nullstellen einer Funktion $f$ die $y$-Achsenschnittpunkte der Umkehrfunktion $\overline{f}$. Dies lässt sich durch die Umwandlung von $(x;y)\to (y;x)$ begründen. Eine Nullstelle ist an der Umkehrfunktion auf der $y$-Achse: $(n;0)\to (0;n)$.

Die Monotonie der Funktion $f_3(x)$ ist streng monoton fallend, wenn die erste Bedingung gilt, und streng monoton steigend, wenn die zweite Bedingung gilt. Die Monotonie der Umkehrfunktion  orientiert sich identisch zu der Funktion $f_3(x)$.

Annahmeweise ist eine lineare Funktion $g(x)$ streng monoton fallend, dann gilt: $g'(x)<0$. Für die Umkehrfunktion gilt dann: $\overline{g}'(x)=\frac{1}{g'(\overline{g}(x))}<0$, durch $g'(\overline{g}(x))<0$. Hierdurch ist gezeigt, dass jede streng monoton fallende Funktion in ihrer Umkehrfunktion ebenfalls streng monoton fallend sein muss.

---
Für $f_4(x)=\sqrt{4-x}-1$ und $\overline{f}_4(x)=-(x+1)^2+4$:
Der Definitionsbereich von $f_4(x)$ ist $D_{f_4}=\{x\in\mathbb{R}\mid x\le4\}$, mit dem Wertebereich $W_{f_4}=\{x\in\mathbb{R}\mid x\ge-1\}$. Hierdurch ist der Definitionsbereich von $\overline{f}_4(x)$ ebenfalls $\{x\in\mathbb{R}\mid x\ge-1\}$.

Allgemein erhalten wir:
- $D_{f_4}=\{x\in\mathbb{R}\mid x\le4\}$; $W_{f_4}=\{x\in\mathbb{R}\mid x\ge-1\}$
- $D_{\overline{f}_4}=\{x\in\mathbb{R}\mid x\ge-1\}$; $W_{\overline{f}_4}=\{x\in\mathbb{R}\mid x\le4\}$
($D_{f_4}=W_{\overline{f}_4}$ und $D_{\overline{f}_4}=W_{f_4}$)

Die Achsenschnittpunkte sind für $f_4(x)$:
- $x$-Achse: $3$
- $y$-Achse: $1$
Die Achsenschnittpunkte sind für $\overline{f}_4(x)$:
- $x$-Achse: $1$
- $y$-Achse: $3$
Allgemein sind Nullstellen einer Funktion $f$ die $y$-Achsenschnittpunkte der Umkehrfunktion $\overline{f}$. Dies lässt sich durch die Umwandlung von $(x;y)\to (y;x)$ begründen. Eine Nullstelle ist an der Umkehrfunktion auf der $y$-Achse: $(n;0)\to (0;n)$.

Die Monotonie der Funktion $f_4(x)$ ist streng monoton fallend, wie $\overline{f}_4(x)$ auch (erkennbar durch die Funktionen und Graphen).

---