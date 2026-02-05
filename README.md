# Hoodstuff Designer  
SVG Drucklayout Tool → Vektor-PDF Export

Live Tool:  
https://muyuubyuyu.github.io/hoodstuff-designer/

---

## Überblick

Der Hoodstuff Designer ist ein browserbasiertes Layout-Tool zum Erstellen von druckfertigen Vektor-PDFs für Textil- und Siebdruck.

Das Tool ist speziell dafür gedacht, Logos, Schriftzüge und einfache Vektormotive effizient auf großen Druckflächen anzuordnen – ohne komplexe Grafiksoftware wie Illustrator oder CorelDRAW.

Alles läuft direkt im Browser. Keine Installation, kein Account, keine Zusatzsoftware.

---

## Hauptfunktionen

- Drag & Drop von SVG-Motiven auf das Canvas  
- Exakte Größensteuerung in Millimetern  
- Mehrere Canvas-Formate (z. B. 600×1000 mm, A4, 1100×500 mm)  
- Zoom per Buttons und Mausrad  
- Verschieben der Arbeitsfläche (Pan) per Tastenkombination  
- Raster-Overlay mit einstellbarem Abstand  
- Optionales Grid-Snapping  
- Sicherheitsrand mit visueller Warnung bei Überschreitung  
- Duplizieren von Motiven in alle Richtungen per + Buttons  
- Freies Drehen von Objekten  
- Objektliste mit direkter Löschfunktion  
- Globale Hintergrundfarbe für bessere Sichtbarkeit  
- Objektfarbe für einfarbige Druckmotive  
- Undo-Funktion  
- Export als echtes Vektor-PDF (keine Rastergrafiken)

---

## Zweck des Tools

Dieses Tool ist kein kreatives Zeichenprogramm, sondern ein Produktionswerkzeug.

Ziel ist:

- exakte Maße  
- saubere Abstände  
- optimale Flächennutzung  
- druckfertige Vektor-PDF-Ausgabe  

Es ersetzt nicht die Gestaltung, sondern die Layout- und Produktionsvorbereitung.

---

## SVG-Assets einbauen

SVG-Dateien werden als Assets im Tool hinterlegt.

Wichtige Hinweise für SVG-Dateien:

- Keine Hintergründe  
- Möglichst nur Pfade  
- ViewBox sollte gesetzt sein  
- Keine Pixelbilder eingebettet  
- Idealerweise einfarbig für editierbare Motive  

Jedes Asset kann zwei Farbmodi haben:

- **editable** – Farbe wird vom Tool gesteuert  
- **fixed** – Originalfarben der SVG bleiben erhalten (z. B. mehrfarbige Logos)

---

## Technische Basis

Das Tool besteht aus einer einzelnen HTML-Datei und nutzt:

- SVG für das Layout-System  
- jsPDF für die PDF-Erstellung  
- svg2pdf.js für die Umwandlung von SVG in Vektor-PDF  

Es wird kein Framework und kein Build-System verwendet.  
Das Projekt kann direkt über GitHub Pages oder einen beliebigen Webserver gehostet werden.


---

## Einsatzbereich

Geeignet für:

- Siebdruck-Vorbereitung  
- Textildruck-Bögen  
- Sammeldrucklayouts  
- Produktionsvorlagen mit festen Maßen  

Nicht gedacht für komplexe Illustration oder Designarbeit.

---

## Lizenz

Dieses Projekt ist ein spezialisiertes Produktionswerkzeug.  
Verwendung auf eigene Verantwortung.
