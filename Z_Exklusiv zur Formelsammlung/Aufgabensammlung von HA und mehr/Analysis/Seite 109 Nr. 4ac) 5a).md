> Bestimmen Sie alle ganzrationalen Funktionen vom Grad $3$, deren Graph durch die Punkte geht.

## a)
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
## c)
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

# Aufgabe 5
> Bestimmen Sie eine ganzrationale Funktion vom Grad $3$, deren Graph

## a)
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