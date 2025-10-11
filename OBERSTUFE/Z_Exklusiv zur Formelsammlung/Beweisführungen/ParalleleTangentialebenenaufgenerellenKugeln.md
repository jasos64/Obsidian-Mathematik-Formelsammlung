> Eine Ebene $E:\vec{n}\circ\overrightarrow{OX}=\vec{n}\circ\overrightarrow{OP}$, und eine Kugel $K:\left(\overrightarrow{OX}-\overrightarrow{OM}\right)^2=r^2$ seien gegeben.
> Zwei zu $E$ parallele Ebenen $F_{1;2}$ sollen unterschiedlich sein, und Tangentialebene der Kugel $K$ heißen.

Zunächst einmal definiere ich folgendermaßen:
- $\vec{n}=\begin{pmatrix}n_1\\n_2\\n_3\end{pmatrix}$
- $\overrightarrow{OM}=\begin{pmatrix}m_1\\m_2\\m_3\end{pmatrix}$
- $\overrightarrow{OX}=\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}$

---
Die Ebenen $F_{1;2}$ besitzen den gleichen Abstand zu dem Mittelpunkt, da diese tangential auf der Kugel $K$ mit Radius $r$ liegen. Folglich $d(M;F_1)=d(M;F_2)=r$.
> Da die Ebene $E_M$ den Punkt $M$ enthält und parallel zu $E$ ist, so kann $E_M$ zur Bildung von $F_{1;2}$ verwendet werden.
> Es gilt:
> - $M\in E_M$
> - $E_M\parallel E$
> 	- $E_M\parallel F_{1;2}$
> - $d(E_M;F_1)=d(E_M;F_2)$

Definiert lautet $E_M$ folgendermaßen:
$$
E_M:\vec{n}\circ\overrightarrow{OX}=\vec{n}\circ\overrightarrow{OM}
$$

Wie beschrieben wird $E_M$ verwendet, um $F_{1;2}$ zu bestimmen. Hierzu wird $d$ als Variable verwendet, die die Ebene zur Tangentialebene von $K$ macht.
$$
E_M:\vec{n}\circ\overrightarrow{OX}=\vec{n}\circ\overrightarrow{OM}+d
$$

---
Folgend werde ich einen generell beschriebenen Schnittpunkt darstellen:
![[GeradeInKugel]]

Bedenken wir hier, dass $\overrightarrow{M_1M_2}=\vec{n}$ ist, und $\overrightarrow{OM_1}=\overrightarrow{OM}$ ist, so erhalten wir für die Schnittmenge, die unsere gesuchten Berührungspunkte beschreibt:
$$
\begin{align}
	\overrightarrow{OS_{1;2}}&=\overrightarrow{OM_1}\pm
		\frac{r}{\left|\overrightarrow{M_1M_2}\right|}
		\cdot\overrightarrow{M_1M_2}\\
	\overrightarrow{OS_{1;2}}&=\overrightarrow{OM}\pm
		\frac{r}{\left|\vec{n}\right|}
		\cdot\vec{n}
\end{align}
$$

Setzen wir diese Schnittpunkte in $E_M$ ein, und lösen anschließend nach $d$ auf, erhalten wir folgendes für die Werte $d$:
$$
\begin{align}
	E_M:\vec{n}\circ\overrightarrow{OX}&=
		\vec{n}\circ\overrightarrow{OM}+d\\
	\vec{n}\circ\left[\overrightarrow{OM}\pm
		\frac{r}{\left|\vec{n}\right|}
		\cdot\overrightarrow{n}\right]&=
		\vec{n}\circ\overrightarrow{OM}+d\\
	\textcolor{Red}{\vec{n}\circ\overrightarrow{OM}}\pm
		\frac{r}{\left|\vec{n}\right|}
		\cdot\textcolor{Orange}{\vec{n}\circ\vec{n}}&=
		\textcolor{Red}{\vec{n}\circ\overrightarrow{OM}}+d\\
	\pm\frac{r}{\left|\vec{n}\right|}
		\cdot\textcolor{Orange}{\left|\vec{n}\right|^2}&=d\\
	d&=\pm~r\cdot \left|\vec{n}\right|
\end{align}
$$
Daraus folgt für die Ebenen $F_{1;2}$:
$$
\begin{align}
	E_M:\vec{n}\circ\overrightarrow{OX}&=
		\vec{n}\circ\overrightarrow{OM}+d\\
	F_{1;2}:\vec{n}\circ\overrightarrow{OX}&=
		\vec{n}\circ\overrightarrow{OM}\pm r\cdot \left|\vec{n}\right|
\end{align}
$$

---
---