Cheatsheet für javafx zum rausreißen und daneben legen war dabei -> letzte Seite

Was ist checked/ unchecked exception ?-> je eine Beispielklasse nennen

Exception abfangen und vordefinierte werfen also
try{ wert = zahlen[5]
}Catch(IndexOutOfBounds e){ throw new MyException(e.getMessage(),"Fehler")}
Welche Exception man abfangen sollte, welche neue Exception man werfen sollte und welchen Fehlertext man mitgeben sollte war gegeben -> du musstest lediglich den try Catch Block mit den gegebenen Infos einfügen in das CodeBeispiel

Aufgabe zu Konstruktor Verkettung:
Codebeispiel mit Konstruktoren ist gegeben:
a) Eingaben sind gegeben (Objektinstantierungen, die unterschiedliche Konstruktoren nutzen)--> wie sehen dann Ausgaben aus (Konstruktoren haben teilweise mit System.out.println() Zeugs ausgegeben)?
b) Über die Objekte, die in a) kreiert wurden, wird iteriert und sie werden ausgegeben -> wie sieht Ausgabe aus? (toString der Objekte muss beachtet werden)

Was ist substituieren mit/auf Klasse oder Interface: ein Erklärungssatz und je ein Codebeispiel

Ankreuzen ob substitution in einem gegebenen Code Beispiel funktioniert oder nicht + kurze Erklärung warum/nicht

UML Diagramm:->Attribute, getter, toString, Konstruktoren erstellen

Zu einer Klasse (des UML ) Funktionen implementieren:
Vorgegeben:(Klasse implements Iterable)
Klasse hat Liste

iterator(): in dieser Funktion einfach den Iterator() der Liste returnen -> return listName.iterator();
(Hier merken: jede Collection hat schon eine iterator() Funktion --> wenn eine Klasse Iterable implementiert und eine Collection hat, können wir theoretisch in der Iterator() Funktion dieser Klasse einfach collectionName.iterator() zurückgeben und schon ist unsere Klasse iterierbar -> wir können über die Klasse iterieren und bekommen als Elemente Objekte aus der Liste --> for(listenObjekt a: Klasse, die Iterable implementiert))

Filtertag(String tag):
Hier musste man über die Klasse in der die Funktion steht/bzw damit über die Liste in der Klasse (Klasse hat ja Iterable implementiert)  iterieren und jedes Element, dass den "Tag" (Parameter der Funktion) hat in eine neue Klasse tun und diese dann zurückgeben

Filterauthor(Author Author): Hier das Gleiche, bloß, dass jetzt alle Elemente mit dem "Author" (Parameter der Funktion) in einer Klasse zurückgegeben werden sollen

In der nächsten Aufgabe musste man anhand dieser Methoden(wenn du die vorherige Aufgabe nicht hattest, dann einfach so tun als wären sie implementiert und verwenden) eine Instanz der Klasse, in der die Methoden definiert wurde filtern und dann ausgeben: class.filterAuthor(); bzw class.filterTag();
Und dann mit schleife ausgeben

Die GUI Aufgabe war ein kleiner Taschenrechner: oben ein Label gesamte erste Zeile lang - darunter alle Buttons (Zahlen 1-9 und "0" "+" "=") in Gitteroptik 4Zeilen mit jeweils 3 Buttons in einer Zeile

Bild war gegeben, ebenso die Elemente (Panes,Buttons) die verwendet wurden (z.B. Label calculationLabel;)--> Aufgabe 1: Layout: Elemente richtig initialisieren (calculationLabel=new Label("->")) und in die Panes stecken(main.add(new Button...))

Aufgabe 2: Die Eventhandler der Buttons implementieren.
Die Eventhandler der meisten Buttons waren schon gegeben -> die musste man nur noch zuweisen
Nur noch den Eventhandler des "=" Buttons musste man implementieren( hier war allerdings eine Funktion schon gegeben, die einen "Mathe" String nimmt und das Ergebnis der Rechnung als String zurückgibt), das heißt man musste hier nur die Rechnung, im Label des Rechners, der Funktion übergeben und hat dann das Ergebnis gleich wieder in einem String und kann dieses wieder in das Label schreiben.