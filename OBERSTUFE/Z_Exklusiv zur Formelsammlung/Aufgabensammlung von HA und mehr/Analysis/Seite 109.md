# Aufgabe 4
> Bestimmen Sie alle ganzrationalen Funktionen vom Grad $3$, deren Graph durch die Punkte geht.

## 4a)
> $A(0\mid1)$; $B(1\mid0)$; $C(-1\mid4)$; $D(2\mid-5)$

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$:
- $f(0)=1$
- $f(1)=0$
- $f(-1)=4$
- $f(2)=-5$
> Es liegen genug Bedingungen vor

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&1\\
		\text{II:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&0\\
		\text{III:} & a\cdot(-1)^3+b\cdot(-1)^2+c\cdot(-1)+d & =&4\\
		\text{IV:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&-5
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d & =&1\\
		\text{II:} & a+b+c+d & =&0\\
		\text{III:} & -a+b-c+d & =&4&\\
		\text{IV:} & 8a+4b+2c+d & =&-5
	\end{array}\\\\
	&\text{I:}\quad d=1\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b+c & =&-1\\
		\text{III:} & -a+b-c & =&3&\mid\text{III}+\text{II}\\
		\text{IV:} & 8a+4b+2c & =&-6
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b+c & =&-1\\
		\text{III:} & 2b & =&2&\\
		\text{IV:} & 8a+4b+2c & =&-6
	\end{array}\\\\
	&\text{III:}\quad 2b=2\quad\Rightarrow \quad b=1\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+c & =&-2&
			\mid\cdot(-2)\\
		\text{IV:} & 8a+2c & =&-10&\quad\mid\text{II}+\text{IV}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+c & =&-2&\\
		\text{IV:} & 6a & =&-6
	\end{array}\\\\
	&\text{IV:}\quad 6a=-6\quad\Rightarrow \quad a=-1\\\\
	&\text{II:}\quad a+c=-2\quad\Rightarrow \quad c=-1
\end{align}
$$
Somit lautet die Lösung:
- $a=-1$
- $b=1$
- $c=-1$
- $d=1$
Die Funktion $f$ lautet $f(x)=-x^3+x^2-x+1$

---
## 4b)
> $A(0\mid-1)$; $B(1\mid1)$; $C(-1\mid-7)$; $D(2\mid17)$

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$:
- $f(0)=-1$
- $f(1)=1$
- $f(-1)=-7$
- $f(2)=17$
> Es liegen genug Bedingungen vor

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&-1\\
		\text{II:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&1\\
		\text{III:} & a\cdot(-1)^3+b\cdot(-1)^2+c\cdot(-1)+d & =&-7\\
		\text{IV:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&17
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d & =&-1\\
		\text{II:} & a+b+c+d & =&1\\
		\text{III:} & -a+b-c+d & =&-7&\\
		\text{IV:} & 8a+4b+2c+d & =&17
	\end{array}\\\\
	&\text{I:}\quad d=-1\\\\
	
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b+c& =&2\\
		\text{III:} & -a+b-c& =&-6&\mid\text{III}+\text{II}\\
		\text{IV:} & 8a+4b+2c& =&18
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b+c& =&2\\
		\text{III:} & 2b& =&-4&\\
		\text{IV:} & 8a+4b+2c& =&18
	\end{array}\\\\
	&\text{III:}\quad 2b=-4\quad\Rightarrow \quad b=-2\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+c& =&4&\quad\mid\text{II}+\text{IV}\\
		\text{IV:} & 8a+2c& =&26&\mid\cdot(-0,5)
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -3a& =&-9&\\
		\text{IV:} & 8a+2c& =&26&
	\end{array}\\\\
	&\text{II:}\quad -3a=-9\quad\Rightarrow \quad a=3\\\\
	&\text{IV:}\quad 8a+2c=26\quad\Rightarrow \quad c=1\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=3$
- $b=-2$
- $c=1$
- $d=-1$
Die Funktion $f$ lautet $f(x)=3x^3-2x^2+x-1$

---
## 4c)
> $A(1\mid0)$; $B(0\mid2)$; $C(-2\mid2)$

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$:
- $f(1)=0$
- $f(0)=2$
- $f(-2)=2$
> Es liegen nicht genug Bedingungen vor:
> 	Scharfunktion von $f$ mit einem Parameter

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&0\\
		\text{II:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&2\\
		\text{III:} & a\cdot(-2)^3+b\cdot(-2)^2+c\cdot(-2)+d & =&2
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&0\\
		\text{II:} &d & =&2\\
		\text{III:} & -8a+4b-2c+d & =&2&
	\end{array}\\\\
	&\text{I:}\quad d=2\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c & =&-2&\mid\cdot2\\
		\text{III:} & -8a+4b-2c & =&0&\quad\mid\text{III}+\text{I}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c & =&-2&\\
		\text{III:} & -6a+6b & =&-4&
	\end{array}\\\\
	&\text{III:}\quad -6a+6b=-4\quad\Rightarrow \quad b=-\frac{2}{3}+a\\\\
	&\text{I:}\quad a+b+c=-2\quad\Rightarrow \quad c=-\frac{4}{3}-2a
\end{align}
$$

Somit lautet die Lösung:
- $a=a$
- $b=-\frac{2}{3}+a$
- $c=-\frac{4}{3}-2a$
- $d=2$
Die Funktion $f$ lautet $f_a(x)=ax^3+\left(-\frac{2}{3}+a\right)x^2+\left(-\frac{4}{3}-2a\right)x+2$

---
## 4d)
> $A(1\mid1)$; $B(0\mid1)$

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$:
- $f(1)=1$
- $f(0)=1$
> Es liegen nicht genug Bedingungen vor:
> 	Scharfunktion von $f$ mit zwei Parametern

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&1\\
		\text{II:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&1
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1\\
		\text{II:} &d & =&1&
	\end{array}\\\\
	&\text{II:}\quad d=1\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c & =&0&
	\end{array}\\\\
	
	&\text{I:}\quad a+b+c=0\quad\Rightarrow \quad a=-b-c
\end{align}
$$

Somit lautet die Lösung:
- $a=-b-c$
- $b=b$
- $c=c$
- $d=1$
Die Funktion $f$ lautet $f_{b;c}(x)=(-b-c)x^3+bx^2+c+1$


---
---
# Aufgabe 5
> Bestimmen Sie eine ganzrationale Funktion vom Grad $3$, deren Graph

## 5a)
> durch $A(2\mid0)$, $B(-2\mid4)$ und $A(-4\mid8)$ geht und einen Tiefpunkt auf der y-Achse hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$:
- $f(2)=0$
- $f(-2)=4$
- $f(-4)=8$
- $f'(0)=0$
> Es liegen genug Bedingungen vor

$f(x)=ax^3+bx^2+cx+d$
$f'(x)=3ax^2+2bx+c$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&0\\
		\text{II:} & a\cdot(-2)^3+b\cdot(-2)^2+c\cdot(-2)+d & =&4\\
		\text{III:} & a\cdot(-4)^3+b\cdot(-4)^2+c\cdot(-4)+d & =&8\\
		\text{IV:} & 3a\cdot0^2+2b\cdot0+c & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 8a+4b+2c+d & =&0\\
		\text{II:}& -8a+4b-2c+d & =&4\\
		\text{III:} & -64a+16b-4c+d & =&8&\\
		\text{IV:} & c & =&0
	\end{array}\\\\
	&\text{I:}\quad c=0\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 8a+4b+d & =&0\\
		\text{II:}& -8a+4b+d & =&4&\mid\text{II}+\text{I}\\
		\text{III:} & -64a+16b+d & =&8
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 8a+4b+d & =&0&\mid\cdot8\\
		\text{II:}& 8b+2d & =&4&\\
		\text{III:} & -64a+16b+d & =&8&\quad\mid\text{III}+\text{I}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 8a+4b+d & =&0&\\
		\text{II:}& 8b+2d & =&4&\mid\cdot(-6)\\
		\text{III:} & 48b+9d & =&8&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 8a+4b+d & =&0&\\
		\text{II:}& 8b+2d & =&4&\\
		\text{III:} & -3d & =&-16&
	\end{array}\\\\
	
	&\text{III:}\quad -3d=-16\quad\Rightarrow \quad d=\frac{16}{3}\\\\
	&\text{II:}\quad 8b+2d=4\quad\Rightarrow \quad b=-\frac{5}{6}\\\\
	&\text{I:}\quad 8a+4b+d=0\quad\Rightarrow \quad a=-\frac{1}{4}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=-\frac{1}{4}$
- $b=-\frac{5}{6}$
- $c=0$
- $d=\frac{16}{3}$
Die Funktion $f$ lautet $f(x)=-\frac{1}{4}x^3-\frac{5}{6}x^2+\frac{16}{3}$.

### Überprüfung des Extremum bei $x=0$
> Es muss gelten: $f''(0)>0$

$f(x)=-\frac{1}{4}x^3-\frac{5}{6}x^2+\frac{16}{3}$
$f'(x)=-\frac{3}{4}x^2-\frac{5}{3}x$
$f''(x)=-\frac{3}{2}x-\frac{5}{3}$

$f''(0)=-\frac{5}{3}<0$

> Da $f''(0)$ die Bedingung nicht erfüllt, so stellt $f$ nicht die gesuchte Funktion dar. Es existiert nur eine Lösung des Gleichungssystems, daher kann $f$ nach den Bedingungen nie existieren.

---
## 5b)
> durch $A(2\mid2)$, $B(3\mid9)$ geht und den Tiefpunkt $T(1\mid1)$ hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$:
- $f(2)=2$
- $f(3)=9$
- $f(1)=1$
- $f'(1)=0$
> Es liegen genug Bedingungen vor

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&2\\
		\text{II:} & a\cdot3^3+b\cdot3^2+c\cdot3+d & =&9\\
		\text{III:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&1\\
		\text{IV:} & 3a\cdot1^2+2b\cdot1+c & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 8a+4b+2c+d & =&2\\
		\text{II:}& 27a+9b+3c+d & =&9\\
		\text{III:} & a+b+c+d & =&1&\\
		\text{IV:} & 3a+2b+c & =&0
	\end{array}\\\\
\end{align}
$$
Dieses LGS werde ich anschließend umsortieren
$$
\begin{align}
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\mid\cdot(-8)\\
		\text{II:} & 8a+4b+2c+d & =&2&\quad\mid\text{II}+\text{I}\\
		\text{III:}& 27a+9b+3c+d & =&9\\
		\text{IV:} & 3a+2b+c & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\mid\cdot(-27)\\
		\text{II:} & -4b-6c-7d & =&-6\\
		\text{III:}& 27a+9b+3c+d & =&9&\quad\mid\text{III}+\text{I}\\
		\text{IV:} & 3a+2b+c & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\mid\cdot(-3)\\
		\text{II:} & -4b-6c-7d & =&-6\\
		\text{III:}& -18b-24c-26d & =&-18\\
		\text{IV:} & 3a+2b+c & =&0&\quad\mid\text{IV}+\text{I}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\\
		\text{II:} & -4b-6c-7d & =&-6&\mid\cdot(-1)\\
		\text{III:}& -18b-24c-26d & =&-18&\mid\cdot(-1)\\
		\text{IV:} & -b-2c -3d& =&-3&\mid\cdot(-1)
	\end{array}\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\\
		\text{II:} & 4b+6c+7d & =&6&\mid\cdot\frac{18}{4}\\
		\text{III:}& 18b+24c+26d & =&18&\quad\mid\text{III}+\text{II}\\
		\text{IV:} & b+2c+3d& =&3&
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\\
		\text{II:} & 4b+6c+7d & =&6&\mid\cdot\frac{-1}{4}\\
		\text{III:}& -3c-\frac{11}{2}d & =&-9\\
		\text{IV:} & b+2c+3d& =&3&\quad\mid\text{IV}+\text{II}
	\end{array}\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\\
		\text{II:} & 4b+6c+7d & =&6&\\
		\text{III:}& -3c-\frac{11}{2}d & =&-9&\mid\cdot\frac{1}{6}\\
		\text{IV:} & \frac{1}{2}c+\frac{5}{4}d& =&\frac{3}{2}&\quad\mid\text{IV}+\text{III}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b+c+d & =&1&\\
		\text{II:} & 4b+6c+7d & =&6&\\
		\text{III:}& -3c-\frac{11}{2}d & =&-9&\\
		\text{IV:} & \frac{1}{3}d& =&0&
	\end{array}\\\\
	&\text{IV:}\quad \frac{1}{3}d=0\quad\Rightarrow \quad d=0\\\\
	&\text{III:}\quad -3c-\frac{11}{2}d=-9\quad\Rightarrow \quad c=3\\\\
	&\text{II:}\quad 4b+6c+7d=6\quad\Rightarrow \quad b=-3\\\\
	&\text{I:}\quad a+b+c+d=1\quad\Rightarrow \quad a=1\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=1$
- $b=-3$
- $c=3$
- $d=0$
Die Funktion $f$ lautet $f(x)=x^3-3x^2+3x$.

### Überprüfung des Extremum bei $x=1$
> Es muss gelten: $f''(1)>0$

$f(x)=x^3-3x^2+3x$
$f'(x)=3x^2-6x+3$
$f''(x)=6x-6$

$f''(1)=6-6=0$

> Da $f''(1)$ die Bedingung nicht erfüllt, so stellt $f$ nicht die gesuchte Funktion dar. Es existiert nur eine Lösung des Gleichungssystems, daher kann $f$ nach den Bedingungen nie existieren.

---
---
# Aufgabe 6
> Bestimmen Sie die ganzrationale Funktion $f$ mit niedrigsten Grades mit den Funktionswerten.

## 6a)
- $f(0)=1$
- $f(1)=0$
- $f(2)=1$
> Es liegen $3$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^2+bx+c$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^2+b\cdot0+c & =&1\\
		\text{II:} & a\cdot1^2+b\cdot1+c & =&0\\
		\text{III:} & a\cdot2^2+b\cdot2+c & =&1\\
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & c & =&1&\\
		\text{II:} & a+b+c & =&0&\\
		\text{III:} & 4a+2b+c & =&1&\\
	\end{array}\\\\
	&\text{I:}\quad c=1\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b & =&-1&\mid\cdot(-2)\\
		\text{III:} & 4a+2b & =&0&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b & =&-1&\\
		\text{III:} & 2a & =&2&
	\end{array}\\\\
	&\text{III:}\quad 2a=2\quad\Rightarrow \quad a=1\\\\
	&\text{II:}\quad a+b=-1\quad\Rightarrow \quad b=-2\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=1$
- $b=-2$
- $c=1$
Die Funktion $f$ lautet $f(x)=x^2-2x+1$.

---
## 6b)
- $f(0)=0$
- $f(1)=1$
- $f(2)=2$
> Es liegen $3$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^2+bx+c$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^2+b\cdot0+c & =&0\\
		\text{II:} & a\cdot1^2+b\cdot1+c & =&1\\
		\text{III:} & a\cdot2^2+b\cdot2+c & =&2\\
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & c & =&0&\\
		\text{II:} & a+b+c & =&1&\\
		\text{III:} & 4a+2b+c & =&2&\\
	\end{array}\\\\
	&\text{I:}\quad c=0\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b & =&1&\mid\cdot(-2)\\
		\text{III:} & 4a+2b & =&2&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b & =&1&\\
		\text{III:} & 2a & =&0&
	\end{array}\\\\
	&\text{III:}\quad 2a=0\quad\Rightarrow \quad a=0\\\\
	&\text{II:}\quad a+b=1\quad\Rightarrow \quad b=1\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=0$
- $b=1$
- $c=0$
Die Funktion $f$ lautet $f(x)=x$.

---
## 6c)
- $f(0)=1$
- $f(1)=1$
- $f(2)=1$
> Es liegen $3$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^2+bx+c$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^2+b\cdot0+c & =&1\\
		\text{II:} & a\cdot1^2+b\cdot1+c & =&1\\
		\text{III:} & a\cdot2^2+b\cdot2+c & =&1\\
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & c & =&1&\\
		\text{II:} & a+b+c & =&1&\\
		\text{III:} & 4a+2b+c & =&1&\\
	\end{array}\\\\
	&\text{I:}\quad c=1\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b & =&0&\mid\cdot(-2)\\
		\text{III:} & 4a+2b & =&0&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+b & =&0&\\
		\text{III:} & 2a & =&0&
	\end{array}\\\\
	&\text{III:}\quad 2a=0\quad\Rightarrow \quad a=0\\\\
	&\text{II:}\quad a+b=0\quad\Rightarrow \quad b=0\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=0$
- $b=0$
- $c=1$
Die Funktion $f$ lautet $f(x)=1$.

---
## 6d)
- $f(-1)=0$
- $f(0)=1$
- $f(2)=0$
> Es liegen $3$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^2+bx+c$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot(-1)^2+b\cdot(-1)+c & =&0\\
		\text{II:} & a\cdot0^2+b\cdot0+c & =&1\\
		\text{III:} & a\cdot2^2+b\cdot2+c & =&0\\
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a-b+c & =&0&\\
		\text{II:} & c & =&1&\\
		\text{III:} & 4a+2b+c & =&0&\\
	\end{array}\\\\
	&\text{II:}\quad c=1\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a-b & =&-1&\mid\cdot2\\
		\text{III:} & 4a+2b & =&-1&\quad\mid\text{III}+\text{I}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & a+b & =&-1&\\
		\text{III:} & 6a & =&-3&
	\end{array}\\\\
	&\text{III:}\quad 6a=-3\quad\Rightarrow \quad a=-\frac{1}{2}\\\\
	&\text{I:}\quad a-b=-1\quad\Rightarrow \quad b=\frac{1}{2}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=-\frac{1}{2}$
- $b=\frac{1}{2}$
- $c=1$
Die Funktion $f$ lautet $f(x)=-\frac{1}{2}x^2+\frac{1}{2}x+1$.

---
## 6e)
- $f(0)=0$
- $f(-1)=0$
- $f(1)=2$
- $f(2)=6$
> Es liegen $4$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^3+bx^2+cx+d$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&0\\
		\text{II:} & a\cdot(-1)^3+b\cdot(-1)^2+c\cdot(-1)+d & =&0\\
		\text{III:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&2\\
		\text{IV:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&6
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d & =&0\\
		\text{II:} & -a+b-c+d & =&0\\
		\text{III:} & a+b+c+d & =&2\\
		\text{IV:} & 8a+4b+2c+d & =&6&
	\end{array}\\\\
	&\text{I:}\quad d=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -a+b-c & =&0\\
		\text{III:} & a+b+c & =&2&\quad\mid\text{III}+\text{II}\\
		\text{IV:} & 8a+4b+2c & =&6&
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -a+b-c & =&0\\
		\text{III:} & 2b & =&2&\\
		\text{IV:} & 8a+4b+2c & =&6&
	\end{array}\\\\
	&\text{III:}\quad 2b=2\quad\Rightarrow \quad b=1\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -a-c & =&-1&\mid\cdot2\\
		\text{IV:} & 8a+2c & =&2&\quad\mid\text{IV}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -a-c & =&-1&\\
		\text{IV:} & 6a & =&0&
	\end{array}\\\\
	&\text{IV:}\quad 6a=0\quad\Rightarrow \quad a=0\\\\
	&\text{II:}\quad -a-c=-1\quad\Rightarrow \quad c=1\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=0$
- $b=1$
- $c=1$
- $d=0$
Die Funktion $f$ lautet $f(x)=x^2+x$.

---
## 6f)
- $f(-1)=0$
- $f(0)=1$
- $f(1)=3$
- $f(2)=4$
> Es liegen $4$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^3+bx^2+cx+d$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot(-1)^3+b\cdot(-1)^2+c\cdot(-1)+d& =&0\\
		\text{II:} &  a\cdot0^3+b\cdot0^2+c\cdot0+d & =&1\\
		\text{III:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&3\\
		\text{IV:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&4
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & -a+b-c+d& =&0&\\
		\text{II:} &  d & =&1\\
		\text{III:} & a+b+c+d & =&3\\
		\text{IV:} & 8a+4b+2c+d & =&4
	\end{array}\\\\
	&\text{II:}\quad d=1\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{I:} & -a+b-c& =&-1\\
		\text{III:} & a+b+c & =&2&\mid\text{III}+\text{I}\\
		\text{IV:} & 8a+4b+2c & =&3
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & -a+b-c& =&-1\\
		\text{III:} & 2b& =&1&\\
		\text{IV:} & 8a+4b+2c & =&3
	\end{array}\\\\
	&\text{III:}\quad 2b=1\quad\Rightarrow \quad b=\frac{1}{2}\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{I:} & -a-c& =&-\frac{3}{2}&\mid\cdot(2)\\
		\text{IV:} & 8a+2c & =&1&\quad\mid\text{IV}+\text{I}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & -a-c& =&-\frac{3}{2}&\\
		\text{IV:} & 6a& =&-2&
	\end{array}\\\\
	&\text{IV:}\quad 6a=-2\quad\Rightarrow \quad a=-\frac{1}{3}\\\\
	&\text{II:}\quad -a-c=-\frac{3}{2}\quad\Rightarrow \quad c=\frac{11}{6}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=-\frac{1}{3}$
- $b=\frac{1}{2}$
- $c=\frac{11}{6}$
- $d=1$
Die Funktion $f$ lautet $f(x)=-\frac{1}{3}x^3+\frac{1}{2}x^2+\frac{11}{6}x+1$.

---
## 6g)
- $f(0)=0$
- $f(1)=0$
- $f(2)=0$
- $f(3)=1$
> Es liegen $4$ Bedingungen vor, daher gilt für den niedrigsten Grad:
$$f(x)=ax^3+bx^2+cx+d$$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d& =&0\\
		\text{II:} & a\cdot1^3+b\cdot1^2+c\cdot1+d  & =&0\\
		\text{III:} & a\cdot2^3+b\cdot2^2+c\cdot2+d & =&0\\
		\text{IV:} & a\cdot3^3+b\cdot3^2+c\cdot3+d & =&1
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d& =&0&\\
		\text{II:} &  a+b+c+d & =&0\\
		\text{III:} & 8a+4b+2c+d & =&0\\
		\text{IV:} & 27a+9b+3c+d & =&1
	\end{array}\\\\
	&\text{I:}\quad d=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} &  a+b+c & =&0&\mid\cdot(-8)\\
		\text{III:} & 8a+4b+2c & =&0&\quad\mid\text{III}+\text{II}\\
		\text{IV:} & 27a+9b+3c & =&1
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} &  a+b+c & =&0&\mid\cdot(-27)\\
		\text{III:} & -4b-6c & =&0&\\
		\text{IV:} & 27a+9b+3c & =&1&\quad\mid\text{IV}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} &  a+b+c & =&0&\\
		\text{III:} & -4b-6c & =&0&\mid\cdot\frac{-18}{4}\\
		\text{IV:} & -18b-24c & =&1&\quad\mid\text{IV}+\text{III}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} &  a+b+c & =&0&\\
		\text{III:} & -4b-6c & =&0&\\
		\text{IV:} & 3c & =&1&
	\end{array}\\\\
	&\text{IV:}\quad 3c=1\quad\Rightarrow \quad c=\frac{1}{3}\\\\
	&\text{III:}\quad -4b-6c=0\quad\Rightarrow \quad b=-\frac{1}{2}\\\\
	&\text{II:}\quad a+b+c=0\quad\Rightarrow \quad a=\frac{1}{6}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=\frac{1}{6}$
- $b=-\frac{1}{2}$
- $c=\frac{1}{3}$
- $d=0$
Die Funktion $f$ lautet $f(x)=\frac{1}{6}x^3-\frac{1}{2}x^2+\frac{1}{3}x$.

---
---
# Aufgabe 7
> Begründen Sie, dass es für die folgenden Bedingungen keine ganzrationale Funktion $f$ gibt.

## 7a)
> Grad von $f$ gleich $2$; Nullstellen für $x=2$ und $x=4$; Maximum für $x=0$.

Diese Funktion kann nicht existieren, da das Extremum durch Symmetrie an der Stelle $x=3$ sein muss.

---
## 7b)
> Grad von $f$ gleich $3$; Extremwerte für $x=0$ und $x=3$; Wendestelle für $x=1$.

Diese Funktion kann nicht existieren, da die Wendestelle mittig der Extremwerte liegen muss. (Siehe Aufgabe 7a)

---
## 7c)
> Grad von $f$ gleich $4$; $f$ gerade, Wendestelle für $x=1$; Maximum für $x=2$

Es ist für $f(x)=ax^4+bx^2+c$ mit $f'(x)=4ax^3+2bx$ und $f''(x)=12ax^2+2b$. Es muss gelten:
- $f''(1)=0$
- $f'(2)=0$

$$
\begin{align}
	0&=f''(1)\\
	0&=12a+2b&&\mid-12a\\
	2b&=-12a&&\mid\div2\\
	b&=-6a
\end{align}
$$
$$
\begin{align}
	0&=f'(2)\\
	0&=4a\cdot2^3+2b\cdot2\\
	0&=32a+4b&&\mid-32a\\
	4b&=-32a&&\mid\div4\\
	b&=-8a
\end{align}
$$
Für $a$ und $b$ existieren aufgrund von $\{b=-6a\}\ne\{b=-8a\}$ keine Lösungen. Folglich kann es keine Funktion $f$ nach diesen Bedingungen geben.

---
---
# Aufgabe 8
> Bestimmen Sie die ganzrationale Funktion $3$ten Grades, deren Graph

## 8a)
> die $x$-Achse im Ursprung berührt und deren Tangente in $P(-3\mid0)$ parallel zur Gerade $y=6x$ ist.

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$ mit $f'(x)=3ax^2+2bx+c$:
- $f(0)=0$
- $f(-3)=0$
- $f'(0)=0$
- $f'(-3)=6$
> Es liegen genug Bedingungen vor

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&0\\
		\text{II:} & a\cdot(-3)^3+b\cdot(-3)^2+c\cdot(-3)+d & =&0\\
		\text{III:} & 3a\cdot0^2+2b\cdot0+c& =&0\\
		\text{IV:} &  3a\cdot(-3)^2+2b\cdot(-3)+c& =&6
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d & =&0\\
		\text{II:} & -27a+9b-3c+d & =&0\\
		\text{III:} & c & =&0&\\
		\text{IV:} & 27a-6b+c & =&6
	\end{array}\\\\
	&\text{I:}\quad d=0\\\\
	&\text{III:}\quad c=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -27a+9b & =&0&\\
		\text{IV:} & 27a-6b & =&6&\mid\text{IV}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -27a+9b & =&0&\\
		\text{IV:} & 3b & =&6&
	\end{array}\\\\
	&\text{II:}\quad 3b=6\quad\Rightarrow \quad b=2\\\\
	&\text{IV:}\quad -27a+9b=0\quad\Rightarrow \quad a=\frac{2}{3}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=\frac{2}{3}$
- $b=2$
- $c=0$
- $d=0$
Die Funktion $f$ lautet $f(x)=\frac{2}{3}x^3+2x^2$.

---
## 8b)
> in $P(1\mid4)$ einen Extrempunkt und in $Q(0\mid2)$ einen Wendepunkt hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^3+bx^2+cx+d$ mit $f'(x)=3ax^2+2bx+c$ und $f''(x)=6ax+2b$:
- $f(0)=2$
- $f(1)=4$
- $f'(1)=0$
- $f''(0)=0$
> Es liegen genug Bedingungen vor

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&2\\
		\text{II:} & a\cdot1^3+b\cdot1^2+c\cdot1+d & =&4\\
		\text{III:} & 3a\cdot1^2+2b\cdot1+c& =&0\\
		\text{IV:} &  6a\cdot0^2+2b& =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d & =&2\\
		\text{II:} & a+b+c+d & =&4&\\
		\text{III:} & 3a+2b+c& =&0\\
		\text{IV:} &  2b& =&0
	\end{array}\\\\
	&\text{I:}\quad d=2\\\\
	&\text{II:}\quad 2b=0\quad\Rightarrow \quad b=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+c & =&2&\mid\cdot(-1)\\
		\text{III:} & 3a+c& =&0&\quad\mid\text{III}+\text{II}\\
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a+c & =&2&\\
		\text{III:} & 2a& =&-2&\\
	\end{array}\\\\
	&\text{III:}\quad 2a=-2\quad\Rightarrow \quad a=-1\\\\
	&\text{II:}\quad a+c=2\quad\Rightarrow \quad c=3\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=-1$
- $b=0$
- $c=3$
- $d=2$
Die Funktion $f$ lautet $f(x)=-x^3+3x+2$.

---
---
# Aufgabe 9
> Bestimmen Sie alle ganzrationalen Funktionen $3$ten Grades, deren Graph

## 9a)
> punktsymmetrisch zum Ursprung ist und für $x=2$ einen Extrempunkt hat

Es gilt durch die Punktsymmetrie zum Ursprung:
- $f(x)=ax^3+bx$
- $f'(x)=3ax^2+b$
Generell gilt:
- $f'(2)=0$
$$
\begin{align}
	0&=f'(2)\\
	0&=3a\cdot2^2+b&&\mid-12a\\
	b&=-12a
\end{align}
$$
Somit lautet die Funktion $f(x)=ax^3-12ax$; $a\ne0$.

---
## 9b)
> im Ursprung einen Wendepunkt mit der Wendetangente $y=x$ hat.

Es gilt für $f(x)=ax^3+bx^2+cx+d$:
- $f(0)=0$
- $f'(0)=1$
- $f''(0)=0$
> Es liegen nicht genug Bedingungen (3 von 4) vor:
> Scharfunktion von $f$ mit einem Parameter

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^3+b\cdot0^2+c\cdot0+d & =&0\\
		\text{II:} & 3a\cdot0^2+2b\cdot0+c & =&1\\
		\text{III:} & 6a\cdot0+2b & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & d & =&0&\\
		\text{II:} & c & =&1\\
		\text{III:} & 2b & =&0
	\end{array}\\\\
	&\text{I:}\quad d=0\\\\
	&\text{II:}\quad c=1\\\\
	&\text{III:}\quad 2b=0\quad\Rightarrow\quad b=0\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=a$
- $b=0$
- $c=1$
- $d=0$
Die Funktion $f$ lautet $f(x)=ax^3+x$; $a\ne0$

---
---
# Aufgabe 10
> Bestimmen Sie die ganzrationale Funktion $4$ten Grades, deren Graph

## 10a)
> den Wendepunkt $O(0\mid0)$ mit der $x$-Achse als Wendetangente und den Tiefpunkt $A(-1\mid-2)$ hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^4+bx^3+cx^2+dx+e$ mit $f'(x)=4ax^3+3bx^2+2cx+d$ und $f''(x)=12ax^2+6bx+2c$
- $f(0)=0$
- $f(-1)=-2$
- $f'(-1)=0$
- $f'(0)=0$
- $f''(0)=0$
> Es liegen genug Bedingungen vor (5 von 5)

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^4+b\cdot0^3+c\cdot0^2+d\cdot0+e & =&0\\
		\text{II:} & a\cdot(-1)^4+b\cdot(-1)^3+c\cdot(-1)^2+d\cdot(-1)+e & =&-2\\
		\text{III:} & 4a\cdot(-1)^3+3b\cdot(-1)^2+2c\cdot(-1)+d& =&0\\
		\text{IV:} &  4a\cdot0^3+3b\cdot0^2+2c\cdot0+d& =&0\\
		\text{V:} &  12a\cdot0^2+6b\cdot0+2c& =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & e & =&0\\
		\text{II:} & a-b+c-d+e& =&-2&\\
		\text{III:} & -4a+3b-2c+d& =&0\\
		\text{IV:} &  d& =&0\\
		\text{V:} &  2c& =&0
	\end{array}\\\\
	&\text{I:}\quad e=0\\\\
	&\text{IV:}\quad d=0\\\\
	&\text{V:}\quad 2c=0\quad\Rightarrow \quad c=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a-b& =&-2&\mid\cdot3\\
		\text{III:} & -4a+3b& =&0&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & a-b& =&-2&\\
		\text{III:} & -a& =&-6&
	\end{array}\\\\
	&\text{III:}\quad -a=-6\quad\Rightarrow \quad a=6\\\\
	&\text{II:}\quad a-b=-2\quad\Rightarrow \quad b=8\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=6$
- $b=8$
- $c=0$
- $d=0$
- $e=0$
Die Funktion $f$ lautet $f(x)=6x^4+8x^3$.

---
## 10b)
> in $O(0\mid0)$ und im Wendepunkt $W(-2\mid2)$ Tangenten parallel zur $x$-Achse hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^4+bx^3+cx^2+dx+e$ mit $f'(x)=4ax^3+3bx^2+2cx+d$ und $f''(x)=12ax^2+6bx+2c$
- $f(0)=0$
- $f(-2)=2$
- $f'(0)=0$
- $f'(-2)=0$
- $f''(-2)=0$
> Es liegen genug Bedingungen vor (5 von 5)

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^4+b\cdot0^3+c\cdot0^2+d\cdot0+e & =&0\\
		\text{II:} & a\cdot(-2)^4+b\cdot(-2)^3+c\cdot(-2)^2+d\cdot(-2)+e & =&2\\
		\text{III:} & 4a\cdot0^3+3b\cdot0^2+2c\cdot0+d& =&0\\
		\text{IV:} &  4a\cdot(-2)^3+3b\cdot(-2)^2+2c\cdot(-2)+d& =&0\\
		\text{V:} &  12a\cdot(-2)^2+6b\cdot(-2)+2c& =&0&
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & e & =&0\\
		\text{II:} & 16a-8b+4c-2d+e & =&2\\
		\text{III:} & d& =&0\\
		\text{IV:} &  -32a+12b-4c+d& =&0\\
		\text{V:} &  48a-12b+2c& =&0&
	\end{array}\\\\
	&\text{I:}\quad e=0\\\\
	&\text{III:}\quad d=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & 16a-8b+4c & =&2&\mid\cdot(2)\\
		\text{IV:} &  -32a+12b-4c& =&0&\quad\mid\text{IV}+\text{II}\\
		\text{V:} &  48a-12b+2c& =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & 16a-8b+4c & =&2&\mid\cdot(-3)\\
		\text{IV:} &  -4b+4c& =&4&\\
		\text{V:} &  48a-12b+2c& =&0&\quad\mid\text{V}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & 16a-8b+4c & =&2&\\
		\text{IV:} &  -4b+4c& =&4&\mid\cdot(3)\\
		\text{V:} &  12b-10c& =&-6&\quad\mid\text{V}+\text{IV}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & 16a-8b+4c & =&2&\\
		\text{IV:} &  -4b+4c& =&4&\mid\cdot(3)\\
		\text{V:} &  2c& =&6&\quad\mid\text{V}+\text{IV}
	\end{array}\\\\
	&\text{V:}\quad 2c=6\quad\Rightarrow \quad c=3\\\\
	&\text{IV:}\quad -4b+4c=4\quad\Rightarrow \quad b=2\\\\
	&\text{II:}\quad 16a-8b+4c=2\quad\Rightarrow \quad a=\frac{3}{8}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=\frac{3}{8}$
- $b=2$
- $c=3$
- $d=0$
- $e=0$
Die Funktion $f$ lautet $f(x)=6x^4+8x^3$.

---
---
# Aufgabe 11
> Bestimmen Sie die ganzrationale Funktion $4$ten Grades, deren Graph

## 11a)
> symmetrisch zur $y$-Achse ist, durch $A(0\mid2)$ geht und den Tiefpunkt $B(1\mid0)$ hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^4+bx^2+c$ mit $f'(x)=4ax^3+2bx$:
- $f(0)=2$
- $f(1)=0$
- $f'(1)=0$
> Es liegen genug Bedingungen vor (3 von 3)

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:}&a\cdot0^4+b\cdot0^2+c&=&2\\
		\text{II:}&a\cdot1^4+b\cdot1^2+c&=&0\\
		\text{III:}&4a\cdot1^3+2b\cdot1&=&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:}&c&=&2\\
		\text{II:}&a+b+c&=&0\\
		\text{III:}&4a+2b&=&0&
	\end{array}\\\\
	&\text{I:}\quad c=2\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:}&a+b&=&-2&\mid\cdot(-2)\\
		\text{III:}&4a+2b&=&0&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:}&a+b&=&-2&\\
		\text{III:}&2a&=&4&
	\end{array}\\\\
	&\text{III:}\quad2a=4\quad\Rightarrow\quad a=2\\\\
	&\text{II:}\quad a+b=-2\quad\Rightarrow\quad b=-4
\end{align}
$$

Somit lautet die Lösung:
- $a=2$
- $b=-4$
- $c=2$
Die Funktion $f$ lautet $f(x)=2x^4-4x^2+2$.

### Überprüfung des Extremum bei $x=1$
> Es muss gelten: $f''(1)>0$

$f(x)=2x^4-4x^2+2$
$f'(x)=8x^3-8x$
$f''(x)=24x^2-8$

$f''(1)=16>0$

> Da $f''(1)$ die Bedingung erfüllt, so stellt $f$ die gesuchte Funktion dar.

---
## 11b)
> symmetrisch zur $y$-Achse ist und in $P(2\mid0)$ eine Wendetangente mit der Steigung $-\frac{4}{3}$ hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^4+bx^2+c$ mit $f'(x)=4ax^3+2bx$ und $f''(x)=12ax^2+2b$:
- $f(2)=0$
- $f'(2)=-\frac{4}{3}$
- $f''(2)=0$
> Es liegen genug Bedingungen vor (3 von 3)

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot2^4+b\cdot2^2+c & =&0\\
		\text{II:} & 4a\cdot2^3+2b\cdot2 & =&-\frac{4}{3}\\
		\text{III:} & 12a\cdot2^2+2b& =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 16a+4b+c & =&0&\mid\cdot(-2)\\
		\text{II:} & 32a+4b & =&-\frac{4}{3}&\quad\mid\text{II}+\text{I}\\
		\text{III:} & 48a+2b& =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 16a+4b+c & =&0&\mid\cdot(-3)\\
		\text{II:} & -4b -2c& =&-\frac{4}{3}&\\
		\text{III:} & 48a+2b& =&0&\quad\mid\text{III}+\text{I}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 16a+4b+c & =&0&\\
		\text{II:} & -4b -2c& =&-\frac{4}{3}&\mid\cdot(-2,5)\\
		\text{III:} & -10b-3c& =&0&\quad\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & 16a+4b+c & =&0&\\
		\text{II:} & -4b -2c& =&-\frac{4}{3}&\\
		\text{III:} & 2c& =&\frac{10}{3}&
	\end{array}\\\\
	&\text{III:}\quad 2c=\frac{10}{3}\quad\Rightarrow \quad c=\frac{5}{3}\\\\
	&\text{II:}\quad -4b -2c=-\frac{4}{3}\quad\Rightarrow \quad b=-\frac{1}{2}\\\\
	&\text{I:}\quad 16a+4b+c=0\quad\Rightarrow \quad a=\frac{1}{48}
\end{align}
$$
Somit lautet die Lösung:
- $a=\frac{1}{48}$
- $b=-\frac{1}{2}$
- $c=\frac{5}{3}$
Die Funktion $f$ lautet $f(x)=\frac{1}{48}x^4-\frac{1}{2}x^2+\frac{5}{3}$.

---
---
# Aufgabe 12
> Bestimmen Sie alle ganzrationalen Funktionen

## 12a)
> vom Grad $2$, deren Graph durch $A(0\mid2)$ und $B(6\mid8)$ geht und die $x$-Achse berührt.

Die Bedingungen folgen für die Funktion $f(x)=ax^2+bx+c$ mit $f'(x)=2ax+b$:
- $f(0)=2$
- $f(6)=8$
- $f'(k)=0$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^2+b\cdot0+c & =&2\\
		\text{II:} & a\cdot6^2+b\cdot6+c & =&8\\
		\text{III:} &2a\cdot k+b  & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:} & c & =&2&\\
		\text{II:} & 36a+6b+c & =&8\\
		\text{III:} &2ka+b  & =&0
	\end{array}\\\\
	&\text{I:}\quad c=2\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & 36a+6b & =&6&\div(-6)\\
		\text{III:} &2ka+b  & =&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -6a-b & =&-1\\
		\text{III:} &2ka+b  & =&0&\mid\text{III}+\text{II}
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{II:} & -6a-b & =&-1\\
		\text{III:} &(2k-6)a  & =&-1&
	\end{array}\\\\
	&\text{III:}\quad (2k-6)a=-1\quad\Rightarrow \quad a=-\frac{1}{2k-6}\\\\
	&\text{II:}\quad -6a-b=-1\quad\Rightarrow \quad b=1+\frac{3}{k-3}\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=-\frac{1}{2k-6}$
- $b=1+\frac{3}{k-3}=\frac{k}{k-3}$
- $c=2$
Die Funktion $f$ lautet $f(x)=-\frac{1}{2k-6}x^2+\frac{k}{k-3}x+2$.

### Berechnung der gesuchten $k$
> Es sollen die $k$ gefunden werden, die zu einer doppelten Nullstelle der Funktion $f$ führen.

$$
\begin{align}
	0&=-\frac{1}{2k-6}x^2+\frac{k}{k-3}x+2\\
	x_{1;2}&=\frac{-\frac{k}{k-3}\pm\sqrt{\left[\frac{k}{k-3}\right]^2+4\cdot\frac{1}{2k-6}\cdot2}}{\frac{2}{2k-6}}\\
	&=\frac{-\frac{k}{k-3}\pm\sqrt{\frac{k^2}{(k-3)^2}+\frac{4}{k-3}}}{\frac{2}{2k-6}}
\end{align}
$$
Der Wurzelterm gibt die Anzahl der Nullstellen an. Dieser muss zwanghaft exakt $0$ sein, damit die doppelte Nullstelle vorhanden ist.
Es gilt:
$$
\begin{align}
	0&=\sqrt{\frac{k^2}{(k-3)^2}+\frac{4}{k-3}}&&\mid()^2\\
	0&=\frac{k^2}{(k-3)^2}+\frac{4(k-3)}{(k-3)^2}\\
	0&=\frac{k^2+4k-12}{(k-3)^2}&&\mid\cdot(k-3)^2\\
	0&=k^2+4k-12\\
	k_{1;2}&=-\frac{4}{2}\pm\sqrt{\left[\frac{4}{2}\right]^2+12}\\
	&=-2\pm\sqrt{16}\\
	&=-2\pm4
\end{align}
$$
Daraus folgt, dass die Funktion $f$ mit den Parametern $k=-6$ und $k=2$ gebildet wird. Somit gilt:
- $f(x)=\frac{1}{18}x^2+\frac{2}{3}x+2$
- $f(x)=\frac{1}{2}x^2-2x+2$

---
## 12b)
> vom Grad $3$, deren Graph durch $A(-2\mid2)$, $B(0\mid2)$ und $A(2\mid2)$ geht und die $x$-Achse berührt.

Anstelle, dass $f$ über ein LGS gefunden wird, verwende ich eine andere Methode.
Es fällt auf, dass die $y$-Koordinate aller drei Punkte $2$ beträgt. So lässt sich jede Funktion, die durch diese Punkte verläuft durch $f_k(x)=k(x+2)(x)(x-2)+2$ beschreiben.
Die passenden $k$ sind dann gefunden, sobald ein Extrempunkt auf der $x$-Achse ist. Somit gilt:
- $f_k(x_{1;2})=0$
- $f_k'(x_{1;2})=0$

$$
\begin{align}
	f_k(x)&=k(x+2)(x)(x-2)+2\\
	&=kx^3-4kx+2\\\\
	f'_k(x)&=3kx^2-4k
\end{align}
$$

$$
\begin{align}
	0&=f'_k(x)\\
	0&=3kx^2-4k&&\mid+4k\\
	4k&=3kx^2&&\mid\div(3k)\\
	\frac{4k}{3k}&=x^2&&\mid\sqrt{}\\
	x_{1;2}&=\pm\sqrt{\frac{4}{3}}
\end{align}
$$

Für $f_k(x_1)=0$:
$$
\begin{align}
	0&=k\cdot\left[\sqrt{\frac{4}{3}}\right]^3-4k\sqrt{\frac{4}{3}}+2&&\mid-2\\
	-2&=k\cdot\frac{8\sqrt{3}}{9}-\frac{8\sqrt{3}}{3}\cdot k\\
	-2&=\left(\frac{8\sqrt{3}}{9}-\frac{8\sqrt{3}}{3}\right)k&&\mid\cdot\left(-\frac{9}{16\sqrt{3}}\right)\\
	k&=\frac{3\sqrt{3}}{8}
\end{align}
$$

Für $f_k(x_2)=0$:
$$
\begin{align}
	0&=k\cdot\left[-\sqrt{\frac{4}{3}}\right]^3-4k\left[-\sqrt{\frac{4}{3}}\right]+2&&\mid-2\\
	-2&=-k\cdot\frac{8\sqrt{3}}{9}+\frac{8\sqrt{3}}{3}\cdot k\\
	-2&=\left(-\frac{8\sqrt{3}}{9}+\frac{8\sqrt{3}}{3}\right)k&&\mid\cdot\left(\frac{9}{16\sqrt{3}}\right)\\
	k&=-\frac{3\sqrt{3}}{8}
\end{align}
$$

Daraus folgen die Funktionen für $f$:
- $f(x)=\frac{3\sqrt{3}}{8}x^3-\frac{3\sqrt{3}}{2}x+2$
- $f(x)=-\frac{3\sqrt{3}}{8}x^3+\frac{3\sqrt{3}}{2}x+2$

---
## 12c)
> vom Grad $4$, die gerade ist, die Wendestelle $x=1$ und das relative Minimum $0$ hat.

Die Bedingungen folgen für die Funktion $f(x)=ax^4+bx^2+c$ mit $f'(x)=4ax^3+2bx$ und $f''(x)=12ax^2+2b$:
- $f(0)=0$
- $f'(0)=0$
- $f''(1)=0$
> Es liegen genug Bedingungen vor:

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & a\cdot0^4+b\cdot0^2+c & =&0\\
		\text{II:} & 4a\cdot0^3+2b\cdot0 & =&0\\
		\text{III:} & 12a\cdot1^2+2b & =&0
	\end{array}\\\\
	&\text{I:}\quad c=0\\\\
	\hline\\
	&\begin{array}{r|rrc|l}
		\text{II:} & 0 & =&0\\
		\text{III:} & 12a+2b & =&0&
	\end{array}\\\\
	&\text{III:}\quad 12a+2b=0\quad\Rightarrow \quad b=-6a
\end{align}
$$
Somit lautet die Lösung:
- $a=a$
- $b=-6a$
- $c=0$
Die Funktion $f$ lautet $f(x)=ax^4-6ax^2$.

---
>Damit für $x=0$ ein Minimum vorliegt, so muss gelten:
- $f''(0)>0$

---
Finden der Bedingung $f''(x)>0$:
$$
\begin{align}
	0&<f''(0)\\
	0&<12a\cdot0^2-12a\\
	0&<-12a&&\mid\div(-12)\\
	a&<0
\end{align}
$$
Somit ist jede geeignete Funktion $f$:
- $f(x)=ax^4-6ax^2$ mit $a<0$

---
---
# Aufgabe 13
> Eine ganzrationale Funktion $f_2$ vom Grad $2$ und die $\cos$-Funktion haben für $x=0$ den selben Funktionswert und dieselben Werte der $1$ten und $2$ten Ableitung.

## 13a)
> Bestimmen Sie $f_2$. Zeichnen Sie die Graphen von $f_2$ und der $\cos$-Funktion für $|x|\le0,5\pi$.

Die Bedingungen folgen für die Funktion $f(x)=ax^2+bx+c$ mit $f'(x)=2ax+b$ und $f''(x)=2a$:
- $f(0)=1$
- $f'(0)=0$
- $f''(0)=-1$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:}&a\cdot0^2+b\cdot0+c&=&1\\
		\text{II:}&2a\cdot0+b&=&0\\
		\text{III:}&2a&=&-1
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:}&c&=&1\\
		\text{II:}&b&=&0&\\
		\text{III:}&2a&=&-1
	\end{array}\\\\
	&\text{I:}\quad c=1\\\\
	&\text{II:}\quad b=0\\\\
	&\text{III:}\quad2a=-1\quad\Rightarrow\quad a=-\frac{1}{2}
