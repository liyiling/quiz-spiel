# quiz-spiel
ein basic Quiz Spiel

## Funktionen
Zwei Spielmodi: Einzelspieler und Mehrspieler (bis zu beliebig vielen Spielern) <br>
Zeitlimits: 15 Sekunden pro Frage, mit Joker-Option bei Zeitüberschreitung  <br>
Joker-System: Nutzen Sie bis zu 2 Joker pro Spiel, um falsche Antworten zu entfernen  <br> 
Highscore-System: Getrennte Bestenlisten für 10, 20 und 30 Fragen  <br>
Punktesystem: Unterschiedliche Punkte je nach Schwierigkeitsgrad (leicht: 1, mittel: 2, schwer: 3 Punkte) <br>
Einfache Konfiguration: Fragen können einfach über JSON-Dateien hinzugefügt oder bearbeitet werden <br>

## Voraussetzungen
Python 3.x installiert
Zusätzliches Paket: inputimeout

## Dateistruktur
Die 3 Datei müssen in gleichen 
### quiz_basic.py
Hauptprogramm mit der Spiel-Logik
### fragen.json:
Enthält alle Quizfragen mit Antwortmöglichkeiten und Schwierigkeitsgraden
### highscore.json
Speichert die Highscore-Daten im JSON-Format


## Mitglieder und 
### Maurice Koppenhagen
Maurice Koppenhagen hat die Grundstruktur des Spiels sowie die Basisfunktionen (Fragen laden, Einzel- und Mehrspielermodus, Highscore-Mechanismus,Zeitcountdown) programmiert.

### Yiling LI
Yiling LI hat das Projekt erweitert, indem ich Schwierigkeitsgrade mit unterschiedlichen Punktwerten eingeführt und in anderen Funktionen und auch in JSON-Datei des Codes integriert habe. Außerdem habe ich die Joker-Funktion selbst umgesetzt, die es ermöglicht, zwei falsche Antwortmöglichkeiten auszublenden. Zusätzliche habe ich etwas Parameternamen geändert und Teile der Logik vereinfacht, sodass der Code leichter verständlich ist.

Viel Spaß beim Spielen und viel Erfolg beim Erreichen der Highscore-Spitze! 🚀
