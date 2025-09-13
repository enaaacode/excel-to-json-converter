Anleitung
# Daten aus Microsoft forms in JSON-Dateien umwandeln

ℹ️ Der folgende Workflow ist bewusst rein lokal umgesetzt, da dies datenschutzrechtlich die sicherste Variante darstellt. Sollte sich diese Vorgehensweise als nicht zielführend oder in der Praxis schwer umsetzbar erweisen, könnte alternativ ggf. ein voll automatisierter Workflow über Microsoft PowerAutomate eingerichtet werden.

**Hinweis: Die neu erstelle Microsoft-Forms-Vorlage ist aktuell noch nicht im Einsatz. Für die Systemeinrichtung habe ich daher einen Test-Datensatz erstellt.**
> Der Konverter ist speziell auf diese Vorlage abgestimmt, da er die dort vergebenen Feldnamen nutzt.
> Die Vorlage muss dafür nur dupliziert werden:
> <a href="https://support.microsoft.com/de-de/office/wie-exporte-ich-meine-formularantworten-fb0aee53-0fd9-43bf-9c48-af081b6895d5](https://enaaacode.github.io/excel-to-json-converter/](https://forms.cloud.microsoft/Pages/ShareFormPage.aspx?id=DQSIkWdsW0yxEjajBLZtrQAAAAAAAAAAAAMAAFt1JPRUQU5OUFhORzUwRTVDQUZTOTNDR1lUMEhCSS4u&sharetoken=JBTHzE9Ps7eJweO3HqnR"
    target="_blank"
    rel="noopener noreferrer">
    Link zur Vorlage </a>

## 5 Schritte 

1. Die Daten werden mittels Microsoft Forms erhoben
 
2. Excel-Datei aus Microsoft Forms exportieren
<a href="https://support.microsoft.com/de-de/office/wie-exporte-ich-meine-formularantworten-fb0aee53-0fd9-43bf-9c48-af081b6895d5"
    target="_blank"
    rel="noopener noreferrer">
    (Anleitung: Excel aus Microsoft Forms exportieren) </a>

4. Excel-zu-JSON-Konverter im Browser öffnen
<a href="https://support.microsoft.com/de-de/office/wie-exporte-ich-meine-formularantworten-fb0aee53-0fd9-43bf-9c48-af081b6895d5](https://enaaacode.github.io/excel-to-json-converter/"
    target="_blank"
    rel="noopener noreferrer">
    (Konverter öffnen) </a>

5. Excel-Datei per Drag and Drop in den Konverter legen. Der Konverter wandelt jede Zeile aus der Excel-Datei in eine JSON-Datei um. Die Dateien werden lokal in einem Zip-Order heruntergeladen.

6. Anschließend müssen die Dateien manuell vom Download-Ordner in den jeweils richtigen KOS-Zielordner verschoben werden.
