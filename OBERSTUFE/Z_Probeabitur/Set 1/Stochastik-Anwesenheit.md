# Stochastik
> Die Anwesenheiten von $50$ Orchestermitgliedern wird an einem Termin betrachtet. Es stellt sich raus, dass allgemein $26\%$ an dieser Probe nicht teilgenommen haben. $8\%$ sind Blechbläser, die nicht da waren. Aus anderen Registern waren $36\%$ anwesend.

> Es gelten die Ereignisse:
> - $A:\text{"Anwesend"}$
> - $B:\text{"Blechregister"}$

### a)
> Veranschaulichen Sie den Sachverhalt in der gegebenen Vierfeldertafel:

$$
\begin{array}{r|ccc}
	&A&\overline{A}&\sum\\ \hline
	B&\qquad &\qquad& \qquad\\
	\overline{B} &\qquad&\qquad &\qquad \\
	\sum&\qquad & \qquad& 1
\end{array}
$$

### b)
> Eine Person aus dem Orchester wird zufällig betrachtet. Bestimmen Sie mit welcher Wahrscheinlichkeit diese an der Probe anwesend war, und im Blechregister ist.
> Bestimmen Sie auch die Wahrscheinlichkeit, dass eine Person aus dem Blechregister anwesend war.

### c)
> Überprüfen Sie, ob die Ereignisse $A$ und $B$ stochastisch unabhängig sind.


### d)
> Begründen Sie, wieso dieses Baumdiagramm nicht aus der Vierfeldertafel gebildet wurde. Verändern Sie das Baumdiagramm anschließend so, dass es der Vierfeldertafel entspricht.


<img src="https://i.upmath.me/svg/%0A%5C%5B%5Cbegin%7Btikzcd%7D%0A%09%26%26%20%7B%7D%20%5C%5C%0A%09%26%20A%20%26%26%20%7B%5Coverline%20A%7D%20%5C%5C%0A%09B%20%26%20%7B%5Coverline%20B%7D%20%26%26%20B%20%26%20%7B%5Coverline%20B%7D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B37%7D%7B50%7D%7D%22%7Bdescription%7D%2C%20from%3D1-3%2C%20to%3D2-2%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B13%7D%7B50%7D%7D%22%7Bdescription%7D%2C%20from%3D1-3%2C%20to%3D2-4%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B19%7D%7B37%7D%7D%22%7Bdescription%7D%2C%20from%3D2-2%2C%20to%3D3-1%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B18%7D%7B37%7D%7D%22%7Bdescription%7D%2C%20from%3D2-2%2C%20to%3D3-2%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B5%7D%7B13%7D%7D%22%7Bdescription%7D%2C%20from%3D2-4%2C%20to%3D3-4%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B8%7D%7B13%7D%7D%22%7Bdescription%7D%2C%20from%3D2-4%2C%20to%3D3-5%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B19%7D%7B50%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20draw%3Dnone%2C%20from%3D3-1%2C%20to%3D3-1%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B9%7D%7B25%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20draw%3Dnone%2C%20from%3D3-2%2C%20to%3D3-2%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B1%7D%7B10%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20draw%3Dnone%2C%20from%3D3-4%2C%20to%3D3-4%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%09%5Carrow%5B%22%7B%5Cfrac%7B4%7D%7B25%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20draw%3Dnone%2C%20from%3D3-5%2C%20to%3D3-5%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%5Cend%7Btikzcd%7D%5C%5D%0A" alt="
\[\begin{tikzcd}
	&amp;&amp; {} \\
	&amp; A &amp;&amp; {\overline A} \\
	B &amp; {\overline B} &amp;&amp; B &amp; {\overline B}
	\arrow[&quot;{\frac{37}{50}}&quot;{description}, from=1-3, to=2-2]
	\arrow[&quot;{\frac{13}{50}}&quot;{description}, from=1-3, to=2-4]
	\arrow[&quot;{\frac{19}{37}}&quot;{description}, from=2-2, to=3-1]
	\arrow[&quot;{\frac{18}{37}}&quot;{description}, from=2-2, to=3-2]
	\arrow[&quot;{\frac{5}{13}}&quot;{description}, from=2-4, to=3-4]
	\arrow[&quot;{\frac{8}{13}}&quot;{description}, from=2-4, to=3-5]
	\arrow[&quot;{\frac{19}{50}}&quot;{description}, shift right=2, draw=none, from=3-1, to=3-1, loop, in=240, out=300, distance=5mm]
	\arrow[&quot;{\frac{9}{25}}&quot;{description}, shift right=2, draw=none, from=3-2, to=3-2, loop, in=240, out=300, distance=5mm]
	\arrow[&quot;{\frac{1}{10}}&quot;{description}, shift right=2, draw=none, from=3-4, to=3-4, loop, in=240, out=300, distance=5mm]
	\arrow[&quot;{\frac{4}{25}}&quot;{description}, shift right=2, draw=none, from=3-5, to=3-5, loop, in=240, out=300, distance=5mm]
\end{tikzcd}\];
}
" width=500/>

