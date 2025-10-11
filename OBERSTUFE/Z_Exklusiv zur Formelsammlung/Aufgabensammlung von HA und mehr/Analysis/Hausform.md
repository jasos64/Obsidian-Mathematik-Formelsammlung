> Eine Fläche ist aus einem Rechteck und zwei gleichseitigen Dreiecken aufgebaut. Die Abbildung verdeutlicht den Aufbau konkret. Der Umfang soll $100~cm$ sein, während die Gesamtfläche maximal ist.

![[HausForm.png]]
Wir erkennen das Rechteck mit den Maßen $a\times b$, und die zwei gleichseitigen Dreiecke mit Seitenlängen $\frac{a}{2}$.

---
## Hauptbedingung
> Die Fläche soll maximiert werden. Daraus folgt folgende Hauptbedingung, wobei $h$ die Höhe eines Dreiecks ist:

$$
\begin{align}
	A(a;b)&=a\cdot b+2\cdot\left(\frac{1}{2}\cdot\frac{a}{2}\cdot h\right)\\
	A(a;b)&=a\cdot b+\frac{a}{2}\cdot h
\end{align}
$$
Die Höhe $h$ lässt sich mittels des Dreiecks selbst bestimmen.
![[Dreieck.png]]
Hier ergibt sich für $h$:
$$
\begin{align}
	\frac{a^2}{2^2}&=\frac{a^2}{4^2}+h^2&&\mid-\frac{a^2}{4^2}\\
	h^2&=\frac{a^2}{2^2}-\frac{a^2}{4^2}\\
	h^2&=\frac{4a^2}{16}-\frac{a^2}{16}\\
	h^2&=\frac{4a^2-a^2}{16}\\
	h^2&=\frac{3a^2}{16}&&\mid\sqrt{}\\
	h&=\frac{\sqrt{3}\cdot a}{4}
\end{align}
$$
Die Hauptbedingung ist daher:
$$
\begin{align}
	A(a;b)&=a\cdot b+\frac{a}{2}\cdot h\\
	A(a;b)&=a\cdot b+\frac{\textcolor{orange}a}{\textcolor{Blue}2}\cdot \frac{\sqrt{3}\cdot \textcolor{orange}a}{\textcolor{Blue}4}\\
	A(a;b)&=a\cdot b+\frac{\sqrt{3}\cdot \textcolor{orange}{a^2}}{\textcolor{Blue}8}
\end{align}
$$

---
## Nebenbedingung
> Der Umfang beschreibt die Nebenbedingung.

$$
\begin{align}
	100&=a+2b+4\cdot\frac{a}{2}\\
	100&=a+2b+2a\\
	100&=3a+2b&&\mid-3a\\
	2b&=100-3a&&\mid\div2\\
	b&=\frac{100-3a}{2}
\end{align}
$$

---
## Zielfunktion
> Die Nebenbedingung nach $b$ wird in $A(a;b)$ eingesetzt.

$$
\begin{align}
	A(a;b)&=a\cdot b+\frac{\sqrt{3}\cdot a^2}{8}\\
	A\left(a;\frac{100-3a}{2}\right)&=a\cdot \frac{100-3a}{2}+\frac{\sqrt{3}\cdot a^2}{8}\\
	&=\frac{100a-3a^2}{2}+\frac{\sqrt{3}\cdot a^2}{8}\\
	&=\frac{400a-12a^2}{8}+\frac{\sqrt{3}\cdot a^2}{8}\\
	&=\frac{\sqrt{3}\cdot a^2-12a^2+400a}{8}\\
	&=\left(\frac{\sqrt{3}}{8}-\frac{12}{8}\right)a^2+\frac{400}{8}a\\
	A(a)&=\left(\frac{\sqrt{3}-12}{8}\right)a^2+50a\\
\end{align}
$$

---
## Extremwertanalyse
$$ \begin{aligned}
	\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad A'(a)=0 \\
	0&=A'(a)\\
	0&=\left(\frac{\sqrt{3}-12}{4}\right)a+50&&\mid-50\\
	-50&=\left(\frac{\sqrt{3}-12}{4}\right)a&&\mid\cdot\frac{4}{\sqrt{3}-12}\\
	a&=-50\cdot\frac{4}{\sqrt{3}-12}\\
	a&=\frac{200\sqrt{3} + 2400}{141}\approx19,478~cm
\end{aligned}$$

$$
\begin{align}
\text{Erstes hinreichendes Kriterium}&\text{ für lokale Extrema:}\quad A''(a)\ne0\\
	A''(a)&=\left(\frac{\sqrt{3}-12}{4}\right)\\
	A''\left(\frac{200\sqrt{3} + 2400}{141}\right)&=
		\left(\frac{\sqrt{3}-12}{4}\right)<0\\
\end{align}$$
$a=\frac{200\sqrt{3} + 2400}{141}$ ist die Kantenlänge, die eine maximale Fläche beschreibt.
Demnach gilt für $b$:
$$
\begin{align}
	b&=\frac{100-3a}{2}\\
	b&=\frac{100-3\cdot\frac{200\sqrt{3} + 2400}{141}}{2}\\
	&~~\vdots\\
	b&=\frac{6900-600\sqrt{3}}{282}\approx20,783~cm
\end{align}
$$

---