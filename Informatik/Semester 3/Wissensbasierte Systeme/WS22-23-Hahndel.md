Begriffe Korrektheit und Vollständigkeit (im Zusammenhang mit Thema Logik) definieren

Geneteischer Algorithmus definieren

Es sind Prolog Unifikationen gegeben und du musst angeben ob true. oder false. (obs funktioniert) und wenn true. auch welche Gleichungen Prolog ausspucken würde z.B. A = 3+4 usw..

Es war auch wieder eine Prolog Funktion gegeben und du musstest zu zwei Aufrufen der Funktion hinschreiben, was dafür rauskommt. Die gegebene PrologFunktion hat eine Liste genommen und alle Dubilkate entfernt, also eine Liste ohne Dublikate zurückgegeben:

```
set( [], []).
set( [ X1| Xs], Ys) :- 
    member( X1, Xs), 
    set( Xs, Ys).
set( [ X1| Xs], [ X1| Ys]) :- 
    not_member( X1, Xs), 
    set( Xs, Ys).
```

(natürlich hat die nicht "set" geheißen - war aber sonst genau gleich)

Es gab auch wieder eine Prolog Aufgabe: Man sollte die Lösung eines 3x3 Sodoku programmieren (so dass in keiner Zeile oder Spalte die gleiche Zahl vorkommt) (evtl. die Funktion aus der vorherigen Aufgabe nutzen, die ja auch schauen kann ob eine Liste ohne Dublikate ist und dann so beschreiben, dass jede Zeile und Spalte ohne Dublikate sein sollen und  sonst ähnlich wie das vierfarben Problem lösen, das er auf den Folien hat)

Dann kam auch noch eine Aufgabe dran, zu der man beschreiben soll wie man ein gegebenes Problem mit einem Suchbaum darstellen/lösen kann. Diesmal hatte man eine Platte mit 2x3 Plätzen auf diesen plätzen lagen 5 Plättchen, d.h. ein Platz war frei-jetzt kann man immer nur ein Plättchen auf das leere Feld schieben, um dann wieder ein weiteres Plättchen auf den neu freigewordenen Platz zu schieben usw... Lösung:Jede neue Zahlenkonstellation ist ein Zustand und die verschiedenen Möglichkeiten, welches Plättchen man jetzt an die freie Stelle schiebt, sind die Kanten. - Man soll einen bestimmten angegebenen A\* Algorithmus nutzen, um den kürzesten Weg zum angegebenen Zielszustand zu finden: die Manhattendistanzen jedes Plättchens zu seinem Zielplatz zusammenzählen sind die geschätzten Kosten/Entfernung eines Zustandes zum Zielzustand. Diese Schätzfunktion sollte man bewerten und dann ausführen -> Baum zeichnen und für jeden Folgezustand Kosten ausrechnen -> nur die mit den geringsten Kosten weiter expandieren.

Beispielzustand:134                     Zielzustand:123  
52\_                                              45\_

Kosten des Beispielzustandes: Kosten zum Beispielzustand + 0(1 steht an richtiger Stelle)+1(3 steht um 1 entfernt von seiner richtigen Stelle)+1(5 steht um 1 entfernt von seiner richtigen Stelle)+1(2steht um 1 entfernt von seiner richtigen Stelle)+3(4 steht um 3 Felder weg von seiner richtigen Stelle) (diagonal gehen geht nicht)= Kosten zum Beispielzustand + 6(geschätzt zum Ziel).

Es gab auch wieder eine Aufgabe, bei der man verschiedene Tupelconstraints gegeben hat und ein Roboter erkennt (oder sonst irgendwer - er nimmt nur oft einenRoboter), dass das Individuum, dass er vor sich hat, bestimmte Eigenschaften nicht hat ->du musst diese Eigenschaften aus der Domäne streichen und mit Tabelle lokal konsistent machen (wie auf Folie und auf Übungsprüfungen) - Danach kommt noch die Frage, ob das entstandene constraintsystem global konsistent ist (war es in diesem Fall, da die Domänen alle einelementig waren)

Man sollte auch ein kleines Constraint Program in Prolog schreiben, dass ein Gleichungssystem mit zwei Gleichungen, die insgesamt zwei Variablen haben, lösen kann: einfach ein Funktionssymbol f(X,Y):-  und dann die beiden Funktionen in geschweiften Klammern mit Komma (logisch UND) getrennt. {X=3-Y},{Y=10+X}.

Man sollte noch kurz iterative Tiefensuche und Breitensuche vergleichen.(bezüglich Speicher und Zeitverhalten)

Den Ausdruck Wissensbasierte Systeme definieren und zwei Beispiele nennen.

Man hat einen Ausdruck und soll mit Tableauverfahren zeigen, dass dieser Ausdruck kein Widerspruch enthält. Verfahren anwenden und wenn nicht alle Zweige abgeschlossen sind, dann gibts keinen Widerspruch.

Man sollte auch noch zeigen ob eine bestimmte Klauselmenge widersprüchlich ist oder nicht(bestand nur aus zwei Klauseln): geht einfach mit Tableauverfahren (Erinnerung: {{A,B,C}{-A,B,-C}} ist das Gleiche wie (A\\/-B\\/C)/\\(-A\\/B\\/-C))

Dann hatte man noch eine Aufgabe, bei der man mehrere Aussagenlogik Ausdrücke hatte A->B  etc. und musste einen anderen Ausdruck C->B explizit mit Resolution beweisen: Lösung:Alle Ausdrücke in Klauselform umformen (-> müssen weg) und den zu beweisenden Ausdruck negiert zur Menge  hinzufügen und dann mit Resolution einen Widerspruch herleiten.

Es gab auch wieder eine Aufgabe, bei der bestimmte Aussagen wörtlich gegeben waren, die du dann in Prädikatenlogik(mit Quantoren) umformen musstest: "Jeder Studen der THI, der die Vorlesung Wissensbasierte Systeme besucht hat, kann Prolog programmieren"

Dann sollte man noch die Frage beantworten, ob man den Regleinterpreter mit Rückwärtsverkettung auch zum Beweisen von Dingen hernehmen kann? Mit kurzer Begründung (ja, eigentlich macht der Regelinterpreter ja nix anders als mit Rückwärts oder Fortwärtsverkettung Fakten zu beweisen)

Von dem Aufbau der Prüfung/Aufgabentypen/Aufgabenstruktur kann man sich eigentlich ganz gut an den Übungsprüfungen orientieren.