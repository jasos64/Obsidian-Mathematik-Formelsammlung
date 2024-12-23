Two lines $g:\vec{x}$ and $h:\vec{x}$ are given:
- $g:\vec{x}=\vec{p}+\lambda\vec{v}$
- $h:\vec{x}=\vec{q}+\mu\vec{u}$

Suppose a sphere $S$ with radius $r>0$ rolls on $g$ tangentially.
Additionaly $r$ should not be chosen such that $h$ is touching $S$.

Because the radius of $S$ is unchanged during its' movement, the center $M$ is always parallel to $g$ with distance $r$.
There is a line $m:\vec{x}$, that contains all $M$, and thus is parallel to $g$.
- $M\in m$
- $d\left(M;g\right)=r$
- $m\parallel g$.

There may exist a point $M$, where both $g$ and $h$ are touching $S$ at one point. For such $M$, the distance of $M$ to $g$ is equal to that of $M$ to $h$. Both these distances will be equal to $r$ as previously stated.
$$d\left(M;g\right)=d\left(M;h\right)=r$$

---
## Construction of $m:\vec{x}$
Because $m$ has a distance $r$ to $g$, a vector $\vec{n}$ with length $r$ perpendicular to $g$ can be constructed which will represent $m.$ There is a group of vectors that can represent that vector $n$.
- $\vec{n}\perp g$
- $\left|\vec{n}\right|=r$
Because it may be important where the sphere rolls on $g$, let the group of vectors be $\vec{n}_\theta$, where $\vec{n}_0$ ($\theta=0$) then is the vector that is "straight above" $g$. This results to the following:
- $\{\vec{n}_0\times\vec{v}\}\perp\begin{pmatrix}0\\0\\1\end{pmatrix}$
We know that the vector $\vec{n}_0\times\vec{v}$ is perpendicular to the $x_1x_2$ plane by description. This allows us to reconstruct the structure to find a vector $\vec{n}_0$:
- $\left[\begin{pmatrix}0\\0\\1\end{pmatrix}\times\vec{v}\right]\perp\vec{n}_0$
The bracket creates a vector that is perpendicular to the line $g:\vec{x}$. When we combine this with the line again, we create a factor of $\vec{n}_0$:
$$
\begin{align}
	\left[\begin{pmatrix}0\\0\\1\end{pmatrix}
		\times\vec{v}\right]\times\vec{v}
		&=\omega^{-1}\cdot\vec{n}_0\\
	\left[\begin{pmatrix}0\\0\\1\end{pmatrix}
		\times\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}\right]
		\times\vec{v}
		&=\omega^{-1}\cdot\vec{n}_0\\
	\left[\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\right]
		\times\vec{v}
		&=\omega^{-1}\cdot\vec{n}_0\\
	\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}
		\times\begin{pmatrix}v_1\\v_2\\v_3\end{pmatrix}
		&=\omega^{-1}\cdot\vec{n}_0\\
	\begin{pmatrix}v_1v_3\\v_2v_3\\-v_2^2-v_1^2\end{pmatrix}
		&=\omega^{-1}\cdot\vec{n}_0\\
\end{align}
$$
The vector on the left side is always pointing towards below the line $g$, hence I will only flip the vector with the factor of $-1$ to make the vector face the upper side of $g$. This makes it possible to normalize the vector without any directional issues (to follow the definition of $\vec{n}_0$):
$$
\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}
		=\omega^{-1}\cdot\vec{n}_0
$$
As of now the left side is a factor of the vector we need. The length of the vector will be $r$.
$$
\begin{align}
	n_0&\coloneqq\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}\cdot\frac{r}{\left|
		\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_1^2+v_2^2\end{pmatrix}\right|}\\
	&=\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}\cdot\frac{r}{\sqrt{(-v_1v_3)^2+(-v_2v_3)^2+(v_1^2+v_2^2)^2}}\\
	&=\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}\cdot\frac{r}{\sqrt{v_1^2v_3^2+v_2^2v_3^2+v_1^4+2v_1^2v_2^2+v_2^4}}\\
\end{align}
$$
For simplification, I will represent this factor as $\omega$.
- $\omega=\frac{1}{\sqrt{v_1^2v_3^2+v_2^2v_3^2+v_1^4+2v_1^2v_2^2+v_2^4}}$

This vector allows us to now define the line $m:\vec x$:
$$
\begin{align}
	m:\vec{x}=\vec{p}+\vec{n}_0+\lambda\vec{v}
\end{align}
$$
> Note that the $0$ is a parameter for rotation, not a unit vector.

---
## Construction of $m_\theta:\vec{x}$
We will now rotate the line $m$ around $g$ with distance $r$.
> For rotation we can use $\vec i\cos(\theta)+\vec j\sin(\theta)$, where $\vec i\perp \vec j$.

From above we know that for this equation:
- $\vec i=\vec{n}_0$
- $\phi^{-1}\vec j=\phi^{-1}\vec{n}_\frac{\pi}{2}=\phi^{-1}\begin{pmatrix}0\\0\\1\end{pmatrix}\times\vec{v}$
Again we have a factor for a vector ($\vec j$). Vector $\vec i$ already has length $1$ by definition.
$$
\begin{align}
	n_\frac{\pi}{2}&\coloneqq\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\cdot\frac{r}{\left|
		\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\right|}\\
	&\coloneqq\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\cdot
		\frac{r}{\sqrt{(-v_2)^2+(v_1)^2+(0)^2}}\\
	&\coloneqq\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\cdot
		\frac{r}{\sqrt{v_1^2+v_2^2}}\\
