# Wichtig: Es mussten nur 6 von 7 Aufgaben bearbeitet werden!

**A1: Oberes Konfidenzintervall Mittelwert**
n = 80, mittelwert = 12, alpha = 0,05
\- Oberes 0,95 KI aufstellen
\- Test ob u <= 10
\- p-Wert berechnen: 4,65..%
\- Aussage bewerten: "Kann man sagen, dass der tatsächliche Mitelwert mit einer Wahrscheinlichkeit von 95% in dem oben erzeugten Intervall liegt?"
Antwort: Nein, der tatsächliche Wert liegt entweder in dem Intervall oder nicht. Es lässt sich nur sagen, dass das Verfahren ein Intervall liefert, dass in         95% aller Fälle den korrekten Wert mü enthält.

**A2: Punktschätzer**
\- 3 Schätzfunktionen gegeben: Auf Erwartungstreue oder asymptotische Erwartungstreue prüfen.
\- Konsistenz angeben
\- Bias angeben
\- Nach Effizienz ranken.

\*\*A3: Punktschätzer \*\*
\-MLS: Für Funktion f(x) = (ß^2^ /x^3^) - e^(-ß/x)^ mit x > 0 den Parameter ß mittels Maximum-Likelihood schätzen.
\-Bayesschätzer

**A4: ANOVA**
Aufgabe: 3 Verschiedene Lernvideos (A, B und C). Jeweils 4 Probanden deren Aufmerksamkeitszeit gemessen wurde. Unterscheiden sich die Mittel der Gruppen                    signifikant von einander?
Gegeben: Mittel und Stichprobenvarianz, Tabelle mit den Kategorien A,B,C mit jeweils 4 Werten
Mittelwert1=8, Mittelwert2=12, Mittelwert3=13
Stiprobenvarianz für alle gleich s=2/3
\- Globales Mittel ausrechnen
\- Effekte ausrechnen
\- SQA und SQR ausrechnen
\- MQA und MQR ausrechnen
\- Prüfgröße ausrechnen und mit entsprechendem Wert in der F-Verteilung vergleichen
Antwort: H1 wird angenommen.
Teilaufgabe: Ergebnis interpretieren! Was will ich erreichen?
Antwort: Zum Signifikanzniveau kann man davon ausgehen, dass sich mindestens eine der Gruppe signifikant von den Anderen unterscheidet. (H1 wird angenommen).

**A5: X² - Anpassungs Test**
\- Annahme gleichvertielt, n = 84
\- h1= 13, h2= 15, h3=14, h4=10, h5=17, h6=15
\- alpha = 0,1
\- Teilaufgabe: Welchen Fehler habe ich möglicherweise in der vorherigen Teilaufgabe gemacht?
Antwort: Fälschlicherweise H1 anzunehmen. Obwohl mit dem Testen zwar der Alphafehler auf ein Minimum reduziert wurde, besteht immer noch ein Restrisiko,             dass wir uns falsch entschieden haben.

**A6: Markov Ketten**
Übergangsmatrix:
0; 0; 0,5; 0,5
1; 0; 0  ;  0
0; 1; 0  ;  0
0; 0; 1  ;  0
\-Zustandsgrapht zeichen
\-irreduzibiltät angeben
\-periode berechen
\-aperiodisch
\-da (1->3->2->1) 3-Schritte & (1->4->3->2->1) 4-Schritte
\-zeigen, dass (2/7; 2/7; 2/7; 1/7) eine Stationäre Verteilung ist
1\. v x M = v
2\. Matrixmultiplikation durchführen
3\. v x M = v
4\. Stationäre Verteilung bestätigt.
\-beurtielen es mehr Stationäre Veitlung gibt
\-Nein, nach Ergodensatz eindeutig.
\-mittlere Rekurrenzeiten berechnen
\-Nach Ergodensatz (mi = 1/vi): m1= 3,5; m2=3,5; m3=3,5; m4=7

**A7: Monte Carlo Methoden**
\-Metropolis Hastings Algorithmus mit sehr kleinem, teils im negativen intervall
\-Rejection Sampling:
\-zwischen 3 Verteilungen zur Simulation die beste ankreuzen und sowohl Annahme als auch Ablehnungsgrund angeben:
N(0,1), U(a,b) & U(-0.1, 0.4)
\--> N(0,1) unpassend: Auf ganz R definiert und zu hohe Streuung.
\--> U(a,b) unpassend: a und b waren so gewählt, dass sie nicht ganz f(x) überdeckte. f(x) war auch für negative x-Werte definiert aber die                             Vorschlagsverteilung nur für Positive. (die genauen Werte für a und b weiß ich auch nicht mehr lol)
\--> U(-0.1, 0.4) passend
\-zwischen 3 Werten für M auswählen und begründen