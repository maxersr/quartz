# Definition
Eine Zuordnung $f:D\to \R$ mit [[Funktion#Definitionsbereich|Definitionsmenge]] $D$ und Zielmenge $\R$ heißt **Funktion**, wenn gilt

$$\forall x \in D\; \exists!\; y\in \R: f(x) = y.$$

# Eigenschaften von Funktionen

## Definitionsbereich
Der Definitionsbereich oder die Definitionsmenge $D$ gibt an, welche Argumente für die Bestimmung der dazugehörigen Funktionswerte nutzbar sind.

### Beispiel
Die Funktion $f(x)=\frac{1}{x}$ ist an der Stelle $x=0$ nicht definiert. Für die Definitionsmenge $D$ gilt somit $D=\R\setminus \{0\}$.


## Wertebereich
Der Wertebereich $W$ einer Funktion ist das [[Intervall]] aller Funktionswerte dieser Funktion.

>[!info]
>Ist der Wertebereich $W$ gleich der Zielmenge $\R$, ist die Funktion [[surjektiv]].

### Beispiel
- Die Funktion $f(x)=x^{2}$ besitzt den Wertebereich $W=[0,\infty)$. 
- Die Funktionen $f(x)=\sin(x)$ und $g(x)=\cos(x)$ haben den Wertebereich $W=[-1,1]$.

## Schnittpunkt mit der y-Achse
Den Schnittpunkt mit der $y-$Achse schreibt man als $S_{y}$. Man kann ihn berechnen, indem man die Funktion an der Stelle $x=0$ auswertet, d.h. $f(0)$ berechnet. 


## Nullstelle
Eine **Nullstelle** $x_0$ ist eine Stelle, für die gilt 
$$
f(x_{0}) = 0.
$$
>[!tip] Hinweis
>Eine Potenzfunktion $n-$ten Grades kann maximal $n-$viele Nullstellen besitzen!

### Vielfachheit von Nullstellen
Die **Vielfachheit** gibt an, wie oft eine Nullstelle in einer Funktion vorkommt.

### Bestimmen von Nullstellen
- [[Quadratische Funktionen#Nullstelle|Quadratische Funktionen]]
- …



## Extremum
Eine Funktion kann auf ihrem Definitionsbereich ein Extremum besitzen. Dabei handelt es sich um ein **Maximum** oder ein **Minimum**. Man unterscheidet in **globale** und **lokale** Extrema.

### globale und lokale Extrema
Mit dem **globalen** Minimum oder Maximum meint man den minimalen bzw. maximalen Punkt einer Funktion im angegebenen [[Intervall]] bzw. [[Funktion#Definitionsbereich|Definitionsbereich]]. Jede Funktion nimmt dabei auf einem Intervall $[a,b]$ je mindestens ein Minimum und Maximum an. 
Von **lokalen** Extrema redet man, wenn der dazugehörige Funktionswert der kleinste bzw. größte in einem Intervall ist. 

### Maximum und Minimum
Für die Bestimmung von Extrema kann man die [[Ableitung]] nutzen. Dabei unterscheidet man in zwei Kriterien: Ein *notwendiges Kriterium*, das entscheidet ob ein Extremum vorliegt oder nicht, und ein *hinreichendes Kriterium*, mit welchem man die Art des Extremums bestimmen kann.

#### Notwendiges Kriterium
Ist $f$ eine Funktion hat an einer Stelle $x_0$ ein Extremum, dann gilt

$$
f'(x_{0})=0.
$$

#### Hinreichendes Kriterium
Ist $f$ eine Funktion, für die gilt $f'(x_0)=0$ und $f''(x_{0})\neq0$, dann hat $f$ ein Extremum $E$ in $x_0$ und 

$$E \text{ ist ein } 
\begin{cases}
\text{ Maximum, falls } f''(x_0)<0 \\
\text{ Minimum, falls } f''(x_0)>0
\end{cases}
\text{ ist. }
$$
## Wendepunkt
Ist $f$ eine Funktion, für die gilt $f''(x_0)=0$ und $f'''(x_{0})\neq0$, dann hat $f$ in $x_0$ einen **Wendepunkt**.

>[!note]
>Gilt zusätzlich $f'(x_0)=0$, handelt es sich um einen *Sattelpunkt*.

## Polstellen & Lücken
Ist $f$ eine Funktion gebrochenrationale Funktion der Form
$$
f(x) = \frac{g(x)}{h(x)},
$$
und ist $h(x_{0})$ eine $m-$fache Nullstelle, gibt es folgende Möglichkeiten: $g(x_{0})$ ist keine Nullstelle, dann ist $x_{0}$ eine **Polstelle**. Ist ansonsten $g(x_0)$ eine $n-$fache Nullstelle, gilt:
- Ist $n<m$, dann ist $x_{0}$ eine Polstelle.
- Ist $n\geq m$, dann ist $x_0$ keine Polstelle und lässt sich [[Stetigkeit|stetig]] fortsetzen. $f$ besitzt dann in $x_0$ eine **Lücke**.

## Monotonie
Gegeben ist eine Funktion $f$. Man betrachte alle $x$ aus einem [[Intervall]] $[a,b]$. Man macht für die **Monotonie** von $f$ folgende Unterscheidungen:

|$f$ ist $\ldots$ |Bedingung|
|:---:|:---:|
|monoton wachsend|$f'(x)\geq 0$|
|streng monoton wachsend|$f'(x)> 0$|
|monoton fallend|$f'(x)\leq 0$|
|streng monoton wachsend|$f'(x)< 0$|

## Symmetrie
Eine Funktion $f$ heißt **achsensymmetrisch** zur $y-$Achse, falls gilt
$$
f(-x) = f(x).
$$
Eine Funktion $f$ heißt **punktsymmetrisch** zum Koordinatenursprung, falls gilt
$$
f(-x) = -f(x).
$$

## Asymptote
Eine **Asymptote** ist eine Gerade oder Kurve, die eine Funktion im Unendlichen annähert. Man unterscheidet in *horizontale* und *vertikale* Asymptoten.
### Beispiel
Die Funktion $f(x)=\frac{1}{x}$
![[1_x.png|300]]
besitzt die beiden Asymptoten $x=0$ und $y=0$. 