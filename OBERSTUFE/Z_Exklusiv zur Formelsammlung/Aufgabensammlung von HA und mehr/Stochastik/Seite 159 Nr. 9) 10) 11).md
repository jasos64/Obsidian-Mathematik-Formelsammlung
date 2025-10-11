# 9)
> Aus der Schale in Fig. $2$ entnimmt man "blind" nacheinander vier Kugeln und legt sie vor sich auf den Tisch. $X$ sei die Anzahl roter Kugeln, die man zieht.
> Wie groß ist der Erwartungswert und die Standartabweichung von $X$? Beschreiben Sie Ihren Lösungsweg genau.

Aus Abbildung 2:
- $w=7$
- $m=3$
- $n=4$
Wir haben $w$ rote und $m$ blaue Kugeln in der Schale. Variablenbezeichnung nach belieben. $n$ gibt hier die Anzahl der Ziehungen an.

> Es kommt hervor, dass $X$ Hypergeometrisch verteilt ist.

Es folgt für $X$ die folgende Verteilung und Wahrscheinlichkeitsverteilung:
$$
\begin{align}
	P(X=k)&=\frac{\begin{pmatrix}w\\k\end{pmatrix}
		\cdot\begin{pmatrix}m\\4-k\end{pmatrix}}{\begin{pmatrix}w+m\\4\end{pmatrix}}\\
	&=\frac{\begin{pmatrix}7\\k\end{pmatrix}
		\cdot\begin{pmatrix}3\\4-k\end{pmatrix}}{\begin{pmatrix}10\\4\end{pmatrix}}
\end{align}
$$
$$
\begin{align}
	&\begin{array}{c|c}
	k&0&1&2&3&4\\\hline
	P(X=k)&P(X=0)&P(X=1)&P(X=2)&P(X=3)&P(X=4)
	\end{array}\\\\
	&\begin{array}{c|c}
	k&0&1&2&3&4\\\hline
	P(X=k)&0&\frac{1}{30}&\frac{3}{10}&\frac{1}{2}&\frac{1}{6}
	\end{array}
\end{align}
$$

Der Erwartungswert ergibt sich durch:
$$
\begin{align}
	\mu&=\sum_{i=0}^{k}i\cdot P(X=i)\\
	&=0\cdot P(X=0)+1\cdot P(X=1)+2\cdot P(X=2)+3\cdot P(X=3)+4\cdot P(X=4)\\
	&=0\cdot0+1\cdot\frac{1}{30}+2\cdot\frac{3}{10}+3\cdot\frac{1}{2}+4\cdot\frac{1}{6}\\
	\mu&=2,8
\end{align}
$$
>Der Erwartungswert dieser Verteilung ist $2,8$. Es können also bei unendlich vielen Durchführungen im Schnitt $2,8$ rote kugeln erwartet werden.

Die Standartabweichung ergibt sich durch:
$$
\begin{align}
	\sigma(X)^2=V(X)&=\sum_{i=0}^{k}\left(i-\mu\right)^2\cdot P(X=i)\\
	&=\left(0-\mu\right)^2\cdot P(X=0)+\left(1-\mu\right)^2\cdot P(X=1)+\left(2-\mu\right)^2\cdot P(X=2)+\left(3-\mu\right)^2\cdot P(X=3)+\left(4-\mu\right)^2\cdot P(X=4)\\
	&=\left(0-2,8\right)^2\cdot 0+\left(1-2,8\right)^2\cdot \frac{1}{30}+\left(2-2,8\right)^2\cdot \frac{3}{10}+\left(3-2,8\right)^2\cdot \frac{1}{2}+\left(4-2,8\right)^2\cdot \frac{1}{6}\\
	&~~\vdots\\
	\sigma(X)^2&=0,56\\
	\sigma(X)&=\sqrt{0,56}\approx0,748
\end{align}
$$

> Die Standartabweichung der Verteilung liegt bei ungefähr $0,748$. Die Verteilung ist daher nicht sehr gestreut.

---
---
# 10)
> Bei einem Spiel würfelt man nach einem Einsatz von einem Euro mit fünf Würfeln. Für jede Sechs erhält man einen Euro ausbezahlt.

## a)
> Welchen mittleren gewinn oder Verlust kann man auf lange Sicht erwarten? Welchen Gewinn oder Verlust kann man bei 120 Spielen erwarten?

- $X:\text{Anzahl Sechsen}$
- $X\sim\mathcal{B}\left(5;\frac{1}{6}\right)$
$$
\begin{array}{c|c}
	1\cdot x_i-1&-1&0&1&2&3&4\\\hline
	P(X=x_i)&P(X=0)&P(X=1)&P(X=2)&P(X=3)&P(X=4)&P(X=5)
\end{array}
$$

