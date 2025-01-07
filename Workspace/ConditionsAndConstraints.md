# Allgemeine Bedingungen und Beschränkungen

## Technische Bedingungen
- **Speicherung**: Passwörter können lokal oder auf einem sicheren, vom Nutzer kontrollierten Server gespeichert werden.
- **Plattformen**:
  - Desktop-Anwendung wird primär für Windows entwickelt.
  - Unterstützung gängiger Webbrowser (Chrome, Firefox, Edge) für die optionale Web-Anwendung.
- **Sicherheit**:
  - Daten werden verschlüsselt gespeichert (z. B. AES-256) und sicher übertragen (z. B. TLS).
  - Es erfolgt keine unverschlüsselte Speicherung oder Weitergabe von Passwörtern.

## Systemanforderungen
- **Hardware**: Aktueller Computer oder Laptop mit Windows-Betriebssystem.
- **Software**: Keine zusätzlichen Programme oder Dienste erforderlich, außer optionaler Server für Synchronisation.

## Risiken und Herausforderungen
- **Technische Risiken**:
  - Sichere Implementierung der Verschlüsselung erfordert Sorgfalt und regelmäßige Tests.
  - Plattformübergreifende Nutzung und Synchronisation können unerwartet komplex werden.
- **Organisatorische Risiken**:
  - Begrenzte Zeit und Ressourcen während der Entwicklung.
  - Abhängigkeit von externen Tools oder Bibliotheken.
- **Lösungsansätze**:
  - **Bewährte Technologien**: Einsatz von sicheren Standards wie AES-256 und TLS.
  - **Tests**: Regelmäßige automatisierte Tests zur Funktionsprüfung und Sicherheit sowie Benutzerfeedback zur Verbesserung der Bedienbarkeit.
  - **Schrittweise Entwicklung**: Das Programm wird in kleinen Schritten verbessert, mit regelmäßigen Updates und schnellen Fehlerbehebungen.

## Einschränkungen
- Der Fokus liegt auf der Desktop-Anwendung.
- Synchronisationsfunktionen und mobile Versionen werden in späteren Phasen geplant und umgesetzt.
- Erweiterte Funktionen wie API-Integration sind nicht Teil der ersten Entwicklungsphase.
