> Gegeben ist die Kurvenschar $f_a(x)=\frac{1}{2}x^4-ax^2\quad(a>0)$.

## a)
> Diskutieren Sie die Kurvenschar allgemein.

Nullstellen der Funktion:
$$
\begin{align}
	0&=f_a(x)\\
	0&=\frac{1}{2}x^4-ax^2\\
	0&=x^2\left(\frac{1}{2}x^2-a\right)\\\\
	0&=\frac{1}{2}x^2-a&&\mid+a\\
	a&=\frac{1}{2}x^2&&\mid\cdot2\\
	2a&=x^2&&\mid\sqrt{}\\
	x_{1;2}&=\mp\sqrt{2a}
\end{align}
$$
>Daraus ergibt sich für alle $a>0$ folgendes:
- $N_1(-\sqrt{2a}\mid0)$
- $N_2(0\mid0)$
- $N_3(0\mid0)$
- $N_4(\sqrt{2a}\mid0)$

---
$$ \begin{aligned}
\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad f_a'(x)=0 \\
0&=f_a'(x)\\
0&=2x^3-2ax\\
0&=x(2x^2-2a)\\
0&=2x^2-2a&&\mid+2a\\
2a&=2x^2&&\mid\div2\\
a&=x^2&&\mid\sqrt{}\\
x_{1;3}&=\mp\sqrt{a}
\end{aligned}$$
- $x_1=-\sqrt{a}$
- $x_2=0$
- $x_3=\sqrt{a}$

$$
\begin{align}
\text{Erstes hinrichteichendes Kriterium}&\text{ für lokale Extrema:}\quad f_a''(x)\ne0\\
f_a''(x)&=6x^2-2a\\
f_a''(-\sqrt{a})&=6\left(-\sqrt{a}\right)^2-2a\\
&=6a-2a\\
&=4a>0\\\\
f_a''(x)&=6x^2-2a\\
f_a''(0)&=6(0)^2-2a\\
&=-2a<0\\\\
f_a''(\sqrt{a})&=6\left(\sqrt{a}\right)^2-2a\\
&=6a-2a\\
&=4a>0
\end{align}$$
>Daraus ergibt sich für alle $a>0$ folgendes:
- Hochpunkt: $E_2(0\mid0)$
- Tiefpunkt: $E_1(-\sqrt{a}\mid-\frac{1}{2}a^2)$
- Tiefpunkt: $E_3(\sqrt{a}\mid-\frac{1}{2}a^2)$

---
$$ \begin{aligned}
\text{Notwendiges Kriterium}&\text{ Wendestellen:}\quad f_a''(x)=0 \\
0&=f_a''(x)\\
0&=6x^2-2a\mid+2a\\
2a&=6x^2&&\mid\div6\\
\frac{a}{3}&=x^2&&\mid\sqrt{}\\
x_{1;2}&=\mp\sqrt{\frac{a}{3}}
\end{aligned}$$
$$
\begin{align}
\text{Erstes hinrichteichendes Kriterium}&\text{ für Wendestellen:}\quad f_a'''(x)\ne0\\
f_a'''(x)&=12x\\
f_a''\left(-\sqrt{\frac{a}{3}}\right)&=12\left(-\sqrt{\frac{a}{3}}\right)\\
&=-12\sqrt{\frac{a}{3}}<0\\\\
f_a''\left(\sqrt{\frac{a}{3}}\right)&=12\left(\sqrt{\frac{a}{3}}\right)\\
&=12\sqrt{\frac{a}{3}}>0\\\\
\end{align}$$
Daraus ergibt sich für alle $a>0$ folgendes:
- Links-Rechts WP: $W_1\left(-\sqrt{\frac{a}{3}}\mid-\frac{5a^{2}}{18}\right)$
- Rechts-Links WP: $W_2\left(\sqrt{\frac{a}{3}}\mid-\frac{5a^{2}}{18}\right)$

---
Aus diesen Informationen folgen folgende Monotonieintervalle:
- Streng monoton steigend in: $x\in\bigg\{~~\left]-\sqrt{a};0\right[~~;~~\left]\sqrt{a};\infty\right[~~\bigg\}$
- Streng monoton fallend in: $x\in\bigg\{~~\left]-\infty;-\sqrt{a}\right[~~;~~\left]0;\sqrt{a}\right[~~\bigg\}$

---
Verhalten im unendlichen.
Durch den $\frac{1}{2}x^4$ als Polynom größten Grades ergibt sich für das Grenzverhalten:
- $\lim_{x\to\infty}f_a(x)=\infty$
- $\lim_{x\to-\infty}f_a(x)=\infty$

---
## b)
> Ortskurve Extrempunkte:

Von oben sind die Extrema bei
- $x_1=-\sqrt{a}$
- $x_2=0$
- $x_3=\sqrt{a}$
Umgestellt ergibt sich daraus:
- $a=x_1^2$
- $0=x_2$
- $a=x_3^2$
Die Ortskurve lautet daher:
$$
\begin{align}
	o(x)&=\frac{1}{2}x^4-x^2\cdot x^2\\
	&=-\frac{1}{2}x^4
\end{align}
$$

> Ortskurve der Wendepunkte:

Von oben sind die Wendepunkte bei:
- $x_1=-\sqrt{\frac{a}{3}}$
- $x_2=\sqrt{\frac{a}{3}}$
Umgestellt ergibt sich daraus:
- $a=3x_1^2$
- $a=3x_2^2$
Die Ortskurve lautet daher:
$$
\begin{align}
	o(x)&=\frac{1}{2}x^4-3x^2\cdot x^2\\
	&=-\frac{5}{2}x^4
\end{align}
$$

---
---