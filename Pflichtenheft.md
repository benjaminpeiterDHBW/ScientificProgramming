# Pflichtenheft
Projektname: KI-gestützte Klassifikation von Tiergesichtern

Gruppe: Benjamin Peiter, Jonathan Jansen, Omer Butt, Julian Greiner, Timo Johannsen <br>
Wir als Gruppe sind alle damit einverstanden, dass wir eine einheitliche Gruppenbewertung erhalten.
## Einleitung
Das vorliegende Projekt beschreibt die Anforderungen und Rahmenbedingungen für ein System zur automatischen Erkennung und Klassifikation von Tiergesichten auf Basis von KI. 
## Ausgangssituation
Wir haben eine Datenbank mit Trainingsdaten für unsere Aufgabe gefunden und müssen diese jetzt sinnvoll einer KI beibringen, um im Endeffekt selbstständig diese Klassifizierung zu tätigen.
https://www.kaggle.com/datasets/andrewmvd/animal-faces
## Ziel
Entwicklung eines KI-gestützten Programms, das digitale Bilder von Tiergesichtern analysiert und die dargestellt Tierart erkennt und klassifiziert
- **S**: Sortierung von Bildern nach Tierarten.
- **M**: Die KI darf maximal einen bestimmten Prozentsatz an Fehlern haben (10%).
- **A**: Tiere werden in der Forschung oft noch manuell klassifiziert, bedeutet durch so eine KI kann man sich eine Menge Zeitaufwand in der Zukunft einsparen.
- **R**: Mithilfe von Python und der Bibliothek PyTorch, ist das Ziel definitiv umsetzbar.
- **T**: Fertigstellung des Projekts bis zum (einschließlich) 04.06.2025
## Produkteinsatz
Das System wird primär zur Bildanalyse in wissenschaftlichen und pädagogischen Kontexten eingesetzt. Es soll auf handelsüblichen Rechnern laufen und mit Jupyter Notebook geschrieben werden.
## Produktfunktionen
- Upload von Bildern (JPG)
- Klassifikation in eine vordefinierte Tierart
- Ausgabe des Ergebnisses mit Konfidenzwert
- Modell: Convolutional Neuronales Netz

## Nicht-funktionale Anforderungen
- Antwortzeit: **< 2 Sekunden** pro **Bild** durchschnittlicher Bildgröße 
- Skalierbarkeit bei Einsatz auf **Cloud-Infrastruktur**
- **Datenschutzkonformität** (z.B. keine Speicherung von Persononbezogenen Daten)
- **Modularer Aufbau** für Zukünftige Erweiterungen 
  
## Technische Anfordeungen
- Programmiersprache: Python (PyTorch)
- Entwicklungsumgebung: Jupyter Notebook
- Datensatz: Tiergesichter von Webseite Kaggle 
  - https://www.kaggle.com/datasets/andrewmvd/animal-faces
  - https://www.kaggle.com/datasets/antobenedetti/animals
  
## Abgrenzungen
- Keine Klassifikation mehrerer Tiere pro Bild
- Keine Erkennung von Emotionen und Zustände
  
## Annahmen und Risiken
- Annahmen: 
    - Aussreichend Testdaten
    - Keine großen Komplikatinen auf dem Weg (Krankheit eines Teammitglieds, Versagen von Technik, etc.)
- Risiken: 
    - Ungleichmäßige Bildqualität kann KI negativ beeinflussen
    - Auf lange Sicht könnte eine zu hohe Vielfalt an Tierarten bei der KI zu einer erhöhten Fehlerquote sorgen
