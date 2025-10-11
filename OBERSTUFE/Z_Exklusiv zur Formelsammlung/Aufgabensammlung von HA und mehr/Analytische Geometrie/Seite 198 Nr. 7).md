> Gegeben ist eine Kugel mit dem Ursprung als Mittelpunkt, Für welchen Radius schneidet die Kugel die [[Ebene(n)]] $E$, berührt sie die Ebene oder hat keinen Punkt mit ihr gemeinsam? Wie lauten die Koordinaten des Berührpunktes?

---
## a)
- $E:3x_1+12x_2+4x_3-13=0$
Aus $E$ resultiert folgender [[Normalenvektor]] $n$:
- $\vec{n}=\begin{pmatrix}3\\12\\4\end{pmatrix}$
- $\vec{n}_0=\frac{1}{13}\cdot\begin{pmatrix}3\\12\\4\end{pmatrix}$
> Eine normierte Lotgerade, die durch den Mittelpunkt der Kugel geht, besitzt einen Schnittpunkt mit $E$, der den kürzesten Abstand besitzt. Durch die Normierung ist der Parameter hier der Radius, den die Kugel für diesen Schnittpunkt benötigt.

![[NormierteGerade]]

---
Die normierte Lotgerade $g_0$ lautet daher:
$$
g_0:\vec x=\frac{\lambda}{13}\cdot
	\begin{pmatrix}3\\12\\4\end{pmatrix}
$$

Die Schnittmenge $g_0\cap E$ beschreibt sowohl in $|\lambda|$ den Radius der Kugel, als auch den Schnittpunkt $S$.

Bestimmung von $\lambda$ und $S$ siehe anhand des Anhangs:
![[GeradeInEbene]]

Es gilt mit den Vektoren von dem Anhang unten:
- $\vec{p}=\begin{pmatrix}0\\0\\0\end{pmatrix}$
- $\vec{n}=\begin{pmatrix}3\\12\\4\end{pmatrix}$
- $|\vec{n}|=13$
- $d=13$

Der Schnittpunkt $S$ lautet somit:
$$
\begin{align}
	\overrightarrow{OS}&=\vec p +
		\frac{d-\vec{n}\circ\vec{p}}{|\vec{n}|^2}\cdot\vec n\\
	&=\begin{pmatrix}0\\0\\0\end{pmatrix} +
		\frac{13-\overbrace{\begin{pmatrix}3\\12\\4\end{pmatrix}\circ\begin{pmatrix}0\\0\\0\end{pmatrix}}^{=0}}{\underbrace{\left|\begin{pmatrix}3\\12\\4\end{pmatrix}\right|^2}_{=13^2}}\cdot\begin{pmatrix}3\\12\\4\end{pmatrix}\\
	&=\frac{13}{13^2}\cdot\begin{pmatrix}3\\12\\4\end{pmatrix}\\
	&=\frac{1}{13}\cdot\begin{pmatrix}3\\12\\4\end{pmatrix}=
		\begin{pmatrix}\frac{3}{13}\\\frac{12}{13}\\\frac{4}{13}\end{pmatrix}\\
	&\Rightarrow S\left(\frac{3}{13}\mid\frac{12}{13}\mid\frac{4}{13}\right)
\end{align}
$$

Für $\lambda$ gilt $\lambda=\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|}$, woraus resultiert:
$$
\begin{align}
	\lambda&=\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|}\\
	&=\frac{d-\vec{n}\circ\vec{p}}{|\vec{n}|}\\
	&=\frac{13-\overbrace{\begin{pmatrix}3\\12\\4\end{pmatrix}\circ\begin{pmatrix}0\\0\\0\end{pmatrix}}^{=0}}{\underbrace{\left|\begin{pmatrix}3\\12\\4\end{pmatrix}\right|}_{=13}}\\
	&=\frac{13}{13}=1
\end{align}
$$

