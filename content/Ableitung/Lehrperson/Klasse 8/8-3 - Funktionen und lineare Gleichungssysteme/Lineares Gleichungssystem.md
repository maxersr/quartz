# Motivation
In einem Hostel stehen $46$ Betten für eine Nacht zur Verfügung. Es ist nur bekannt, dass es insgesamt $30$ Zweibettzimmer und Einbettzimmer. Wie viele Zimmer hat das Hostel?

*Ansatz*
Man erstellt ein lineares Gleichungssystem:
$x \ldots$ Anzahl von Zweibettzimmern
$y \ldots$ Anzahl von Einbettzimmern
Aus dem zweiten Satz ist bekannt, dass
$$
x+y=30 \tag{$f(x)$}
$$
gilt. Die Information, dass es **Zwei**bett- und **Ein**bettzimmer sind, führt zur zweiten Gleichung:
$$
2\cdot x + 1 \cdot y = 46. \tag{$g(x)$}
$$
Es ist also eine gemeinsame Lösung beider Gleichungen zu bestimmen.
# Grafische Lösung
Gegeben ist das Gleichungssystem
$$
\begin{vmatrix}
x&+&y&= &30  \\ 
2x&+&y&=&46
\end{vmatrix}
$$

Bei beiden Gleichungen handelt es sich nach Umstellen nach $y$ um eine lineare Funktion. Haben beide Funktionen einen unterschiedlichen Anstieg, kann man einen Schnittpunkt beider Geraden ablesen:

![[LGS_Bsp.png|500]]

Der Schnittpunkt lautet $S(16|14)$. Eine Probe ergibt, dass das Ergebnis stimmt. Somit gibt es $16$ Zweibett- und $14$ Einbettzimmer.

# Lösungsverfahren
Das Ergebnis Gleichungssystem
$$
\begin{vmatrix}
x&+&y&= &30  \\ 
2x&+&y&=&46
\end{vmatrix}
$$
lässt sich mithilfe von *drei* Lösungsverfahren bestimmen.

## Additionsverfahren
Man sucht sich eine der beiden Variablen aus, die den kleinsten $\text{kgV}$ haben. In diesem Falle ist es $y$, da beide den Koeffizienten $1$ haben. Man **addiert** nun ein **Vielfaches** einer Zeile zu einer anderen, um diese Variable zu streichen, d.h. man addiert zur ersten Zeile „$-1$ mal“ die zweite Zeile:
$$
\begin{align*}
x + y -(2x+y) &= 30 - 46\\
-x &=-16 \\
\Rightarrow x&=16.
\end{align*}
$$
Setzt man $x=16$ nun in die erste Gleichung ein, erhält man das $y=14$.

## Einsetzungsverfahren
Der Term der ersten Zeile lässt sich nach einer der Variablen umformen, beispielsweise $x = 30-y$. Dieser Term wird nun in die zweite Gleichung eingesetzt:
$$
\begin{align*}
2(30-y) + y &= 46\\
60-2y+y&= 46\\
60-y&= 46\\
-y&= -14\\
\Rightarrow y&= 14.
\end{align*}
$$
Setzt man $y=14$ in die erste Gleichung ein, erhält man $x=16$.

## Gleichsetzungsverfahren
Man formt für das Gleichsetzungsverfahren alle Gleichungen nach einer Variablen um. Man erhält durch Umstellen nach $y$ folgendes Gleichungsssystem:
$$
\begin{vmatrix}
y & = & 30&-&x \\ 
y & = & 46&-&2x
\end{vmatrix}
$$
Diese beiden Gleichungen kann man nun gleichsetzen:
$$
\begin{align*}
30-x &= 46-2x\\
30+x &= 46\\
x &= 16
\end{align*}
$$
und man erhält $y=14$ durch Einsetzen in die erste Gleichung. 