\end{align}
$$
Again we separate the factor with a variable.
- $\phi=\frac{1}{\sqrt{v_1^2+v_2^2}}$
For the next, $\hat{z}$ is the unit vector of the third axis $x_3$ ($z$)
$$
\begin{align}
	\vec{n}_\theta&=\vec i\cos(\theta)+\vec j\sin(\theta)\\
		&=\vec{n}_0\cos(\theta)+\vec{n}_{\frac{\pi}{2}}\sin(\theta)\\
	&=\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}\cdot\frac{r}{\sqrt{v_1^2v_3^2+v_2^2v_3^2+v_1^4+2v_1^2v_2^2+v_2^4}}\cdot\cos(\theta)+\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\cdot
		\frac{r}{\sqrt{v_1^2+v_2^2}}\cdot\sin(\theta)\\
	&=\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}\cdot r\cdot\omega\cdot\cos(\theta)+\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\cdot
		r\cdot\phi\cdot\sin(\theta)\\
	&=r\cdot\left[\begin{pmatrix}-v_1v_3\\-v_2v_3\\v_2^2+v_1^2\end{pmatrix}
		\cdot\omega\cdot\cos(\theta)+\begin{pmatrix}-v_2\\v_1\\0\end{pmatrix}\cdot\phi\cdot\sin(\theta)\right]\\
	&=r\cdot\left[-\left(\begin{pmatrix}0\\0\\1\end{pmatrix}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\begin{pmatrix}0\\0\\1\end{pmatrix}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]\\
	&=r\cdot\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]
\end{align}
$$

This makes it able to represent $m_\theta:\vec x$ as follows:
$$
\begin{align}
	m_\theta:\vec{x}=\vec{p}+r\cdot\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]+\lambda\vec{v}
\end{align}
$$

---
---
## Calculating for $r$
> For two lines, their distance is defined as follows:
- $d(g_1;g_2)=\frac{\left|\vec{n}\circ\left(\overrightarrow{OR}-\overrightarrow{OP}\right)\right|}{\left|\vec{n}\right|}$

We know that the distance of the two lines is exactly $r$. $\vec n$ here is the cross product from both the directions. $\overrightarrow{OR}$ will here be the independent vector from $m_\theta:\vec x$ . $\overrightarrow{OP}=\vec q$.

$$
\begin{align}
	d(m_\theta;h)&=\frac{\left|\vec{n}\circ\left(\overrightarrow{OR}-\overrightarrow{OP}\right)\right|}{\left|\vec{n}\right|}\\
	
	r&=\frac{\left|\left[\vec{v}\times\vec{u}\right]\circ\left(
		\vec{p}+r\cdot\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]-\vec{q}\right)\right|}
		{\left|\vec{v}\times\vec{u}\right|}\\
	
	r&=\frac{\left|
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\right|}
		{\left|\vec{v}\times\vec{u}\right|}
			&&\mid\cdot\left|\vec{v}\times\vec{u}\right|\\
	\left|\vec{v}\times\vec{u}\right|\cdot r&=\left|
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\right|
\end{align}
$$
The left side can not be negative by definition. The absolute value on the right side will be split into positive and negative.
Positive:
$$
\begin{align}
	\left|\vec{v}\times\vec{u}\right|\cdot r&=\left|
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\right|\\
	\left|\vec{v}\times\vec{u}\right|\cdot r&=
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\\
	\left|\vec{v}\times\vec{u}\right|\cdot r-r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]&=
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\\
	\left(\left|\vec{v}\times\vec{u}\right|-
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]\right)\cdot r&=
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\\
	r&=\frac{\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}}
		{\left|\vec{v}\times\vec{u}\right|-
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]}\\
	r&=\frac{\left[\vec{v}\times\vec{u}\right]\circ\left(\vec{p}
		-\vec{q}\right)}
		{\left|\vec{v}\times\vec{u}\right|-
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]}
\end{align}
$$

Negative:
$$
\begin{align}
	\left|\vec{v}\times\vec{u}\right|\cdot r&=\left|
		\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]-\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\right|\\
	\left|\vec{v}\times\vec{u}\right|\cdot r&=
		-\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		-r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]
		+\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\\
	\left|\vec{v}\times\vec{u}\right|\cdot r+r\cdot\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]&=
		-\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\\
	\left(\left|\vec{v}\times\vec{u}\right|+
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]\right)\cdot r&=
		-\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+\left[\vec{v}\times\vec{u}\right]\circ\vec{q}\\
	r&=\frac{-\left[\vec{v}\times\vec{u}\right]\circ\vec{p}
		+\left[\vec{v}\times\vec{u}\right]\circ\vec{q}}
		{\left|\vec{v}\times\vec{u}\right|+
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]}\\
	r&=\frac{\left[\vec{v}\times\vec{u}\right]\circ\left(-\vec{p}
		+\vec{q}\right)}
		{\left|\vec{v}\times\vec{u}\right|+
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]}\\
	r&=\frac{-\left[\vec{v}\times\vec{u}\right]\circ\left(\vec{p}
		-\vec{q}\right)}
		{\left|\vec{v}\times\vec{u}\right|+
		\left[\vec{v}\times\vec{u}\right]\circ\left[-\left(\hat{z}
		\times\vec{v}\right)\times\vec{v}
		\cdot\omega\cdot\cos(\theta)+
		\left(\hat{z}\times\vec{v}\right)
		\cdot\phi\cdot\sin(\theta)\right]}
\end{align}
$$
