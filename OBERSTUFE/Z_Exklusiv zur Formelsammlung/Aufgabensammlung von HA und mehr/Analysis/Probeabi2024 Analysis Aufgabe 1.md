> Auf Grundlage der Daten vergangener Jahre wird die Einwohnerzahl Deutschlands mithilfe verschiedener Funktionen modelliert. Die Funktionswerte dieser Funktionen beschreiben die Einwohnerzahl in Millionen in Abhängigkeit von der Zeit $t$ in Jahren, die seit dem Beginn des Jahres $1950$ vergangen ist. Alle Abgaben beziehen sich auf den Beginn des jeweiligen Jahres

## a)
> Die Funktion $f$ mit
> $f(t)=0,000~098t^3-0,0154t^2+0,785t+69,3$
> beschreibt für $0\le t\le74$ de Einwohnerzahl von $1950$ bis $2024$. Der Graph von $f$ ist in der Abbildung auf dem Beiblatt dargestellt.

### a1)
> Geben Sie anhand der Abbildung näherungsweise die Einwohnerzahl für das Jahr $1970$ und das Jahr $1980$ sowie die Zunahme der Einwohnerzahl innerhalb dieser $10$ Jahre an.

Sei aus der Abbildung:
- $f(20)=79,6$
- $f(30)=81,6$
Die Einwohnerzahl im Jahr $1970$ ist nach der Abbildung $79,6$ Millionen, und in $1980$ nach der Abbildung $81,6$ Millionen Menschen. Demnach gab es in diesen zwei Jahren einen Zuwachs an der Einwohnerzahl von $2$ Millionen Einwohnern.

### a2)
> Ermitteln Sie rechnerisch die Länge des Zeitraumes, in dem die Einwohnerzahl fällt.

$f(t)=0,000~098t^3-0,0154t^2+0,785t+69,3$
daraus folgt:
$f'(t)=0,000~294t^2-0,0308t+0,785$

$$
\begin{align}
	0&=f'(t)\\
	0&=0,000~294t^2-0,0308t+0,785&&\mid\div0,000~294\\
	0&=t^2-\frac{2200}{21}t+\frac{392500}{147}\\
	t_{1;2}&=-\frac{-\frac{2200}{21}}{2}\pm
		\sqrt{\left(\frac{-\frac{2200}{21}}{2}\right)^2-\frac{392500}{147}}\\
	&=\frac{1100}{21}\pm
		\sqrt{\left(-\frac{1100}{21}\right)^2-\frac{392500}{147}}\\
	&=\frac{1100}{21}\pm
		\sqrt{\frac{1210~000}{441}-\frac{392500}{147}}\\
	&=\frac{1100}{21}\pm
		\sqrt{\frac{32500}{441}}\\
	&=\frac{1100}{21}\pm\frac{50\sqrt{13}}{21}
\end{align}
$$
Per Symmetrie von $f'(t)$ ist der Abstand beider Nullstellen zum Scheitelpunkt identisch. Dieser befindet sich an der Stelle $t=\frac{1100}{21}$, wobei die Länge des Zeitraumes $2\cdot\frac{50\sqrt{13}}{21}$ sein muss. In der Abbildung zeigt sich für $t=\frac{1100}{21}$ eine negative Steigung, was im Sachzusammenhang bedeutet, dass die Einwohnerzahl fällt.

