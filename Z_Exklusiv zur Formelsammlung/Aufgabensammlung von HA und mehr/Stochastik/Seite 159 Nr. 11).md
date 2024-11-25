 >Begründen Sie, dass der Graph der binomialverteilten [Zufallsvariablen](Zufallsvariable) $X$ mit den Parametern $n=10$ und $p=\frac{1}{2}$ symmetrisch zur Geraden $x=5$ ist. Verwenden Sie die Bernoulli-Formel.

 $$
\begin{align}
	P(X=k)&=\begin{pmatrix}n\\k\end{pmatrix}
	\cdot p^{k}\cdot (1-p)^{n-k}\\
	P(X=k)&=\begin{pmatrix}10\\k\end{pmatrix}
	\cdot 0,5^{k}\cdot{(1-0,5)}^{10-k}\\
\end{align}$$

Eine Funktion ist symmetrisch zu der Y-Achse, insofern $f(-x)\equiv f(x)$ gilt. Die Symmetrie befindet sich hier an der Stelle $x=0$. Laut Definition sind Werte für Stellen, die die gleiche Entfernung zu der Symmetriestelle haben, gleich. Insofern eine [Funktion](Funktion(en)) eine [[Symmetrie]] zu einer Gerade $x=a$ hat, so muss durch die Beschreibung für Y-Achsensymmetrien folgendes gelten, damit eine [Funktion](Funktion(en)) Symmetrisch zu dieser Geraden heißt: $f(a-x)\equiv f(a+x)$.
Beispielsweise sei die Funktion $f(x)=0,1(x-a)^4+(x-a)^2$ gegeben, welche eine Achsensymmetrie zu der Geraden $x=a$ besitzt. Damit $f(a-x)\equiv f(a+x)$ für dieses Beispiel "bewiesen" werden kann, werde ich dies zunächst nur einsetzen und vereinfachen und auf Identität vergleichen.

$$
\begin{align}
	f(a-x)&\stackrel{?}{=}f(a+x)\\
	0,1((a-x)-a)^4+((a-x)-a)^2&=0,1((a+x)-a)^4+((a+x)-a)^2\\
		0,1(\textcolor{red}a-x\textcolor{red}{-a})^4+(\textcolor{red}a-x\textcolor{red}{-a})^2
		&=0,1(\textcolor{red}a-x\textcolor{red}{-a})^4+(\textcolor{red}a-x\textcolor{red}{-a})^2\\
	0,1\textcolor{orange}{(-x)^4}+\textcolor{orange}{(-x)^2}&=0,1(x)^4+(x)^2&&\mid
		\boxed{
			\begin{align}
				(-x)^4&=x^4\\
				(-x)^2&=x^2
			\end{align}}\\
	0,1x^4+x^2&\equiv0,1x^4+x^2
\end{align}
$$

Da hier das beschriebene gilt, ist die Symmetrie an der Stelle $a$ dargestellt. Generell gesehen lässt sich (anzunehmen) sagen, dass eine Geradensymmetrie an einer Funktion vorhanden ist, insofern es für $f(a-x)=f(a+x)$ eine Lösung $0=0$ gibt.
$$\forall x\exists a\in \mathbb{R},\quad f(a-x)\equiv f(a+x)$$
![[Geradensymmetrie]]

---
## Aufgabe
Damit die Geradensymmetrie von $P(X=k)=\begin{pmatrix}10\\k\end{pmatrix}\cdot 0,5^{k}\cdot{(1-0,5)}^{10-k}$ für $x=5$ bewiesen werden kann, gilt erneut $f(a-x)=f(a+x)$
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

---
---
## Übertragen auf generelle Verteilungen
Hier werde ich versuchen einen Zusammenhang zwischen einer *"Symmetriegerade"* und der Auswahl verschiedener $n$ und $p$ aufzustellen, insofern einer besteht.
Eine Binomialverteilung sei gegeben, mit den Parametern
>- $0< p<1$
>- $n\in\mathbb{N}_0$
>- $0\le (k,a)\le n$