### e)
> Der Orchestervorstand vermutet, dass sich die Anwesenheit der Musiker, die nicht im Blechregister sind, mittlerweile weiter reduziert hat. Der Vorstand geht hierbei von einer Anwesenheit von $p=30\%$ aus. Erstellen Sie einen beidseitigen Hypothesentest mit einem Signifikanzniveau von $5\%$ und einer Stichprobengröße von $50$. Beschreiben Sie die Entscheidungsregel zum Annehmen der Vermutung.
> Entscheiden Sie, ob eine Annäherung der Binomialverteilung mit der Laplace-Bedingung möglich wäre.

### f)
> Es werden nacheinander zufällig Anwesenheiten von Musikern betrachtet. Weiterhin sind es $50$ Teilnehmer.
> Bestimmen Sie die Wahrscheinlichkeit des folgenden Ereignisses:
> - Mit $8$ maligem ziehen sind exakt $1$ oder $2$ Musiker teil der Menge $\{\overline A\cap B\}$
> 
> Wie viele Musiker müssen von den $50$ Mitgliedern ohne zurücklegen gezogen werden, sodass die Wahrscheinlichkeit, dass alle anwesenden aus dem Blasregister gezogen wurden, mindestens $20\%$ beträgt?
> 
> Falls die Vierfeldertafel fehlt, nutzen Sie:
$$
\begin{align}
	\left|\{A\cap B\}\right|&=19\\
	\left|\{\overline A\cap B\}\right|&=4
\end{align}
$$

---
# Lösungen
### a)
$$
\begin{array}{llrr}
	\begin{array}{r|ccc}
		&A&\overline{A}&\sum\\ \hline
		B&0,38 &0,08& 0,46\\
		\overline{B} &0,36&0,18 &0,54 \\
		\sum&0,74 & 0,26& 1
	\end{array}&&&
	\begin{array}{r|ccc}
		&A&\overline{A}&\sum\\ \hline
		B&19 &4& 23\\
		\overline{B} &18&9 &27 \\
		\sum&37 & 13& 50
	\end{array}
\end{array}
$$

### b)
Person ist im Blechregister und anwesend:
$$
P(A\cap B)=0,38
$$
Eine Person aus dem Blechregister ist anwesend:
$$
P(E)=\frac{P(A\cap B)}{P(B)}=\frac{0,38}{0,46}=\frac{19}{23}\approx0,826
$$

### c)
Die Ereignisse $A$ und $B$ sind stochastisch unabhängig, wenn gilt $P(A\cap B)=P(A)\cdot P(B)$.
$$
\begin{align}
	P(A\cap B)&\stackrel{!}{=}P(A)\cdot P(B)\\
	0,38&=0,74\cdot0,46\\
	0,38&\ne0,3404
\end{align}
$$
Da $P(A\cap B)\ne P(A)\cdot P(B)$, so sind die Ereignisse stochastisch abhängig zueinander.

### d)
Das Baumdiagramm ist nicht aus der Vierfeldertafel gebildet, da $P(\overline A\cap B)$ und $P(\overline A\cap \overline B)$ nicht der Vierfeldertafel entsprechen ($P_\overline A(B)$ und $P_\overline A(\overline B)$ folglich auch nicht).
Aus dem Baumdiagramm:
$$
\begin{align}
	P(\overline A\cap B)&=0,1&&(\ne 0,08)\\
	P(\overline A\cap\overline B)&=0,16&&(\ne 0,18)
