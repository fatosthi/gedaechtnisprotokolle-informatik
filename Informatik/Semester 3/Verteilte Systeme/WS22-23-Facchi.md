Es kam eine Aufgabe dran, wo drei prozesse als striche dargestellt werden, die sich mit Pfeilen nachrichten schicken und es gibt punkte auf den Strichen. Du musst zu jedem Punkt die Vektorzeit eintragen.

Es kam eine Aufgabe zur kausalen Konsistenz dran: also mehrere Prozesse die W(x)a R(x)b und si zeugs machen - hier mit Pfeilen die kausal verknüpften Schreib oder Leseprozesse verbinden und auch Vorgänge innerhalb eines Prozesses mit einem Pfeil verbinden - dann sagen ob kausal konsistent oder nicht - zusätzliche Frage: Was für ein Event(Lese- oder Schreibprozess) muss man entfernen damit das ganze konsistent wird?/falls es nicht kausal konsistent ist)

Es kam eine Aufgabe dran die war sehr ähnlich wie die in der Probeklausur mit dem Parktplatz und den Autos -hier nur mit Ausichtsplattform auf die nur eine gewisse anzahl an menschen drauf dürfen: -> Semaphore mit der Anzahl initialisieren und dann an richtiger Stelle das P() und V() auf den Semaphore einfügen

Es gab einen Algorithmus vorgegeben, der zu den nudelessenden Philosophen am runden Tisch war (die immer zwei gabeln brauchen). Erst wurde sich der Mutex semaphore geschnappt und dann in einem Schritt die eine Gabel und dann mit noch einem P() die andere Gabel - erst danach wurde der Mutex wieder freigegeben und der Philosoph beginnt zu essen - nach dem essen gibt er mit V() zuerst die rechte und dann wieder mit V() für die linke Gabel alle Gabeln ab. (sehr ähnlich zu einer Aufgabe (2b) in einer seiner älteren Prüfungen(Wintersemester 19/20), die er zur Übung zur Verfügung gestellt hat - mit dem einzigen Unterschied, dass der Mutex nicht mehr benutzt wird um die Gabeln abzugeben (nur um sie zu nehmen - abgegeben werden sie einfach so ohne Mutex)) Die Frage zu dem Algorithmus war: Wieso funktioniert hier der gegenseitige Ausschluss/kommt es hier NICHT zu einem Deadlock (hier funktioniert er - in der ältereren Prüfung nicht - wegen dem einen Unterschied) - 2.Frage: Wieso ist der Algorithmus trotzdem nicht fair/besonders gut?

Was ist eine Clientzentrische Sicht auf Konsistenz und wieso benutzt man diese, obwohl sie nicht so gut ist?

3Charakterisika von Verteilten Systemen nennen.

Definition von Verteilten Systemen angeben.

Definition von Skalierbarkeit angeben.

Wieso verändert sich die Internettopologie und wieso macht das verteilte Systeme schwieriger?

Beispiel angeben für einen Fall, wo sich die Internettopologie verändert.

Welche Kommunikationsformen sind bei Nachrichtenorientierter Kommunikation im Gegensatz zum Client-Server Verfahren möglich? (vielleicht transitive und persistive)

Wieso ist ein offenes System nie zu 100% sicher ?

Cyber Physical Systems definieren.

Wieso ist das globale Zeit Problem bei verteilten Systemen schwieriger als bei lokalen Systemen? (lokale Systeme:globaler Speicher,gemeinsamer Takt,geringere Nachrichtenverzögerung)

Was heißt Transparenz?

Semaphore mit worten definieren und P() und V() operationen in Pseudocode hinschreiben (wahrscheinlich einfach zähler rauf - bzw- runterzählen) und erklären wie der wechselseitige Ausschluss mit den Semaphoren gemacht wird

Was ist asymmetrische und was ist symmetrische Kommunikation?

Was für Fehler können passieren, wenn man nachrichtenorientierte Methoden für streamorientierte Kommunikation verwendet?

Bully algorithmus ausführen (Zahlen sind schon gegeben - welche Zahl ausfällt ist auch schon gegeben -> das stößt die election los) (ähnliche Aufgabe gab es schon mal in Probeklausur)

Vektorzeiten vergleichen (wie in Probeklausur)

Verfügbarkeit und Zuverlässigkeit definieren.

Ein Algorithmus mit angeblicher Lösung für Leser Schreiber Problem war gegeben und du musstest sagen, wieso ein Fehler auftritt.(war der Gleiche Algorithmus wie auf der Folie Verteilte Systeme 2 -3.Lösungsversuch des wechselseitigen Ausschluss) -> Ausschluss gewährleistet, aber es kann zu Deadlock kommen

Aufgaben der Art "a.b||d.f =" und du musst eventuelle Interleavings {a.d.b.f,...} bestimmen - kam mit Synchronisation dran

Es kam eine Aufgabe dran, da war mit Worten eine Maschine beschrieben: Maschine nimmt 1€ und gibt kleine Tüte aus, bei 2€ gibt die Maschine eine große Tüte aus. Und jetzt musst du wieder die Interleavings bestimmen M= (1€.kleineTüte+2€.großeTüte+1€.1€.großeTüte....).M (rekursiven Aufruf am Ende nicht vergessen - Maschine macht weiter -hört ja nicht auf)

Mit der "Formel" solltest du erklären wieso die Fehlerwahrscheinlichkeit drastisch durch redundante parallel geschaltete Geräte reduziert werden kann/bzw. die Ausfallsicherheit erhöht werden kann (ganz am Anfang vom SIcherheitskapitel - Geräte in Sequenz geschaltet vs Geräte parallel geschaltet)pok= 1 – 0,1\*0,1\*0,1 = (1-pfn) = 0,999 = 99,9% => Wahrscheinlichkeit, dass es funktioniert für den Fall, dass drei gleiche Geräte parallel geschaltet sind und die Ausfallwahrscheinlichkeit eines Geräts 0,1 bzw 10% beträgt

Zum Lamport Thema ist es wichtig zu wissen was beide Pfeilarten bedeuten (gestrichelt und nicht gestrichelt): Er gibt verschiedene Aktionen auf einem Zeitstrahl an und es sind ganz viele Aussagen in Pfeilnotation gemacht (A endet vor Anfang B) (B beginnt bevor C endet) usw. und du musst die Aussagen die nicht zu den Aktionen auf dem Zeitstrahl passen durchstreichen.

Ebenso gab es noch eine Aufgabe zum Lamport, wo eine Aussage in Pfeilnotation gegeben war und eine weitere die dann mit der ersten bewiesen werden sollte(funktioniert genau so wie er es in der Vorlesung durchgesprochen hat) Von der ersten Formel arbeitest du dich vor und formst diese um, bis du bei der Zielformel bist. (A endet vor Beginn von B d.h. A beginnt vor dem Beginn von B und weil B vor dem Anfang von C beginnt, beginnt auch damit A vor dem Anfang von C....sowas)

Man kann sich von der Aufgabenstruktur eigentlich ganz gut an den Übungsprüfungen orientieren.