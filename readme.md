# Sammlung Statistischer Rechner

Eine Sammlung von webbasierten Rechnern für verschiedene statistische Analysen, Berechnungen und Visualisierungen. Dieses Projekt wurde mit HTML, CSS und JavaScript erstellt und verwendet externe Bibliotheken wie Plotly.js für Diagramme, KaTeX für die Darstellung mathematischer Formeln und Fraction.js für exakte Bruchrechnung.

## Übersicht

Das Hauptportal (`index.html`) bietet eine Navigation zu den verschiedenen spezialisierten Rechnern. Jeder Rechner ist als eigenständige HTML-Datei konzipiert und befindet sich im Ordner `assignments/`.

## Verfügbare Rechner

Hier ist eine Liste der aktuell verfügbaren Rechner:

1.  **[Übersichtsseite (index.html)](./index.html)**: Das Hauptportal, das zu allen unten aufgeführten Rechnern verlinkt.

2.  **[Boxplot Rechner (Basis)](./assignments/boxplot.html)**
    * **Beschreibung:** Berechnet statistische Kennwerte für einen Boxplot (Minimum, Maximum, 1. Quartil, Median, 3. Quartil) aus einer einfachen Zahlenreihe und stellt diese dar.

3.  **[Diagramm-Generator (Rohdaten)](./assignments/diagramme.html)**
    * **Beschreibung:** Erstellt einen Boxplot, ein Kreisdiagramm, ein Säulendiagramm und ein Balkendiagramm sowie die wichtigsten statistischen Kennwerte aus einer einfachen Zahlenreihe.

4.  **[Analyse gruppierter Daten](./assignments/gruppierteDaten.html)**
    * **Beschreibung:** Ermöglicht die Eingabe von bereits gruppierten Daten (Klassen mit Häufigkeiten). Berechnet approximierte Statistiken (Mittelwert, Median, Quartile) und stellt Diagramme dar, einschließlich eines horizontalen Boxplots basierend auf Klassenmitten und Häufigkeiten. Zeigt auch Klassendetails wie Klassenmitten an.

5.  **[Statistische Kennzahlen (Basis)](./assignments/kennzahlen.html)**
    * **Beschreibung:** Ein grundlegender Rechner für Mittelwert, Median, Standardabweichung (Stichprobe) und Spanne aus einer einfachen Zahlenreihe, inklusive der Darstellung der zugrundeliegenden Formeln.

6.  **[Statistische Kennzahlen (Erweitert)](./assignments/kennzahlenerw.html)**
    * **Beschreibung:** Eine erweiterte Version des Kennzahlen-Rechners, die zusätzlich Quartile und den Interquartilsabstand (IQR) berechnet und die Formeln detailliert anzeigt.

7.  **[Rohdaten-Analyse mit Automatischer Gruppierung](./assignments/datenGruppieren.html)**
    * **Beschreibung:** Nimmt Rohdaten entgegen, berechnet deren statistische Kennzahlen und gruppiert die Daten anschließend automatisch in Klassen (basierend auf Nutzerangaben zur Anzahl der Klassen und optional zur Klassenbreite). Stellt die gruppierten Daten tabellarisch und als Histogramm dar.

8.  **[Kennzahlen für Häufigkeitsverteilungen](./assignments/statischeKennzahlen.html)**
    * **Beschreibung:** Speziell für Daten, die als Werte mit zugehörigen Häufigkeiten vorliegen (z.B. Notenverteilungen). Berechnet Mittelwert, Varianz (Population), Standardabweichung (Population), Median, Quartile, IQR und Spanne. Verwendet Bruchrechnung für exakte Ergebnisse und zeigt Formeln ohne Summenzeichen.

9.  **[Arithmetischer Mittelwert Rechner](./assignments/arithmetischerMittelwert.html)**
    * **Beschreibung:** Ein fokussierter Rechner zur Berechnung des arithmetischen Mittelwerts. Bietet eine detaillierte Formeldarstellung und nutzt Bruchrechnung für exakte Ergebnisse.

## Ordnerstruktur

/├── index.html├── README.md└── assignments/├── boxplot.html├── diagramme.html├── gruppierteDaten.html├── kennzahlen.html├── kennzahlenerw.html├── datenGruppieren.html├── statischeKennzahlen.html├── arithmetischerMittelwert.html└── ... (weitere Rechner)
## Verwendung

1.  Klonen Sie dieses Repository oder laden Sie die Dateien herunter.
2.  Öffnen Sie die `index.html`-Datei in Ihrem Webbrowser, um zur Übersichtsseite zu gelangen.
3.  Von dort aus können Sie zu den einzelnen Rechnern navigieren.
4.  Alternativ können Sie jede HTML-Datei im `assignments/`-Ordner direkt in Ihrem Browser öffnen.

Für die korrekte Darstellung von Formeln und Diagrammen ist eine Internetverbindung erforderlich, da externe Bibliotheken (KaTeX, Plotly.js, Fraction.js) über CDNs geladen werden.

## Technologien

* HTML5
* CSS3
* JavaScript (ES6+)
* **Plotly.js:** Für interaktive Diagramme und Grafiken.
* **KaTeX:** Für schnelle und qualitativ hochwertige Darstellung mathematischer Formeln.
* **Fraction.js:** Für exakte Berechnungen mit Brüchen.

## Beitrag

Vorschläge und Beiträge zur Verbesserung dieser Rechner sind willkommen. Bitte erstellen Sie einen Issue oder einen Pull Request.

---

*Hinweis: Die Dateinamen in den Links dieser README.md basieren auf den zuletzt bereitgestellten Informationen. Bitte stellen Sie sicher, dass sie mit Ihren tatsächlichen Dateinamen im `assignments`-Ordner übereinstimmen.*
