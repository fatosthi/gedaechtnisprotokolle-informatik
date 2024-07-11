Was ist O-Notation? Erklären

Programmbeispiele sind gegeben und du musst O-Notation dazu angeben. Wie bei dem ersten Übungsblatt, wenn es das bei euch gibt.

Es war ein Term gegeben z.B. (4-3)\*3+5 und man musste dazu einen Binary Expression Tree malen ( so dass bei in-order traversierung(infix notation) der Term in der "richtigen"/bzw. normalen Schreibweise rauskommt) - dann musste man dazu noch vom Baum ablesen was für eine Schreibweise rauskommt, wenn man den Baum pre-order traversiert (prefix notation) bzw. dann auch noch mit post-order(postfix notation).

Du hattest ein Netzwerk gegeben und musstest den Max flow rausfinden (es waren nicht beschriftete Graphen vorgegeben wie auf dem Übungsblatt - pro Schritt zwei Graphen -> einen für den graphen mit residiual network und am anderen Graphen antragen wie viel verbraucht wurde von Kapazität z.B. 0/8) - Vorsicht!! Der erste Weg/Schritt, den du machen sollst, war schon vorgegeben(wie in der Übungsaufgabe). Zu diesem Netzwerk musstest du dann den Min-Cut-Max-Flow rausfinden und dann erklären was das ist: also so mit einem Schnitt Quelle und Ziel trennen, dass die Summe der Kanten durch die der Schnitt läuft, die von Quellenseite auf Zielseite gehen und die der Schnitt schneidet,möglichst klein ist.

Dann eine Aufgabe, bei der du nach und nach (Max-)Heap aufbauen solltest (immer eine weitere Zahl einfügen) -nach jedem Schritt zeichnen und dann das Maximum extrahieren und den entstandenen Heap als Array schreiben.

3 Heaps/Trees waren in Array-Schreibweise gegeben und du solltest ankreuzen (Ja-Nein), ob diese die Heap EIgenschaften erfüllen.

Du musst nach und nach einen B-Tree aufbauen - wieder nach jedem EInfügen zeichnen- und dann danach erst einen Knoten löschen -zeichnen- noch einen Knoten löschen -wieder zeichnen (die zu löschenden Knoten waren angegeben)

Rechenaufgabe: Es gibt 28Kanten. Der Graph hat 6 Knoten mit Grad 3. Die restlichen Knoten haben Grad 2. Wie viele Knoten hat der Graph insgesamt? (Graph ist undirected) Lösung: Du musst die Formel: "Summe aller Grade = 2 mal alle Kanten" verwenden  -> 6\*3+x\*2=2\*28 ( x sind die fehlenden Knoten die Grad 2 haben - muss man noch zu den 6Knoten die in der Angabe standen dazuzählen)

Es waren zwei Hash Tabellen gegeben und zwei Hash-Funktionen (je eine Hash Funktion für eine Tabelle). Du musstest jetzt erst bei der ersten Tabelle alle Elemente einfügen und dann bei der zweite Tabelle die selben Elemente (aber halt mit der anderen Hash-Funktion) Dann musste man beide vergleichen: Welches Element bei der jeweiligen Hash-Funktion am meisten Speicherzugriffe/Kollisionen gebraucht hat und wie viele das waren.

Du musstest auch noch die insert() Funktion der LinkedList in python programmieren (steht eigentlich komplett auf den Folien)