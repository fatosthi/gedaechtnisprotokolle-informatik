Analysemuster Stückliste skizzieren und erklären wann man dieses benutzt.

Wie man Köhärenz erhöhen kann erklären.

Drei Vorteile nennen, die man hat wenn man sein System in Komponenten einteilt. Drei Voraussetzungen nennen,die man braucht um sein System in Komponente einteilen zu können. Begründen!

Drei Möglichkeiten nennen und erklären, wie man Zuverlässigkeit/Reliability verbessern kann.

Wieso ist es schwierig anzugeben,ob die Funktion public long evil(int x, int v, int z) komplett fehlerfrei ist?Gib an wie viele Tests man brauchen würde (Tipp: ein int hat 4 Byte) (Tipp stand in der Angabe)

Eine Anforderung ist gegeben, in Worten (ein Satz) und du musst diese in verbessert nochmal hinschreiben (genauer -einfach irgendwelche genauen Zahlen erfinden glaub ich mal)

Erkläre welche Auswirkungen die Anforderungsdefinition auf Entwurf, Implementierung und Testphase hat.

Nenne wann man FIlter and Pipes Architektur verwendet, begründe deine Antwort und erläutere das Prinzip.

Was ist das Geheimhaltungsprinzip und wie kann man das mehr erreichen?

Ein Use Case Diagramm ist gegeben und du musst markieren was falsch ist und begründen und Verbesserungsvorschlag machen (3 Sachen musste man finden).

Zwei Klassen sind in UML gegeben mit beidseitiger Assoziation und Multiplizität 0...\* -Beide Klassen haben eine +add( andere Klasse) Funktion und die Elemente in der jeweiligen Liste (in der sie sich gegenseitig speichern) sind unique (nur einnmal vorhanden) . Du musst in Java die eine Klasse implementieren (also Liste erstellen als Property und dann die add(element) funktion- nicht vergessen in der add funktion muss man erst abfragen, obs das element schon in der liste gibt und dann erst hinzufügen und nach dem hinzufügen musst du abfragen, ob das element nicht null ist- wenn es nicht null ist, dann rufst du an dem Element die element.add(this) funktion ( diese Funktion gehört der anderen Klasse -"element" ist ein Objekt der anderen Klasse) auf.

Es ist ein Zustandsdiagramm gegeben, der StartZustand und die Pfeile die ausgeführt werden und du musst zu jedem ausgeführten Pfeil sagen in welchem Zustand man landet(Oberzustand,Unterzustand,..) -einmal kommt eine tiefe Historie und einmal eine flache Historie vor

Dann ist ein anderer Pfad durch das Zustandsdiagramm gegeben und diesmal musst du sagen wie sich die variable x verändert (entry, exit, aktionen die auf Pfeilen stehen ..) Hier bin ich mir nicht sicher gewesen, ob man zuerst den Guard auswertet des nächsten Pfeils und dann erst exit funktion ausführt und dann die aktion die auf dem Pfeil steht oder ob man zuerst die exit funktion macht und danach die guards aller ausgehenden Pfeile checked?! (wahrscheinlich ersters)

Dann hatte man ein Stück programmcode (kleinstes gemeinsames Vielfaches) und du musstest den Kontrollflussgraphen zeichnen. Dann musstest du dazu eine minimale Anzahl an Tests/Funktionsaufrufe definieren, so dass die Zweigüberdeckung 100% ist. Zu jedem Testfall eine Begründung und den Ausführungspfad angeben (CodeZeilenreihenfolge). - Da war noch eine Aufgabe zu einer if Abfrage dieses Code Beispiels z.B. if(max%b ==0 &&max%a==0) und man musste ankreuzen welche Kombinationen man bei der minimalen Bedingungsüberdeckung testen müsste: gegeben waren Bedingungsauswertungen: bei denen beide Bedingungen: 11, 01, 10, 00 sind (linke Zahl = 1.Bedingung, rechte Zahl 2.Bedingung) Lösung: weil wir hier &&(UND) haben müssen wir (11,01,10) ankreuzen

Dann musste man drei verschiedene Überdeckungen allgemein vergleichen(welche ist besser und so weiter): Anweisungsüberdeckung,Zweigüberdeckung,Pfadüberdeckung