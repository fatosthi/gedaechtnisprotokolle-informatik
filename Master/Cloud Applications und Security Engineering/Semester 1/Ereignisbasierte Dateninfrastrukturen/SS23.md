### 

**Inhaltliche Fragen**

1\. Beschreiben Sie Stream Processing

2\. Bewerten Sie MOM hinsichtlich Verfügbarkeit, Ausfallsicherheit, Kopplung und Skalierung

3\. Differenzieren Sie Event und Message

**Programmier-Aufgaben**

*Ledigliche grobe Beschreibung der Aufgabenform*

Ziel ist es eine Funktion umzusetzen: Verspätungen von Zügen an Bahnhöfen zu berechnen und bei Verspätungen größer als 5 Minuten als Event zu verteilen.

Gegeben ist die geplante Ankunftszeit aus einem Topic /{Bahnhof}/{ZugID} und die Topic für Verspätungen /delayed/{ZugID} worin sich die aktuelle Verspätung befinden soll.

1\. Anbindung an MQTT gegeben, subscribe vorgegeben, Berechnung und Veröffentlichung umsetzen

2\. Dasselbe wie in 1) nur mit Webflux

3\. Dasselbe wie in 2) nur jetzt mit Kafka Streams

**Szenario-Aufgabe**

Umsetzung eines Charging-Station-System.

\- Admin-Service soll Kundenverträge über Frontendbearbeiten können

\- Kunden-Service beinhaltet die Informationen zu Kundenverträgen

\- Price-Service stellt die aktuellen Strompreise an MQTT bereit

\- Solar-Service stellt die aktuelle Solar-Power an einem Standort in MQTT bereit

\- Charging-Station hat Endpunkt zur Steuerung des Strom-Flusses

Solange Strompreis unter gewissen Schwelle soll mit maximaler Leistung des Kundenvertrags geladen werden.

Falls Strompreis über Schwelle soll mit minimaler Leistung und aktueller Solarleistung geladen werden.

Einsetzen von Services, Kommunikationsschnittstellen, Veränderungen an den Services, um einen Ladevorgang korrekt und sinnvoll abzubilden

1\. Umsetzungsbeschreibung relativ frei, gewünscht ist eine Kafka Instanz, Data Streaming, Reaktive Programming, Kommunikationsfluss, Pseudo-Code, ggf. Marble Diagramm