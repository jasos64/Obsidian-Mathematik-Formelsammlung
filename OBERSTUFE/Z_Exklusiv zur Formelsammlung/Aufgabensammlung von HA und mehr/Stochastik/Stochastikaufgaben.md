# a)
Für das Baumdiagramm gilt im letzten Zweig:
$$
\begin{align}
	P(\overline{T}\cap\overline{L})+P(T\cap\overline{L})&=
		\textcolor{green}{P(\overline{T}\cap L)}+P(T\cap L)\\
	P(\overline{T}\cap\overline{L})+P(T\cap\overline{L})&=
		\textcolor{green}{0,3}+P(T\cap L)\\
	\underbrace{\textcolor{orange}{P(\overline{T}\cap\overline{L})}}_{\text{Aus Diagramm}}
	+P(T\cap\overline{L})&=
		\textcolor{green}{0,3}+P(T\cap L)\\
	\textcolor{orange}{0,4}
	+P(T\cap\overline{L})&=
		\textcolor{green}{0,3}+P(T\cap L)\\
	P(T\cap\overline{L})-P(T\cap L)&=0,3-0,4\\
	P(T\cap\overline{L})-P(T\cap L)&=-0,1\\\hline\\
	\overbrace{P(T\cap\overline{L})+P(T\cap L)}^{\text{Aus Diagramm}}&=0,3\\\\
	\hline\\
	
	
	&\begin{array}{r|rc|}
		\text{I:} & P(T\cap\overline{L})-P(T\cap L)&=&-0,1\\
		\text{II:} & P(T\cap\overline{L})+P(T\cap L) &=&0,3
	\end{array}\\\\
	&P(T\cap\overline{L})=0,1\\
	&P(T\cap L)=0,2
\end{align}
$$

---
## c)
> Der Verkäufer behauptet, dass im letzten Jahr unter $1000$ Bestellungen $80\%$ Stühle sind. Um diese Hypothese zu prüfen soll ein geeigneter Hypothesentest erstellt werden. Der Hypothese soll zugestimmt werden, wenn eine Stichprobenanzahl innerhalb des $2\sigma$-Intervalls ist. Berechnen Sie den Fehler 1. Art.

Wir haben eine Binomialverteilung gegeben nach:
- $X\sim B(1000;0,8)$
- $X:\text{Anzahl Stühle unter den }1000$
Es folgt ein zweiseitiger Hypothesentest nach
- $H_0:p=0,8$
- $H_1:p\ne0,8$

> Berechnung des Sigmaintervalls

$$
\begin{align}
	\sigma&=\sqrt{n\cdot p\cdot(1-p)}\\
	&=\sqrt{1000\cdot0,8\cdot0,2}=4\sqrt{10}\\\\
	\mu&=n\cdot p=1000\cdot0,8=800
\end{align}
$$
Für das Intervall gilt:
$$
\begin{align}
	I:&\left[\left\lceil\mu-2\sigma\right\rceil;\left\lfloor\mu+2\sigma\right\rfloor\right]\\
	&\left[\left\lceil800-2\cdot4\sqrt{10}\right\rceil;\left\lfloor800+2\cdot4\sqrt{10}\right\rfloor\right]\\
	&\left[\left\lceil800-8\sqrt{10}\right\rceil;\left\lfloor800+8\sqrt{10}\right\rfloor\right]\\
	&\left[\left\lceil774,702\right\rceil;
		\left\lfloor825,298\right\rfloor\right]\\
	&\left[775;825\right]
\end{align}
$$

Es folgt im weiteren die Berechnung des Flächeninhaltes außerhalb diesen Intervalls.
