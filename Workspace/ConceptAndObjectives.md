# Projektziele

Unser Ziel ist es, einen sicheren und benutzerfreundlichen Passwortmanager zu entwickeln, der unabhängig von Drittanbietern funktioniert und die Kontrolle über gespeicherte Passwörter vollständig dem Nutzer überlässt.

## **Kurzfristige Ziele (erste Version)**
- Entwicklung einer **Windows-Desktop-Anwendung** zur sicheren Speicherung von Passwörtern.
- **Lokale Speicherung mit End-to-End-Verschlüsselung** (AES-256).
- **Einfache Bedienbarkeit**, um auch für Nicht-Techniker nutzbar zu sein.
- **Kein Cloud-Zwang** – Passwörter bleiben auf dem eigenen Gerät.
- **Import & Export-Funktion**, um bestehende Passwörter einfach zu übertragen.

## **Langfristige Ziele (zukünftige Erweiterungen)**
- **Web-Anwendung**, um Passwörter plattformübergreifend zu nutzen.
- **Mobile App für iOS & Android**.
- **Optionaler Server-Support**, um Passwörter sicher zu synchronisieren.
- **Automatische Speicherung von Passwörtern**, wenn sich Nutzer in neue Dienste einloggen.

---
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
