Ein Produkt $h(x)=f(x)\cdot g(x)$ sei gegeben, wobei $f(x)$ und $g(x)$ auf einem Intervall $I=\left[a;b\right]$ integrierbar sind.
Bei [Ableitungen](Ableitung) ist die Produktregel gegeben, welche hier verwendet wird, um Stammfunktionen von Produkten zu bilden.
$$
\boxed{\begin{align}
	Q(x)&=r(x)\cdot w(x)\\
	q(x)&=r'(x)\cdot w(x)+r(x)\cdot w'(x)
\end{align}}
$$
Da $Q(x)$ hier eine Stammfunktion von $q(x)$ ist, so können wir annehmen, dass $q(x)$ $h(x)$ ist. Somit ist $Q(x)$ dann ebenfalls die Stammfunktion $H(x)$.
($\int h(x)~dx=H(x)$)
Da wir somit ein Integral darstellen können, finden wir die Definition des Produktes der Differention vor:
$$
\begin{align}
	q(x)&=r'(x)\cdot w(x)+r(x)\cdot w'(x)\\
	h(x)&=f'(x)\cdot g(x)+f(x)\cdot g'(x)\\
	f(x)\cdot g(x)&=f'(x)\cdot g(x)+f(x)\cdot g'(x)&&\mid
		\boxed{\begin{align}
			\text{Anwendung des Integrals,}\\
			\text{zur bildung von }H(x)
		\end{align}}\\
	\int^{b}_{a}f(x)\cdot g(x)&=
		\int^{b}_{a}f'(x)\cdot g(x)+
		\int^{b}_{a}f(x)\cdot g'(x)\\
\end{align}
$$

