
# Aufgabe 1: Analysis
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
---
# Aufgabe 3: Analytische Geometrie
> Das Dach eines Sonnenschirmes besitzt die Eckpunkte $A(1,5\mid0\mid2)$, $B(1,5\mid3\mid2)$, $C(-1,5\mid3\mid2)$, $D(-1,5\mid0\mid2)$ und die Spitze $E(0\mid1.5\mid2,6)$. Der Boden wird durch die $x_1x_2$ modelliert. Eine Einheit entspricht $1~m$ in der Realität.

## a)
a1)
Zeigen Sie, dass es sich bei der Form $ABCD$ um ein Quadrat handelt

---
a2)
Bestimmen Sie den Flächeninhalt des Daches in $m^2$

---
## b)
> Es gibt eine Ebenengleichung, die die Form $ax_1+cx_3=d$ besitzt und durch die Punkte $A$, $B$ und $E$ aufgespannt wird.

b1)
Berechnen Sie Werte für $a>0$ und $c>0$, die die Bedingung erfüllt:
$E:~ax_1+cx_2=234$

(Zur Kontrolle: $E:~36x_1+270x_2=234$)

---
b2)
Berechnen Sie den Winkel zwischen dem Boden und der Ebene $E$.

---
b3)
Eine Kugelförmige Lampe wird an die Spitze mit einem Faden angehängt. Bestimmen Sie den Mittelpunkt der Lampe, sodass dieser einen Abstand von $0,5m$ zu den Deckenflächen besitzt.

---
## c)
c1)
> Sonnenstralen fallen zu bestimmten Zeiten wie moddeliert mit dem Parameter $0,25\le k\le0,5$. Die Sonnenstralen werden durch $$\vec{v_k}=\begin{pmatrix}0\\1\\-k\end{pmatrix}$$
dargestellt.

c1)
Die Sonnenstralen treffen den Punkt $B$. Dieser bildet einen Schattenpunkt $B_k$ auf dem Boden. Bestimmen Sie den Punkt $B_k$ unter Abhängigkeit von $k$.

---
c2)
Es gibt einen Wert, bei dem die Schattenform auf dem Boden ein Fünfeck ist. Erläutern Sie eine Möglichkeit, wie das kleinstmögliche k gefunden werde kann, dass die Schattenform gerade so ein Quadrat ist.

---
---
# Aufgabe 4: Analytische Geometrie

---
# Aufgabe 5: Stochastik
> Ein Limonadenabieter gibt an, dass $5\%$ aller Flaschen eine falsche Füllmenge besitzen. $1\%$ der Flaschen haben einen Fehldeuck beim Etikett. $0,1\%$ sind Flaschen, die sowohl einen Fehldruck besitzen, als auch eine falsche Füllmenge.

$F:\text{"Richtige Füllmenge"}$
$M:\text{"Richtige Markierung des Etikettes"}$

$$
\begin{array}{c|c|c|c}
& F&\overline{F}&\\\hline
M&&&\\\hline
\overline{M}&&&\\\hline
&&&1
\end{array}
$$

a1)
Füllen Sie die oben gegebene Vierfeldertafel aus

---
a2)
Eine Flasche mit falscher Füllmenge wird zufällig gezogen. Bestimmen Sie die Wahrscheinlichkeit, dass diese Flasche ebenfalls ein fehlerhaftes Etikett besitzt.

---
## b)
> Auf einem Tisch stehen Flaschen. In den Deckeln dieser Flaschen sind Lose angebracht, die von außen nicht erkennbar sind. Diese Lose zeigen entweder einen Gewinn, oder eine Niete.

b1)
Auf dem Tisch stehen $6$ Flaschen mit einem Gewinn und $9$ Flaschen mit einer Niete. Es werden zufällig vier Flaschen entnommen. Bestimmen Sie die Wahrscheinlichkeit, dass exakt zwei Flaschen ein Gewinnlos beinhalten.

---
b2)
Auf einem anderem Tisch stehen $7$ Flaschen mit einem Gewinnlos und weitere mit Nieten. Es werden zwei Flaschen entnommen. Bestimmen Sie die exakte Anzahl der Flaschen auf dem Tisch, sodass die Wahrscheinlichkeit, dass beide diese Flaschen ein Gewinnlos beinhalten exakt $10\%$ beträgt.

---
## c)
> Eine Füllmaschine für Limonadenflaschen wird von einem Arbeiter rekalibriert. Dieser gibt an, dass die Maschine nun zu $p<5\%$ die Füllmenge nicht einhält. Eine Stichprobengröße von $500$ Flaschen soll untersucht werden.

Erstellen Sie einen geeigneten Hypothesentest der die Aussage des Mitarbeiters mit dem Signifikanzniveau von $8\%$ unterstützt. Geben Sie die Hypothesen und die Bestimmungsregel an.

---