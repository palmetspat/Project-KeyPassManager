# Systemkonzept

Unser Konzept basiert auf einer modularen und flexiblen Architektur, die es ermöglicht, die Anwendung sowohl lokal als auch optional über einen Server zu nutzen.

## **Plattformen**
- **Windows-Desktop-Anwendung** (erste Version).
- **Linux & macOS-Unterstützung (zukünftig geplant)**.
- **Docker-Compose für eine einfache Installation**.
- **Web-Anwendung (später zur plattformübergreifenden Nutzung geplant).**

## **Speicherung**
- Passwörter werden **lokal verschlüsselt gespeichert**.
- **Server-Option in späteren Versionen möglich**, aber kein Cloud-Zwang.
- **AES-256-Verschlüsselung** zum Schutz der gespeicherten Daten.

## **Sicherheit**
- **End-to-End-Verschlüsselung** bei Datenübertragungen.
- Keine **unverschlüsselte Speicherung oder Weitergabe** von Passwörtern.
- Unterstützung für **SSL/TLS** zur sicheren Kommunikation.

## **Benutzerfreundlichkeit**
- **Einfache Bedienung** für alle Nutzergruppen.
- **Schnelle Suchfunktion**, um gespeicherte Passwörter leicht zu finden.
- **Import/Export-Funktion**, um bestehende Passwörter zu übernehmen.

## **Erweiterbarkeit**
- Modular aufgebaut, um zukünftige Funktionen **wie Synchronisation, Team-Zugriff oder mobile Apps** zu integrieren.

---

# **Nicht im ersten Release enthalten (zukünftig geplant)**
- **Keine mobile Version** in der ersten Version.
- **Keine zentrale Cloud-Speicherung** (lokale Speicherung bleibt Fokus).
- **Kein Team-Management** – der Fokus liegt zunächst auf Einzelbenutzer. 
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
