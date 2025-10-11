Eine Ebene $E$ in beliebiger Form und ein Punkt $\overrightarrow{OR}$ wird auf [[Abstand]] überprüft.
Abstände benötigen stets die Verwendung des *Lot*es, wodurch hier ein Punkt mit dem [[Ortsvektor(en)]] $\overrightarrow{OS}$ auf der [[Ebene(n)]] gesucht wird, dessen [[Verbindungsvektor(en)]] zum anderem Punkt (also $\overrightarrow{RS}$ oder $\overrightarrow{SR}$) senkrecht gegen der Ebene ist. Die Länge dieses Verbindungsvektors heißt dann Abstand.
Zusammengefasst lässt sich dies wie folgt beschreiben:
$$
\begin{array}{}
	\overrightarrow{OS}\in E&& \overrightarrow{RS}\perp E
\end{array}
$$
Zum Berechnen dieses Punktes $\overrightarrow{OS}$ gibt es mindestens zwei Wege, diesen zu erhalten.

---
## Verwendung einer Hilfsgerade
Eine Gerade kann verwendet werden, um den gesuchten Ortsvektor $\overrightarrow{OS}$ zu bestimmen. Hierbei wird diese Gerade durch den Punkt $\overrightarrow{OR}$ gestützt, und mit einem zur Ebene senkrechten Richtungsvektor versehen. Einer dieser Richtungsvektoren ist der [[Normalenvektor]] der Ebene, da dieser senkrecht zu dieser liegt.
An dieser Stelle ist es sinnvoll, die Ebenengleichung in die Normalen oder Koordinatenform zu ändern (falls nicht bereits vorhanden), da das spätere arbeiten einfacher ist, und der [[Normalenvektor]] ablesbar verwendet werden kann.
>Die Ebenengleichung wird fortführend in der Koordinatenform angegeben.

Die Ebenengleichung wird generalisiert dargestellt, mit einer Geradengleichung die zuvor beschrieben wurde:
$$
\begin{align}
	E:n_1x_1+n_2x_2+n_3x_3&=d&&\boxed{\vec{n}\coloneqq
	\left(\begin{array}{}n_1\\n_2\\n_3
	\end{array}\right)}\\
	g:\vec{x}&=\overrightarrow{OR}+\lambda\cdot\vec{n}&&
		\boxed{\overrightarrow{OR}\coloneqq
	\left(\begin{array}{}r_1\\r_2\\r_3
	\end{array}\right)}
\end{align}
$$

Da $g$ senkrecht auf $E$ liegt, so ist der Schnittpunkt der gesuchte Ortsvektor $\overrightarrow{OS}$.
$$
\begin{align}
	E:n_1x_1+n_2x_2+n_3x_3&=d&&\mid g \text{ in }E\\
	n_1(r_1+n_1\lambda)+n_2(r_2+n_2\lambda)+n_3(r_3+n_3\lambda)&=d\\
	&~~\vdots\\
	\lambda&=\mu
\end{align}
$$

Hierdurch ist gegeben, welches $\lambda$ für die Gerade eingesetzt werden muss, damit der Ortsvektor herauskommt.
Der Abstand ist die Länge des Verbindungsvektors $\overrightarrow{RS}$, welcher durch $\overrightarrow{OS}-\overrightarrow{OR}$ bestimmt wird.

---
