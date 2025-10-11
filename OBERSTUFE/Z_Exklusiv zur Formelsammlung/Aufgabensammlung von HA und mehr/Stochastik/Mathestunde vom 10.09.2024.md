> Unter dem Thema "Testen" verstehen wir Aufgabenstellungen, die eine Hypothese bestätigt, oder ablehnt. Beispielsweise soll eine Münze überprüft werden, ob sie fair ist ($50$:$50$).

Folgende Begriffe sind wichtig:
> - Hypothese
> - [[Signifikanzniveau]] (auch Irrtumswahrscheinlichkeit)
> - Verwurfsbereich
> - Annahmebereich

---
### Hypothesen
Beispielsweise soll überprüft werden, ob eine Münze fair ist. Es wurde $50$ mal geworfen, und $20$ mal wurde Zahl geworfen.
Die Hypothese, die wir verfolgen, lautet also:
$$H_0:p=0,5$$
Quasi gelesen als:
> Die (Null)hypothese besagt, dass die Münze fair ist, weil die [[Wahrscheinlichkeit]] für beide Seiten gleich sind ($50\%$).

Es gibt zusätzlich eine weitere Hypothese, die das Gegenteil der Nullhypothese ist. Diese wird **"[[Alternativhypothese]]"** $H_1$ oder $H_A$ genannt.
Die [[Alternativhypothese]] lautet für unser Beispiel also:
$$H_1:p\ne 0,5$$
Quasi gelesen als:
> Die Münze ist nicht fair

---
### Verwurfsbereich und [[Signifikanzniveau]]
(Weiterhin orientieren wir uns an das Beispiel der fairen Münze.)

> Das [[Signifikanzniveau]] gibt an, zu wie viel Prozent die [[Nullhypothese]] fälschlicherweise angenommen wird (Als "Hypothese stimmt" festgelegt).

Diese [[Wahrscheinlichkeit]] wird mit dem griechischen Buchstaben $\alpha$ ausgedrückt. Häufig werden werte wie $5\%$ oder $1\%$ verwendet.
> Wichtig zu sagen ist, dass meistens $\alpha= 0,05$ für $5\%$ ist, und Alpha **unter** dieser Grenze liegen soll.

---
$\alpha$ wird benutzt, um den sogenannten *Verwerfungsbereich* zu bestimmen. Dieser beschreibt, welche Werte (z.B. Anzahl an Zahl) nach durchführen eines Experimentes die Nullhypothese ablehnen. Hierzu ein Beispiel:
> Eine Münze wird $100$ mal geworfen, und der Annahmebereich ist für das Intervall $40\le X\le60$, durch $\alpha=5\%$ festgelegt. $X$ ist hier die Anzahl an Zahl nach den $100$ würfen.
> Das Intervall wurde so gewählt wie es ist, weil die Wahrscheinlichkeiten außerhalb diesen Bereiches klein sind, und in der Summe unter diesen $5\%$ liegen. Im folgenden Bild ist es dargestellt.

![[Annahmebvereich.png]]
Sobald man nun $100$ mal die Münze wirft, und eine Anzahl an Zahl kommt, die sich im roten Bereich aufhält, dann lässt sich hier sagen, dass die Münze nicht fair ist.
Der linke Verwerfungsbereich soll hier, weil es eben einen zweiten noch gibt, nicht $5\%$ sein, sondern $2,5\%$, damit diese $5\%$ insgesamt nicht überschritten werden.
>Wobei es sich hier handelt, ist ein beidseitiger Hypothesentest

---
---
---
---
---
---
---
### Berechnung des Verwerfungsbereiches
Erneut das Beispiel von vorhin, wo wir eine Münze $100$ mal werfen, und auf Fairness überprüfen. Es ergibt sich dadurch folgendes:
$$
\begin{align}
	X&:\text{Anzahl Zahl}\\
	H_0:p&=0,5\\
	H_1:p&\ne0,5
\end{align}
$$
Das Signifikanzniveau wird hier auf $\alpha=0,05$ gelegt.

Da wir einen beidseitigen Test durchführen, benötigen wir zwei Verwerfungsbereiche, mit je einer Wahrscheinlichkeit von maximal $2,5\%$. Da wir eine Fläche suchen, die unter dieser Verteilung entsteht, müssen wir die kumulierte Binomialverteilung verwenden.
Hierfür im Taschenrechner für die linke Seite:
>- Menü
>- $7$
>- $\downarrow$
>- $1$
>- $1$
>- *Hier in der Tabelle $k$ einige Werte eingeben; $=$ drücken*
>- *$n$ und $p$ einsetzen; $=$ drücken*
>- Tabellenwerte angucken, und sehen, welche Werte über oder unter den $2,5\%$ liegen.
>- Den größten Wert von $k$ nehmen, der unter $2,5\%$ ist und notieren.

Hier im Beispiel sollte dann $k=39$ mit einem Wert von ungefähr $0,0176$ der größte Wert sein. Somit geht der linke Verwerfungsbereich von $0$ bis $39$. 

---
Für die rechte Seite gehen wir ähnlich vor, müssen aber zuvor noch umformen.
Wir suchen formal geschrieben folgendes:
$$
\begin{align}
	P(X\ge k)\le 0,025
\end{align}
$$
Durch das $\ge$ können wir nicht den Taschenrechner benutzen, ehe wir es nicht umgeformt haben.
$$
\begin{align}
	P(X\ge k)&\le 0,025\\
	1-P(X\le k-1)&\le 0,025&&\mid -1\\
	-P(X\le k-1)&\le -0,975&&\mid \cdot(-1)\\
	P(X\le k-1)&\ge 0,975
\end{align}
$$
Nun haben wir ein $\le$ in der Klammer stehen, und wir können den Taschenrechner benutzen.
Hierfür im Taschenrechner für die rechte Seite:
>- Menü
>- $7$
>- $\downarrow$
>- $1$
>- $1$
>- *Hier in der Tabelle $k$ einige Werte eingeben; $=$ drücken*
>- *$n$ und $p$ einsetzen; $=$ drücken*
>- Tabellenwerte angucken, und sehen, welche Werte über oder unter den $0,975$ liegen.
>- Den kleinsten Wert von $k$ nehmen, der über $0,975$ ist und notieren.
>- Weil das $k$ aus der Tabelle quasi $k-1$ ist, müssen wir unseren Fund mit $1$ addieren um unser endgültiges $k$ zu erhalten.

Hier im Beispiel sollte dann $k=60$ mit einem Wert von ungefähr $0,9824$ der kleinste Wert sein. Somit geht der rechte Verwerfungsbereich von $60+1$ bis $100$.

---