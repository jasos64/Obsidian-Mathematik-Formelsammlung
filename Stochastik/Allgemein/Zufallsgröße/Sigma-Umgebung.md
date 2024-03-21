Die Sigma-Umgebung ist ein Bereich, in welchem für ein Experiment [[Ereignis(se)]] gehäuft auftreten. Aufgestellt wird dieser mittels des [[Erwartungswert]] und [[Standartabweichung]]. Die Standartabweichung gibt die Breite der Umgebung vor, da für diese die folgende Formel benutzt werden kann:
Eine $n$-te Sigma-Umgebung ($\sigma$-Umgebung) wird durch eine Intervallsbeschreibung dargestellt.
Für dieses Intervall gilt stets das folgende:
$$
\sigma_n=\left[\lceil\mu-n\cdot\sigma\rceil;\lfloor\mu+n\cdot\sigma\rfloor\right]
$$
Die Verwendung von [Rundungsklammern](Runden) ermöglicht es die Grenzen in Richtung des Erwartungswertes zu runden.

Beispielsweise sei eine [binomialverteilte](Binomialverteilung) Wahrscheinlichkeitsverteilung mit $n=100$ und $p=0,35$ gegeben.
Es gilt somit:
$$
\begin{align}
	\mu&=np\\
	&=100\cdot0,35\\
	&=35\\\\
	
	\sigma&=\sqrt{np(1-p)}\\
	&=\sqrt{100\cdot0,35\cdot(0,65)}
\end{align}
$$