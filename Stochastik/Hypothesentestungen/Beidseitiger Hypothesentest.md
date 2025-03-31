> Bei einem beidseitigem Hypothesentest wird eine Hypothese genannt, die sich auf eine spezifische Wahrscheinlichkeit bezieht.
> Es ist die Nullhypothese $H_0:p=p_0$, wobei $0<p_0<1$.

Bei allen Nullhypothesen wird in der Aufgabenstellung beschrieben, dass ein Sachverhalt mit einer exakten Wahrscheinlichkeit $p_0$ existiert ($p=p_0$ nicht $p>p_0$ oder ähnliches).

> Ein beidseitiger Hypothesentest schließt aus, dass diese Wahrscheinlichkeit größer oder kleiner sein muss. Die [[Alternativhypothese]] ist $H_1:p\ne p_0$.

## Vorgehen
### Rauslesen
Zuerst muss eine Null- und Alternativhypothese definiert werden. In einer Aufgabe ist meist erkennbar, wann es sich um einen beidseitigen Hypothesentest handelt.

> Nehmen wir für dieses Beispiel an, dass eine [binomialverteilte](Binomialverteilung) [[Zufallsvariable]] $X$ auf $H_0:p=0,7$, mit einer Stichprobengröße von $100$, überprüft werden soll. Das [[Signifikanzniveau]] soll bei $5\%$ liegen.

Wir haben die Binomialverteilung $X\sim\mathcal{B}_{100;0,7}$. Die [[Alternativhypothese]] leitet sich aus der [[Nullhypothese]] ab:
$$H_1:p\ne 0,7$$
Zusätzlich haben wir das [[Signifikanzniveau]] von $\alpha=5\%=0,05$ gegeben.

### Intervallbestimmung
> Anschließend wird der Verwerfungsbereich oder auch Verwerfungsintervall bestimmt, bei dem wir die angegebene Nullhypothese ablehnen.

Wir haben bei dem beidseitigem Test generell folgenden Aufbau für die beiden Intervalle $I_1=[0;k_1]$ und $I_2=[k_2;n]$, wobei $n$ der Stichprobenumfang ist:
$$
\begin{align}
	P(X\le k_1)&\le\frac\alpha2\\
	P(X\ge k_2)&\le\frac\alpha2
\end{align}
$$
$\frac\alpha2$ ist hier, damit der Gesamtwert des Signifikanzniveaus maximal $\alpha$ ist.
Durch Umstellen erhalten wir:
$$
\begin{align}
	P(X\le k_1)&\le\frac\alpha2\\\hline\\
	P(X\ge k_2)&\le\frac\alpha2\\
	1-P(X\le k_2-1)&\le\frac\alpha2&&\mid-1\\
	-P(X\le k_2-1)&\le\frac\alpha2-1&&\mid\cdot(-1)\\
	P(X\le k_2-1)&\ge1-\frac\alpha2\\\hline
\end{align}
$$
Hier kann eine Variable eingeführt werden, die einem Verwirrtheiten ersparen kann:
$$
\begin{align}
	P(X\le \textcolor{green}{k_2-1})&\ge1-\frac\alpha2;&&\boxed{k_2-1=g}\\
	P(X\le \textcolor{green}{g})&\ge1-\frac\alpha2
\end{align}
$$

---
Auf dem Beispiel angewendet erhalten wir für die Verwerfungsbereiche:
$$
\begin{align}
	P(X\le k_1)&\le\frac\alpha2\\
	P(X\le k_1)&\le\frac{0,05}{2}\\
	P(X\le k_1)&\le0,025\\
	P(X\le 60)&\approx0,0210\le0,025\\\hline
	\\
	P(X\le g)&\ge1-\frac\alpha2\\
	P(X\le g)&\ge1-\frac{0,05}{2}\\
	P(X\le g)&\ge0,975\\
	P(X\le 79)&\approx0,984\ge0,975
\end{align}
$$
Hierdurch erhalten wir $k_1=60$ und $g=79$. Folglich sind unsere Intervalle:
- $I_1=[0;60]$
- $I_2=[80;100]$
man bedenkt, dass $k_2-1=g$, also $k_2=g+1$ ($k_2=79+1=80$).

### Verwerfungs- und Annahmebereiche
> Wir haben die Intervalle des Verwerfungsbereiches. Diese bilden den Verwerfungsbereiches, und formen den Annahmebereich als Komplement des Verwerfungsbereiches.

$V=I_1\cup I_2=[0;60]\cup [80;100]$ ist der Verwerfungsbereich.
$\overline V=\Omega\backslash V=\Omega\backslash\{I_1\cup I_2\}=\Omega\backslash\{[0;60]\cup [80;100]\}=[61;79]$ ist der Annahmebereich. $\Omega$ beschreibt hier alle möglichen Werte der Zufallsvariable $X$. Also $\Omega=[0;100]$.

### Hypothesenannahme oder Verwerfung
> Mit diesen Bereichen kann eine Entscheidungsregel bestimmt werden, die die Tatkräftigkeit der Nullhypothese bestimmt. Wenn nun unter diesen $100$ Stichprobenelementen eine Zahl das bestimmte Merkmal besitzen, die im Annahmebereich ist, dann kann $H_0:p=0,7$ angenommen werden. Wenn diese Zahl nicht in diesem ist, dann muss die Nullhypothese verworfen werden, und die Alternativhypothese gilt.

---