# Verzeichnisstruktur der Black Market Software GmbH

## .github
Enthält GitHub-spezifische Konfigurationen, wie zum Beispiel die Workflows für GitHub Actions zur Automatisierung des Repositories.

## assets
Beinhaltet statische Dateien und Medien, wie zum Beispiel die extrahierten Bilder (z.B. das DevOps-Logo und die Scooter-Fotos), die für Dokumentationen und die Hauptseite verwendet werden.

## docs
Enthält alle Markdown-Dokumentationen des Projekts (wie diese Datei) sowie das Archiv mit den historischen Word-Dokumenten der vergangenen Jahre.

## secrets
Enthält lokal gespeicherte, geheime und sensible Dateien (wie Kreditkartendaten, API-Keys und Passwörter). Dieser Ordner wird von Git strikt ignoriert, um katastrophale Sicherheits-Leaks in Zukunft zu vermeiden.

## src
Enthält den eigentlichen Quellcode der Softwareanwendungen (aus dem extrahierten Code-Archiv).

## website
Beinhaltet die Vorlagen und Rohdaten für die Unternehmenswebsite, wie beispielsweise die `index.html`.

## README.md
Beinhaltet eine kurze Beschreibung des Projekts und eine Übersicht über die wichtigsten Verzeichnisse und Dateien.