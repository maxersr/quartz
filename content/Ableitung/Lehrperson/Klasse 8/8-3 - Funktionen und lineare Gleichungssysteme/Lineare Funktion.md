# Definition
Eine **lineare Funktion** ist eine [[Funktion]] höchstens *ersten Grades*. Es ist eine Funktion $f$ der Form
$$
f(x)= y = mx+n,
$$
wobei $m$ der **Anstieg** der Funktion, $x$ die Variable und $n$ die Verschiebung entlang der $y-$Achse ist.
## Beispiele
$f(x) = x, f(x)=2x+1, f(x)=\frac{1}{2}x- \frac{3}{2}$

# Graph
Der **Graph** einer linearen Funktion ist eine [[Gerade]]:
![[2x.png|200]]


# Anstieg 
Der **Anstieg** einer linearen Funktion $f$ gibt an, dass die Gerade 
$$
\begin{cases}
\text{ steigt, wenn} &m>0 \\
\text{ konstant ist, wenn} &m=0 \\
\text{ sinkt, wenn} &m<0. \\
\end{cases}
$$
Der Anstieg stellt den **Winkel** zwischen dem Graphen und der $x-$Achse dar. Diesen kann man mit dem Differenzenquotienten berechnen:

## Differenzenquotient
### Beispiel
Man kann den Anstieg einer linearen Funktion mithilfe eines **Anstiegsdreiecks** vom Graphen ablesen.

![[anstiegsdreieck.png|500]]

An diesem Dreieck kann man erkennen: es handelt sich um ein [[Rechtwinkliges Dreieck|rechtwinkliges Dreieck]] mit Seitenlängen $b=0,4$ und $c=0,8$ und dem Winkel $\alpha \approx 63,435$. Die Seitenlängen $x$ und $y$ haben sich wie folgt berechnet:
- Zunächst werden die Punkte bestimmt. Diese sind $A(0,8|0,8), B(0,8|1,6)$ und $C(0,4|0,8)$. 
- Für $b$ werden die $x-$Koordinaten von $A$ und $C$ genommen und voneinander subtrahiert, d.h
$$
b=0,8 - 0,4 = 0,4.
$$
- Für $c$ werden die $y-$Koordinaten von $A$ und $B$ genommen und voneinander subtrahiert, d.h.
$$
c=1,6 - 0,8 = 0,8.
$$

Der Anstieg berechnet sich nun durch den **Differenzenquotienten**, also den Quotienten der beiden Differenzen $b$ und $c$:
$$
m = \frac{c}{b}= \frac{\Delta y}{\Delta x}=\frac{0,8}{0,4} = 2.
$$
>[!tip] Anmerkung
>Der Buchstabe Delta ($\Delta$) ist eine abkürzende Schreibweise für die Differenz. $\Delta y$ heißt also, dass eine Differenz von zwei $y-$Werten genommen wird!
>>[!info] Hinweis
>>Der [[Differenzenquotient]] spielt in der Sekundarstufe II eine große Rolle!
### Definition
![[Differenzenquotient#Definition]]

# Nullstelle
Die **[[Funktion#Nullstelle|Nullstelle]]** einer linearen Funktion ist derjenige $x-$Wert, für den gilt
$$
f(x) = 0.
$$
## Ablesen
Anhand des Funktionsgraphen kann man die Nullstelle einer linearen Funktion auch ablesen. Die Funktion $f(x)=2x$ hat die Nullstelle $x_{0}= 0$:

![[anstiegsdreieck.png|300]]

## Berechnung
Hat man also eine lineare Funktion in der Form $f(x)=mx+n$, kann man die Funktionsgleichung nach $x$ umstellen:
$$
\begin{align*}
0 &= f(x)\\
0&= mx+n\\
-n &= mx\\
\frac{-n}{m}&= x.
\end{align*}
$$