\end{align}
$$


<img src="https://i.upmath.me/svg/%0A%5C%5B%5Cbegin%7Btikzcd%7D%0A%09%26%26%20%7B%7D%20%5C%5C%0A%09%26%20A%20%26%26%20%7B%5Coverline%20A%7D%20%5C%5C%0A%09B%20%26%20%7B%5Coverline%20B%7D%20%26%26%20B%20%26%20%7B%5Coverline%20B%7D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B37%7D%7B50%7D%7D%7D%22%7Bdescription%7D%2C%20from%3D1-3%2C%20to%3D2-2%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B13%7D%7B50%7D%7D%7D%22%7Bdescription%7D%2C%20from%3D1-3%2C%20to%3D2-4%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B19%7D%7B37%7D%7D%7D%22%7Bdescription%7D%2C%20from%3D2-2%2C%20to%3D3-1%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B18%7D%7B37%7D%7D%7D%22%7Bdescription%7D%2C%20from%3D2-2%2C%20to%3D3-2%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B4%7D%7B13%7D%7D%7D%22%7Bdescription%7D%2C%20color%3D%7Brgb%2C255%3Ared%2C214%3Bgreen%2C92%3Bblue%2C92%7D%2C%20from%3D2-4%2C%20to%3D3-4%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B9%7D%7B13%7D%7D%7D%22%7Bdescription%7D%2C%20color%3D%7Brgb%2C255%3Ared%2C214%3Bgreen%2C92%3Bblue%2C92%7D%2C%20from%3D2-4%2C%20to%3D3-5%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B19%7D%7B50%7D%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20draw%3Dnone%2C%20from%3D3-1%2C%20to%3D3-1%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B9%7D%7B25%7D%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20draw%3Dnone%2C%20from%3D3-2%2C%20to%3D3-2%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B4%7D%7B50%7D%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20color%3D%7Brgb%2C255%3Ared%2C214%3Bgreen%2C92%3Bblue%2C92%7D%2C%20draw%3Dnone%2C%20from%3D3-4%2C%20to%3D3-4%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%09%5Carrow%5B%22%7B%7B%5Cfrac%7B9%7D%7B50%7D%7D%7D%22%7Bdescription%7D%2C%20shift%20right%3D2%2C%20color%3D%7Brgb%2C255%3Ared%2C214%3Bgreen%2C92%3Bblue%2C92%7D%2C%20draw%3Dnone%2C%20from%3D3-5%2C%20to%3D3-5%2C%20loop%2C%20in%3D240%2C%20out%3D300%2C%20distance%3D5mm%5D%0A%5Cend%7Btikzcd%7D%5C%5D%0A" alt="
\[\begin{tikzcd}
	&amp;&amp; {} \\
	&amp; A &amp;&amp; {\overline A} \\
	B &amp; {\overline B} &amp;&amp; B &amp; {\overline B}
	\arrow[&quot;{{\frac{37}{50}}}&quot;{description}, from=1-3, to=2-2]
	\arrow[&quot;{{\frac{13}{50}}}&quot;{description}, from=1-3, to=2-4]
	\arrow[&quot;{{\frac{19}{37}}}&quot;{description}, from=2-2, to=3-1]
	\arrow[&quot;{{\frac{18}{37}}}&quot;{description}, from=2-2, to=3-2]
	\arrow[&quot;{{\frac{4}{13}}}&quot;{description}, color={rgb,255:red,214;green,92;blue,92}, from=2-4, to=3-4]
	\arrow[&quot;{{\frac{9}{13}}}&quot;{description}, color={rgb,255:red,214;green,92;blue,92}, from=2-4, to=3-5]
	\arrow[&quot;{{\frac{19}{50}}}&quot;{description}, shift right=2, draw=none, from=3-1, to=3-1, loop, in=240, out=300, distance=5mm]
	\arrow[&quot;{{\frac{9}{25}}}&quot;{description}, shift right=2, draw=none, from=3-2, to=3-2, loop, in=240, out=300, distance=5mm]
	\arrow[&quot;{{\frac{4}{50}}}&quot;{description}, shift right=2, color={rgb,255:red,214;green,92;blue,92}, draw=none, from=3-4, to=3-4, loop, in=240, out=300, distance=5mm]
	\arrow[&quot;{{\frac{9}{50}}}&quot;{description}, shift right=2, color={rgb,255:red,214;green,92;blue,92}, draw=none, from=3-5, to=3-5, loop, in=240, out=300, distance=5mm]
\end{tikzcd}\]
" width=500/>

