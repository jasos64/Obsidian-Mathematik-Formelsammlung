Das Monotonieverhalten einer [[Funktion(en)]] beschreibt, wie sich diese diese auf einem Intervall $\text{I}=\left[a;b\right]$ verhält.

Es gelten folgende Aussagen, insofern $f$ auf $\text{I}$ differenzierbar ist:
>- Insofern $f'(x)>0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ streng monoton steigend.
>- Insofern $f'(x)<0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ streng monoton fallend.
>- Insofern $f'(x)\ge0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ monoton steigend.
>- Insofern $f'(x)\le0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ monoton fallend.

Die Definition einer nicht streng monotonen Funktion auf $\text{I}$ ist scheinbar nicht richtig definiert, da Unterschiede dieser ungleich sind.
Eine Definition ist die oben genannte. Eine weitere werde ich nun beschreiben.

---
Eine Funktion $f$ sei auf $\text{I}$ differenzierbar:
>- Insofern $f'(x)\ge0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ streng monoton steigend.
>- Insofern $f'(x)\le0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ streng monoton fallend.
>- Insofern $f'(x)\ge0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ monoton steigend.
>- Insofern $f'(x)\le0$ für alle $x\in \text{I}$, so ist $f(x)$ auf $\text{I}$ monoton fallend.

Der Zusatz zu diesen Beschreibungen ist der folgende Ausdruck, der so erfüllt strenge Monotonie andeutet:
$$\begin{array}{}\nexists x{_1}\in\text{I,}~f(x{_1}+\varepsilon)-f(x{_1})=0&&\boxed{\varepsilon^{2}=0,~\varepsilon\neq0}
\end{array}$$
Es gibt keine $x_1$ auf $\text{I}$, sodass $f$ von $x_{1}$ aus auf $x_{1}+\varepsilon$ nicht vom Wert gleich ist. $f$ ist also an jeder Stelle steigend, obwohl $f'(x)=0$ sein kann, diese Steigung aber nur Punktuell vorliegt.

Sattelpunkte sind folglich durch $\nexists x{_1}\in\text{I,}~f(x{_1}+\varepsilon)-f(x{_1})=0$ immer streng monoton. Für alle ganzrationalen Funktionen liegt folglich zwischen Extrema immer eine streng monotone Steigung vor, da es keine Stellen gibt, bei der $x_{1}+\varepsilon=0$ sein kann.

---