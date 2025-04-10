# Analysis
> Die Temperaturveränderung eines Topfes kann mit der Funktionenschar $t_a(x)=\left(-\frac{16}{5a}x^2+\frac{16}{5}x\right)\cdot e^{-0,2x}$ für $a\ge10$ dargestellt werden. Mittels eines Drehknopfes kann der Topf kurzzeitig, oder Langzeitig aufgeheizt werden. Die Einheit von $t_a(x)$ ist $\left[\frac{\textdegree C}{min}\right]$ (Grad Celsius pro Minute). $x$ gibt die Zeit in Minuten nach Einschalten des Heizmechanismus an an.
> Der Raum (und somit der Topf zu Beginn auch), hat eine Temperatur von $20\textdegree C$.

> Abb. 1: $f_{10}(x)$
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [0,25,-10,10]
disableZoom: true
grid: true
---
f(x)=(-(16/50)x^2+(16/5)*x)*exp(-0.2x)
```

## Aufgabe 1
### a)
> Erklären Sie, wieso $t_a(x)$ nicht mehr als $2$ Nullstellen haben kann. Bestimmen Sie zusätzlich die Punkte $P_{1;2}$, die die Nullstellen sind.

### b)
> Zeigen Sie, dass die Extrema von $t_{10}(x)$ einen $x$ Abstand von $10\sqrt{2}$ haben.

### c)
> Bestimmen Sie den Zeitpunkt der stärksten Temperaturveränderung, und zeichnen Sie diese in Abb. 1 ein. Geben Sie die Tangentengleichung dieser Stelle zu $t_{10}(x)$ an.

### d)
> Überprüfen Sie, ob $T_a(x)=\left(\frac{16}{a}x^{2}+\frac{160-16a}{a}x+\frac{800-80a}{a}\right)\cdot e^{-0,2x}+\frac{100a-800}{a}$ eine Stammfunktion ist, die den Sachverhalt optimal darstellt.

### e)
> Für $\lim_{a\to\infty}~t_a(x)=\frac{16}{5}x\cdot e^{-0,2x}$. Bestätigen Sie diese Aussage anhand des Funktionsterms.
> Bestimmen Sie die Wertemenge der Endtemperaturen für $\lim_{x\to\infty}$ des Topfes unter allen möglichen $a$. Nutzen Sie $T_a(x)$ aus Aufgabe d).

---