> In Extremwertaufgaben werden Sachverhalte dargestellt, in denen dieser maximiert oder minimiert werden soll. Es werden [Funktionen](Funktion(en)) hierfür beschrieben und benutzt.
> Dies wird meistens mit einer Einschränkung gegeben. In vielen Fällen sollen Volumina oder Flächen maximiert werden.

Es gibt einen Ablaufplan, der für Extremwertaufgaben verwendet werden kann.
Als fortgehendes Beispiel die folgende Aufgabe:
> Eine quadratische Säule mit den Maßen $a\times a\times h$ (in $cm$) soll mit einem $100~cm$ langen Draht an den Kanten beschrieben werden. Das Volumen dieser Säule soll maximal sein. Bestimmen Sie die Dimensionen und das Maximalvolumen der Säule.

---
## Bildung der Hauptbedingung
> Die [[Hauptbedingung]] ist der zu minimierende oder maximierende Sachverhalt unter Abhängigkeit aller [Variablen](Variable(n)), die diesen verändern.

Das Volumen soll maximiert werden, daher lautet unsere Hauptbedingung:
$$
V(a;h)=a^2h
$$
Das Volumen wird durch die Grundfläche, mit Fläche $a^2$, und der Höhe $h$ gebildet.

> Anzumerken:
> **Sollte eine [[Hauptbedingung]] nur eine Anhängigkeit besitzen, dann ist diese Bedingungsfunktion direkt die [[Zielfunktion]] und kann direkt analysiert werden.**

---
## Bildung der Nebenbedingung
> Die [[Nebenbedingung]] ist eine Einschränkung der Hauptfunktion. Es kann mehrere Nebenbedingungen geben, falls eine Hauptfunktion mehrere Abhängigkeiten besitzt.

Da wir ein Draht mit der Länge $100~cm$ um die Säule führen müssen, haben wir hier die folgende Nebenbedingung:
$$
100=8a+4h
$$
Die Kantenlänge dieser Form wird durch $L(a;h)=8a+4h$ angegeben, wobei $L$ exakt $100~cm$ ist (Siehe Aufgabenstellung).

> Die Nebenbedingung wird dazu verwendet, eine Variable aus der Hauptbedingung durch einsetzen und Umformen zu entfernen.

$$
\begin{align}
	100&=8a+4h&&\mid-8a\\
	100-8a&=4h&&\mid\div4\\
	h&=\frac{100-8a}{4}\\
	h&=25-2a
\end{align}
$$

> Diese Abhängigkeit für $h$ wird in die Hauptbedingung eingesetzt, um die Zielfunktion zu erhalten.

---
## Bildung der Zielfunktion
> Die Zielfunktion wird für den Sachverhalt benutzt, um diesen zu beantworten. Meist wird hier eine Extremwertanalyse durchgeführt, um Minima oder Maxima zu bestimmen.

Von oben notieren wir die Hauptbedingung:
$$
V(a;h)=a^2h
$$
Setzen wir in diese $h$ unter Abhängigkeit der anderen Variable aus der Nebenbedingung, herhalten wir:
$$
\begin{align}
	V(a;h)&=a^2h\\
	V(a;h=25-2a)&=a^2(25-2a)\\
	V(a)&=25a^2-2a^3\\
	V(a)&=-2a^3+25a^2
\end{align}
$$
$V(a)$ ist unsere Zielfunktion.

---
## Extremwertanalyse
> Die Zielfunktion wird auf Extrema untersucht.

Für generelle Aufgaben siehe: [[Lokale Extrema]].

$$\begin{aligned}
\text{Notwendiges Kriterium}&\text{ für lokale Extrema:}\quad V'(a)=0 \\
	0&=V'(a)\\
	0&=-6a^2+50a\\
	0&=a(-6a+50)\\
	a_{1;2}=0&\quad \vee\quad 0=-6a+50\\\\
	0&=-6a+50&&\mid+6a\\
	6a&=50&&\mid\div6\\
	a_3&=\frac{25}{3}=8,\overline{3}
\end{aligned}$$

$$\begin{aligned}
\text{Erstes hinreichendes }&\text{Kriterium für lokale Extrema:}\quad V''(a)\ne0 \\
	V''(a)&=-12a+50\\
	V''(a_{1;2}=0)&=-12\cdot 0+50=38>0\\
	V''\left(a_3=\frac{25}{3}\right)&=-12\cdot\frac{25}{3} +50=-50<0
\end{aligned}$$

Da $a_3=\frac{25}{3}$ hier als einziger Hochpunkt durch $V''(a_3)<0$ gegeben ist, ist die Seitenlänge von der Grundseite ($a$) hier $a=a_3=\frac{25}{3}~cm$. Hieraus bildet sich durch $h=25-2a=25-2\cdot\frac{25}{3}=\frac{25}{3}~cm$ aus.
Die Seitenlängen sind demnach:
- $a=\frac{25}{3}$
- $h=\frac{25}{3}$
Das Volumen lässt sich aus der Zielfunktion bilden:
$$
\begin{align}
	V(a)&=-2a^3+25a^2\\
	V(a=\frac{25}{3})&=-2\left(\frac{25}{3}\right)^3+25\left(\frac{25}{3}\right)^2\\
	&=\frac{15625}{27}\approx578,704~cm^3
\end{align}
$$
Das Volumen ist daher ungefähr $578,704~cm^3$. Dieses Volumen ist für diese Bedingungen maximal.

---