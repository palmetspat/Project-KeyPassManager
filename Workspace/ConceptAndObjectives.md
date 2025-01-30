# Systemkonzept

Unser Konzept basiert darauf, einen Passwortmanager zu entwickeln, der Passwörter lokal oder auf einem sicheren Server speichert. Die Anwendung wird modular aufgebaut, um Flexibilität und zukünftige Erweiterbarkeit zu gewährleisten:

- **Speicherung**: Passwörter werden sicher verschlüsselt gespeichert, entweder lokal auf dem Gerät oder serverbasiert.
- **Plattformen**:
  - Desktop-Anwendung für Windows (weitere Plattformen wie Linux und macOS optional in der Zukunft).
  - Erhältlich auch als Docker Compose-File.
  - Web-Anwendung für den Zugriff über den Browser.
- **Kernfunktionen**:
  - Hinzufügen, Bearbeiten und Löschen von Passwörtern.
  - Sichere Suche innerhalb der gespeicherten Passwörter.
  - Import und Export von Passwörtern im verschlüsselten Format.
- **Sicherheit**:
  - End-to-End-Verschlüsselung bei Datenübertragungen zwischen Geräten.
  - Daten werden niemals unverschlüsselt zwischengespeichert oder weitergegeben.
- **Erweiterbarkeit**:
  - Modularer Aufbau ermöglicht die zukünftige Integration von Funktionen wie Synchronisation, Teamzugriff oder mobilen Apps.

# Projektziele

## Unabhängigkeit von Drittanbietern
- **Self-Hosted Applikation**:  
  Eine Anwendung, die selbst administriert und gehostet wird. Das bedeutet:  
  - Der Passwortmanager wird auf einem lokalen Medium (Server, Client-PC, etc.) installiert und ausgeführt.  
  - Es ist keine zusätzliche Software erforderlich; der Passwortmanager arbeitet eigenständig.

## Kein Problem mit fremden Datenschutzkonzepten
- Da die Anwendung nicht von einem Drittanbieter gehostet wird, gelten die Datenschutzregeln des eigenen Landes oder der Region.

## Einfache Anwendung
- Ziel ist es, die Handhabung für den Benutzer so einfach wie möglich zu gestalten, ohne auf wichtige Features zu verzichten.  
- Das Feedback der Nutzer wird analysiert, um Fehler zu beheben oder neue Features zu implementieren bzw. bestehende auszubauen und zu verbessern.

## Modernste Sicherheit
- Der Passwortmanager wird mit modernsten Sicherheitsalgorithmen (SHA 256) und Features z.B SSL oder TSL ausgestattet, um den neuesten Standards in der IT-Sicherheit zu entsprechen.

## Kompatibilität
- Ziel ist es, dass der Passwortmanager,durch ständige Weiterentwicklungen, auf den gängigsten Systemen eingesetzt und installiert bzw. ausgerollt werden kann:
  - Microsoft  
  - Linux  
  - VM / Docker  
  - App (Android / iOS)

## Stetige Weiterentwicklung ?!
- Es werden nicht nur neue Features implementiert, sondern auch bestehende Funktionen weiterentwickelt.  
- Fehler (Bugs) und technische Probleme (Error Issues) werden kontinuierlich behoben.

## Kein Limit bei Einträgen (Mögliche Kaufoption?!)
- Es gibt keine Begrenzung bei der Anzahl der Einträge. Benutzer können beliebig viele Einträge erstellen.
