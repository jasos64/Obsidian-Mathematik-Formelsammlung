> Aus einem Kreis mit dem Radius $r$ wird ein symmetrischer Stern ausgeschnitten und die vier Ecken $A$, $B$, $C$, $D$ zur Spitze einer quadratischen Pyramide hochgebogen. Wie groß kann das Volumen der entstehenden Pyramide höchstens werden? Wie groß ist in diesem Fall die Pyramidenoberfläche?

![[Pyramide11.png]]

---
## Hauptbedingung
> Das Volumen soll maximal sein.

Das Volumen bildet sich aus der sich ergebenen Höhe, die die gefaltenen Seiten ergeben. Im folgenden ist dieses Falten seitlich dargestellt:
![[Seite.png]]
Hier ist das grüne weiterhin die Kante mit Länge $d$. Die gesamtstrecke von zwei gegenüberstehenden Punkten beträgt $2r$. Somit erhalten wir für die Länge der einzelnen Faltseiten (folgend mit $l$):
$$
\begin{align}
	2r&=2l+d&&\mid-d\\
	2l&=2r-d&&\mid\div2\\
	l&=r-\frac{d}{2}
\end{align}
$$
$l$ ist hier die Hypotenuse des Dreiecks zwischen der Faltecke, der Spitze und dem Mittelpunkt des Kreises. Die höhe dieses halben Dreiecks ist dann:
$$
\begin{align}
	\left(r-\frac{d}{2}\right)^2&=\left(\frac{d}{2}\right)^2+h^2\\
	h&=\sqrt{\left(r-\frac{d}{2}\right)^2-\left(\frac{d}{2}\right)^2}\\
	&=\sqrt{r^2-dr+\frac{d^2}{4}-\frac{d^2}{4}}\\
	&=\sqrt{r^2-dr}\\
\end{align}
$$
Die Höhe der gefalteten Pyramide ist somit $h=\sqrt{r^2-dr}$.

Daraus bildet sich folgende Hauptbedingung:
$$
\begin{align}
	V(d;r)&=\frac{1}{3}\cdot d^2\cdot\sqrt{r^2-dr}
\end{align}
$$

Da der Radius von dem Kreis zu $d$ unabhängig ist, ändere ich die Betrachtungsweise $d$ prozentual zu $r$.
$$
\begin{align}
	V(p)&=\frac{1}{3}\cdot p^2\cdot\sqrt{1^2-p\cdot 1}\\
	&=\frac{1}{3}\cdot p^2\cdot\sqrt{1-p}
\end{align}
$$

---