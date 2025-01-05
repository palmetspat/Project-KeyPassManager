# Allgemeine Bedingungen und Beschränkungen

## Technische Einschränkungen
- **Speicherung**: Passwörter werden lokal in verschlüsselter Form gespeichert (AES-256).
- **Datenübertragung**: Kommunikation erfolgt ausschließlich über verschlüsselte Verbindungen (TLS).
- **Plattformen**:
  - Desktop: Unterstützung für Windows, macOS und Linux.
  - Web: Unterstützung für gängige Browser (Chrome, Firefox, Edge).
- **Datenbank**: Verwendung von SQLite oder PostgreSQL für die Speicherung.

## Systemanforderungen
- **Hardware**: Die Anwendung benötigt einen Standard-PC oder Laptop mit moderner Betriebssystemunterstützung.
- **Software**:
  - Desktop: Entwicklung in C# mit WPF oder Avalonia UI.
  - Web: Nutzung von Blazor oder React für die Frontend-Entwicklung.
- **Self-Hosting**: Docker wird für optionale Serverinstallation unterstützt.

## Sicherheit
- **Verschlüsselung**: Alle Daten werden mit AES-256 verschlüsselt.
- **Synchronisierung**: Optional über sichere, manuell eingerichtete Server (kein Cloud-Zwang).
- **Datenschutz**: Keine Speicherung oder Verarbeitung sensibler Daten auf Drittanbietersystemen.

## Einschränkungen
- Teamfunktionen und Erweiterungen sind erst in späteren Phasen verfügbar.
- Der initiale Fokus liegt auf der Desktop-Anwendung, mobile Versionen folgen später.
