>Skizzieren Sie die Graphen der Binomialverteilung und bestimmen Sie jeweils den Erwartungswert und die Standartabweichung

### a1) $p=0,5\quad n_1=8$
$$
\begin{align}
	\mu&=n_1\cdot p\\
	\mu&=8\cdot 0,5\\
	\mu&=4
\end{align}
$$

$$
\begin{align}
	P(X=\mu)&=\begin{pmatrix}n_1\\\mu\end{pmatrix}
	\cdot p^{\mu}\cdot (1-p)^{n_1-\mu}\\
	P(X=4)&=\begin{pmatrix}8\\4\end{pmatrix}
	\cdot 0,5^{4}\cdot (1-0,5)^{8-4}\\
	&=\begin{pmatrix}8\\4\end{pmatrix}
	\cdot 0,5^{4}\cdot 0,5^{4}\\
	&=70\cdot 0,5^8=\frac{35}{128}\approx 0,273
\end{align}
$$

$$
\begin{align}
	\sigma&=\sqrt{\mu\cdot p\cdot (1-p)}\\
	&=\sqrt{8\cdot 0,5\cdot (1-0,5)}\\
	\sigma&=\sqrt{2}
\end{align}
$$

$$
\begin{align}
	\mu-\sigma&=4-\sqrt{2}\\
	&\text{Da hier }\sigma\in\mathbb{R}\backslash\mathbb{Q}\text{ ist, so muss dieser für hier }k\\
	&\text{angenommene Wert gerundet werden, da für }k \text{ gilt:}\\
	&k\in\mathbb{N}\\
	k_1=4-\sqrt{2}&\approx2,58578643763\approx3
	\\\\
	&\text{Es muss ebenfalls für }\mu+\sigma\text{ der Wert gerundet werden}\\
	k_2=4+\sqrt{2}&\approx5,41421356237\approx5
\end{align}
$$

$$
\begin{align}
	P(X=k_1)&\approx0,219\\
	P(X=k_2)&\approx0,219
\end{align}
$$
<iframe src="https://www.desmos.com/calculator/o3eeiwu4ie?embed" width="1000" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

### a2) $p=0,5\quad n_2=64$
$$
\begin{align}
	\mu&=n_2\cdot p\\
	\mu&=64\cdot 0,5\\
	\mu&=32
\end{align}
$$

$$
\begin{align}
	P(X=\mu)&=\begin{pmatrix}n_2\\\mu\end{pmatrix}
	\cdot p^{\mu}\cdot (1-p)^{n_2-\mu}\\
	P(X=32)&=\begin{pmatrix}64\\32\end{pmatrix}
	\cdot 0,5^{32}\cdot (1-0,5)^{64-32}\\
	&=\begin{pmatrix}64\\32\end{pmatrix}
	\cdot 0,5^{32}\cdot 0,5^{32}\approx0,0994
\end{align}
$$
$$
\begin{align}
	\sigma&=\sqrt{\mu\cdot p\cdot (1-p)}\\
	&=\sqrt{32\cdot 0,5\cdot (1-0,5)}\\
	\sigma&=\sqrt{8}
\end{align}
$$

$$
\begin{align}
	\mu-\sigma&=32-\sqrt{8}\\
	&\text{Da hier }\sigma\in\mathbb{R}\backslash\mathbb{Q}\text{ ist, so muss dieser für hier }k\\
	&\text{angenommene Wert gerundet werden, da für }k \text{ gilt:}\\
	&k\in\mathbb{N}\\
	k_1=32-\sqrt{8}&\approx29,1715728753\approx29
	\\\\
	&\text{Es muss ebenfalls für }\mu+\sigma\text{ der Wert gerundet werden}\\
	k_2=32+\sqrt{8}&\approx34,8284271247\approx35
\end{align}
$$

$$
\begin{align}
	P(X=k_1)&\approx0,0753\\
	P(X=k_2)&\approx0,0753
\end{align}
$$

<iframe src="https://www.desmos.com/calculator/zuyoaa3csx?embed" width="1000" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>