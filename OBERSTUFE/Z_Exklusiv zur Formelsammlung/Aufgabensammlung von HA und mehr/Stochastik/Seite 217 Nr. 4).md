> In einem Zeitungsbericht wird behauptet, dass sich nur $70\%$ der Autofahrer angurten. Ein Autoklub behauptet, dass der Anteil in Wirklichkeit höher ist. Die Polizei meint dagegen, dass der Anteil in Wirklichkeit kleiner ist. Es wird ein Test der [[Nullhypothese]] $H_0:p=0,7$ (Stichprobenumfang $100$; [[Signifikanzniveau]] $5\%$) durchgeführt.

## a)
> Welche Gegenhypothese $H_1$ und welchen Verwerfungsbereich geben der Autoklub bzw. die Polizei an?

$X:$ "Anzahl angegurteter Autofahrer"

Für den Autoklub:
- $H_0:p=0,7$
- $H_1:p>0,7$
Es folgt ein rechtsseitiger Hypothesentest.
$$
\begin{align}
	P(X\ge g_2)&\le\alpha\\
	P(X\ge g_2)&\le0,05\\
	1-P(X\le g_2-1)&\le0,05&&\mid -1\\
	-P(X\le g_2-1)&\le-0,95&&\mid \cdot(-1)\\
	P(X\le g_2-1)&\ge0,95&&\boxed{\textit{Sei:}\quad k=g_2-1}\\
	P(X\le k)&\ge0,95&&\mid \textit{Binomialkumuliert im TR}\\
	P(X\le 77)\approx0,952&\ge0,95\\
	\Rightarrow \qquad k&=77\\\\
	
	k&=g_2-1&&\mid+1\\
	g_2&=k+1\\
	g_2&=78\\
	
	\Rightarrow \qquad V_a&=\left[78;100\right]
\end{align}
$$

---
Für die Polizei:
- $H_0:p=0,7$
- $H_1:p<0,7$
Es folgt ein linksseitiger Hypothesentest.
$$
\begin{align}
	P(X\le g_1)&\le\alpha\\
	P(X\le g_1)&\le0,05&&\mid \textit{Binomialkumuliert im TR}\\
	P(X\le 61)\approx0.0340&\le0,05\\
	g_1&=61\\
	
	\Rightarrow \qquad V_p&=\left[0;61\right]
\end{align}
$$
---
---
## b)
> Die Stichprobe ergibt, dass $79$ Fahrer angegurtet sind. Wie fällt die Entscheidung des Autoklubs bzw. der Polizei aus?

Eine Stichprobe von $s=79$ ist gegeben. Vergleichen wir $s$ mit den Verwerfungsbereichen $V_a$ und $V_p$:

Für den Autoklub:
- $H_0:p=0,7$
- $H_1:p>0,7$
- $V_a=\left[78;100\right]$
Da $s=79$ Element des Verwerfungsbereiches $V_a$ ist, so verwerfen wir die Nullhypothese $H_0:p=0,7$, weshalb wir nun $H_1:p>0,7$ annehmen können.

Für die Polizei:
- $H_0:p=0,7$
- $H_1:p<0,7$
- $V_p=\left[0;61\right]$
Da $s=79$ kein Element des Verwerfungsbereiches $V_p$ ist, so können wir die Nullhypothese $H_0:p=0,7$ nicht verwerfen, weshalb wir diese weiterhin annehmen müssten.

>Da in beiden Bespielen gegeben ist, dass $p\ge0,7$ ist, könnten wir diese Aussage nun für diese Stichprobe annehmen.

---