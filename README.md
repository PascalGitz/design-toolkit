# Idee
Es soll eine umfangreiche, zuverlässige, zukunftssichere und anwenderfreundliche Sammlung von Berechnungsblättern für Bauingenieure entstehen. 

# Umsetzung 
Die Ablage als öffentlich zugängliches "Repository" bietet einen barrierefreien Zugang für Anwender und Authoren.
Durch die Nutzung und Überprüfung einer vielzahl von Nutzern werden Berechnungsfehler minimiert und die Qualität erhöht. 

Die Sammlung ist nach ingenieurtechnischen Themen organisiert. Bei den Berechnungsblättern werden die notwendigen Hintergrundinformationen übersichtlich hinterlegt, sodass eine transparente, nutzerfreundliche und nachvollziehbare Anwendung gewährleistet ist. 

Alle Berechnungsblätter werden mit [CalcpadCE](https://github.com/imartincei/CalcpadCE) umgesetzt, dessen Open-Source-Charakter langfristige Nachhaltigkeit und Zukunftssicherheit gewährleisten soll. Sämtliche Inhalte werden zunächst auf Deutsch verfasst.

# Installation
Die beste Möglichkeit, das *design-toolkit* zu nutzen, ist das **Klonen des Repositorys**. Das geklonte Repository synchronisiert sich mit Änderungen und stellt somit ein stets aktuelles *design-toolkit* bereit. Das Klonen lässt sich einfach mit [GitHub Desktop](https://desktop.github.com/download/) umsetzen.

---

# Mach mit!
Beiträge sind ausdrücklich erwünscht!  
Dieses Repository lebt von Zusammenarbeit. Eine Anleitung zum Beitragen findet sich [hier](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)

## Struktur
Die Beiträge haben sich an folgende Struktur zu richten:
### Namenskonvention
Die Dateibenennung erfolgt nach folgendem Schema:
`{titel_der_berechnung}-{hintergrund}-{datum des hintergrunds}.cpd`

### Inhalt
Die Struktur eines Berechnungsblatts orientiert sich an folgendem Aufbau:
```
"Berechnungstitel"
Beschrieb des theoretischen Hintergrunds. Verweis auf Normen oder Forschung.

"Parameter"
Verwendete Berechnungsparameter.

"Berechnungen"
Berechnungsapparat

"Resultate"
Wichtigste Resultate in Form von Text oder Plots.
```

Ein Beispiel eines Berechnungsblatts findet sich [hier](Geotechnik/Einbindetiefe_Freie_Wand-Lang-2011.cpd).
