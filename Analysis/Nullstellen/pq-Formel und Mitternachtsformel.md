## pq-Formel
Mittels der pq-Formel können [[Nullstellen]] bei ganzrationalen Funktionen 2. Grades ermittelt werden.
Sei $f(x)=x^{2}+px+q$, so sind dessen Nullstellen laut pq-Formel folgende:
$$x_{1,2}=-\frac{p}{2}\pm\sqrt{\left(\frac{p}{2}\right)^{2}-q}$$
Falls $f$ einen Öffnungsfaktor $\neq1$ hat, so muss durch [[Äquivalenzumformung(en)]] dieser Faktor der Funktion entzogen werden.
$$\begin{align}
f(x)&=ax^{2}+px+q&\big|\cdot a^{-1}\\
&=x^{2}+\frac{p}{a}x+\frac{q}{a}
\end{align}$$
Diese neue Funktion kann nun mit der pq-Formel nach Nullstellen untersucht werden.

---
## Mitternachtsformel
Nehme man sich die Funktion $f(x)=ax^{2}+bx+c$ und möchte diese vereinfachen, so kann die Mitternachtsformel verwendet werden.
Um diese Formel zu erhalten kann die pq-Formel vereinfacht werden.
$$\begin{align}
f(x)&=ax^{2}+bx+c&\big|\cdot a^{-1}\\
&=x^{2}+\frac{b}{a}x+\frac{c}{a}\\
x_{1,2}&=-\frac{\frac{b}{a}}{2}\pm\sqrt{\left(\frac{\frac{b}{a}}{2}\right)^{2}-\frac{c}{a}}\\
&=-\frac{b}{2a}\pm \sqrt{\left(\frac{b}{2a}\right)^{2}-\frac{c}{a}}\\
&=-\frac{b}{2a}\pm \sqrt{\frac{b^{2}}{4a^2}-\frac{c}{a}}\\
&=-\frac{b}{2a}\pm \sqrt{\frac{ab^{2}-4a^{2}c}{4a^{3}}}\\
&=-\frac{b}{2a}\pm \sqrt{\frac{b^{2}-4ac}{4a^{2}}}\\
&=-\frac{b}{2a}\pm \frac{\sqrt{b^{2}-4ac}}{\sqrt{4a^{2}}}\\
&=-\frac{b}{2a}\pm \frac{\sqrt{b^{2}-4ac}}{2a}\\
x_{1,2}&=\frac{-b\pm\sqrt{b^{2}-4ac}}{2a}
\end{align}$$

---