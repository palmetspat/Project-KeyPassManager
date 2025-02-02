# Projektziele

Unser Ziel ist es, einen sicheren und benutzerfreundlichen Passwortmanager zu entwickeln, der unabhängig von Drittanbietern funktioniert und dem Nutzer die volle Kontrolle über seine gespeicherten Passwörter gibt.

## **Kurzfristige Ziele (erste Version)**
- Entwicklung einer **Windows-Desktop-Anwendung** zur sicheren Speicherung von Passwörtern.
- **Lokale Speicherung mit End-to-End-Verschlüsselung** (AES-256).
- **Einfache Bedienbarkeit**, um auch für Nicht-Techniker nutzbar zu sein.
- **Kein Cloud-Zwang** – Passwörter bleiben ausschließlich auf dem eigenen Gerät gespeichert.
- **Import & Export-Funktion**, um bestehende Passwörter einfach zu übernehmen.
- **AutoFill-Funktion**, um Passwörter direkt in Login-Felder einfügen zu können.
- **Optimierung für ältere Geräte**, damit die Software auch auf leistungsschwächeren Systemen stabil läuft.

## **Langfristige Ziele (zukünftige Erweiterungen)**
- **Web-Anwendung**, um Passwörter plattformübergreifend zu nutzen.
- **Mobile App für iOS & Android**.
- **Optionale Synchronisation über einen eigenen Server**, ohne Abhängigkeit von Cloud-Diensten.
- **Automatische Speicherung von Passwörtern**, wenn sich Nutzer in neue Dienste einloggen.
- **Integration von Zwei-Faktor-Authentifizierung (2FA)** zur zusätzlichen Sicherheit.

---

# **Systemkonzept**

Unsere Software basiert auf einer modularen und flexiblen Architektur, die eine lokale Nutzung ermöglicht, aber auch eine optionale Server-Unterstützung bietet.

## **Plattformen**
- **Windows-Desktop-Anwendung** als erste Version.
- **Linux & macOS-Unterstützung** (geplant für spätere Versionen).
- **Docker-Compose für eine einfache Installation**.
- **Web-Anwendung** (zukünftig für plattformübergreifende Nutzung vorgesehen).

## **Speicherung**
- **Lokale Speicherung mit Verschlüsselung** auf dem Endgerät.
- **Optionale Server-Unterstützung** für eigene Hosting-Lösungen (kein externer Cloud-Zwang).
- **AES-256-Verschlüsselung** zum Schutz der gespeicherten Daten.

## **Sicherheit**
- **End-to-End-Verschlüsselung** für die Kommunikation zwischen Geräten.
- **Keine unverschlüsselte Speicherung oder Übertragung von Passwörtern**.
- **Unterstützung für SSL/TLS**, um die Kommunikation abzusichern.
- **Automatische Sperre nach Inaktivität**, um unbefugten Zugriff zu verhindern.

## **Benutzerfreundlichkeit**
- **Einfache Bedienung** für Nutzer ohne technisches Wissen.
- **Schnelle Suchfunktion**, um gespeicherte Passwörter leicht zu finden.
- **Import/Export-Funktion**, um bestehende Passwort-Datenbanken zu übernehmen.

### **Benutzungskonzept**
Unser Passwortmanager soll für alle Nutzer leicht verständlich sein und eine sichere Verwaltung ermöglichen.

- **Erstnutzung:**  
  - Nutzer erstellt ein **Master-Passwort**, das alle gespeicherten Passwörter schützt.  
- **Passwort speichern:**  
  - Manuelle Eingabe oder automatische Speicherung durch AutoFill.  
- **Passwort abrufen:**  
  - Nutzer kann Passwörter über eine **Suchfunktion** schnell finden und abrufen.  
- **AutoFill-Funktion:**  
  - Gespeicherte Passwörter können **direkt in Login-Felder** eingefügt werden.  
- **Sicherheitseinstellungen:**  
  - Automatische Sperre der Anwendung nach einer bestimmten Inaktivitätszeit.  

## **Erweiterbarkeit**
- **Modularer Aufbau**, um künftige Funktionen wie **Synchronisation, Team-Zugriff oder mobile Apps** einfach zu integrieren.
- Möglichkeit zur **Anpassung an verschiedene Betriebssysteme** in späteren Versionen.

---

## **Nicht im ersten Release enthalten (zukünftig geplant)**
- **Mobile Version** für iOS & Android.
- **Zentrale Cloud-Speicherung** (fokus bleibt auf lokaler Speicherung).
- **Team-Management** (Erste Version ist für Einzelbenutzer gedacht).
- **Erweiterte Web-Version** mit zusätzlichen Features.

