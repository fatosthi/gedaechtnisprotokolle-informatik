1\. Komplexitätsklassen ordnen + eine Komplexitätsgleichung beweisen

1a) f1 = (log n)^-1

f2 = 5^n

f3 = n^(1/2)

f4 = ((n+1)! / n!)

f5 = 1/n!

1b) zeigen dass:

sum_i=1_n (log(i / (i+1) + log(i+1)) = log(n!)

2\. Optimierungsproblem grafisch lösen + Simplex

2a)

max 500x + 300y

s.t.  x<= 150

y<=60

y <= 85-1/2 \* x

y <= 150 - x

x>= 0

y>=0

2b)

max x + 2y

x + y <= 16

\-x-y <= -4

x <= 4

noch eine

x>=0

y>=0

3\. Lagrange

f(x1, x2, x3) = x1^2 + (1/8)x2^4 + x3^2

h = 6 - 2x1 - x2^2 = 0

grad_f = \[ 2x1 - 2lambda,

1/2  *x2^3 - 2lambda*  x2,

2x3,

6 - 2x1 - x2^2

\]

4\. Graphensuche Dijkstra

Suche von S nach Z

Graph = S nach A mit 6 und B mit 2

A nach Z mit 2

B nach mit 2 und B nach C mit 4

C nach Z mit 4

Wann ist ein suchverfahren vollständig?

Nenne ein vollständiges und ein nicht vollständiges Suchverfahren

5\. Konstruktive Constraints erklären + Fuzzy Constraints Aufgabe

a) warum sind constrainsts konstruktiv angegeben? Geben sie ein Beispiel für konstruktive constraints an

Fuzzy Constraint Aufgabe: Firma will Lagerhalle mit kleiner Fläche von 400 bis 600 m^2 und einer hohen Höhe von 4-6 Meter und 2-3 Türen, jedoch würden 4 auch noch gerade so gehen.

Lösung:

ma(x) = if 400 <= x <= 600, 1 - (1/600-400)\*x

mb(x) = if 4 <= x <= 6, (1/6-4)\*x

mc(x) = 1 if x element of {2,3}, 1/2 if x = 4, 0 else

5c)

2 fuzzy sets gegeben. Man soll deren Vereinigung berechnen -> A or B einfach

und das einzeichnen