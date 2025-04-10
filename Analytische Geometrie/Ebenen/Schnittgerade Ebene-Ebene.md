## Parameterform-Parameterform
> Zwei [[Ebene(n)]] in Parameterform sind gegeben, zu denen die Schnittgerade berechnet werden soll.

Generell werden beide Gleichungen gleichgesetzt und in einem [[LGS]] nach einer [Variable](Variable(n)) von einer Gleichung aufgelöst. Wir erhalten beispielsweise:
$$
\begin{align}
	E_1:\vec x=
		\begin{pmatrix}1\\2\\-2\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}0\\2\\1\end{pmatrix}+\mu\cdot
		\begin{pmatrix}1\\-2\\0\end{pmatrix};\quad&\quad
		E_2:\vec x=\begin{pmatrix}2\\0\\-2\end{pmatrix}+\omega\cdot
			\begin{pmatrix}1\\1\\-1\end{pmatrix}+\psi\cdot
			\begin{pmatrix}1\\2\\-3\end{pmatrix}\\\hline\\
	\begin{pmatrix}1\\2\\-2\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}0\\2\\1\end{pmatrix}+\mu\cdot
		\begin{pmatrix}1\\-2\\0\end{pmatrix}&=
		\begin{pmatrix}2\\0\\-2\end{pmatrix}+\omega\cdot
			\begin{pmatrix}1\\1\\-1\end{pmatrix}+\psi\cdot
			\begin{pmatrix}1\\2\\-3\end{pmatrix}
\end{align}
$$
$$
\begin{align}
	&\begin{array}{r|rc|}
		\text{I:} & 1+\mu & =&2+\omega+\psi\\
		\text{II:} & 2+2\lambda-2\mu & =&\omega+2\psi\\
		\text{III:} &-2+\lambda&=&-2-\omega-3\psi
	\end{array}\\\\
	&\begin{array}{r|ccc|l}
		\text{I:} & \mu-\omega-\psi& =&1&\mid\cdot2\\
		\text{II:} & 2\lambda-2\mu-\omega-2\psi& =&-2&\quad\mid\text{I}+\text{II}\\
		\text{III:} &\lambda+\omega+3\psi&=&0
	\end{array}\\\\
	&\begin{array}{r|ccc|l}
		\text{I:} & \mu-\omega-\psi& =&1&\\
		\text{II:} & 2\lambda-3\omega-4\psi& =&0&\quad\mid\text{III}+\text{II}\\
		\text{III:} &\lambda+\omega+3\psi&=&0&\mid\cdot(-2)
	\end{array}\\\\
	&\begin{array}{r|ccc|l}
		\text{I:} & \mu-\omega-\psi& =&1&\\
		\text{II:} & -5\omega-10\psi& =&0&\\
		\text{III:} &\lambda+\omega+3\psi&=&0&
	\end{array}\\\\
	&\text{II:}\quad -5\omega-10\psi=0
	\quad\Rightarrow \quad\omega=-2\psi
\end{align}
$$
Dieser Zusammenhang wird in die Geradengleichung eingesetzt:
$$
\begin{align}
	E_2:\vec x&=\begin{pmatrix}2\\0\\-2\end{pmatrix}+\omega\cdot\begin{pmatrix}1\\1\\-1\end{pmatrix}+\psi\cdot
	\begin{pmatrix}1\\2\\-3\end{pmatrix}&&\mid\boxed{\omega=-2\psi}\\
	&=\begin{pmatrix}2\\0\\-2\end{pmatrix}-2
		\psi\cdot\begin{pmatrix}1\\1\\-1\end{pmatrix}+\psi\cdot
	\begin{pmatrix}1\\2\\-3\end{pmatrix}=
		\begin{pmatrix}2\\0\\-2\end{pmatrix}+
		\psi\cdot\begin{pmatrix}-2\\-2\\2\end{pmatrix}+\psi\cdot
	\begin{pmatrix}1\\2\\-3\end{pmatrix}\\
	\Rightarrow\quad g:\vec x&=\begin{pmatrix}2\\0\\-2\end{pmatrix}+\psi\cdot
		\begin{pmatrix}-1\\0\\-1\end{pmatrix}
\end{align}
$$

---
## Parameterform-Koordinatenform
> Eine Ebene in Parameterform und eine Ebene in Koordinatenform sind gegeben, zu denen die Schnittgerade berechnet werden soll.

Generell wird bei dieser Kombination die Ebenengleichung in Parameterform jeweils in die Koordinatenform eingesetzt und vereinfacht. Wir erhalten beispielsweise:
$$
\begin{align}
	E_1:\vec x
	=\begin{pmatrix}\textcolor{green}1\\
	\textcolor{orange}2\\\textcolor{Blue}{-2}\end{pmatrix}
	+\lambda\cdot
	\begin{pmatrix}\textcolor{green}0\\\textcolor{orange}2\\\textcolor{Blue}1\end{pmatrix}+\mu\cdot
	\begin{pmatrix}\textcolor{green}1\\\textcolor{orange}{-2}\\\textcolor{Blue}0\end{pmatrix};\quad&\quad E_2:x_1-2x_2-x_3=4\\\hline\\
	\begin{pmatrix}x_1\\x_2\\x_3\end{pmatrix}&=
		\begin{pmatrix}\textcolor{green}{1+\mu}\\\textcolor{orange}{2+2\lambda-2\mu}\\\textcolor{Blue}{-2+\lambda}\end{pmatrix}\\\\
	E_2:\textcolor{green}{x_1}-2\textcolor{orange}{x_2}-\textcolor{Blue}{x_3}&=4\\
	\textcolor{green}{(1+\mu)}-2\cdot\textcolor{orange}{(2+2\lambda-2\mu)}-\textcolor{Blue}{(-2+\lambda)}&=4\\
	
	1+\mu-4-4\lambda+4\mu+2-\lambda&=4\\
	-1-5\lambda+5\mu&=4&&\mid+1+5\lambda\\
	5\mu&=5+5\lambda&&\mid\div5\\
	\mu&=1+\lambda
