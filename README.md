# Masterarbeit - Lars Büchler - Simulation der drohnenbasierten pharmazeutischen Logistik in Deutschland


Dieses Repository enthält Python-Code, der in sechs Hauptdateien organisiert ist. Jede Datei erfüllt einen bestimmten Zweck im Gesamtprozess der Datengenerierung, -transformation, -optimierung und -visualisierung. Nachfolgend finden Sie eine kurze Erklärung der Funktionalität jeder Datei:

### 1. OSM_Daten
Diese Datei wird verwendet, um Gebäudedaten der Bevölkerung mithilfe von OpenStreetMap (OSM)-Daten zu generieren. Sie enthält die Skripte, die notwendig sind, um Gebäudedaten zu extrahieren und zu verarbeiten.

### 2. Gebäude_Apotheken
Diese Datei berechnet die Entfernungen von jedem Gebäude zur nächstgelegenen Apotheke. Sie ist entscheidend für die Analyse der Zugänglichkeit von Gesundheitseinrichtungen in den untersuchten Regionen.

### 3. Daten_Immobilien
Diese Datei enthält den Code zur Beschaffung und Anpassung von Informationen über verfügbare Lagerstandorte. Sie verarbeitet Immobiliendaten, um potenzielle Standorte für Logistikoperationen zu identifizieren.

### 4. Daten_Transformation
Diese Datei behandelt die Transformation von Bevölkerungsdaten und anderen notwendigen Datensätzen. Sie enthält Skripte zur Datenbereinigung, -aggregation und -vorbereitung für weitere Analysen.

### 5. Optimierung_Simulation
Diese umfassende Datei enthält den Code zur Lösung des Optimierungsproblems, zur Durchführung von Simulationen, zur Durchführung von Sensitivitätsanalysen und zur Durchführung von Kostenvergleichssimulationen. Sie implementiert die Kernfunktionen, die für die Optimierung und Bewertung erforderlich sind.

### 6. Visualisierungen
Diese Datei ist verantwortlich für die Erstellung aller Visualisierungen und Tabellen basierend auf den berechneten Daten. Sie erzeugt Diagramme, Charts und andere grafische Darstellungen, um die Interpretation und Präsentation der Ergebnisse zu unterstützen.
