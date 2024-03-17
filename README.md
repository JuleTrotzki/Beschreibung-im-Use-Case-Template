# Anwendungsfall - Alarm bei zu hoher Herzfrequenz
##  Name und Identifikationsnummer
UC 1.03. - Alarm bei zu hoher Herzfrequenz
## Beschreibung
Kontinuierliche Überwachung der Herzfrequenz des Probanden. Überschreitet diese einen vordefinierten Schwellenwert, wird ein Alarm ausgelöst.
## Beteiligte Akteure
Überwachungssystem, Proband/in
## Status 
In Arbeit
## Verwendete Anwendungsfälle
- UC 1.01. - Proband/in anlegen
* UC 1.02. - Leistungstest anlegen
+ UC 1.04. - Alarm bei Leistungsabweichung
- UC 1.07. - Abbruch des Leistungstests
## Auslöser
Die Herzfrequenz des Probanden während des Leistungstests.
## Vorbedingungen
- Der Leistungstest wurde gestartet, korrekte Konfiguration des Überwachungssystems und Messung der Herzfrequenz.
* (UC 1.01. - Proband/in anlegen, UC 1.02. - Leistungstest anlegen)
## Invarianten
Aufzeichnung der bis zum Abbruch erhobenen Daten
## Nachbedingung / Ergebnis
Auslösung eines Alarms und Information des Diagnostikers über die zu hohe Herzfrequenz.
## Standartablauf
1. Das System überwacht die Herzfrequenz des Probanden kontinuierlich während des Tests
2. Wenn die gemessene Herzfrequenz den vordefinierten Schwellenwert überschreitet, wird ein Alarm ausgelöst
3. Das System zeigt den Alalm auf dem Bildschirm an und informiert den/die Diagnostiker/in über die zu hohe Herzfrequenz
## Alternative Ablaufschritte
Widerstandswerte werden verletzt. Neustart und Abbruch werden angeboten.
## Hinweise
Die Schwellenwerte für die Herzfrequenz werden individuell festgelegt und an die Bedürfnisse des Probanden angepasst.
## Änderungsgeschichte
Version: 0.01; Name der Autoren: Anna Mauthner, Jule Trotzki; Datum: 17.03.2024