$$
\begin{align}
	P(X=a-k)&=P(X=a+k)\\
	
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot p^{a-k}\cdot (1-p)^{n-(a-k)}&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot p^{a+k}\cdot (1-p)^{n-(a+k)}\\
		
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot p^a\cdot\frac{1}{p^k}\cdot(1-p)^{n-a+k}&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot p^a\cdot p^k\cdot (1-p)^{n-a-k}\\
	
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot p^a\cdot\frac{1}{p^k}\cdot(1-p)^n\cdot\frac{1}{(1-p)^a}\cdot(1-p)^k&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot p^a\cdot p^k\cdot (1-p)^n\frac{1}{(1-p)^a}\cdot\frac{1}{(1-p)^k}\\
	
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot\frac{(1-p)^k}{p^k}\cdot\textcolor{red}{(1-p)^n}\cdot\textcolor{red}{\frac{p^a}{(1-p)^a}}&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot\textcolor{red}{(1-p)^n}\cdot\textcolor{red}{\frac{p^a}{(1-p)^a}}\cdot\frac{p^k}{(1-p)^k}\\
	
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot\frac{(1-p)^k}{p^k}&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot\frac{p^k}{(1-p)^k}\\
	
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot\left(\frac{1-p}{p}\right)^k&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot\left(\frac{p}{1-p}\right)^k
\end{align}
$$
Gesehen kann dies wie eine Art von [[Koeffizientenvergleich]], wobei die beiden Binomialkoeffizienten und die Basen der Exponentialfunktionen auf einen identischen Wert (hier für alle $k$) gebracht werden sollen.
Insofern beide identisch sind, so sind beide Terme ebenfalls identisch.

---
### Vergleich der Binomialkoeffizienten
Anfangen werde ich mit den Binomialkoeffizienten.

![[nÜberK=nÜberN-k]]

Da hier $k=n-k$ im ***(Nenner vom Binomialkoeffizienten?)*** dargestellt ist, werde ich diesen dazu benutzen, um $a-k$ und $a+k$ durch diesen gleich zu setzen.
$$
\begin{align}
	&\left(
		\begin{array}{ccc|cc}
			&0n&k&a&-k \\
			&n&-k&a&k
		\end{array}
		\right)
			\begin{array}{}
				&|+k\\
				&|-k
			\end{array}
		\\ \\
	&\left(
		\begin{array}{ccc|cc}
			&0n&2k&a \\
			&n&-2k&a
		\end{array}
		\right)
			\begin{array}{}
				&|+II\\
				&
			\end{array}
		\\ \\
	&\left(
		\begin{array}{ccc|cc}
			&n&0&2a \\
			&n&-k&a
		\end{array}
		\right)
			\begin{array}{}
				&\\
				&
			\end{array}
		\\ \\
\end{align}$$
$$
\begin{align}
	\text{Aus I:}&&n&=2a&&\mid\div2\\
	&&a&=0,5n
\end{align}$$
Folglich existiert eine Symmetriegerade $x=0,5n$ für aktuell unbekannte $p$.

---
### Vergleich der Exponentialfunktionen
Für die Exponentialfunktionen der beiden Terme gilt, damit diese identisch sind $\left(\frac{1-p}{p}\right)^k=\left(\frac{p}{1-p}\right)^k$. Die Exponenten sind hier identisch, weshalb gleiche Werte der Basen diese Bedingung herstellt.
Folglich gilt:
$$
\begin{align}
	\frac{1-p}{p}&=\frac{p}{1-p}&&\mid -\frac{1-p}{p}\\
	0&=\frac{p}{1-p}-\frac{1-p}{p}\\
	0&=\frac{p^2-(1-p)^2}{p-p^2}\\
	0&=\frac{p^2-(1-2p+p^2)}{p-p^2}\\
	0&=\frac{\textcolor{red}{p^2}-1+2p\textcolor{red}{-p^2}}{p-p^2}\\
	0&=\frac{2p-1}{p-p^2}
