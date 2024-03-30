## Analysis
### 1)
Die Wachstumsrate einer Waldfläche in $km^2$ kann für die ersten $24$ Monaten durch die Funktion $\omega(t)=0,01(t^2 -36t+288)e^{0,1t}$ dargestellt werden. Die Waldfläche ist zu Beginn $4km$ groß. ($\omega(t)$ in $\frac{km^2}{m}$).
#### a)
>Bestimmen Sie den Zeitbereich, in welchem durch ein Waldsterben die Waldfläche reduziert wird.

$$
\begin{align}
	\textbf{Notwendiges Kriterium für }&\textbf{Monotonieverhalten}: \omega(t)=0\\
	0&=\omega(t)\\
	0&=0,01(t^2 -36t+288)e^{0,1t}&&\mid\div0,01\\
	0&=(t^2 -36t+288)e^{0,1t}\\
	0=t^2 -36t+288\quad&\vee\quad0=e^{0,1t}\\
	\mathbb{L}=\{12;24\}~~~~~~\,\qquad&{\quad}\quad\mathbb{L}=\{\}\\\\
	x_1=12\quad&\vee\quad x_2=24\\\\
	
	\textbf{Intervallbildung für }&\textbf{Monotonieverhalten}:\\
	I_1&=\left[0;12\right[\\
	I_2&=\left]12;24\right[\\\\
	
	\text{Vorzeichen von }\omega(t) &\text{ auf }I_1:\\
	w(t)&=0,01(t^2 -36t+288)e^{0,1t}\\
	w(1)&=0,01\cdot(1 -36+288)\cdot e^{0,1}\\
	&=0,01\cdot(253)\cdot e^{0,1}>0\\
	
	\text{Vorzeichen von }\omega(t) &\text{ auf }I_2:\\
	w(t)&=0,01(t^2 -36t+288)e^{0,1t}\\
	w(13)&=0,01\cdot(13^2-36\cdot13+288)\cdot e^{0,1\cdot13}\\
	&=0,01\cdot(-11)\cdot e^{1,3}<0
\end{align}
$$
Weil $\omega(13)$ negativ ist, so ist das Monotonieverhalten von einer Stammfunktion von $\omega$ auf $I_2$ streng monoton fallend.
>Das Waldsterben lässt somit die Waldfläche zwischen $12$ und $24$ Monaten kleiner werden.

#### b)
>Bestimmen Sie die maximale Wachstumsrate der Waldfläche, und geben Sie diese im Sachzusammenhang an.

$$
\begin{align}
	\omega(t)&=0,01(t^2 -36t+288)e^{0,1t}\\
	\omega'(t)&=0,01\left(\left(2t -36\right)e^{0,1t}+\left(t^2 -36t+288\right)e^{0,1t}\cdot0,1\right)\\
	&=0,01
	\left(
		\left(2t -36\right)e^{0,1t}+0,1\left(t^2 -36t+288\right)e^{0,1t}
	\right)\\
	&=0,01
	\left(
		\left(2t -36\right)+\left(0,1t^2 -3,6t+28,8\right)
	\right)e^{0,1t}\\
	\omega'(t)&=0,01
	\left(
		0,1x^{2}-1,6x-7,2
	\right)e^{0,1t}
\end{align}
$$

$$
\begin{align}
	\textbf{Notwendiges Kriterium für }&\textbf{lokale Extrema}: \omega'(t)=0, \quad x\in\left[0;24\right]\\
	0&=\omega'(t)\\
	0&=0,01\left(0,1x^{2}-1,6x-7,2\right)e^{0,1t}&&\mid\div0,01\\
	0&=\left(0,1x^{2}-1,6x-7,2\right)e^{0,1t}\\
	0=0,1x^{2}-1,6x-7,2\quad&\vee\quad0=e^{0,1t}\\
	\mathbb{L}=\{8-\sqrt{136};8+\sqrt{136}\}~~~~~~\,\qquad&{\quad}\quad\mathbb{L}=\{\}\\
	\approx\{-3,66;19,66\}~~~~~~\,\qquad&{\quad}\\\\
	x_1&=8+\sqrt{136}\approx19,66\\\\
\end{align}
$$