Die Sigma/$\sigma$-Umgebung ist ein Bereich, in welchem für ein Experiment [[Ereignis(se)]] gehäuft auftreten. Aufgestellt wird dieser mittels des [[Erwartungswert]] und [[Standartabweichung]]. Die Standartabweichung gibt die Breite der Umgebung vor, in welcher um dem Erwartungswert $\mu$ eine angehäufte Wahrscheinlichkeitsmenge zu erwarten ist.
Eine $n$-te Sigma-Umgebung wird durch eine Intervallsbeschreibung dargestellt.
Für dieses Intervall gilt stets das folgende:
$$
\sigma_n=\left[\lceil\mu-n\cdot\sigma\rceil;\lfloor\mu+n\cdot\sigma\rfloor\right]
$$
>(Zu bedenken ist, dass $\sigma_n$ kein fest definierter Ausdruck zu sein scheint. Vielmehr wird das Intervall zu dem Ausdruck "$n$-te $\sigma$-Umgebung" zugeordnet. Zum vereinfachtem weiterführendem Verständnis wird die Verwendung $\sigma_n$ fortgeführt und ist dem beschriebenem Ausdruck gleichzusetzen.)

Die Verwendung von [Rundungsklammern](Runden) ermöglicht es die Grenzen in *Richtung des Erwartungswertes* zu runden.

Beispielsweise sei eine [binomialverteilte](Binomialverteilung) [[Wahrscheinlichkeitsverteilung]] mit $n=100$ und $p=0,35$ gegeben. Es soll die Wahrscheinlichkeit bestimmt werden, mit der ein Ereignis in der ersten $\sigma$-Umgebung trifft.
Es gilt somit:
$$
\begin{align}
	\mu&=np\\
	&=100\cdot0,35\\
	&=35\\\\
	
	\sigma&=\sqrt{np(1-p)}\\
	&=\sqrt{100\cdot0,35\cancelto{0,65}{\cdot(1-0,35)}}\\
	&=\frac{\sqrt{91}}{2}\approx4,77\\\\
	
	\sigma_n&=\left[\lceil\mu-n\cdot\sigma\rceil;\lfloor\mu+n\cdot\sigma\rfloor\right]\\
	
	\sigma_1&=\left[\bigg\lceil35-1\cdot\frac{\sqrt{91}}{2}\bigg\rceil;\bigg\lfloor35+1\cdot\frac{\sqrt{91}}{2}\bigg\rfloor\right]&&\boxed{
		\begin{align}
			35-1\cdot\frac{\sqrt{91}}{2}&\approx30,23\\
			35+1\cdot\frac{\sqrt{91}}{2}&\approx39,77
		\end{align}}\\
	&=\left[\big\lceil30,23\big\rceil;
	\big\lfloor39,77\big\rfloor\right]\\
	&=\left[31;39\right]
\end{align}
$$
Die erste $\sigma$-Umgebung befindet sich folglich auf $\left[34;36\right]$. Um nun die Wahrscheinlichkeit in diesem zu bestimmen benutzt man die Grenzen als Ungleichung für Wahrscheinlichkeiten mit einer Zufallsvariable.
Für $\sigma$-Umgebungen auf Intervallen $\left[a;b\right]$ gilt für dessen Wahrscheinlichkeit das folgende: (Beispiel wird daran angewandt)
$$
\begin{align}
	P(a\le X\le b)&=P(X\le b)-P(X\le a-1)\\
	P(31\le X\le 39)&=P(X\le 39)-P(X\le 31-1)\\
	&=P(X\le 39)-P(X\le 30)\\
	&=F_{100;0,35}(39)-F_{100;0,35}(30)\\
	&\approx0,655
\end{align}
$$

---