\end{align}
$$
$$
\begin{array}{rclccc||cl}
	&0&=&2p-1&\mid+1&&0&=&p-p^2&\\
	&-1&=&2p&\mid\div2&&0&=&p\cdot(1-p)&\mid p_{n1}=0\\
	&p&=&0,5&&&0&=&1-p&\mid-1~~\mid \div(-1)\\
	&p&=&0,5&&&p&=1&&
\end{array}
$$
Folglich daraus muss $p=0,5$ sein. Zusätzlich dazu darf $p$ weder $0$, noch $1$ annehmen, da hier durch null geteilt werden würde.

---
### Einsetzen der Werte $p$ und $a$
Die erhaltenen Werte und Verbindungen der Variablen $p=0,5$ und $a=0,5n$ werde ich zum Schluss in die Ursprüngliche Funktion oben einsetzen um diese auf Identität zu bringen:
$$
\begin{align}
	P(X=a-k)&=P(X=a+k)\\
	
	\begin{pmatrix}n\\a-k\end{pmatrix}
	\cdot p^{a-k}\cdot (1-p)^{n-(a-k)}&=
		\begin{pmatrix}n\\a+k\end{pmatrix}
		\cdot p^{a+k}\cdot (1-p)^{n-(a+k)}\\
	
	\begin{pmatrix}n\\0,5n-k\end{pmatrix}
	\cdot 0,5^{0,5n-k}\cdot (1-0,5)^{n-(0,5n-k)}&=
		\begin{pmatrix}n\\0,5n+k\end{pmatrix}
		\cdot 0,5^{0,5n+k}\cdot (1-0,5)^{n-(0,5n+k)}\\
	
	\begin{pmatrix}n\\0,5n-k\end{pmatrix}
	\cdot 0,5^{0,5n-k}\cdot 0,5^{n-0,5n+k}&=
		\begin{pmatrix}n\\0,5n+k\end{pmatrix}
		\cdot 0,5^{0,5n+k}\cdot 0,5^{n-0,5n-k}\\
	
	\begin{pmatrix}n\\0,5n-k\end{pmatrix}
	\cdot \textcolor{darkred}{ 0,5^{0,5n-k}}\cdot \textcolor{red}{0,5^{0,5n+k}}&=
		\begin{pmatrix}n\\0,5n+k\end{pmatrix}
		\cdot\textcolor{red}{ 0,5^{0,5n+k}}\cdot \textcolor{darkred}{ 0,5^{0,5n-k}}\\
	
	\begin{pmatrix}n\\0,5n-k\end{pmatrix}&=
		\begin{pmatrix}n\\0,5n+k\end{pmatrix}\\
	
	\frac{n!}{(n-(0,5n-k))!\cdot(0,5n-k)!}&=
		\frac{n!}{(n-(0,5n+k))!\cdot(0,5n+k)!}\\
	
	\frac{n!}{(n-0,5n+k)!\cdot(0,5n-k)!}&=
		\frac{n!}{(n-0,5n-k)!\cdot(0,5n+k)!}\\
	
	\frac{n!}{(0,5n+k)!\cdot(0,5n-k)!}&\equiv
		\frac{n!}{(0,5n-k)!\cdot(0,5n+k)!}\\
	
	0&\equiv0
\end{align}
$$

### Ende der Untersuchung und "Fazit"
Durch diese letzten beiden "Untersuchungen" zeigt sich, dass jede Binomialverteilung mit dem Wert $p=0,5$ für alle $n$ eine Geradensymmetrie mit der Geraden $x=0,5n$ besitzt.

$$
\begin{align}
	\forall n\in\mathbb{N},~
\end{align}
$$
<p align="right">
■
</p>

---
$p=0,5$:
![[BinomialeSymmetrien.svg]]