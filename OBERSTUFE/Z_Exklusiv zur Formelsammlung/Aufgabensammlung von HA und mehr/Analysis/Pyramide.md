> Aus einem Kreis mit dem Radius $r$ wird ein symmetrischer Stern ausgeschnitten und die vier Ecken $A$, $B$, $C$, $D$ zur Spitze einer quadratischen Pyramide hochgebogen. Wie groß kann das Volumen der entstehenden Pyramide höchstens werden? Wie groß ist in diesem Fall die Pyramidenoberfläche?

![[Pyramide11.png]]

---
## Hauptbedingung
> Das Volumen soll maximal sein.

Das Volumen bildet sich aus der sich ergebenen Höhe, die die gefaltenen Seiten ergeben. Im folgenden ist dieses Falten seitlich dargestellt:
![[Seite.png]]
Hier ist das grüne weiterhin die Kante mit Länge $d$. Die gesamtstrecke von zwei gegenüberstehenden Punkten beträgt $2r$. Somit erhalten wir für die Länge der einzelnen Faltseiten (folgend mit $l$):
$$
\begin{align}
	2r&=2l+d&&\mid-d\\
	2l&=2r-d&&\mid\div2\\
	l&=r-\frac{d}{2}
\end{align}
$$
$l$ ist hier die Hypotenuse des Dreiecks zwischen der Faltecke, der Spitze und dem Mittelpunkt des Kreises. Die höhe dieses halben Dreiecks ist dann:
$$
\begin{align}
	\left(r-\frac{d}{2}\right)^2&=\left(\frac{d}{2}\right)^2+h^2\\
	h&=\sqrt{\left(r-\frac{d}{2}\right)^2-\left(\frac{d}{2}\right)^2}\\
	&=\sqrt{r^2-dr+\frac{d^2}{4}-\frac{d^2}{4}}\\
	&=\sqrt{r^2-dr}\\
\end{align}
$$
Die Höhe der gefalteten Pyramide ist somit $h=\sqrt{r^2-dr}$.

Daraus bildet sich folgende Hauptbedingung:
$$
\begin{align}
	V(d;r)&=\frac{1}{3}\cdot d^2\cdot\sqrt{r^2-dr}
\end{align}
$$

>Da der Radius von dem Kreis zu $d$ unabhängig ist, ändere ich die Betrachtungsweise $d$ prozentual zu $r$.

$$
\begin{align}
	V(p)&=\frac{1}{3}\cdot p^2\cdot\sqrt{1^2-p\cdot 1}\\
	&=\frac{1}{3}\cdot p^2\cdot\sqrt{1-p}~~;\quad 0\le p\le1
\end{align}
$$

---
## Extremwertanalyse
$$ \begin{aligned}
	\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad V'(p)=0 \\
	0&=V'(d)\\
	0&=\frac{2}{3}\cdot p\cdot\sqrt{1-p}-\frac{1}{6}\cdot p^{2}\cdot\frac{1}{\sqrt{1-p}}\\
	\\
	p_1=0\quad&\vee\quad 0=\frac{2}{3}\cdot\sqrt{1-p}-\frac{1}{6}\cdot p\cdot\frac{1}{\sqrt{1-p}}\\\\
	0&=\frac{2}{3}\cdot\sqrt{1-p}-\frac{1}{6}\cdot p\cdot\frac{1}{\sqrt{1-p}}&&\mid-\frac{2}{3}\cdot\sqrt{1-p}\\
	-\frac{2}{3}\cdot\sqrt{1-p}&=-\frac{1}{6}\cdot p\cdot\frac{1}{\sqrt{1-p}}&&\mid\cdot(-6)\\
	4\cdot\sqrt{1-p}&=p\cdot\frac{1}{\sqrt{1-p}}&&\mid\cdot\sqrt{1-p}\\
	4\cdot(1-p)&=p\\
	4-4p&=p&&\mid+4p\\
	4&=5p&&\mid\div5\\
	p&=\frac{4}{5}=0,8
\end{aligned}$$

$$
\begin{align}
\text{Erstes hinreichendes Kriterium}&\text{ für lokale Extrema:}\quad V''(p)\ne0\\
	V''(p)&=\frac{2}{3}\cdot\sqrt{1-x}-\frac{2}{3}x\cdot\frac{1}{\sqrt{1-x}}-\frac{1}{12}\cdot x^{2}\cdot\left(1-x\right)^{-\frac{3}{2}}\\
	V''(0,8)&=
		\frac{2}{3}\cdot\sqrt{1-0,8}-\frac{2}{3}\cdot0,8\cdot\frac{1}{\sqrt{1-0,8}}-\frac{1}{12}\cdot 0,8^{2}\cdot\left(1-0,8\right)^{-\frac{3}{2}}\\
		&\approx-1,491<0
\end{align}$$
Weil $p=0,8$ durch $V''(0,8)<0$ ein Hochpunkt ist, so ist die optimale Länge $d$ exakt $80\%$ von $r$.
$$
\begin{align}
	V(d;r)&=\frac{1}{3}\cdot d^2\cdot\sqrt{r^2-dr}\\
	V(0,8r;r)&=\frac{1}{3}\cdot (0,8r)^2\cdot\sqrt{r^2-0,8r\cdot r}\\
	&=\frac{16}{75}r^2\cdot\sqrt{r^2-0,8r^2}\\
	&=\frac{16}{75}r^2\cdot\sqrt{0,2r^2}\\
	&=\frac{16}{75}r^2\cdot\sqrt{0,2}\cdot r
\end{align}
$$

---
## Oberfläche
Die Oberfläche der Pyramide:
$$
\begin{align}
	O(d;r)&=d^2+4\cdot\left[d\cdot l\cdot \frac{1}{2}\right]\\
	&=d^2+2\cdot d\cdot l
\end{align}
$$
Setzen wir ein, so erhalten wir:
$$
\begin{align}
	O(r)&=d^2+2\cdot \overbrace{d}^{=0,8r}\cdot \underbrace{l}_{=r~-\frac{\overbrace{d}^{=0,8r}}{2}}\\
	O(r)&=\frac{16}{25}r^2+2\cdot 0,8r\cdot \left(r-0,4r\right)\\
	&=\frac{16}{25}r^2+0,96r
\end{align}
$$

---