> Eine Gerade $g:\vec x=\vec p +\lambda \cdot\vec v$ und eine Ebene $E:\vec n\circ \vec x=\vec n\circ\vec q$ sollen auf einen Schnittpunkt untersucht werden.

Hierzu wird $g$ in $E$ eingesetzt und nach $\lambda$ umgestellt:
$$
\begin{align}
	E:\vec n\circ \vec x&=\vec n\circ\vec q\\
	\textcolor{orange}{\vec n~\circ}\left[\vec p+\lambda\cdot\vec v\right]
		&=\vec n\circ\vec q\\
	\textcolor{orange}{\vec n~\circ~}\vec p+\lambda\cdot\textcolor{orange}{\vec n~\circ~}\vec v
		&=\vec n\circ\vec q&&\mid -\vec{n}\circ\vec{p}\\
	\lambda\cdot\vec n\circ\vec v
		&=\vec n\circ\vec{q}-\vec{n}\circ\vec{p}\\
	\lambda\cdot\vec n\circ\vec v
		&=\vec n\circ\left[\vec{q}-\vec{p}\right]&&\mid\div\vec n\circ\vec v\\
	\lambda&=\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{\vec n\circ\vec v}\\\\
	
	\Rightarrow\overrightarrow{OS}&=\vec p +\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{\vec n\circ\vec v}\cdot\vec v
\end{align}
$$
Da $\vec q$ oft nicht gegeben ist, so ist per Definition von $d=\vec n\circ\vec q$ auch folgende Form für $\overrightarrow{OS}$ möglich:
$$
\overrightarrow{OS}=\vec{p} +\frac{d-\vec{n}\circ\vec{p}}{\vec n\circ\vec v}\cdot\vec v
$$

---
> Sollte es sich bei der Gerade um eine normierte Lotgerade der Ebene $E$ handeln, dann gilt folgendes:
> - $g_0:\vec x=\vec p +\frac{\lambda}{|\vec n|} \cdot\vec n$

$$
\begin{align}
	E:\vec n\circ \vec x&=\vec n\circ\vec q\\
	\textcolor{orange}{\vec n~\circ}\left[\vec p +\frac{\lambda}{|\vec n|} \cdot\vec n\right]
		&=\vec n\circ\vec q\\
	\textcolor{orange}{\vec n~\circ~}\vec p+\frac{\lambda}{|\vec n|}\cdot\textcolor{orange}{\vec n~\circ~}\vec n
		&=\vec n\circ\vec q&&\mid -\vec{n}\circ\vec{p}\\
	\frac{\lambda}{|\vec n|}\cdot\vec n\circ\vec n
		&=\vec n\circ\vec{q}-\vec{n}\circ\vec{p}\\
	\frac{\lambda}{|\vec n|}\cdot\underbrace{\vec n\circ\vec n}_{=|\vec{n}|^2}
		&=\vec n\circ\left[\vec{q}-\vec{p}\right]\\
	\lambda\cdot|\vec{n}|
		&=\vec n\circ\left[\vec{q}-\vec{p}\right]&&\mid\div|\vec{n}|\\
	\lambda&=\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|}\\\\
	
	\Rightarrow\overrightarrow{OS}&=\vec p +\frac{\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|}}{|\vec{n}|}\cdot\vec n\\
	&=\vec p +\frac{\vec{n}\circ\left[\vec{q}-\vec{p}\right]}{|\vec{n}|^2}\cdot\vec n
\end{align}
$$
Da $\vec q$ oft nicht gegeben ist, so ist per Definition von $d=\vec n\circ\vec q$ auch folgende Form für $\overrightarrow{OS}$ möglich:
$$
\overrightarrow{OS}=\vec p +\frac{d-\vec{n}\circ\vec{p}}{|\vec{n}|^2}\cdot\vec n
$$

---
---