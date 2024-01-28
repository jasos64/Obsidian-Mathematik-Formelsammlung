Mit der Polynomdivision kann eine [[Funktion(en)]], von welcher eine Nullstelle gegeben ist, eine weitere Funktion gebildet werden, welche alle [[Nullstellen]] wie davor, außer die gegebene, enthält.
Als Beispiel nehme man $f\left(x\right)=x^{3}-2x^{2}+1$ mit der Nullstelle $x_1=1$.
$$ \begin{aligned}
f(x)&=x^{3}-2x^{2}+1&\text{(blau)}\\
g(x)&=x^{2}-x-1&\text{(rot)}
\end{aligned} $$

```functionplot
---
title: 
xLabel: x
yLabel: y
bounds: [-1,2,-1,2]
disableZoom: true
grid: true
---
f(x)=x^3-2x^2+1
g(x)&=x^2-x-1
```
## Vorbereitung
Eine ganzrationale Funktion muss mit einer Nullstelle gegeben sein. Diese kann man sonst mittels des [[Newtonverfahren]] oder durch raten bestimmen.
Die Funktion wird zunächst nach ansteigende Exponentzahl sortiert und anschließend mit der Nullstelle dividiert.
$$f(x)\divsymbol (x-x_1)=$$

---
## Division
Der folgende Ablauf wiederholt sich so oft, bis 0 als Rest übrig bleibt:
>Das erste Polynom wird durch $x$ geteilt und rechts neben das $=$ geschrieben

Hier als Beispiel:
$$\begin{align}
x^3-2x^2+1\divsymbol(x-1)&=\frac{x^3}{x}\\
x^3-2x^2+1\divsymbol(x-1)&=x^2
\end{align}$$

---
>Das neu hinzugefügte Polynom hinter dem $=$ wird mit der Nullstelle $(x-1)$ multipliziert und unter die passenden Polynome der Funktion geschrieben

$$\begin{align}
&x^{2}\cdot(x-1)=x^{3}-x^2\\
\\
&x^3-2x^2+1\divsymbol(x-1)=x^{3}-x^2\\
&x^3-x^2
\end{align}$$

---
>Das multiplizierte wird mit dem oberen Subtrahiert addiert und darunter hingeschrieben

$$\begin{align}
&x^3-2x^2+1\divsymbol(x-1)=x^{3}-x^2\\
-(&x^3-x^2)\quad\downarrow\\
&\text{----------}\quad\downarrow\\
&0~-~x~+~1
\end{align}$$

---
## Ergebnis
Führt man diese Schritte nun fort, so bildet sich als neue Funktion $g(x)=x^2-x-1$, von welcher man nun Nullstellen einfacher finden kann.

---