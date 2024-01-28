Um Wendestellen an einer [[Funktion(en)]] zu untersuchen benötigen wir die [[Ableitungsregeln]] um Steigungen einer Funktion darzustellen.

---
## Vorbereitung
Gegeben sei eine Funktion $f$. Diese wird zunächst nach den [[Ableitungsregeln]] zweifach abgeleitet.

---
## Notwendiges Kriterium
Nachdem dieser folgende Satz angepasst formuliert wurde:
> Notwendiges Kriterium für Wendestellen: $f''(x)=0$

Nun kann so wie beschrieben die [Ableitungsfunktion](Ableitung) nach [[Nullstellen]] untersucht werden. Wichtig hierbei ist es, dass folgender erster Aufbau (hier für $f$) nicht fehlen sollte:
$$ \begin{aligned}
\text{Notwendiges Kriterium}&\text{ für Wendestellen:}\quad f''(x)=0 \\
0&=f''(x)\\
\Leftrightarrow0&=[...]\\
\Rightarrow x_1&=q_1\quad\vee\quad x_2=q_2\quad\vee\quad\ldots\quad\vee\quad x_n=q_n
\end{aligned}$$
Sollte ein [[Definitionsbereich]] oder ein Intervall für die Funktion gegeben sein, so ist es wichtig zu überprüfen, dass die Nullstellen in diesem sind um nicht unnötig Zeit beim weiteren rechnen zu verschwenden.

---
## Hinreichendes Kriterium
Nachdem das notwendige Kriterium Stellen angegeben hat wird nun an diesen weiter gearbeitet.
Um zu bestimmen, ob es sich an einer Stelle um einen Links-Rechts oder Rechts-Links Wendepunkt handelt.
Hierfür gibt es zwei verschiedene Möglichkeiten. Welche man von diesen anwendet hängt von der Funktion ab.
### Erstes
> Erstes hinreichendes Kriterium für Wendestellen: $f'''(x)\neq0$

Dieser Lösungsweg bietet sich an, insofern die Funktion einfach mehrfach ableitbar ist (e-Funktionen sind es nicht, außer sie sind durch die Aufgabe gegeben) [[Ableitungsregeln]] und mit exakten Werten weiter gearbeitet wird.
Das Ergebnis beim Einsetzen der Stelle $x_n$ in die zweite Ableitung $f'''(x)$ gibt die Art des Extrema aus. Hierbei gilt:
- $f'''(x_n)<0\Rightarrow \text{links-rechts}$
- $f'''(x_n)>0\Rightarrow \text{rechts-links}$
- $f'''(x_n)=0\Rightarrow \text{Ungültig}$
### Zweites
>  Zweites hinreichendes Kriterium für Wendestellen:

Dieser Lösungsweg kann immer verwendet werden, bedarf allerdings mehr Berechnungen von Stellen.
Es werden vor jeder Nullstelle die Vorzeichenwechsel beobachtet, wodurch sich dann die Form des Wendepunktes darstellt.
Für jede Nullstelle muss folgende Satzkombination beschrieben werden:
> Vorzeichen von $f''(x)$ links von $x_n$

> Vorzeichen von $f''(x)$ rechts von $x_n$

Nach diesem Satz wird jeweils eine beliebige Stelle im [[Definitionsbereich]] vor oder nach der Nullstelle $x_n$ in $f''(x)$ eingesetzt. Insgesamt gilt hierbei folgendes:
- $\text{Vorzeichenwechsel auf }f''\text{ von + nach -} \Rightarrow\text{links-rechts}$
- $\text{Vorzeichenwechsel auf }f''\text{ von - nach +} \Rightarrow\text{rechts-links}$

---
## Lösung
Nachdem alle Nullstellen analysiert wurden wird der Befund zum Schluss erneut formuliert.
>An der Stelle $x_n=q_n$ liegt ein ___ -Wendepunkt von $f$,
>weil ___ an dieser Stelle ___ hat.

Zusätzlich werden Punkte der Wendepunkte angegeben, wobei man die Stelle dieser in $f(x)$ einsetzt.

---