# Motivation
Die Zellteilung unterliegt dem Prinzip, dass sich eine einzelne Zelle immer in zwei neue aufteilt. Beginnt man mit einer Zelle, teilt sich diese in zwei Zellen auf. Diese beiden Zellen teilen sich wiederum in zwei weitere Zellen, man erhält also insgesamt vier Zellen. Dieser Prozess wiederholt sich quasi beliebig lang. 
Mathematisch gesehen verdoppelt sich die Anzahl der Zellen bei jeder Zellteilung. Zu Beginn gab es eine Zelle. Diese wurde dann verdoppelt:
$$1 \cdot2 = 2.$$
Auch diese beiden Zellen wurden weiter verdoppelt:
$$
\begin{align*}
1\cdot2 \cdot2 &=  4,\\
1 \cdot2 \cdot2 \cdot2 &= 8,\\
1 \cdot2 \cdot2 \cdot2 \cdot2 &= 16,\\
\vdots
\end{align*}$$
Nun kann man die Faktoren der $2$ zusammenfassen. Wenn $x$ die Anzahl der Zellteilungen ist, können wir die Anzahl der Zellen mit einer Funktion $f(x)$ beschreiben:
$$
f(x) = 2^{x}.
$$
Wie viele Zellen gab es nach acht Teilungen? $f(8)=2^{8}=256$.

# Definition
Eine Funktion $f$ nennt man **Exponentialfunktion**, wenn sie der Form $f(x)=a^{x}$ ist, wobei $a\in\R$ gilt.

# Eigenschaften

## Monotonie
Die [[Funktion#Monotonie|Monotonie]] von Exponentialfunktionen $f(x)=a^x$ hängt vom Parameter $a$ ab:
$$
f \text{ ist }
\begin{cases}
\text{ streng monoton fallend,} & \text{falls } 0<a<1\\
\text{ konstant, } & \text{falls } a=1 \\
\text{ streng monoton steigend,  } & \text{falls } a>1.
\end{cases}
$$
## Achsenschnittpunkte
Die Exponentialfunktion $f(x)=a^x$ besitzt **keine** [[Funktion#Nullstelle|Nullstelle]]. Es gibt einen Schnittpunkt mit der $y-$Achse im Punkt $S_{y}(0|1): f(0)=a^0=1$.

# $e-$Funktion
Die **$e-$Funktion** ist eine besondere Exponentialfunktion. $e$ ist die **eulersche Zahl** und beträgt in etwa $e\approx 2,72$. 

## Eigenschaften

>[!tip] Ausblick
>Eine weitere Definition der $e-$Funktion lautet wie folgt: Es ist diejenige Funktion, die ihre eigene [[Ableitung]] ist! 

