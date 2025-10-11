# 1
> Bestimmen Sie mit dem Taschenrechner die folgenden Werte.

$$
\begin{align}
	a)&&\Phi(0,5)&\approx0,6915\\
	b)&&\Phi(1,63)&\approx0,9484\\
	c)&&\Phi(-1,04)&\approx0,1492\\
	d)&&\Phi\left(-\frac{2}{3}\right)&\approx0,2524
\end{align}
$$
---
# 2
> Bestimmen Sie $x$ mithilfe des Taschenrechners.

$$
\begin{align}
	a)&&\Phi(x)&=0,9082\\
	&&x&\approx1,3298\\
	b)&&\Phi(x)&=0,2420\\
	&&x&\approx-0,6999\\
	c)&&\Phi(x)&\ge 0,0055\\
	&&x&\underset{\sim}{\ge}-2,543\\
	d)&&\Phi(x)&<0,0668\\
	&&x&\underset{\sim}{<}-1,5001
\end{align}
$$
---
# 3
> Eine Zufallsgröße ist $B_{225;0,5}$-Verteilt. Berechnen Sie näherungswese.

$$
\begin{align}
	a)&&P(X\le 108)=P(0\le X\le108)&\approx
		\Phi\left(\frac{k_2+0,5-\mu}{\sigma}\right)-
		\Phi\left(\frac{k_1-0,5-\mu}{\sigma}\right)\\
		&&&=\Phi\left(\frac{108+0,5-112,5}{7,5}\right)-
		\Phi\left(\frac{0-0,5-112,5}{7,5}\right)\\
		&&&=\Phi\left(-\frac{8}{15}\right)-
		\Phi\left(-\frac{226}{15}\right)\\
		&&&\approx0,2969\\
	b)&&P(X> 110)=P(111\le X\le225)&\approx
		\Phi\left(\frac{k_2+0,5-\mu}{\sigma}\right)-
		\Phi\left(\frac{k_1-0,5-\mu}{\sigma}\right)\\
		&&&=\Phi\left(\frac{225+0,5-112,5}{7,5}\right)-
		\Phi\left(\frac{111-0,5-112,5}{7,5}\right)\\
		&&&=\Phi\left(\frac{226}{15}\right)-
		\Phi\left(-\frac{4}{15}\right)\\
		&&&\approx0,6051
\end{align}
$$
---
# 4
> Eine Zufallsgröße ist $B_{1200;0,6}$-Verteilt. Berechnen Sie näherungswese.

$$
\begin{align}
	a)&&P(X\le 700)=P(0\le X\le700)&\approx
		\Phi\left(\frac{k_2+0,5-\mu}{\sigma}\right)-
		\Phi\left(\frac{k_1-0,5-\mu}{\sigma}\right)\\
		&&&=\Phi\left(\frac{700+0,5-720}{12\sqrt{2}}\right)-
		\Phi\left(\frac{0-0,5-720}{12\sqrt{2}}\right)\\
		&&&=\Phi\left(-\frac{13\sqrt{2}}{16}\right)-
		\Phi\left(-\frac{1439\sqrt{2}}{48}\right)\\
		&&&\approx0,1253\\
	b)&&P(X> 730)=P(731\le X\le1200)&\approx
		\Phi\left(\frac{k_2+0,5-\mu}{\sigma}\right)-
		\Phi\left(\frac{k_1-0,5-\mu}{\sigma}\right)\\
		&&&=\Phi\left(\frac{1200+0,5-720}{12\sqrt{2}}\right)-
		\Phi\left(\frac{731-0,5-720}{12\sqrt{2}}\right)\\
		&&&=\Phi\left(\frac{961\sqrt{2}}{48}\right)-
		\Phi\left(\frac{7\sqrt{2}}{16}\right)\\
		&&&\approx0,2681
\end{align}
$$
---
# 5
> Eine Zufallsgröße ist $B_{50;0,6}$-Verteilt. Berechnen Sie näherungswese.

