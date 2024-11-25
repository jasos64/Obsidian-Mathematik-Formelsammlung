## Kreise
> Ein Kreis wird hier in $\mathbb{R}^2$ mit einem Mittelpunkt $M(m_1\mid m_2)$, und einem Radius $r$ beschrieben.
> Es ist definiert, dass jeder [[Ortsvektor(en)]], dessen [[Abstand]] zu dem Mittelpunkt $r$ ist, auf dem Kreis ist, und alle diese den Kreis bilden.

Hier zeigt sich, dass dadurch ein Kreis mit der Gleichung $\left|\overrightarrow{MX}\right|=r$ beschrieben werden kann.
Zusätzlich lässt sich dies weiter vereinfachen, insofern wir folgendes annehmen:
- $\overrightarrow{OX}=\begin{pmatrix}x_1\\x_2\end{pmatrix}$
- $\overrightarrow{OM}=\begin{pmatrix}m_1\\m_2\end{pmatrix}$

$$
\begin{align}
	\left|\overrightarrow{MX}\right|&=r\\
	\left|\overrightarrow{OX}-\overrightarrow{OM}\right|&=r\\
	\left|\begin{pmatrix}x_1\\x_2\end{pmatrix}-
		\begin{pmatrix}m_1\\m_2\end{pmatrix}\right|&=r\\
	\left|\begin{pmatrix}x_1-m_1\\x_2-m_2\end{pmatrix}\right|&=r\\
	\sqrt{\left(x_1-m_1\right)^2+\left(x_2-m_2\right)^2}&=r
\end{align}
$$
Da der Wurzelterm hier stören würde, wird dieser durch eine Quadrierung beider Seiten entfernt, wodurch diese Koordinatenform eines Kreises definiert wird:
$$
\begin{align}
	\sqrt{\left(x_1-m_1\right)^2+\left(x_2-m_2\right)^2}&=r\\
	\left(x_1-m_1\right)^2+\left(x_2-m_2\right)^2&=r^2
\end{align}
$$

---
Die Vektorform eines Kreises wird aus $\left|\begin{pmatrix}x_1\\x_2\end{pmatrix}-\begin{pmatrix}m_1\\m_2\end{pmatrix}\right|=r$ beschrieben, wobei der Betrag ( $\left|\quad\right|$ ) direkt beschrieben wird:
$$
\begin{align}
	\left|\begin{pmatrix}x_1\\x_2\end{pmatrix}-\begin{pmatrix}m_1\\m_2\end{pmatrix}\right|&=r\\
	\left[\begin{pmatrix}x_1\\x_2\end{pmatrix}-\begin{pmatrix}m_1\\m_2\end{pmatrix}\right]^2&=r^2
\end{align}
$$

---
---
## Kugeln
> Kugeln in $\mathbb{R}^3$ sind von den Gleichungen gleich, wobei wir einen Ortsvektor $\overrightarrow{OX}=\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}$ und einen Mittelpunkt $M(m_1\mid m_2\mid m_3)$ haben.

Für die Gleichungen resultiert also das folgende:
$$
\begin{align}
	\left(x_1-m_1\right)^2+\left(x_2-m_2\right)^2+\left(x_3-m_3\right)^2&=r^2\\\\
	\left[\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}-\begin{pmatrix}m_1\\m_2\\m_3\end{pmatrix}\right]^2&=r^2
\end{align}
$$

---
---