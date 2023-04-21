# Motivation

Die **Stetigkeit** von Funktionen spielt eine wichtige Rolle in der Analysis. Mit der Stetigkeit überprüft man sinngemäß, wie „kontinuierlich“ eine Funktion ist. Es gibt unterschiedlich starke Voraussetzungen der Stetigkeit, wobei die reine Stetigkeit die schwächste Stetigkeit ist. Man benötigt die Stetigkeit als notwendige Voraussetzung für die Differenzierbarkeit von Funktionen.

>[!caution] Achtung
>Aus Stetigkeit folgt nicht, dass eine Funktion differenzierbar ist!
 
# Definition

## Stetigkeit an einer Stelle
Gegeben ist eine Funktion $f$ und eine Stelle $x_0$. Falls für ==alle== beliebigen Umgebungen um $f(x_0)$ mit Radius $\varepsilon$ ==mindestens eine== Umgebung um $x_0$ mit Radius $\delta$ existiert, sodass die Funktionswerte von $x_{0}-\delta$ bis $x_0+\delta$ auch zwischen $f(x_0)-\varepsilon$ und $f(x_{0})+\varepsilon$ liegen. Mathematisch formuliert heißt das

$$\forall \varepsilon >0 \,\exists\; \delta>0 \;\forall x\in\R: |x-x_{0}| < \delta \Longrightarrow |f(x)-f(x_0)|<\varepsilon.$$
Ist diese Bedingung für ein $x_0$ erfüllt, heißt $f$ **stetig in der Stelle $x_0$**.

## Stetigkeit in einem Intervall
Gilt die obige [[Stetigkeit#Stetigkeit an einer Stelle|Definition]] für Stetigkeit in einem Intervall $[a,b]$, heißt $f$ **stetig im Intervall $[a,b]$**.

## Stetigkeit im Definitionsbereich
Gilt die obige [[Stetigkeit#Stetigkeit an einer Stelle|Definition]] für Stetigkeit auf dem [[Funktion#Definitionsbereich|Definitionsbereich]] von $f$, heißt $f$ stetig.

