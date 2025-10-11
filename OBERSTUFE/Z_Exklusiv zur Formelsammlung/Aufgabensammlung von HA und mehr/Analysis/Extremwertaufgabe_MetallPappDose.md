> Eine aus Metall und Pappe gebaute Dose soll gebaut werden. Diese soll ein Fassungsvolumen von $V=1000~cm^3$ besitzen und durch einen Zylinder modelliert werden. Der Mantel ist aus Pappe, die Ober- und Unterseiten sind aus Metall.
> Der Preis der verwendeten Pappe kostet $P_P$, wobei der Preis des Metalls pro Quadratzentimeter ($P_M$) viermal so viel wie $P_P$ ist.
> Welche Oberfläche kostet am wenigsten?

Aus der Beschreibung erkennen wir:
$$P_M=4P_P$$
Ein Zylinder besitzt folgende Eigenschaften:
- $O(r;h)=\underbrace{2\pi r^2}_{\text{Grundseiten}}+\underbrace{2\pi rh}_{\text{Mantel}}$
- $V(r;h)=\pi r^2h$

---
## 1. Hauptbedingung
Der Preis der Materialien soll minimiert werden. Dieser Wird durch $P(r;h)=P_M\cdot2\pi r^2+P_P\cdot2\pi rh$ gegeben. Durch einsetzen von $P_M=4P_P$ in $P(r;h)$, erhalten wir das folgende:
$$
\begin{align}
	P(r;h)&=\textcolor{orange}{P_M}\cdot2\pi r^2+P_P\cdot2\pi rh\\
	&=\textcolor{orange}{4P_P}\cdot2\pi r^2+P_P\cdot2\pi rh\\
	P(r;h)&=8P_P\cdot\pi r^2+2P_P\cdot\pi rh\\
\end{align}
$$

---
# 2. Nebenbedingung
Die Dose muss ein Fassungsvolumen von exakt $1000~cm^3$ besitzen. Daher gilt für die Nebenbedingung das folgende, wobei nach $h$ umgestellt wird.
$$
\begin{align}
	V(r;h)&=\pi r^2h\\
	1000&=\pi r^2h&&\mid\div(\pi r^2)\\
	h&=\frac{1000}{\pi r^2}
\end{align}
$$

---
## 3. Zielfunktion
Die Nebenbedingung nach $h$ wird in die Hauptbedingung eingesetzt:
$$
\begin{align}
	P(r;h)&=8P_P\cdot\pi r^2+2P_P\cdot\pi rh\\
	P(r)&=8P_P\cdot\pi r^2+\textcolor{orange}2P_P\cdot\textcolor{red}{\pi r}\cdot\frac{\textcolor{orange}{1000}}{\textcolor{red}\pi r^\textcolor{red}2}\\
	&=8P_P\cdot\pi r^2+P_P\cdot\frac{\textcolor{orange}{2000}}{r}\\
	P(r)&=8P_P\cdot\pi r^2+P_P\cdot\frac{2000}{r}
\end{align}
$$

---
## 4. Extrema von $P(r)$
$$ \begin{aligned}
	\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad P'(r)=0 \\
	0&=V'(d)\\
	0&=16P_P\cdot\pi r-P_P\cdot\frac{2000}{r^2}&&\mid\div P_P\\
	0&=16\pi r-\frac{2000}{r^2}&&\mid\cdot r^2\\
	0&=16\pi r^3-2000&&\mid+2000\\
	2000&=16\pi r^3&&\mid\div16\pi\\
	r^3&=\frac{2000}{16\pi}\\
	r^3&=\frac{125}{\pi}&&\mid\sqrt[3]{}\\
	r&=\sqrt[3]{\frac{125}{\pi}}
\end{aligned}$$
$$
\begin{align}
\text{Erstes hinreichendes Kriterium}&\text{ für lokale Extrema:}\quad P''(r)\ne0\\
	P''(r)&=16P_P\cdot\pi+P_P\cdot\frac{4000}{r^3}\\
	P''\left(\sqrt[3]{\frac{125}{\pi}}\right)&=
		16P_P\cdot\pi+P_P\cdot\frac{4000}{\left[\sqrt[3]{\frac{125}{\pi}}\right]^3}\\
	&=
	16P_P\cdot\pi+P_P\cdot\frac{4000}{\frac{125}{\pi}}>0\\
\end{align}$$
Da der Preis $P_P$ positiv ist, so ist hier der Minimalkostenpreis mit dem Radius $r=\sqrt[3]{\frac{125}{\pi}}\approx3,414~cm$ erreicht. Die Höhe hier ist:
$$
\begin{align}
	h&=\frac{1000}{\pi r^2}\\
	h&=\frac{1000}{\pi \left(\sqrt[3]{\frac{125}{\pi}}\right)^2}\approx27,311~cm
\end{align}
$$

Die Minimaloberfläche ist:
$$
\begin{align}
	O\left(\sqrt[3]{\frac{125}{\pi}};\frac{1000}{\pi \left(\sqrt[3]{\frac{125}{\pi}}\right)^2}\right)=2\pi \left(\sqrt[3]{\frac{125}{\pi}}\right)^2+2\pi \sqrt[3]{\frac{125}{\pi}}\cdot \frac{1000}{\pi \left(\sqrt[3]{\frac{125}{\pi}}\right)^2}\approx659,066~cm^2
\end{align}
$$
Mit diesen Werten ist der Kostenaufwand für die Materialien am geringsten.