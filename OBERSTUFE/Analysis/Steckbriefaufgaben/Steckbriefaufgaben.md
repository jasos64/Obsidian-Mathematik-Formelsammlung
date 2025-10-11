> Steckbriefaufgaben beschreiben Aufgaben, in denen eine [[Funktion(en)]] unter gegebenen Voraussetzungen gebildet werden soll. Meist soll hierbei eine Funktion durch bestimmte Punkte gehen, oder [[Lokale Extrema]] an konkreten Stellen besitzen. [[Wendestellen-Wendepunkte]] fallen ebenfalls in diese Liste möglicher Aufgaben.

Eine Beispielaufgabe könnte lauten:
> Die ganzrationale Funktion $2$-ten Grades $f(x)$ geht durch die Punkte $A(2\mid4)$ und $B(-1\mid3)$. Zusätzlich besitzt $f$ ein Extremum an der Stelle $x=0$. Bestimmen Sie alle möglichen Funktionen von $f$ an.

Nehmen wir die Beispielaufgabe als Fundament der weiteren Erklärung.

---
## Schritt 1: Bedingungen formulieren
Zuerst müssen die Bedingungen aus der Beschreibung ausgearbeitet werden. Es ist wichtig, alle diese zu identifizieren.
Abgelesen erkennen wir die $3$ Bedingungen
- $f(2)=4$
- $f(-1)=3$
- $f'(0)=0$
Ebenfalls muss die allgemeine Funktionsgleichung des gewünschten Grades angegeben werden, damit diese mit den Bedingungen verglichen werden kann:
- $f(x)=ax^2+bx+c$
- $f'(x)=2ax+b$
$f$ besitzt $3$ Parameter, dadurch gibt es eine oder keine Lösung für $f$.

---
## Schritt 2: [[LGS]] erstellen
Damit die Kombination der Werte der Parameter bestimmt werden kann, wird ein lineares Gleichungssystem erstellt, welches sich aus den Bedingungen aus Schritt 1 zusammensetzt.
> Hier lautet das LGS folglich:

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & f(2) & =&4\\
		\text{II:} & f(-1) & =&3\\
		\text{III:} & f'(0) & =&0
	\end{array}\\\\
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot2^2+b\cdot2+c & =&4\\
		\text{II:} & a\cdot(-1)^2+b\cdot(-1)+c & =&3\\
		\text{III:} & 2a\cdot0+b & =&0
	\end{array}\\\\
	&\begin{array}{r|rc|}
		\text{I:} & 4a+2b+c & =&4\\
		\text{II:} & a-b+c & =&3\\
		\text{III:} & b & =&0
	\end{array}
\end{align}
$$
Alternativ kann das LGS auch in der Matrizenform vorliegen:
$$
\begin{align}
\left(
	\begin{array}{ccc|c}
		4&2&1&4\\
		1&-1&1&3\\
		0&1&0&0
	\end{array}
\right)
\end{align}
$$

---
## Schritt 3: LGS lösen
Nachdem zuvor das LGS aufgestellt wurde, wird dieses anschließend gelöst, damit die gesuchten Werte herausgefunden werden können.
> Sollte sich rausstellen, dass ein unterbestimmtes LGS vorliegt, so muss ein Parameter in der Funktion bestehen bleiben, der die anderen Parameter bestimmt. $b=1-a$ oder $c=-4+0,25a$ beispielsweise.

Mit dem LGS von oben erhalten wir maximal eine Lösung, die hier lautet:
- $a=\frac{1}{3}$
- $b=0$
- $c=\frac{8}{3}$
Zum Schluss muss die Funktion noch angegeben werden. Somit lautet $f$:
$f(x)=\frac{1}{3}x^2+\frac{8}{3}$.

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-4,4,2,5]
disableZoom: true
grid: true
---
f(x)=((1)/(3))x*x + (8)/(3)
```

---