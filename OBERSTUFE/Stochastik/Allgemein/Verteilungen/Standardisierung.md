Im folgenden wird die Standardisierung der Normalverteilung veranschaulicht.

---
Eine Verteilung wird standardisiert, damit diese verglichen werden können. Der Erwartungswert wird mittels linearer Transformationen auf die Stelle $0$ verschoben. Anschließend wird diese Transformation durch $\sigma$ geteilt. Hierbei ergibt sich $Z=\frac{X-\mu}{\sigma}$, wobei $Z$ die aus $X$ gebildete zentrierte [[Zufallsvariable]] ist.
> Für die Normalverteilung folgt aus der Standardisierung das folgende für eine [[Zufallsvariable]] $X\sim\mathcal{N}(0;1)$
$$
\begin{align}
	\varphi(x)=\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}x^2}
\end{align}
$$

Sollte eine [[Normalverteilung]] $Y\sim\mathcal{N}(\mu;\sigma^2)$ gegeben sein, dann kann diese durch die standardisierte Normalverteilung $X\sim\mathcal{N}(0;1)$ mittels $\varphi\left(\frac{x-\mu}{\sigma}\right)$ ausgedrückt werden. Hierbei ist $\varphi$ die bereits definierte Gaußfunktion $\varphi(x)=\frac{1}{\sqrt{2\pi}}\cdot e^{-\frac{1}{2}x^2}$.

---