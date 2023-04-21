## Motivation

Hat man eine [[Funktion]] wie $f(x) = \frac{1}{x}$, fällt auf, dass es für $x=0$ keinen Funktionswert gibt. Aber wie sieht es für $x=0,5;\; x=0,25;\; x=0,125;\; \ldots$  aus? Der Funktionsgraph sieht wie folgt aus:

![[1_x.png|300]]

# Grenzwert an einer Stelle

Wie in der Abbildung zu sehen: nähert man sich von **rechts** an die Stelle $x=0$, steigen die $y-$Werte ins unendlich an. Man schreibt

$$
\lim_{x\to0^+} \frac{1}{x} = \infty
$$

und sagt: „Der **==Grenzwert==** der Funktion $\frac{1}{x}$ für $x$ gegen $0$ von rechts ist (plus/positiv) unendlich“. 

Nähert man sich von **links** der Stelle $x=0$, ist der Grenzwert stattdessen $-\infty$, also ist
$$
\lim_{x\to0^{-}} \frac{1}{x}= - \infty
$$
und sagt analog: „Der Grenzwert der Funktion $\frac{1}{x}$ für $x$ gegen $0$ von links ist (minus/negativ) unendlich“.

>[!tip] Bemerkung
>Bei dem Beispiel $f(x)=\dfrac{1}{x}$ handelt es sich an der Stelle $x=0$ um eine [[Funktion#Polstellen & Lücken|Polstelle]].


## Beispiel

Die Funktion $f(x) = \dfrac{x^2-4}{x+2}$ an der Stelle $x=-2$ nicht definiert. Gesucht ist der Grenzwert der Funktion $f(x)$ an der Stelle $x=-2$.

- Schritt 1: Skizze des Funktionsgraphen anfertigen
![[fkt-luecke.png|300]]
- Schritt 2: Verhalten der Funktion an gewünschter Stelle beschreiben
Die Funktion $f(x)$ scheint an Stelle $x=-2$ von beiden Seiten gegen $-4$ zu gehen, hat dort aber eine [[Funktion#Polstellen & Lücken|Lücke]].

- Schritt 3: Grenzwert bestimmen
$$
\begin{align*}
\lim_{x\to-2} \frac{x^{2}-4}{x+2}&= \lim_{x\to-2} \frac{\cancel{(x+2)}(x-2)}{\cancel{(x+2)}}\\
&= \lim_{x\to-2} (x-2) \\
&= (-2 -2)\\
&= -4.
\end{align*}
$$
tags: #Funktion, #Grenzwert, #unendlich, #1/x, #Polstelle, #Definitionsbereich 

# Grenzwerte im unendlichen
![[Verhalten von Funktionen im unendlichen#Bedeutung]]

# Grenzwertsätze

Gegeben sind zwei Funktionen $f$ und $g$ mit der Voraussetzung, dass sie an der Stelle $x_0$ definiert sind und einen Grenzwert besitzen. Dann gelten die folgenden Regeln:

## Grenzwertsätze an einer Stelle

1. $$\lim_{x\to x_{0}}(f(x)+g(x)) = \lim_{x\to x_{0}}f(x) + \lim_{x\to x_{0}}g(x)$$
2. $$\lim_{x\to x_{0}}(f(x)-g(x)) = \lim_{x\to x_{0}} f(x) - \lim_{x\to x_{0}}g(x)$$
3. $$\lim_{x\to x_{0}}(f(x)\cdot g(x)) = \lim_{x\to x_{0}} f(x) \cdot\lim_{x\to x_{0}} g(x)$$
## Grenzwertsätze im Unendlichen

1. $$\lim_{x\to \pm \infty} = (f(x) \pm g(x)) = \lim_{x\to \pm \infty}f(x) \pm \lim_{x\to \pm \infty} g(x)$$
2. $$\lim_{x\to \pm \infty}(f(x)\cdot g(x)) = \lim_{x\to \pm \infty} f(x) \cdot\lim_{x\to \pm \infty} g(x)$$
3. Falls gilt $$\lim_{x\to \pm \infty} f(x) = \pm \infty,$$ dann ist $$\lim_{x\to \pm \infty} \frac{1}{f(x)}=0.$$
