> Für welche reellen Zahlen $c$ liegt der Punkt $P$ innerhalb der Kugel, auf der Kugel bzw. außerhalb der Kugel mit der Gleichung $x_1^2+x_2^2+x_3^2-4x_1+6x_2-2x_3-36=0$?

---
## a)
Gegeben ist $P(3\mid2\mid c)$.
Der Punkt $P$ ist auf der Kugel, wenn:
- $x_1^2+x_2^2+x_3^2-4x_1+6x_2-2x_3=36$.
Der Punkt $P$ ist in der Kugel, wenn:
- $x_1^2+x_2^2+x_3^2-4x_1+6x_2-2x_3<36$.
Der Punkt $P$ ist außerhalb der Kugel, wenn:
- $x_1^2+x_2^2+x_3^2-4x_1+6x_2-2x_3>36$.

>Vereinfachung der Gleichung nach Einsetzen von $P$:
- $x_1=3$
- $x_2=2$
- $x_3=c$

$$
\begin{align}
x_1^2+x_2^2+x_3^2-4x_1+6x_2-2x_3&=36\\
3^2+2^2+c^2-4\cdot3+6\cdot 2-2c&=36&&\mid-13\\
c^2-2c&=23&&\mid-23\\
c^2-2c-23&=0
\end{align}
$$

---
Punkt $P$ ist auf der Kugel:
$$
\begin{align}
	c^2-2c-23&=0&&\mid \text{pq-Formel}\\
	c_{1;2}&=-\frac{p}{2}\mp\sqrt{\left(\frac{p}{2}\right)^2-q}&&\mid\boxed{p=-2\qquad q=-23}\\
	
	&=-\frac{-2}{2}\mp\sqrt{\left(\frac{-2}{2}\right)^2+23}\\
	&=1\mp \sqrt{24}
\end{align}
$$
Daraus folgt, dass $c_1=1-2\sqrt{6}$, oder $c_2=1+2\sqrt{6}$ sein muss, damit $P$ auf der Kugel liegt.

---
---
>Da $c_1$ und $c_2$ Grenzen zwischen $\text{"Punkt innerhalb"}$ und $\text{"Punkt außerhalb"}$ sind, so sind diese ebenfalls in den Intervallen auffindbar.
>Somit gilt:
- Auf: $c\in\{c_1;c_2\}$
- In: $c\in\left(c_1;c_2\right)$
- Außerhalb: $c\in\left(-\infty;c_1\right)\cup\left(c_2;\infty\right)$

Daraus folgt:
- Auf: $c\in\{1-2\sqrt{6};1+2\sqrt{6}\}$
- In: $c\in\left(1-2\sqrt{6};1+2\sqrt{6}\right)$
- Außerhalb: $c\in\left(-\infty;1-2\sqrt{6}\right)\cup\left(1+2\sqrt{6};\infty\right)$.

---
---
---
---
## d)
>Vereinfachung der Gleichung nach Einsetzen von $P$:
- $x_1=0$
- $x_2=0$
- $x_3=c$

$$
\begin{align}
	x_1^2+x_2^2+x_3^2-4x_1+6x_2-2x_3&=36\\
	0^2+0^2+c^2-0\cdot3+0\cdot 2-2c&=36\\
	c^2-2c&=36&&\mid-36\\
	c^2-2c-36&=0&&\mid\text{pq-Formel}\\
	c_{1;2}&=-\frac{p}{2}\mp\sqrt{\left(\frac{p}{2}\right)^2-q}
		&&\mid\boxed{p=-2\qquad q=-36}\\
	&=-\frac{-2}{2}\mp\sqrt{\left(\frac{-2}{2}\right)^2+36}\\
	&=1\mp\sqrt{37}
\end{align}
$$

---
Daraus folgt, dass $c_1=1-\sqrt{37}$, oder $c_2=1+\sqrt{37}$ sein muss, damit $P$ auf der Kugel liegt.

---
---
>Da $c_1$ und $c_2$ Grenzen zwischen $\text{"Punkt innerhalb"}$ und $\text{"Punkt außerhalb"}$ sind, so sind diese ebenfalls in den Intervallen auffindbar.
>Somit gilt:
- Auf: $c\in\{c_1;c_2\}$
- In: $c\in\left(c_1;c_2\right)$
- Außerhalb: $c\in\left(-\infty;c_1\right)\cup\left(c_2;\infty\right)$

Daraus folgt:
- Auf: $c\in\{1-\sqrt{37};1+\sqrt{37}\}$
- In: $c\in\left(1-\sqrt{37};1+\sqrt{37}\right)$
- Außerhalb: $c\in\left(-\infty;1-\sqrt{37}\right)\cup\left(1+\sqrt{37};\infty\right)$.

---
---