\end{align}
$$
Somit lautet die Lösung:
- $a=-\frac{1}{2}$
- $b=0$
- $c=1$
Die Funktion $f_2$ lautet $f_2(x)=-\frac{1}{2}x^2+1$.
```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-1.57080,1.57080,-1,1]
disableZoom: true
grid: true
---
f(x)=cos(x)
g(x)=-0.5x^2+1
```
- $\textcolor{Blue}{f(x)=\cos(x)}$
- $\textcolor{Red}{f_2(x)}$

---
## 13b)
> Bestimmen Sie die ganzrationale Funktion $f_4$ vom Grad $4$ so, dass $f_4$ und die $\cos$-Funktion für $x=0$ denselben Funktionswert und dieselben Werte der $1$ten, $2$ten und $3$ten Ableitung haben. Zeichnen Sie den Graphen von $f_4$ in die vorhandene Abbildung ein.

Die Bedingungen folgen für die Funktion $f(x)=ax^4+bx^3+cx^2+dx+e$ mit $f'(x)=4ax^3+3bx^2+2cx+d$ und $f''(x)=12ax^2+6bx+2c$:
- $f(0)=1$
- $f'(0)=0$
- $f''(0)=-1$
- $f'''(0)=0$

$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:}&a\cdot0^4+b\cdot0^3+c\cdot0^2+d\cdot0+e&=&1\\
		\text{II:}&4a\cdot0^3+3b\cdot0^2+2c\cdot0+d&=&0\\
		\text{III:}&12a\cdot0^2+6b\cdot0+2c&=&-1\\
		\text{IV:}&24a\cdot0+6b&=&0
	\end{array}\\\\
	&\begin{array}{r|rrc|l}
		\text{I:}&e&=&1&\\
		\text{II:}&d&=&0\\
		\text{III:}&2c&=&-1\\
		\text{IV:}&6b&=&0
	\end{array}\\\\
	&\text{I:}\quad e=1\\\\
	&\text{II:}\quad d=0\\\\
	&\text{III:}\quad2c=-1\quad\Rightarrow\quad c=-\frac{1}{2}\\\\
	&\text{IV:}\quad2b=0\quad\Rightarrow\quad b=0\\\\
\end{align}
$$
Somit lautet die Lösung:
- $a=a$;
- $b=0$
- $c=-\frac{1}{2}$
- $d=0$
- $e=1$
Die Funktion $f_4$ lautet $f_4(x)=ax^4-\frac{1}{2}x^2+1$.
> Da es sich um Taylorpolynome handelt, muss folgendes gelten:

- $a=\frac{f^n(0)}{n!}=\frac{\cos(0)}{24}=\frac{1}{24}$
Demnach: $f_4(x)=\frac{1}{24}x^4-\frac{1}{2}x^2+1$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-1.57080,1.57080,-1,1]
disableZoom: true
grid: true
---
f(x)=cos(x)
g(x)=-0.5x^2+1
h(x)=1/24x^4-0.5x^2+1
```
- $\textcolor{Blue}{f(x)=\cos(x)}$
- $\textcolor{Red}{f_2(x)}$
- $\textcolor{Green}{f_4(x)}$

---
## 13c)
> Berechnen Sie $\cos(1)$ und $f_4(1)$. Wie groß ist der Fehler, wenn man $\cos(1)=f_4(1)$ setzt?

$$
\begin{align}
	\cos(1)&=f_4(1)\\
	\cos(1)&=\frac{1}{24}\cdot1^4-\frac{1}{2}\cdot1^2+1\\
	\cos(1)&=\frac{1}{24}-\frac{1}{2}+1\\
	0,5403&=0,541\overline{6}
\end{align}
$$
Der Fehler ist $\Delta y=0,0013\overline{6}$.

---
## 13d)
> Bestimmen Sie entsprechend eine Funktion $f_6$. Vergleichen Sie $f_6(1)$ bis $\cos(1)$.

Für Taylorpolynome gilt: $f_n(x)=\sum^{n}_{k=0}\frac{f^k(x_0)}{k!}\cdot(x-x_0)^k$.
Daraus folglich gilt für $x_0=0$, $n=6$ und $f(x)=\cos(x)$:
$$
\begin{align}
	f_n(x)&=\sum^{n}_{k=0}\frac{f^k(x_0)}{k!}\cdot(x-x_0)^k\\
	f_6(x)&=\sum^{6}_{k=0}\frac{f^k(0)}{k!}\cdot x^k\\
	&=\frac{f^6(0)}{6!}\cdot x^6+\frac{f^5(0)}{5!}\cdot x^5+\frac{f^4(0)}{4!}\cdot x^4+\frac{f^3(0)}{3!}\cdot x^3+\frac{f^2(0)}{2!}\cdot x^2+\frac{f^1(0)}{1!}\cdot x^1+\frac{f^0(0)}{0!}\cdot x^0\\
	
	&=\frac{-\cos(0)}{6!}\cdot x^6+\frac{-\sin(0)}{5!}\cdot x^5+\frac{\cos(0)}{4!}\cdot x^4+\frac{\sin(0)}{3!}\cdot x^3+\frac{-\cos(0)}{2!}\cdot x^2+\frac{-\sin(0)}{1!}\cdot x^1+\frac{\cos(0)}{0!}\\
	
	&=\frac{-1}{720}\cdot x^6+\frac{0}{120}\cdot x^5+\frac{1}{24}\cdot x^4+\frac{0}{6}\cdot x^3+\frac{-1}{2}\cdot x^2+\frac{0}{1}\cdot x^1+1\\
	
	f_6(x)&=-\frac{1}{720}\cdot x^6+\frac{1}{24}\cdot x^4-\frac{1}{2}\cdot x^2+1
\end{align}
$$

Die Funktion $f_6$ lautet $f_6(x)=-\frac{1}{720}\cdot x^6+\frac{1}{24}\cdot x^4-\frac{1}{2}\cdot x^2+1$.

$$
\begin{align}
	\cos(1)&=f_6(1)\\
	\cos(1)&=-\frac{1}{720}\cdot 1^6+\frac{1}{24}\cdot 1^4-\frac{1}{2}\cdot 1^2+1\\
	\cos(1)&=-\frac{1}{720}+\frac{1}{24}-\frac{1}{2}+1\\
	0,5403&=0,5402\overline{7}
\end{align}
$$
Der Fehler ist $\Delta y\approx0,000~0245$.

> $f_6(1)$ ist ähnlich zu $\cos(1)$. In kleineren Intervallen lässt sich demnach $\cos(x)$ durch $f_6(x)$ annähern.

---
---