Der Erwartungswert ergibt sich durch:
$$
\begin{align}
	\mu&=-1\cdot P(X=0)+\textcolor{red}{0\cdot P(X=1)}+1\cdot P(X=2)+2\cdot P(X=3)+3\cdot P(X=4)+4\cdot P(X=5)\\
	&=-1\cdot P(X=0)+1\cdot P(X=2)+2\cdot P(X=3)+3\cdot P(X=4)+4\cdot P(X=5)\\
	&~~\vdots\\
	\mu&=-\frac{1}{6}
\end{align}
$$
>Der Erwartungswert dieser Verteilung ist $-\frac{1}{6}$. Es werden durchschnittlich demnach für jedes Spiel $17\textcent$ an Verlust generiert.
>Nach $120$ Spielen sind hier durchschnittlich folglich $-\frac{1}{6}\cdot120=-20\texteuro$ an Verlust zu beschreiben.

## b)
> Wie könnte man die Spielregeln abändern, damit das Spiel fair ist?

Nehmen wir an, dass $6$ Würfel geworfen werden dürfen:

- $X:\text{Anzahl Sechsen}$
- $X\sim\mathcal{B}\left(6;\frac{1}{6}\right)$
$$
\begin{array}{c|c}
	1\cdot x_i-1&-1&0&1&2&3&4&5\\\hline
	P(X=x_i)&P(X=0)&P(X=1)&P(X=2)&P(X=3)&P(X=4)&P(X=5)&P(X=6)
\end{array}
$$

Der Erwartungswert ergibt sich durch:
$$
\begin{align}
	\mu&=-1\cdot P(X=0)+\textcolor{red}{0\cdot P(X=1)}+1\cdot P(X=2)+2\cdot P(X=3)+3\cdot P(X=4)+4\cdot P(X=5)+5\cdot P(X=6)\\
	&=-1\cdot P(X=0)+1\cdot P(X=2)+2\cdot P(X=3)+3\cdot P(X=4)+4\cdot P(X=5)+5\cdot P(X=6)\\
	&~~\vdots\\
	\mu&=0
\end{align}
$$
> Hier ist der Erwartungswert $0$. Somit muss der Würfel $6$ mal geworfen werden, damit das Spiel fair ist.

---
---
# 11)
> Begründen Sie, dass der Graph der binomialverteilten Zufallsvariablen $X$ mit den Parametern $n=10$ und $p=\frac{1}{2}$ symmetrisch zur Geraden $x=5$ ist. Verwenden Sie die Bernoulli-Formel.

Damit die Geradensymmetrie von $P(X=k)=\begin{pmatrix}10\\k\end{pmatrix}\cdot 0,5^{k}\cdot{(1-0,5)}^{10-k}$ für $x=5$ bewiesen werden kann, gilt $f(a-x)=f(a+x)$
($P(X=a-x)=P(X=a+x)$), wobei $a=5$, durch $x=5$ der Gerade gegeben ist.

$$
\begin{align}
	P(X=a-x)&=P(X=a+x)\\
	P(X=5-x)&=P(X=5+x)\\
	\begin{pmatrix}10\\5-x\end{pmatrix}\cdot 0,5^{5-x}\cdot{(1-0,5)}^{10-(5-x)}&=
		\begin{pmatrix}10\\5+x\end{pmatrix}\cdot 0,5^{5+x}\cdot{(1-0,5)}^{10-(5+x)}\\
	
	\frac{10!}{(10-(5-x))!\cdot(5-x)!}
	\cdot 0,5^5\cdot\frac{1}{0,5^x}\cdot0,5^{10-5+x}
	&=
		\frac{10!}{(10-(5+x))!\cdot(5+x)!}
		\cdot 0,5^5\cdot0,5^x\cdot0,5^{10-5-x}\\
	
	\frac{10!}{(10-5+x)!\cdot(5-x)!}
	\cdot \cancel{0,5^5}\cdot\cancel{\frac{1}{0,5^x}}\cdot0,5^{10}\cdot\cancel{\frac{1}{0,5^5}}\cdot\cancel{0,5^x}
	&=
		\frac{10!}{(10-5-x)!\cdot(5+x)!}
		\cdot \cancel{0,5^5}\cdot\cancel{0,5^x}\cdot0,5^{10}\cdot\cancel{\frac{1}{0,5^5}}\cdot\cancel{\frac{1}{0,5^x}}\\
	
	\frac{10!}{(10-5+x)!\cdot(5-x)!}
	\cdot0,5^{10}&=
		\frac{10!}{(10-5-x)!\cdot(5+x)!}
		\cdot 0,5^{10}\\
		
	\frac{10!}{(5+x)!\cdot(5-x)!}
	\cdot0,5^{10}&=
		\frac{10!}{(5-x)!\cdot(5+x)!}
		\cdot 0,5^{10}\\
		1&=1
\end{align}
$$

Durch dem Erfüllen der Bedingung $P(X=5-x)=P(X=5+x)$ ist folglich "bewiesen", dass eine Geradensymmetrie zu der Gerade $x=5$ bei dieser Binomialverteilung besteht.

**Beweisführung:** [[Seite 159 Nr. 11)]]

---
---