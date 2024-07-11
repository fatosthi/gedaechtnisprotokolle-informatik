### 1\.

a) KNN erklären

b) KNN generativer oder diskriminativer Ansatz -> Diskriminant weil direkt modelliert aus daten ohne annahme. Die Entscheidungsgrenzen zwischen den Klassen werden direkt aus den Daten modelliert.

c) KNN anwenden auf Beispiel

ح

d) Warum k ungerade wählen -> Weil sonst evtl die Entscheidung zwischen Klassen gerade ausfällt und die zuweisung zufällig erfolgen müsste.

e) Weiteres Problem bei dem Beispiel aus c) erklären und lösen --> Daten sind nicht Skaliert.

### 2\.

a) Confusion Matrix aufstellen + Precision, Recall, F1-Score berechnen

b) ROC Kurve zeichnen

c) AUC berechnen von ROC

d) Was gibt die Diagonale bei der ROC Kurve an?

e) Klassifikator mit Schwellwert t angeben wo Accuracy maximal wird

### 3\. Backpropagation Aufgabe

a) Forward pass + Loss berechnen

b) Update step für Parameter

### 4\. PyTorch Code interpretieren

a) Handelt es sich im Neural Net Klassifikation oder Regression? Begründe.

b) Anzahl der Parameter berechnen

c) Welche der 3 Activation Functions sollte man nicht im Hidden Layer verwenden: Identity, Tanh oder ReLU

d) Was ist ein Neuronales Netzwerk mit um keiner Hidden Layer und nur einem Output Neuron mit Sigmoid Aktivierung? A: Logistic Regression

e) Die Logistic Regression ist ursprünglich nur auf binäre Probleme anwendbar. Erkläre wie mittels der Softmax Funktion die das Problem auf ein Multiclass Problem erweitert werden kann (keine mathematischen Formeln notwendig, verbale Erklärung reicht)

### 5\.

a) Overfitting, guter Fit und Underfitting einzeichnen

b) Was neigt eher zu Underfitting:

* 1\. Lineare Regression oder Neural Net mit 4 Hidden Layer -> Lineare Regression
* 2\. KNN mit k=5 oder k=500 -> k=500

d) Beschreibe die K fache Kreuzvalidierung -> Datenset wir in k teile geteilt. Beim ersten Trainingslauf wird das erste k für das Testen raus genommen. Beim zweiten durchlauf das 2. k.

e) Was sind die Vorteile bei der Kreuzvalidierung gegenüber des normalen Train Test Split.  ->

\- Jeder einzelne Datenpunkt wird sowohl für das Training als auch für die Validierung verwendet.

\- Die Verzerrung durch eine schlecht gewählte Aufteilung in Test- und Trainingsdatensatz wird minimiert.

\- Kreuzvalidierung reduziert die Möglichkeit von overfitting

### 6\.

a) Unterschied Random Oversampling und Selektives Oversampling

b) Borderline SMOTE an Skizze zeigen und die 3 Klassen in welche SMOTE unterteilt in Skizze zeigen

c) Nenne Problem von SMOTE welches von Borderline SMOTE behoben wird

d) Outlier LOF vs KNN mit k=3. Scores gegeben -> Zuordnung der Scores zu Outlier Punkten

7\. Aufgabe zu Data Preprocessing

a) Erkläre wie sie den gegebenen Datensatz preprocessen würd

b) One Hot Encodin

c) Mode Imputing am Beispiel machen -> MODE IST DER AM HÄUFIGST VORKOMMENDE WERT ;'((((((((((

Ach nicht weinen alles gut :))))