$$
\begin{align}
	a)&&P(X=15)&\approx
		\frac{1}{\sigma}\cdot\varphi_{\mu;\sigma}(k)
		=\frac{1}{\sigma\cdot\sqrt{2\pi}}\cdot e^{-\frac{1}{2}\cdot\left(\frac{x-\mu}{\sigma}\right)^2}\\
		&&&=\frac{1}{2\sqrt{3}\cdot\sqrt{2\pi}}\cdot e^{-\frac{1}{2}\cdot\left(\frac{15-30}{2\sqrt{3}}\right)^2}\\
		&&&=\frac{\sqrt{6\pi}}{12\pi}\cdot e^{-\frac{75}{8}}\\
		&&&\approx0,000009768\\
	e)&&P(X=28)&\approx
		\frac{1}{\sigma}\cdot\varphi_{\mu;\sigma}(k)
		=\frac{1}{\sigma\cdot\sqrt{2\pi}}\cdot e^{-\frac{1}{2}\cdot\left(\frac{x-\mu}{\sigma}\right)^2}\\
		&&&=\frac{1}{2\sqrt{3}\cdot\sqrt{2\pi}}\cdot e^{-\frac{1}{2}\cdot\left(\frac{28-30}{2\sqrt{3}}\right)^2}\\
		&&&=\frac{\sqrt{6\pi}}{12\pi}\cdot e^{-\frac{1}{6}}\\
		&&&\approx0,09748
\end{align}
$$
---
# 7
## a)
> Eine Zufallsgröße $X$ ist $B_{50;0,7}$-Verteilt. Berechnen Sie $P(37\le X\le40)$

$$
\begin{align}
	(1)~\text{Exakt}&&P(37\le X\le40)&=P(X\le40)-P(X\le36)\\
	&&&=F_{50;0,7}(40)-F_{50;0,7}(36)\\
	&&&\approx0,28765\\
	(2)~\text{Näherung mit Korrektur}&&
		P(37\le X\le40)&\approx
		\Phi\left(\frac{k_2+0,5-\mu}{\sigma}\right)-
		\Phi\left(\frac{k_1-0,5-\mu}{\sigma}\right)\\
		&&&=\Phi\left(\frac{40+0,5-35}{\frac{\sqrt{42}}{2}}\right)-
		\Phi\left(\frac{37-0,5-35}{\frac{\sqrt{42}}{2}}\right)\qquad \boxed{\sigma=\frac{\sqrt{42}}{2}>3}\\
		&&&=\Phi\left(\frac{11\sqrt{42}}{42}\right)-
		\Phi\left(\frac{\sqrt{42}}{14}\right)\\
		&&&\approx0,27690\\
	(3)~\text{Näherung ohne Korrektur}&&
		P(37\le X\le40)&\approx
		\Phi\left(\frac{k_2-\mu}{\sigma}\right)-
		\Phi\left(\frac{k_1-\mu}{\sigma}\right)\\
		&&&=\Phi\left(\frac{40-35}{\frac{\sqrt{42}}{2}}\right)-
		\Phi\left(\frac{37-35}{\frac{\sqrt{42}}{2}}\right)\qquad \boxed{\sigma=\frac{\sqrt{42}}{2}>3}\\
		&&&=\Phi\left(\frac{5\sqrt{42}}{21}\right)-
		\Phi\left(\frac{2\sqrt{42}}{21}\right)\\
		&&&\approx0,207136\\
\end{align}
$$
## b)
> Um wie viel Prozent steigt der Fehler der Näherung an, wenn man auf die Korrektur der Integrationsgrenzen verzichtet?

$$
\begin{align}
	\xi&=\frac{\Phi\left(\frac{11\sqrt{42}}{42}\right)-
		\Phi\left(\frac{\sqrt{42}}{14}\right)-\left[F_{50;0,7}(40)-F_{50;0,7}(36)\right]}{F_{50;0,7}(40)-F_{50;0,7}(36)}-
		\frac{\Phi\left(\frac{5\sqrt{42}}{21}\right)-
		\Phi\left(\frac{2\sqrt{42}}{21}\right)-\left[F_{50;0,7}(40)-F_{50;0,7}(36)\right]}{F_{50;0,7}(40)-F_{50;0,7}(36)}\\
	&\approx\frac{0,27690-0,28765}{0,28765}-\frac{0,207136-0,28765}{0,28765}\\
	&\approx\frac{34882}{143825}\approx0,242531
\end{align}
$$
Beim weglassen der Integrationsgrenzen steigt der Fehler um ungefähr $24,25\%$.

---