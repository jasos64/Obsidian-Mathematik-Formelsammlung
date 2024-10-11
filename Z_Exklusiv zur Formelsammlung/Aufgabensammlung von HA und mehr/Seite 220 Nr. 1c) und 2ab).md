## 1
> Bei einem Bernoulli-Versuch wird ein Signifikanztest mit Stichprobenumfang $n$ durchgeführt ([[Ungeordnetes ziehen mit zurücklegen (Bernoulli)]]). Bestimmen Sie den Verwerfungsbereich und die Irrtumswahrscheinlichkeit für $\alpha=5\%$ und $\alpha=1\%$.

---
### c)
$$H_0:p=\frac{2}{3};\quad n=50$$
Für $\alpha=5\%$ gilt:
	Linke Seite: $P(X\le g_1)\le 0,025$
	Rechte Seite: $P(X\ge g_2)\le 0,025$

>Aufstellung des linken kritischen Wertes:
$$
\begin{align}
	P(X\le g_1)&\le 0,025&&\mid\boxed{\text{Menü},~7~,\downarrow,~1,~1,26,=,50,\frac{2}{3}}\\
	P(X\le 26)&\approx 0,0222\le0,025
\end{align}
$$

$V_l$ ist also $\left[0;26\right]$.

>Aufstellung des rechten kritischen Wertes:

$$
\begin{align}
	P(X\ge g_2)&\le 0,025\\
	1-P(X\le g_2-1)&\le 0,025&&\mid -1\quad \mid\cdot(-1)\\
	P(X\le g_2-1)&\ge 0,975
\end{align}
$$
Der Taschenrechner gibt für $k=40$ den kleinsten Wert an, somit ist $V_r=\left[41;50\right]$.
Daraus ergibt sich für den Verwerfungsbereich $V=\left[0;26\right]\cup\left[41;50\right]$.

---
---
Für $\alpha=1\%$ gilt:
	Linke Seite: $P(X\le g_1)\le 0,005$
	Rechte Seite: $P(X\ge g_2)\le 0,005$

>Aufstellung des linken kritischen Wertes:
$$
\begin{align}
	P(X\le g_1)&\le 0,005&&\mid\boxed{\text{Menü},~7~,\downarrow,~1,~1,24,=,50,\frac{2}{3}}\\
	P(X\le 24)&\approx 0,00492\le0,005
\end{align}
$$

$V_l$ ist also $\left[0;24\right]$.

>Aufstellung des rechten kritischen Wertes:

$$
\begin{align}
	P(X\ge g_2)&\le 0,005\\
	1-P(X\le g_2-1)&\le 0,005&&\mid -1\quad \mid\cdot(-1)\\
	P(X\le g_2-1)&\ge 0,995
\end{align}
$$
Der Taschenrechner gibt für $k=42$ den kleinsten Wert an, somit ist $V_r=\left[43;50\right]$.
Daraus ergibt sich für den Verwerfungsbereich $V=\left[0;24\right]\cup\left[43;50\right]$.

---
---
---
## 2
> Laura behauptet, dass Lukas mit seinem gezinkten Würfel würfelt, der nicht die zu erwartende Anzahl Sechsen würfelt. Um die Behauptung zu testen, wirft sie Lukas' Würfel $n$-mal. Wie ist beim Signifikanzniveau $5\%$ zu entscheiden, wenn dabei $k$ Sechsen fallen?

### a)
Gegeben ist $n=25$ und $k=6$.
$X:Anzahl~~ 6$.
Daraus folgen die Hypothesen:
$$
\begin{align}
	H_0:p&=\frac{1}{6}\\
	H_1:p&\ne\frac{1}{6}
\end{align}
$$

Für $\alpha=5\%$ gilt:
	Linke Seite: $P(X\le g_1)\le 0,025$
	Rechte Seite: $P(X\ge g_2)\le 0,025$

>Aufstellung des linken kritischen Wertes:

$$
\begin{align}
	P(X\le g_1)&\le 0,025&&\mid\boxed{\text{Taschenrechner}}\\
	P(X\le 0)\approx 0,0105&\le 0,025\\\\
	g_1&=0
\end{align}
$$
Daraus folgt für den linken Verwerfungsbereich $V_l=\left[0\right]$.

>Aufstellung des rechten kritischen Wertes:

$$
\begin{align}
	P(X\ge g_2)&\le 0,025\\
	1-P(X\le g_2-1)&\le 0,025&&\mid -1~\quad\mid \cdot(-1)\\
	P(X\le g_2-1)&\ge 0,975&&\mid\boxed{\text{Taschenrechner}}\\
	P(X\le 8)\approx 0,984&\ge 0,975\\\\
	g_2&=9
\end{align}
$$
Daraus folgt für den rechten Verwerfungsbereich $V_r=\left[9;25\right]$.
Ein Würfel heißt gezinkt, sobald dieser nach $25$ würfen ein Element aus $V=\left[0\right]\cup\left[9;25\right]$ als Anzahl an $6$-en ergibt.
Mit $k=6$ gilt $k\notin V$, wodurch dieser Würfel nach $\alpha=5\%$ nicht gezinkt ist.

---
### b)
Gegeben ist $n=50$ und $k=12$.
$X:Anzahl~~ 6$.
Daraus folgen die Hypothesen:
$$
\begin{align}
	H_0:p&=\frac{1}{6}\\
	H_1:p&\ne\frac{1}{6}
\end{align}
$$

Für $\alpha=5\%$ gilt:
	Linke Seite: $P(X\le g_1)\le 0,025$
	Rechte Seite: $P(X\ge g_2)\le 0,025$

>Aufstellung des linken kritischen Wertes:

$$
\begin{align}
	P(X\le g_1)&\le 0,025&&\mid\boxed{\text{Taschenrechner}}\\
	P(X\le 3)\approx 0,0238&\le 0,025\\\\
	g_1&=3
\end{align}
$$
Daraus folgt für den linken Verwerfungsbereich $V_l=\left[0;3\right]$.

>Aufstellung des rechten kritischen Wertes:

$$
\begin{align}
	P(X\ge g_2)&\le 0,025\\
	1-P(X\le g_2-1)&\le 0,025&&\mid -1~\quad\mid \cdot(-1)\\
	P(X\le g_2-1)&\ge 0,975&&\mid\boxed{\text{Taschenrechner}}\\
	P(X\le 14)\approx 0,986&\ge 0,975\\\\
	g_2&=15
\end{align}
$$
Daraus folgt für den rechten Verwerfungsbereich $V_r=\left[15;50\right]$.
Ein Würfel heißt gezinkt, sobald dieser nach $50$ würfen ein Element aus $V=\left[0;3\right]\cup\left[15;50\right]$ als Anzahl an $6$-en ergibt.
Mit $k=12$ gilt $k\notin V$, wodurch dieser Würfel nach $\alpha=5\%$ nicht gezinkt ist.

---