Die Schnittmenge einer Gerade $E$ und Gerade $g:\vec{x}$ gesucht wird. Nennen wir hier diese Schnittmenge $S$, so gilt $S\coloneqq E\cap g:\vec{x}$.

Für die Ebene $E_k$ in Koordinatenform definieren wir wie folgend:
>- $\vec{n}$: Normalenvektor der Ebene $E$
>- $\vec{x}$: Hier als Abkürzung für den Vektor $\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}$
>- $\vec{q}$: Signifikanter Punkt der Ebene ($\overrightarrow{OQ}\in E_k$)
>- $E_k:\vec{n}\circ\vec{x}=\vec{n}\circ\vec{q}$

Für die Gerade $g:\vec{x}$ definieren wir wie folgend:
>- $\vec{r}$: Richtungsvektor der Gerade $g:\vec{x}$
>- $\vec{\lambda}$: Skalar für $\vec{r}$
>- $\vec{p}$: Signifikanter Punkt der Gerade ($\overrightarrow{OP}\in g:\vec{x}$)
>- $g:\vec{x}=\vec{p}+\lambda\vec{r}$

---
Um den Punkt $S$ zu bestimmen, welcher sowohl auf der Geraden, als auch der Ebene liegt, ist es ratsam die Gerade in die Ebene einzusetzen. Eine Beschreibung der Berechnung kann wie folgend beschrieben werden:
>"$g:\vec{x}$ in $E_k$"
>"Gerade $g:\vec{x}$ in Ebene $E$ einsetzen"
>o. Ä.

$$
\begin{aligned}
	E_k:\vec{n}\circ\vec{x}&=\vec{n}\circ\vec{q}
		&&\mid g:\vec{x}~~in~~E_k\\
	
	\vec{n}\circ\left(\vec{p}+\lambda\vec{r}\right)
		&=\vec{n}\circ\vec{q}
\end{aligned}
$$
Dieser Ausdruck besitzt entweder keine Lösung, eine, oder unendlich viele. Folgend wird nach legalen Operationen nach dem Parameter $\lambda$ umgestellt:
$$
\begin{align}
	\vec{n}\circ\left(\vec{p}+\lambda\vec{r}\right)
		&=\vec{n}\circ\vec{q}\\
	
	\vec{n}\circ\vec{p}+\left[\vec{n}\circ\vec{r}\right]\lambda
		&=\vec{n}\circ\vec{q}
			&&\mid -\vec{n}\circ\vec{p}\\
	
	\left[\vec{n}\circ\vec{r}\right]\lambda
		&=\vec{n}\circ\vec{q}-\vec{n}\circ\vec{p}
			&&\mid \div \left[\vec{n}\circ\vec{r}\right]\\
	
	\lambda&=\frac{\vec{n}\circ
		\left[
			\vec{q}-\vec{p}
		\right]}{\vec{n}\circ\vec{r}}
\end{align}
$$
Wichtig zu sagen ist, dass der Nennerterm nicht $0$ werden darf. Ist nur dieser $0$, so ist keine Lösung vorhanden. Sobald $\lambda=\frac{0}{0}$ ist, dann befindet sich die Gerade $g$ vollständig in $E$, weshalb unendlich viele Lösungen möglich sind. Sobald ein fehlerfreies Ergebnis gegeben ist, existiert nur eine Lösung.
Dies lässt sich zeigen, wenn wir den Zähler und Nenner einzeln betrachten:
>- Der Zähler wird $0$, wenn $\vec{p}$ teil der Ebene $E_k$ ist
>- Der Nenner wird $0$, wenn die Gerade parallel zu der Ebene $E_k$ ist

---
Da $\lambda$ selbst nicht den Punkt angibt, muss $\lambda$ anschließend noch in die Gerade eingesetzt werden. Es resultiert für $\overrightarrow{OS}$:
$$
\begin{align}
	g:\vec{x}&=\vec{p}+\lambda\vec{r}\\
	
	\overrightarrow{OS}&=\vec{p}+\frac{\vec{n}\circ
		\left[
			\vec{q}-\vec{p}
		\right]}{\vec{n}\circ\vec{r}}\cdot\vec{r}
\end{align}
$$

---