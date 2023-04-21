# Motivation
Der Begriff „Differenzenquotient“ setzt sich aus zwei Substantiven zusammen: Differenz und Quotient. Es handelt sich also um einen Quotienten aus zwei Differenzen. 

## Beispiel
Gegeben sei die Funktion 
$$
f(x) = \sin\left(x + \frac{3}{2}\pi\right) + 1
$$

>[!help] Aufgabe
>Angenommen diese Kurve beschreibt das Volumen eines Wassertanks. Auf der $x-$Achse ist die Zeit in Minuten abgebildet, auf der $y-$Achse das Volumen in Litern. 
>Gesucht ist die Wassermenge, die von Beginn der Messung bis zum maximalen Volumen *durchschnittlich in der Minute*  in den Tank geflossen ist.

## Vorgehensweise
Zunächst muss bestimmt werden, welche Menge Wasser zum Zeitpunkt des Maximums vorlag und nach wie vielen Minuten dieser Zeitpunkt erreicht war. Mithilfe der [[Parameter der Sinusfunktion]] lässt sich erkennen, dass sich das Maximum im Punkt $M(\pi, 2)$ befindet. Nach $\pi$ Minuten - das sind in etwa 3 Minuten und 9 Sekunden - befanden sich 2 Liter im Tank. Um die durchschnittliche *Änderungsrate* $r$ zu bestimmen, setzt man die Werte ins Verhältnis zueinander:

$$
r = \frac{2 \text{ Liter}}{\pi \text{ Minuten}}\approx 0,63662 \frac{\text{Liter}}{\text{Minute}}.
$$
Geometrisch ist Folgendes passiert: es wurde eine [[Sekante]] durch den Koordinatenursprung $O(0,0)$ und dem Maximum $M(\pi,2)$ konstruiert. Hierbei handelt es sich um eine [[Lineare Funktion]] mit Funktionsgleichung $g(x) = \dfrac{2}{\pi}\cdot x$.

![[sin(x+3,5pi)+1 mit Sekante.png|300]]

Die Sekante besitzt den [[Lineare Funktion#Anstieg|Anstieg]] $\dfrac{2}{\pi}$, d.h. **genau unsere berechnete Änderungsrate $r$**. 

# Definition
Gegeben ist eine Funktion $f$. Der **==Differenzenquotient==** von $f$ im [[Intervall]] $[x_0,x_1]$ lautet
$$
\frac{f(x_{1})-f(x_{0})}{x_{1}-x_{0}}.
$$
Man setzt oft $\Delta y = f(x_{1}) - f(x_0)$ und $\Delta x = x_{1}-x_{0}$, wodurch sich die Formel zu
$$
\frac{\Delta y}{\Delta x}
$$
vereinfacht. Es handelt sich um den **Anstieg der Sekante** zwischen den Punkten $(x_{0}, f(x_{0}))$ und $(x_{1}, f(x_{1}))$.
# Bemerkung
>[!tip] Hinweis
>Die Schreibweise $\dfrac{\Delta y}{\Delta x} = m$ entspricht dem [[Lineare Funktion#Anstieg|Anstieg einer linearen Funktion]]!

>[!warning] Achtung!
>Im obrigen Beispiel galt $x_{0}= f(x_{0}) = 0$. Dennoch handelt es sich um einen Differenzenquotienten!
