> Die Kugeln $K_1:\left[\vec{x}-\begin{pmatrix}1\\7\\-2\end{pmatrix}\right]^2=36$ und $K_2:\left[\vec{x}-\begin{pmatrix}7\\13\\1\end{pmatrix}\right]^2=9$ berühren sich. Bestimmen Sie eine Gleichung der gemeinsamen Tangentialebene.

Gegeben durch $K_1$:
- $M_1(1\mid7\mid-2)$
- $r_1=6$
Gegeben durch $K_2$:
- $M_2(7\mid13\mid1)$
- $r_2=3$

In dem folgendem Bild ist ein Querschnitt beider Kugeln durch beide Mittelpunkte abgebildet. Variablenbezeichnungen werden weitergehend wie in der Abbildung behandelt:
![[Kreise4.png]]

Die Kreise $K_1$ und $K_2$ berühren sich hier in dem Punkt $S$, durch welchen die Ebene $E$ verläuft.

> Da eine Gerade durch $M_1$ und $M_2$ den kürzesten Weg von $M_1$ und $M_2$ beschreibt, so muss $S$ auf dieser Geraden $g$ liegen.
> Es gilt hier für den Punkt $S$:
> $\{M_1\cap M_2\}\in g:\vec{x}$
> $\Rightarrow S=\{g\cap K_1\}\wedge\{g\cap K_2\}$

Eine solche Gerade $g$ definiere ich hier durch $g:\vec{x}=\overrightarrow{OM_1}+\frac{\lambda}{\left|\overrightarrow{M_1M_2}\right|}\cdot\overrightarrow{M_1M_2}$.


> $\lambda$ gibt hier durch die Normierung einen Punkt $P$ auf der Gerade $g$ an, dessen Abstand sich mit $d(M_1;P)=\left|\lambda\right|$ beschreiben lässt. Der Radius $r_1$ von $K_1$ ist $6$, wodurch wir den Abstand $d(M_1;P)$ ebenfalls bei $6$ erhalten müssen. $\lambda$ muss folglich $\pm6$ sein.

---
---
![[GeradeInKugel]]

---
---


Da der Richtungsvektor $\overrightarrow{M_1M_2}$ die Verschiebung in Richtung $K_2$ von $M_1$ beschreibt, nähert sich mit positiven $\lambda$ der Punkt $P$, wodurch $\lambda=6$ sein muss. $\lambda=-6$ gibt hier folglich in $g$ den Punkt $Q$ an.

$$
\begin{align}
	g:\vec{x}&=\overrightarrow{OM_1}+\frac{\lambda}{\left|\overrightarrow{M_1M_2}\right|}\cdot\overrightarrow{M_1M_2}\\
	\overrightarrow{OS}&=
		\begin{pmatrix}1\\7\\-2\end{pmatrix}+
		\frac{6}{\left|\begin{pmatrix}7-1\\13-7\\1+2\end{pmatrix}\right|}\cdot
		\begin{pmatrix}7-1\\13-7\\1+2\end{pmatrix}\\
	&=\begin{pmatrix}1\\7\\-2\end{pmatrix}+
		\frac{6}{\left|\begin{pmatrix}6\\6\\3\end{pmatrix}\right|}\cdot
		\begin{pmatrix}6\\6\\3\end{pmatrix}\\
	&=\begin{pmatrix}1\\7\\-2\end{pmatrix}+
		\frac{6}{\sqrt{6^2+6^2+3^2}}\cdot
		\begin{pmatrix}6\\6\\3\end{pmatrix}\\
	&=\begin{pmatrix}1\\7\\-2\end{pmatrix}+
		\begin{pmatrix}4\\4\\2\end{pmatrix}\\
	\overrightarrow{OS}&=\begin{pmatrix}5\\11\\0\end{pmatrix}
\end{align}
$$

> Der gemeinsame Punkt lautet also $S(5\mid11\mid0)$.

---
>Die Ebene $E$ heißt Tangentialebene zu den Kugeln $K_1$ und $K_2$. Daraus folgt für die Ebene $E$:
> $\{E\perp \{K_1\wedge K_2\}\}\wedge \{S\in E\}$

Damit $E$ tangential zu den Kugeln $K_1$ und $K_2$ durch den Punkt $P$ geht, muss der Normalenvektor der Verbindungsvektor $\overrightarrow{M_1M_2}$ sein. Daraus resultiert die folgende Ebene:
$$
\begin{align}
	E:\overrightarrow{M_1M_2}\circ\left[\overrightarrow{OX}-\overrightarrow{OS}\right]&=0\\
	\overrightarrow{M_1M_2}\circ\overrightarrow{OX}&=
		\overrightarrow{M_1M_2}\circ\overrightarrow{OS}\\
	\begin{pmatrix}6\\6\\3\end{pmatrix}\circ
		\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}&=
		\begin{pmatrix}6\\6\\3\end{pmatrix}\circ
		\begin{pmatrix}5\\11\\0\end{pmatrix}\\
	6x_1+6x_2+3x_3&=96\\
	2x_1+2x_2+x_3&=32
\end{align}
$$

---