Der Radius $r$ der Kugel $K$ ist also $r=1$. Damit die Kugel folgende Lagebeziehungen zu $E$ besitzt, so gilt folgendes:
> Es gibt keine Schnittmenge:
> - $r\in(0;1)$
> Es gibt einen Berührpunkt $S\left(\frac{3}{13}\mid\frac{12}{13}\mid\frac{4}{13}\right)$:
> - $r=1$
> Es gibt einen Schnittkreis:
> - $r\in(1;\infty)$

---
---
## b)
- $E:2x_1+3x_2-6x_3-14=0$
Aus $E$ resultiert folgender Normalvektor $n$:
- $\vec{n}=\begin{pmatrix}2\\3\\-6\end{pmatrix}$
- $\vec{n}_0=\frac{1}{7}\cdot\begin{pmatrix}2\\3\\-6\end{pmatrix}$
Die normierte Lotgerade $g_0$ lautet daher:
$$
g_0:\vec x=\frac{\lambda}{7}\cdot
	\begin{pmatrix}2\\3\\-6\end{pmatrix}
$$

Die Schnittmenge $g_0\cap E$ beschreibt sowohl in $|\lambda|$ den Radius der Kugel, als auch den Schnittpunkt $S$.

---
Es gilt mit den Vektoren von dem Anhang unten:
- $\vec{p}=\begin{pmatrix}0\\0\\0\end{pmatrix}$
- $\vec{n}=\begin{pmatrix}2\\3\\-6\end{pmatrix}$
- $|\vec{n}|=7$
- $d=14$

Der Schnittpunkt $S$ lautet somit:
$$
\begin{align}
	\overrightarrow{OS}&=\vec p +
		\frac{d-\vec{n}\circ\vec{p}}{|\vec{n}|^2}\cdot\vec n\\
	&=\begin{pmatrix}0\\0\\0\end{pmatrix} +
		\frac{14-\overbrace{\begin{pmatrix}2\\3\\-6\end{pmatrix}\circ\begin{pmatrix}0\\0\\0\end{pmatrix}}^{=0}}{\underbrace{\left|\begin{pmatrix}2\\3\\-6\end{pmatrix}\right|^2}_{=7^2=49}}\cdot\begin{pmatrix}2\\3\\-6\end{pmatrix}\\
	&=\frac{14}{49}\cdot\begin{pmatrix}2\\3\\-6\end{pmatrix}\\
	&=\frac{2}{7}\cdot\begin{pmatrix}3\\3\\-6\end{pmatrix}=
		\begin{pmatrix}\frac{4}{7}\\\frac{6}{7}\\-\frac{12}{7}\end{pmatrix}\\
	&\Rightarrow S\left(\frac{4}{7}\mid\frac{6}{7}\mid-\frac{12}{7}\right)
\end{align}
$$

Für $\lambda$ gilt $\lambda=\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|}$, woraus resultiert:
$$
\begin{align}
	\lambda&=\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|}\\
	&=\frac{d-\vec{n}\circ\vec{p}}{|\vec{n}|}\\
	&=\frac{14-\overbrace{\begin{pmatrix}2\\3\\-6\end{pmatrix}\circ\begin{pmatrix}0\\0\\0\end{pmatrix}}^{=0}}{\underbrace{\left|\begin{pmatrix}2\\3\\-6\end{pmatrix}\right|}_{=7}}\\
	&=\frac{14}{7}=2
\end{align}
$$

Der Radius $r$ der Kugel $K$ ist also $r=2$. Damit die Kugel folgende Lagebeziehungen zu $E$ besitzt, so gilt folgendes:
> Es gibt keine Schnittmenge:
> - $r\in(0;2)$
> Es gibt einen Berührpunkt $S\left(\frac{4}{7}\mid\frac{6}{7}\mid-\frac{12}{7}\right)$:
> - $r=2$
> Es gibt einen Schnittkreis:
> - $r\in(2;\infty)$

---