### e)
$$
\begin{align}
	H_0:p&=0,3\\H_1:p&\ne0,3\\
	X&:\text{"Anzahl anwesend"}\\
	X&\sim\symcal{B}(50;0,3)\\
	\alpha&=0,05
\end{align}
$$
Für den Test:
$$
\begin{align}
	P(X\le k_1)&\le\frac\alpha2\\
	P(X\le k_1)&\le0,025\\
	P(X\le 8)&\approx0,018\quad(\le0,025)\\
	\Rightarrow\quad k_1&=8\\\hline\\
	P(X\ge k_2)&\le\frac\alpha2\\\\
	1-P(X\le k_2-1)&\le0,025&&\mid\boxed{g=k_2-1}\\
	1-P(X\le g)&\le0,025&&\mid-1\quad\cdot(-1)\\
	P(X\le g)&\ge0,975\\
	P(X\le 22)&\approx0,988\quad(\ge,975)\\
	\Rightarrow\quad g&=22\Rightarrow k_2=23\\\hline\\
	V&=\left[0;k_1\right]\cup\left[k_2;n\right]
		=\left[0;8\right]\cup\left[23;50\right]\\
	\overline V&=\left[k_1+1;k_2-1\right]=\left[9;22\right]
\end{align}
$$
Die Nullhypothese wird verworfen, wenn eine Stichprobenanzahl von maximal $8$ oder mindestens $23$ anwesend sind.

Für die Laplace-Bedingung gilt: $\sigma>3$:
$$
\begin{align}
	\sigma=\sqrt{np(1-p)}&\stackrel!>3\\\\
	\sqrt{50\cdot0,3\cdot0,7}=\sqrt{10,5}&>3
\end{align}
$$
Eine Annäherung wäre für diese Binomialverteilung möglich, da $\sigma>3$.

### f)
Es liegt einer hypergeometrische Verteilung vor, da nacheinander Musiker betrachtet werden.
Wir definieren:
$$
\begin{align}
	X&:\text{"Anzahl Musiker aus }\{\overline A\cap B\}\text{"}\\
	Y&:\text{"Anzahl Musiker aus }\{ A\cap B\}\text{"}
\end{align}
$$
$$
\begin{align}
	E_1=P(X=1)+P(X=2)&=
		\frac{\begin{pmatrix}4\\1\end{pmatrix}\cdot
		\begin{pmatrix}46\\7\end{pmatrix}}
		{\begin{pmatrix}50\\8\end{pmatrix}}+
		\frac{\begin{pmatrix}4\\2\end{pmatrix}\cdot
		\begin{pmatrix}46\\6\end{pmatrix}}
		{\begin{pmatrix}50\\8\end{pmatrix}}\approx
		0,503
\end{align}
$$

Damit unter $n$ Zügen das gesamte anwesende Blechregister mit einer Wahrscheinlichkeit von $0,2$ gezogen wird gilt:
$$
\begin{align}
	P(Y=19)&\ge0,2\\
	\frac{\begin{pmatrix}19\\19\end{pmatrix}\cdot
		\begin{pmatrix}31\\n-19\end{pmatrix}}
		{\begin{pmatrix}50\\n\end{pmatrix}}&\ge0,2\\
	\frac{\begin{pmatrix}31\\n-19\end{pmatrix}}
		{\begin{pmatrix}50\\n\end{pmatrix}}&\ge0,2\\
	\frac{\begin{pmatrix}31\\47-19\end{pmatrix}}
		{\begin{pmatrix}50\\47\end{pmatrix}}&\approx
			0,229\quad(\ge0,2)
\end{align}
$$
Für $n=47$ ist die Wahrscheinlichkeit größer als $0,2$. Es müssen demnach mindestens $47$ Personen gezogen werden, damit die Wahrscheinlichkeit, das gesamte anwesende Blechregister zu ziehen, mindestens $20\%$ beträgt.