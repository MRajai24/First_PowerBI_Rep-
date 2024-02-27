# Power BI - Verkaufsperformance-Analyse: Datenintegration, Modellierung und Visualisierung

## Datenaufbereitung im Power Query Editor

1. **Datenverbindung herstellen**
   - Power BI mit den Quelldateien: `Bestelldaten.csv`, `Kundendaten.csv`, `Produktdaten.csv`

### Bestelldaten

2. **Bereinigung der Daten**
   - Entferne erste Zeilen und leere Zeilen
   - Verwende erste Zeile als Überschrift
   - Passe Datentypen an
   - Teile die Spalte "Artikel" nach Trennzeichen

### Kundendaten

3. **Bereinigung der Daten**
   - Verwende erste Zeile als Überschrift
   - Passe Datentypen an
   - Ersetze Werte in der Spalte "Geschlecht"
   - Erstelle bedingte Spalte für Altersgruppen

### Produktdaten

4. **Bereinigung der Daten**
   - Verwende erste Zeile als Überschrift
   - Benenne die Spaltenüberschrift von „MARGE” zu „Marge“ um
   - Passe Datentypen an

5. **Entpivotisierung der Artikel-Spalten**
   - Nutze die Funktion „Andere Spalten entpivotisieren“
   - Entferne leere Werte
   - Benenne die Spalten um
   - Ersetze Werte in der Spalte „Artikelposition“
   - Ändere den Datentyp von „Artikelposition“ zu „Ganze Zahl“
   - Extrahiere den Wochentag aus dem Datum

## Modellerstellung

6. **Beziehungen erstellen:**
    Wechsle in die Modellansicht und erstelle Beziehungen zwischen den Tabellen
   ![Screenshot 2024-02-27 105734](https://github.com/MRajai24/Test/assets/77150117/3649737a-9eaa-47b7-9fa2-5e4fb42fa620)

## Datenvisualisierung

### Teil 1

7. **Verkaufsvisualisierung nach Produktkategorie**
   - Kreisdiagramm mit „Kategorie“ und „Transaktions-ID“
   - Erstelle einen Drilldown zu „Unterkategorie“ und „Produkt“
   - Entferne die Legende und wähle als Datenbeschriftung „Kategorie + Prozentwert“
   - Wähle einen passenden Titel

8. **Gestapeltes Balkendiagramm**
   - Visualisiere die Top-10 Kunden nach Menge der gekauften Artikel
   - Wähle einen passenden Titel, Datenbeschriftung und Datenfarbe
   - Blende die Titel der Achsen aus

9. **Filter nach Produkten & Datum**
   - Aktiviere die Filterung über Produkte mit Suchfunktion
   - Erstelle einen Datumsfilter

### Teil 2

10. **Balkendiagramm & Tabelle**
   - Erstelle eine neue Seite
   - Erstelle eine Tabelle mit den Spalten: Artikelname, Artikelposition, Datum
   - Sortiere die Tabelle aufsteigend nach Datum und Artikelposition
   - Deaktiviere die Anzeige der unteren „Gesamt“-Anzeige in der Tabelle
   - Erstelle ein gestapeltes Balkendiagramm mit Anzahl der Verkäufe nach Wochentagen
   - Wähle einen passenden Titel und formatiere das Diagramm nach deinen Wünschen

11. **Drillthrough erstellen**
   - Erstelle einen Drillthrough zu Seite 2 über die Spalte „Name“
   - Erstelle ein Kartenvisual mit der Spalte „Kunde“
   - Ändere die Feldbeschriftung hier zu „ausgewählter Kunde“
 
 ![Screenshot 2024-02-27 174203](https://github.com/MRajai24/First_PowerBI_Rep-/assets/77150117/9e33cee8-43c9-4c54-9f02-2dfa8d3c080a)

