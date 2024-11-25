
## Aufgabe 2: Analysis
In einer Nährlösung wird eine Bakterienkultur angelegt. Der Wachstumsprozess dieser Bakterienkultur wird untersucht. Die Funktion $\omega$ mit
$$\omega(t)=\left( -0,02t^{2}+4t\right)\cdot e^{-0.01t}$$
modelliert für $t\geq0$ die Wachstumsrate der Bakterienzahl. Dabei ist $t$ die Zeit in Minuten, die seit dem Anlegen der Bakterienkultur vergangen ist. Die Wachstumsrate $\omega(t)$ wird in der Einheit Anzahl pro Minute ($\frac{1}{\text{min}}$) angegeben.

```functionplot
---
title: 
xLabel: t
yLabel: y
bounds: [0,400,-40,120]
disableZoom: true
grid: true
---
f(x)=(-0.02x^2+4x)exp(-0.01x)
```

### a)
a1)
Die Stellen $t=0$ und $t=200$ sind Nullstellen der Funktion $\omega$.
Begründen Sie anhand des Funktionsterms, dass $\omega$ keine weiteren Nullstellen hat.
(2 P)

---
a2)
Berechnen Sie die Wachstumsrate der Bakterienanzahl $20$ Minuten nach Anlegen der Bakterienkultur.
(2 P)

---
a3)
Weisen Sie nach, dass die zeitliche Dauer, in der die Wachstumsrate größer als $80\frac{1}{\text{min}}$, größer als $55$ Minuten ist.
(4 P)

---
a4)
Berechnen Sie die durchschnittliche Wachstumsrate innerhalb der ersten zwei Stunden nach Anlegen der Bakterienkultur.
(3 P)

---
a5)
Zu einem Zeitpunkt $t_0$ liegt eine bestimmte Wachstumsrate vor. $10$ Minuten vorher ist die Wachstumsrate nur halb so groß.
Geben Sie eine Gleichung an, mit deren Hilfe man $t_0$ bestimmen könnte.
(2 P)

---
a6)
Der Graph von $\omega$ besitzt im Intervall $\left[ 0; 200\right]$ einen Wendepunkt.
Markieren Sie die ungefähre Position des Wendepunkts auf dem Graphen von $\omega$ in der Abbildung und geben Sie die Bedeutung der Wendestelle im Sachzusammenhang an.
(3 P)

---
### b)
Die ersten beiden Ableitungsfunktionen der Funktion $\omega$ besitzen die folgenden Funktionsterme:
$$
\begin{align}
\omega'(t)&=(0,0002t^{2}-0,08t+4)\cdot e^{-0,01t}\\
\omega''(t)&=\left(0,000002\cdot (t-300)^2+0,06\right)\cdot e^{-0,01t}
\end{align}$$

---
b1)
Innerhalb der ersten beiden Stunden nach Anlegen der Bakterienkultur erreicht die Wachstumsrate ihren Maximalwert. Berechnen Sie diesen.
(5 P)

---
b2)
Begründen Sie anhand des Funktionsterms von $\omega''$: Es gibt ein Intervall $\left[t_1;t_2\right]$, in dem die Stelle $300$ liegt und in dem $\omega''>0$ für alle $t\in \left[ t_1;t_2\right]$ gilt.
(4 P)

---
### c)
c1)
Weisen Sie nach, dass die Funktion $W$ mit
$$W(t)=2t^{2}\cdot e^{-0,01t}$$
eine Stammfunktion von $\omega$ ist.
(2 P)

---
c2)
Zeigen Sie, dass der Grenzwert von $\int^{b}_{0}\omega(t)~dt$ für $b\to \infty$ Null ist und erläutern Sie, was dieser Grenzwert im Modell in Bezug auf den Wachstumsprozess der Bakterienkultur bedeuten würde.
(4 P)

---
### d)
Im Verlauf des Wachstumsprozesses wächst die Bakterienanzahl zunächst an, erreicht dann einen Maximalwert und sinkt danach wieder ab. Je nach Umgebungstemperatur wird ein höherer oder niedrigerer Maximalwert erreicht.
Die Schar der Funktionen $W_k$ mit
$$W_{k}(t)=2k\cdot t^{2}\cdot e^{-0,01k\cdot t}+10000 \qquad\text{und}\qquad t\geq0$$
modelliert für $k>0$ die Bakterienanzahl für unterschiedliche Umgebungstemperaturen.

---
d1)
Begründen Sie, dass die Funktionen $W_k$ weder für $k=0$ noch für $k<0$ einen Wachstumsprozess mit dem beschriebenen Verlauf modellieren.
(3 P)

---
d2)
Untersuchen Sie, welche Werte von $k$ mit $k>0$ geeignet sind, einen Wachstumsprozess zu modellieren, bei dem eine maximale Bakterienanzahl von mehr als $20000$ Bakterien erreicht wird.
(6 P)

---