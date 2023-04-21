# Motivation

Wir betrachten das Beispiel aus dem Differenzenquotienten erneut:
![[Differenzenquotient#Beispiel]]

## Herangehensweise
Zur Erinnerung: die Änderungsrate war $r = \dfrac{2}{\pi}$. Wie verändert sich $r$, wenn man nicht den Startpunkt $x_{0}= 0$, sondern $x_{0}= 1, x_{0}=2, x_{0}=3$ oder sogar $x_{0}=\pi$ nimmt? Berechnen wir diese Werte:

$$
\begin{align*}
\frac{f(\pi)-f(0)}{\pi-0}   &=\frac{2}{\pi}&\approx 0,63\\
\frac{f(\pi)-f(1)}{\pi-1} &= \frac{1+\cos(1)}{\pi-1}&\approx 0,72\\
\frac{f(\pi)-f(2)}{\pi-2} &= \frac{1+\cos(2)}{\pi-2}&\approx 0,51\\\\
\frac{f(\pi)-f(3)}{\pi-3} &= \frac{1+\cos(3)}{\pi-3}&\approx 0,07\\
\frac{f(\pi)-f(\pi)}{\pi-\pi} &= \text{n.d.!}
\end{align*}
$$
https://www.youtube.com/watch?v=8zM-CrtJmGg&feature=youtu.be !! - iframe’isieren!

<iframe src="https://www.geogebra.org/graphing/bqudw95f?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

Zunächst werden die Änderungsraten größer, aber je näher wir an die Stelle $x_0=\pi$ kommen, desto kleiner wird die Änderungsrate. Das macht tatsächlich Sinn, denn bis zum Zeitpunkt des Maximums kommt Wasser dazu, die Änderungsrate muss also positiv sein. Genau an der Stelle $x_0 = \pi$ muss die Änderungsrate aber gleich $0$ sein! Aber wie kann man das berechnen, wenn im Nenner $0$ steht?

## Näherung zur Tangente
Wie bereits oben geschehen, wurde die erste Stelle der Sekante immer näher an $x_{0}= \pi$ verschoben - die Sekante wird allmählich zur [[Tangente]] an der Stelle! Was man also erhält, ist eine **lokale Änderungsrate**, also eine Auskunft darüber, wie sich etwas „gleich“ ändern wird. 

# Definition
Gegeben ist eine Funktion $f$. Der ==**Differentialquotient**== von $f$ *an der Stelle* $x_0$ lautet
$$
f'(x_{0})=\lim_{x\to x_{0}} \frac{f(x)-f(x_{0})}{x-x_{0}}.
$$
Man nennt $f'(x_0)$ die **Ableitung** von $f$ an der Stelle $x_0$. Es handelt sich um den **[[Anstieg]] der Tangente** im Punkt $(x_{0}, f(x_{0}))$.

## Alternative Definition
Alternativ ist es möglich, auch $h = x-x_{0}$ zu setzen. Damit ändert sich der Differentialquotient zu
$$
f'(x_{0}) = \lim_{h\to 0}\frac{f(x)-f(x-h)}{h}.
$$
Hierbei ist $h$ geometrisch als „Intervalllänge der [[Sekante]]“ zu verstehen. 

# Beispiel
>[!faq] Aufgabe
>Gesucht ist die Ableitung der Funktion $f(x)=x^2$ an der Stelle $x_{0}=2$.

$$
\begin{align*}
f'(2) &= \lim_{x\to2}\frac{x^{2}-2^{2}}{x-2}\\
&=\lim_{x\to2} \frac{x^{2}-4}{x-2}\\
&=\lim_{x\to2}\frac{(x+2)\cancel{(x-2)}}{\cancel{x-2}}\\
&=\lim_{x\to2}x+2\\
&=4
\end{align*}
$$




