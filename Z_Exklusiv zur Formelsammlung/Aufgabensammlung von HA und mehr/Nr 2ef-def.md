## 2) e
> Wie oft muss man diesen Würfel werfen, um mit einer Wahrscheinlichkeit von wenigstens $95\%$ mindestens eine Drei zu erzielen?

Gegeben ist von vorher:
- $Y:\text{"Anzahl 3-en"}$
- $P(3)=\frac{1}{3}$
Gegeben aus der Aufgabe:
- $P(Y\ge1)\ge0,95$
- $n$-gesucht

---
Es gilt:
$$
\begin{align}
	P(Y\ge1)&\ge0,95\\
	1-P(Y<1)&\ge0,95\\
	1-P(Y=0)&\ge0,95&&\mid -1\\
	-P(Y=0)&\ge-0,05&&\mid\cdot( -1)\\
	P(Y=0)&\le0,05
\end{align}
$$
Weil $Y$ binomialverteilt ist, gilt für $P(Y=k)=\begin{pmatrix}n\\k\end{pmatrix}\cdot p^k\cdot(1-p)^{n-k}$

$$
\begin{align}
	P(Y=0)&\le0,05\\
	\underbrace{\begin{pmatrix}n\\0\end{pmatrix}}_{=1}\cdot \underbrace{\left(\frac{1}{3}\right)^0}_{=1}\cdot\left(1-\frac{1}{3}\right)^{n-0}
		&\le0,05\\
	1\cdot1\cdot\left(\frac{2}{3}\right)^n
		&\le0,05\\
	\left(\frac{2}{3}\right)^n
		&\le0,05
\end{align}
$$
Folgend wird der $ln$ benutzt, um den Exponenten $n$ aus der Potenz zu entfernen. Es gilt für allgemeine Logarithmen:
$$
\ln(a^b)=b\cdot\ln(a)
$$
$$
\begin{align}
	\left(\frac{2}{3}\right)^n
		&\le0,05&&\mid \ln\\
	
	n\cdot\ln\left(\frac{2}{3}\right)
		&\le\ln(0,05)&&\mid \div \ln\left(\frac{2}{3}\right)
\end{align}
$$
Für Werte zwischen $0$ bis $1$ ist der $\ln$ negativ. Bei Ungleichungen wird bei einer Division oder Multiplikation hier die Ungleichung umgedreht
$$
\begin{align}
	n&\ge\frac{\ln(0,05)}{\ln\left(\frac{2}{3}\right)}\approx 7,288\\
	n&\ge8
\end{align}
$$
Weil $n$ nur ganze Zahlen beinhalten kann, muss der Würfel mindestens $8$ mal geworfen werden, damit die Bedingungen der Aufgabe erfüllt sind.

---
## f)
$P(D)=\begin{pmatrix}3\\1\end{pmatrix}\cdot\frac{1}{6}\cdot\left(\frac{5}{6}\right)^2=0,347\overline{2}$
$P(E)=\frac{1}{2}\cdot\frac{1}{3}\cdot\frac{1}{6}=\frac{1}{36}$
![[Pasted image 20240915221824.png]]