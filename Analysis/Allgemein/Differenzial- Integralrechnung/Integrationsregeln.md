Für [[Integration]] verwendet

**Bedenke: Nach jeder Funktion darf eine Konstante theoretisch nicht fehlen**

Für jede Funktion gelten folgende grundlegende Konzepte:
$$\boxed{
	\begin{align}{}
		f(x)&=g(x)+h(x) & f(x)&=k\cdot g(x)\\
		F(x)&=G(x)+H(x) & F(x)&=k\cdot G(x)
	\end{align}
}$$

---
### Potenzregel
Eine Potenzfunktion $f~x\rightarrowtail y$ sei integrierbar. So gilt:
$$\begin{align}
f(x)&=ax^{n}\\
F(x)&=\frac{1}{n+1}\cdot ax^{n+1}&n\in\mathbb{R}\backslash\{-1\}\\
\\
g(x)&=ax^{-1}\\ 
G(x)&=a\cdot \ln(x)
\end{align}$$

---
### "Kreislaufaufleitungen"
Eine trigonometrische Funktion $f~x\rightarrowtail y$ sei integrierbar. So gilt für die hier gegebenen folgender Kreislauf:
$$\begin{array}{}
	&&&&\sin(x)&&&&\\
	&&\swarrow&& && \nwarrow\\
	-\cos(x)&& && && &&\cos(x)\\
	&&\searrow&& && \nearrow\\
	&&&&-\sin(x)&&&&
\end{array}$$

---
### Kettenregel
Folgender Ausdruck sei gegeben und integrierbar, so gilt, nur sobald $g_{linear}(x)$ ist:
$$\begin{align}
	f(x)&=v\big(u(x)\big)\qquad\boxed{n\in\mathbb{R}}\\
	f(x)&=\big(g(x)\big)^{n}\\
	F(x)&=\frac{1}{n+1}\big(g(x)\big)^{n+1}\cdot\frac{1}{g'(x)}\\\\
	f(x)&=\frac{1}{g(x)}\\
	F(x)&=\ln\big(\big|g(x)\big|\big)\cdot\frac{1}{g'(x)}\\\\
	
	f(x)&=e^{x}\\
	F(x)&=e^{x}\\\\
	\\
	&\boxed{
		h(x)=\{\sin(x)~\vee~-\sin(x)~\vee~\cos(x)~\vee~-\cos(x)\}}\\
	f(x)&=h(g(x))\\
	F(x)&=H(g(x))\cdot\frac{1}{g'(x)}
\end{align}$$

---