\end{align}
$$
Diesen Zusammenhang setzen wir in die Parameterform ein, und erhalten durch vereinfachen die Schnittgerade:
$$
\begin{align}
	E_1:\vec x&=\begin{pmatrix}1\\2\\-2\end{pmatrix}+\lambda\cdot
	\begin{pmatrix}0\\2\\1\end{pmatrix}+\mu\cdot
	\begin{pmatrix}1\\-2\\0\end{pmatrix}&&\mid\boxed{\mu=1+\lambda}\\
	&=\begin{pmatrix}1\\2\\-2\end{pmatrix}+\lambda\cdot
	\begin{pmatrix}0\\2\\1\end{pmatrix}+(1+\lambda)\cdot
	\begin{pmatrix}1\\-2\\0\end{pmatrix}\\
	&=\textcolor{orange}{\begin{pmatrix}1\\2\\-2\end{pmatrix}}+\lambda\cdot
	\textcolor{green}{\begin{pmatrix}0\\2\\1\end{pmatrix}}+
	\textcolor{orange}{\begin{pmatrix}1\\-2\\0\end{pmatrix}}+\lambda\cdot
	\textcolor{green}{\begin{pmatrix}1\\-2\\0\end{pmatrix}}=
		\textcolor{orange}{\begin{pmatrix}2\\0\\-2\end{pmatrix}}+\lambda\cdot
		\textcolor{green}{\begin{pmatrix}1\\0\\1\end{pmatrix}}\\
	\Rightarrow\quad g:\vec x&=\begin{pmatrix}2\\0\\-2\end{pmatrix}+\lambda\cdot
		\begin{pmatrix}1\\0\\1\end{pmatrix}
\end{align}
$$

---
## Koordinatenform-Koordinatenform
 >Zwei Ebenen in Koordinatenform sind gegeben, zu denen die Schnittgerade berechnet werden soll.
 
Generell werden die Koordinatenformen in einem [[LGS]] gleichgesetzt und jeweils $x_1$, $x_2$ und $x_3$ unter einer gemeinsamen Bedingung aufgelöst. Wir erhalten beispielsweise:
$$
\begin{align}
	E_1:2x_1+x_2-2x_3=8\quad&\quad
		E_2:x_1-2x_2-x_3=4\\\hline
\end{align}
$$
$$
\begin{align}
	&\begin{array}{r|ccc|l}
		\text{I:} & 2x_1+x_2-2x_3&=&8&\mid\cdot2\quad\mid\text{I}+\text{II}\\
		\text{II:} & x_1-2x_2-x_3&=&4&
	\end{array}\\\\
	&\begin{array}{r|ccc|l}
		\text{I:} & 5x_1-5x_3&=&20&\\
		\text{II:} & x_1-2x_2-x_3&=&4&
	\end{array}\\\\
	&\text{I:}\quad 5x_1-5x_3=20
		\quad\Rightarrow \quad x_1(x_3)=4+x_3
\end{align}
$$
$$
\begin{align}
	\text{II:}\qquad
		x_1-2x_2-x_3&=4&&\mid\boxed{x_1(x_3)=4+x_3}\\
	4+x_3-2x_2-x_3&=4\\
	4-2x_2&=4\\
	x_2&=0
\end{align}
$$
Hierdurch erhalten wir die Lösungen, die einen Lösungsvektor bilden, der die Gerade definiert:
$$
\begin{align}
	x_1(x_3)&=4+x_3\\
	x_2(x_3)&=0\\
	x_3(x_3)&=x_3\\\\
	\Rightarrow\quad
		\begin{pmatrix}x_1(x_3)\\x_2(x_3)\\x_3(x_3)\end{pmatrix}
	&=\begin{pmatrix}4+x_3\\0\\x_3\end{pmatrix}=
		\begin{pmatrix}4\\0\\0\end{pmatrix}+\begin{pmatrix}
		x_3\\0\\x_3\end{pmatrix}=
		\begin{pmatrix}4\\0\\0\end{pmatrix}+x_3\cdot\begin{pmatrix}
		1\\0\\1\end{pmatrix}\\
	\Rightarrow\quad g:\vec x&=
		\begin{pmatrix}4\\0\\0\end{pmatrix}+\lambda\cdot\begin{pmatrix}
		1\\0\\1\end{pmatrix}
\end{align}
$$
Zu bedenken ist, dass beim Einsetzen der ersten Variable, diese abhängige Variable weitergehend für alle weiteren Lösungen die abhängige Variable sein muss (Hier $x_3$). $x_1$ und $x_2$ sind von $x_3$ abhängig.

---
([[Parameterform einer Ebene]], [[Koordinatenform einer Ebene]])