> Gegeben ist eine Oberfläche mit den Maßen $40~cm$ und $25~cm$. Eine nach oben offene Schachtel mit maximalem Volumen soll gefaltet werden. Das Schneiden der Oberfläche ist möglich.

Wir erkennen zunächst die Darstellung der Oberfläche:
![[BlattFalten.png]]
Die Oberfläche wird entlang der roten Linie gefaltet. Die blauen Linien stellen Schnitte in der Oberfläche dar. Das graue bildet am Ende die Schachtel.

---
## 1. Hauptbedingung
Das Volumen soll maximiert werden, daher lautet unsere Hauptbedingung:
$$
\begin{align}
	V(d)&=d\cdot\left(40-2d\right)\cdot\left(25-2d\right),\quad d\in[0;12,5]
\end{align}
$$
> Da es hier eine Hauptfunktion mit einer Abhängigkeit ist, so ist diese Funktion zugleich die Zielfunktion.

$$
\begin{align}
	V(d)&=d\cdot\left(40-2d\right)\cdot\left(25-2d\right)\\
	&=d\cdot\left(1000-80d-50d+4d^2\right)\\
	&=d\cdot\left(1000-130d+4d^2\right)\\
	&=4d^3-130d^2+1000d
\end{align}
$$

---
## Extremstellen der Zielfunktion $V(d)$
$$ \begin{aligned}
	\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad V'(d)=0 \\
	0&=V'(d)\\
	0&=12d^2-260d+1000&&\mid\div12\\
	0&=d^2-\frac{65}{3}d+\frac{250}{3}\\
	d_{1;2}&=-\frac{-\frac{65}{3}}{2}\pm
		\sqrt{\left(\frac{-\frac{65}{3}}{2}\right)^2-\frac{250}{3}}\\
	&=\frac{65}{6}\pm
		\sqrt{\left(-\frac{65}{6}\right)^2-\frac{250}{3}}\\
	&=\frac{65}{6}\pm\sqrt{\frac{1225}{36}}\\
	d_{1;2}&=\frac{65}{6}\pm\frac{35}{6}\\\\
	d_1&=\frac{65}{6}-\frac{35}{6}=5\\
	d_2&=\frac{65}{6}+\frac{35}{6}=\frac{50}{3}>12,5
\end{aligned}$$
Da hier $d_2=\frac{50}{3}$ größer als $12,5$ ist, so wird diese Stelle nicht weiter untersucht. (Siehe Definitionsbereich)
$$
\begin{align}
\text{Erstes hinreichendes Kriterium}&\text{ für lokale Extrema:}\quad V''(d)\ne0\\
V''(d)&=24d-260\\
V''(5)&=24\cdot5-260\\
&=-140<0
\end{align}$$

> Durch $V''(5)<0$ ist $d_1=5$ eine Lösung. An dieser Stelle hat die Zielfunktion $V(d)$ ein lokales Maximum mit dem Wert $V(5)=2250~cm^3$

---