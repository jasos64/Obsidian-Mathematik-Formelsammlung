Um Stellen zu finden, bei welcher sich zwei [[Funktion(en)]] schneiden/berühren, so werden diese zunächst subtrahiert und anschließend nach [[Nullstellen]] untersucht.
Dies wird gemacht, da die Differenz von (zum Beispiel) $f(x)$ zu $g(x)$ an Stellen, wo diese sich berühren $=0$ ist.
Hierbei handelt es sich um eine Termumformung von:
$$ \begin{aligned}
f(x)&=g(x)&|-f(x)\\
0&=g(x)-f(x)
\end{aligned} $$

Gegeben seien folgende Funktionen:
$$ \begin{aligned}
f(x)&=x^{2}-2x&\text{(blau)}\\
g(x)&=x+1&\text{(rot)}
\end{aligned} $$
```functionplot
---
title:
xLabel: x
yLabel: y
bounds: [-2, 5, -2, 9]
disbaleZoom: true
grid: true
---
f(x)=x^2-2x
g(x)=x+4
h(x)=x^2-3x-4
```
Wenn man nun $f$ und $g$ subtrahiert, so erhält man eine Funktion mit Nullstellen bei Schnittpunkten. $$ \begin{aligned}
d(x)&=g(x)-f(x)\\
&=(x+1)-(x^{2}-2x)\\
&=x^{2}-3x-4&\text{(grün)}
\end{aligned} $$
$d(x)$ kann nun nach [[Nullstellen]] untersucht werden. Diese wären in diesem Fall $x_1=-1\vee x_2=4$.
Da zusätzlich Punkte gegebenenfalls gesucht werden, bei denen dies der Fall ist, so muss man zunächst die erhaltenen Stellen in eine der Funktionen einsetzen. Da die Funktionen an den Stellen den gleichen Wert haben ist es egal ob es hier $f(x)$ oder $g(x)$ ist.
Generalisiert dargestellt lauten Schnittpunkte folgendermaßen:
$$\begin{aligned}
P_1(x_1&|f(x_1))~~~~~~~=&P_1(x_1&|g(x_1))\\
P_2(x_2&|f(x_2))~~~~~~~=&P_2(x_2&|g(x_2))\\
&\vdots&\vdots\\
P_n(x_n&|f(x_n))~~~~~~~=&P_n(x_n&|g(x_n))\\
\end{aligned} $$

---