> Eine Funktion kann mit einer Substitution  integriert werden.

Beispielsweise haben wir die Funktion $f(x)=(x^4-4)^4\cdot x^3$, die integriert werden soll. Über die uns bekannten Integrationsregeln können wir $f$ nur partiell integrieren, was länger dauert.

Mit der Substitution von $u=x^4-4$ lässt sich folgendes erarbeiten:
$$\int (x^4-4)^4\cdot x^3~dx=\int u^4\cdot x^3~dx$$
Parallel muss $u$ abgeleitet werden und umgeformt werden:
$$
\begin{align}
	u&=x^4-4\\\\
	du&=4x^3~dx&&\mid\div4x^3\\
	dx&=\frac{du}{4x^3}
\end{align}
$$
Das $dx$ wird automatisch zur Ableitung von $u$ dazugeschrieben.
Wir setzen die Abhängigkeit von $dx$ in den Integranden ein:
$$
\begin{align}
	\int u^4\cdot x^3~dx&=\int u^4\cdot x^3\cdot\frac{du}{4x^3}\\
	&=\int \frac{1}{4}\cdot u^4~du\\
	&=\frac{1}{20}\cdot u^5=\frac{1}{20}\cdot (x^4-4)^5
\end{align}
$$
Die Stammfunktion ist somit $F(x)=\frac{1}{20}\cdot (x^4-4)^5$.

---