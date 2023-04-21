# Definition
Eine Folge ist eine Funktion $x(n): \N\to \R$. 

# Schreibweise
## Notation
Statt $x(n)$ schreibt man Folgen in der Form $(x_{n})_{n\in\N}$, welche man oft mit $(x_n)$ abkürzt. Ein **Folgenglied** ist die zugeordnete reelle Zahl zu einem bestimmten $n\in\N$.

## rekursive Vorschrift
### Beispiel 1
Bei den **Fibonacci-Zahlen** handelt es sich um eine **rekursiv** definierte Folge: man startet mit den beiden Folgengliedern 
$$
\begin{align*}
x_{0}&= 0\\
x_{1}&= 1
\end{align*}
$$
und berechnet jedes weitere Folgenglied mit 
$$
x_{n} = x_{n-1}+x_{n-2}.
$$
Die nächsten Folgenglieder lauten also:
$$
\begin{align*}
x_{2}&= 1\\
x_{3}&= 2\\
x_{4}&= 3\\
x_{5}&= 5\\
x_{6}&= 8\\
x_{7}&= 13\\
x_{8}&= 21\\
& \vdots 
\end{align*}
$$
### Beispiel 2
Zur Berechnung von Wurzeln kann man das alte, babylonische **Heron-Verfahren** nutzen. Möchte man die Wurzel einer Zahl $a$ bestimmen, berechnet man Folgenglieder nach der Vorschrift
$$
x_{n+1}=\frac{1}{2}\left(x_{n}+\frac{a}{x_{n}}  \right).
$$
Ein „gutes“ erstes Folgenglied ist $x_{0}=\frac{a+1}{2}$. 

## explizite Vorschrift
### Beispiel
Die **Nullfolge** $x_{n}=\frac{1}{n}$ ist eine explizite Folge, denn ein Folgenglied lässt sich direkt mithilfe des Arguments $n$ berechnen. 

# Schranke


# Grenzwert
## Definition
Eine Folge $x_n$ **konvergiert** gegen ein $x$, falls es zu jedem Abstand $\varepsilon > 0$ eine natürliche Zahl $N$ gibt, sodass für alle Folgenglieder mit $n\geq N$ gilt
$$
|x_{n}- x|<\varepsilon.
$$
$x$ nennt man **Grenzwert**.

>[!caution] Achtung
>Eine Folge, die keinen Grenzwert in $\R$ hat, **divergiert**.
>Man sagt auch, dass eine divergente Folge *uneigentlich (gegen $\pm \infty$) konvergiert.*

## Beispiele
- Die [[Folgen#Beispiel|Nullfolge]] besitzt den Grenzwert $0$.
- Das [[Folgen#Beispiel 2|Heron-Verfahren]] konvergiert für eine gegebene Zahl $a$ gegen $\sqrt{a}$. 
- Die Folge $x_{n}=n$ divergiert / konvergiert uneigentlich gegen $\infty$.