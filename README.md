Anleitung
# Daten aus Microsoft forms in JSON-Dateien umwandeln

ℹ️ Der folgende Workflow ist bewusst rein lokal umgesetzt, da dies datenschutzrechtlich die sicherste Variante darstellt. Sollte sich diese Vorgehensweise als nicht zielführend oder in der Praxis schwer umsetzbar erweisen, könnte alternativ ggf. ein voll automatisierter Workflow über Microsoft PowerAutomate eingerichtet werden.

**Hinweis: Die neu erstelle Microsoft-Forms-Vorlage ist aktuell noch nicht im Einsatz. Für die Systemeinrichtung habe ich daher einen Test-Datensatz erstellt.**
> Der Konverter ist speziell auf diese Vorlage abgestimmt, da er die dort vergebenen Feldnamen nutzt.
> Die Vorlage muss dafür nur dupliziert werden: [Link zur Vorlage](https://forms.cloud.microsoft/Pages/ShareFormPage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAMAAFt1JPRUQU5OUFhORzUwRTVDQUZTOTNDR1lUMEhCSS4u&sharetoken=JBTHzE9Ps7eJweO3HqnR)

## 5 Schritte 

1. Die Daten werden mittels Microsoft Forms erhoben
 
2. Excel-Datei aus Microsoft Forms exportieren [(Anleitung)](https://support.microsoft.com/de-de/office/wie-exporte-ich-meine-formularantworten-fb0aee53-0fd9-43bf-9c48-af081b6895d5)

3. Excel-zu-JSON-Konverter öffnen [(Konverter öffnen)](https://enaaacode.github.io/excel-to-json-converter/)

4. Excel-Datei per Drag and Drop in den Konverter legen. Der Konverter wandelt jede Zeile aus der Excel-Datei in eine JSON-Datei um. Die Dateien werden lokal in einem Zip-Order heruntergeladen.

5. Anschließend müssen die Dateien manuell vom Download-Ordner in den jeweils richtigen KOS-Zielordner verschoben werden.
